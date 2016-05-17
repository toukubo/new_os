# workflow: branching and pushing your work to us

it goes like

'''topicBranch().push().pullRequest().release().deploy().test(development).report(bc).taskChainBack();
'''

it goes like a straight one liner right?

ours is "[git flow](git-flow - Google 検索 https://www.google.co.jp/search?q=git-flow&oq=git-flow&aqs=chrome..69i57j69i60j69i61.175j0j4&sourceid=chrome&ie=UTF-8)" tick. 

Common Process

------------------

 + Sample code is needed to be implement. (rails:rspecs, and so on)

## Topic Branching ( TB )

 + checkout development_branch

 + Naming close to the title of the [id_todo] in branch bc

For example:check this image.

http://cl.ly/0T1K291Z2S29

The end of todo page's url is [246591223].

In this case,it should be [246591223] and [246574797_fullfill_sensorLogs].
 
The second half is anything OK, even if meaning is conprehensible.
copy URL and paste is better way.because,it can search in BC, and easy to find later.

 * complete and check and test locally then push to your TB
 + pull req to development
 + You should write comment [I sent the PR.] on Basecamp's correspond to-do.
 + add client code to curl in Basecamp's comment.
 + If you have any responses, please paste sample responses.


## development_branch

for the most of the cases development_branch name is "development" and depending on the development environment, it could be different.

### build and deploy

circle ci we use. and after PR -> Merge by Releaser, it would be built automatically and deployed in development server.

### test on the dev

see your development server. and test there

### change the interface specs if needed

usually you need to commit and push there.

### reporting

 1. report into ticket ( basecamp ) todo comment ( not git side but in bc )
 2. change the assignment, to the LineHead ( LH ). don't complete it. give it to Line head .
