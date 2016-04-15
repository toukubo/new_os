How to make Storyteller Templates
================================================================

First of all, what you want to get is somethign like this. 


```
class V1::{{noun.name}}sController < V1::BaseController
  before_action :authenticate_agent!, only: [:show, :update, :destroy, :confirm_modify, :modified_fields]
  before_action :find_{{noun.lowername}}!, only:[:show, :update, :destroy, :confirm_modify, :modified_fields]
  before_action :authenticate_user!, only: [:index]

  def index
    if current_user.role.name == "operator"
      {{noun.name}}s = {{noun.name}}.all
    elsif (current_user.role.name == "owner") || (current_user.role.name == "user")
      {{noun.name}}s = current_user.account.{{noun.lowername}}s
    else
      render json: {error: 'authentication failed'} , status: 401 and return
    end
    render json: {{{noun.name}}s: {{noun.lowername}}s}
  end

```

This is an example of rails code. 


## how to make this ? 
----------------------------------------------------------------  

First, just think your work is very standard web mvc development.   
In web development, we recieve html file from your client or desigenrs. You need to turn it to your view template file. let’s say templating. and template engines helps you to render the template to the output htmls. They are integrated in the frameworks, but you still know template engines are inside there. famous ones, in rails: erb,slim,haml. Angular uses ng html, php uses php as templating, java: jsp. We use Mustache template engines for us.   

in the web development which has html front view, and if you use json as model data object, then it goes as below. 

### html material you recieve from your client or designer,   

```
<html>	<body>	hello, koji!</body></html>
```

###  model data 

```
{"user":
  {"name" : "ForContentOnly","mail":"toukubo@gmail.com"}
}
```

### view == template file you make 

```
<html>
	<body>
		hello, {{user.name}}! <br /> 
			yoru email address is {{user.mail}} ? 
	</body>
</html>
```



### generated result if you render this using mustache 

```
<html>	<body>	hello, koji!</body></html>
```

But this is completely the same as the "input html", because this is what expected. 
    
Note that : With Mustache, you don't need the controller for the simplest use without logic code. just load the template file and objects ( of hte models ) to load into the varilables place holders. if you want to make it, you can load it. 
  

## Storyteller templating works
----------------------------------------------------------------
  
Then, get back to this our job. now the material you recieve is not html, but the "code" itself. and however, the difference between html and source as view template ? nothing! so if we recieve this file as below ? you want to render this file. 

### Material you recieve as view file.   

```
class V1::UsersController < V1::BaseController
  before_action :authenticate_agent!, only: [:show, :update, :destroy, :confirm_modify, :modified_fields]
  before_action :find_user!, only:[:show, :update, :destroy, :confirm_modify, :modified_fields]
  before_action :authenticate_user!, only: [:index]

  def index
    if current_user.role.name == "operator"
      Users = User.all
    elsif (current_user.role.name == "owner") || (current_user.role.name == "user")
      Users = current_user.account.users
    else
      render json: {error: 'authentication failed'} , status: 401 and return
    end
    render json: {Users: users}
  end
end
```


### model data (model.json)

```
{
  "name" : "ForContentOnly",
  "noun" : {
    "name" : "User",
    "lowername" : "user",
    "attr" : [ {
      "name" : "name",
      "type" : "String"
    },{
      "name" : "id",
      "type" : "Integer"
    },{
      "name" : "mail",
      "type" : "String"
    } ]
  },
  "verb" : {
    "name" : "Hello World!"
  }
}
```
  
yeah, our case the data is “models” itself. this is confusing maybe we call our model classes “noun”.

that’s it, and with mustache we can generate the code. if you are using mustache comamnd line, just this 
```
mustache model.json railsController.mustache > railsController.rb
```

then we can gerate. yey.
But we use our templates in our framework so that we can collecrtively use them whole 




## RareCases 

In the web development, mvc, you have controller usually holds logic and loading the data. yes. we have them. you can do it. in this simple case, just a model set, and render it. 
if you want to cahnge the name decorated displayed ( oh to hold view logic in controller is good manner, tho, we do it ) 

### 

```
Map map = new Map();
User user = loadJsonString("sample.json");
user.setName(user.getName() + " the storyteller! ");
Mustache.render(templateName,user);
```
