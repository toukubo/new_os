# Postman & Prospective for future work policy and role sharing
 
 
## Future Plan
 
For those who I haven’t requested individually among Rails Developers, I would like you to write tests for Postman as much as possible.
 
We have set up new Basecamp project for Postman.
https://basecamp.com/2947346/projects/12139785
 
I would like to complete Postman perfectly! Postman is quite useful. It is such essential that 40-50% of one development project could be completed with.
 
 
I would like anyone who can do integration or knows the logic to put the priority for what you are specialised. For the rest of developers, I would like you to make thing to hit single end points of Postman.
 
 
 
## Authorization Process (How to join Basecamp project)
 
We have procedure how your access to projects are authorized. Please contact Admin team, but not DIR or your LH.
 
Admin List:
https://basecamp.com/2947346/groups/1937436
 
 
In the case you have enquiries regarding employment related paperwork, please contact Admin team as well.
 
 
## Refactoring based task
 
Refactoring system developers needs to organize request names. Please correct the request names created with Postman.
 
 Please meet these three requirements.
  - To use the same names
  - To create as short as possible
  - To ensure there is no duplication
  
Example: Let’s remove “User” on the top as it is in the user's folder so that there is no need to be.
We would not use “GW” on the top for anything related Gateway.
 
 
### URL
 
 End points should be human readable, therefore, I don’t like the idea to use like “get a gateway”
I would prefer readable URLs. Please use words to make sense as English. And this is naming convention.
 

## Environment tasks (environment variables) and ID setting
 
Please use ID with environment variable. You can use all ID individually at a binding test such as "This ID", "This ID," "This ID" ...

"This ID if User", "This ID if Gateway." By doing this, you will be able to switch the environment easily.

Thus by creating ID system for every environment to switch over, for example, by switching to another production completely such as
 
 - No. 16 account
- No. 9 user
- No. 21 Gateway,
 
another test will be able to carried out easily. It is very convenient.
  

So, for what you created by Postman, user system, Gateway system and single system, please follow this method.
 
I would like hard coated URL or ID system to be replaced by environment variables.
 
 
Please make sure to follow the rule. As we have meta programming framework, And all of these Postman messages will be replaced by code generation.
 
 
Soon,  total end-point requests of Postman for a single test will be calculated from Code generation framework without manually.
(I did all on my own, though it will still need to write binding parts)
 
 
So, refactoring of Postman has tasks such as naming, environment variables system, and ID system modification.
 
 
 
## Sealing

I'd like to request you to carry out sealing as well. When various Gateway tests are carried out, various things are added manually apart from sealing to touch directly Ruby on Rails database. Hearing will be required for them as well.
 
  
While maintaining some table model of the data and the relevance, for example
 "Gateway and sensor are linked like this," or "sensors and users are linked like this," there needs to allow them to have a set.

When you try sealing generally, majorities will do. When they say to me that they want to create something, I would like to let them do.
 
 
When they want to create, for example, they want to add more sensors, or want to change the sensor value, everything needed will be posted with one click. I would like to prepare for this.
 

## Preparations
 
 
Up to this point, I was talking intersection part such as meta, refactoring, structure, etc. After that, I'm planning to carry out Postman preparation.
 
 
 Preparation what I mean is a work to fill the current end points for all user system, Gateway system, and management screen system, etc. I would like you to request to continue if it is not finished.
 
 
 
## How to start
 
 
I have explained roughly. Then how we will start? I would like to set the rule like this.
 
To undertake

- Starting from anyone who is available
- Starting from anything you can do
- Starting from the most difficult one
 
 
I don’t think I have enough time to consider who to be assigned each time. I would like whoever is ready to start by saying on Basecamp “I’m gonna do this task!”
 
 
 
## message for the developers who joined us via Flowdock (Flowdock and Basecamp)
 
 
 
For everyone who join us through Flowdock (you might not experience yet).
The above work has been managed with ticket on Basecamp. I assume you will start working with us by the time you hear this.
 
You can find tasks on Basecamp. You can take assignment for those tasks. If you still have no idea, I would like you to start from a task creating Postman request.
 
Once tasks I talked above are completed, I would like you to move over to
 
 
  - Automated analysis process
  - Work Books
 
 
I think I would be grateful if you could look into API Code.
 
 
 
## Arrangement members and future work plans
 
  
I would like to Takafuji san & Wataru san to continue Release 1 mix as there is still function system tasks and gift system tasks left.
 
I’ve been thinking people who have newly joined us to start with test coefficient system or Postman, then gradually will move to share the responsibility for the systems.
 
 
Probably I will ask someone from among those who newly joined to take the role for code generation system.
