# workflow: branching and pushing your work to us
it goes like 
```
topicBranch().push().pullRequest().release().deploy().test(development).report(bc).taskChainBack();
```
it goes like a straight one liner right? 

ours is "[git flow](git-flow - Google 検索 https://www.google.co.jp/search?q=git-flow&oq=git-flow&aqs=chrome..69i57j69i60j69i61.175j0j4&sourceid=chrome&ie=UTF-8)" tick. 

共通 Common Process
------------------

+ 試験コードも(rails:rspecsなど）も実装してくださいね。

## topic branching ( TB ) 

+ checkout development_branch
+ branch bcのtodoのid部位_todoのタイトルに近い命名
(http://cl.ly/0T1K291Z2S29)todoページのurlの末尾（この場合は「246591223」と246574797_fullfill_sensorLogsで。後半は意味がわかればOK。コピペベースがいいです。検索できるから。）
* complete and check and test locally then push to your TB
+ pull req to development 
+ bcの当該チケットに「PR送った宣言。」
+ curlするクライアントのコードをbcコメントに添えてください。
+ responseがある場合はサンプルのresponseも貼ってください。

## development_branch

for the most of the cases development_branch name is "development" and depending on the development environment, it could be different. 

### build and deploy 

circle ci we use. and after PR -> Merge by Releaser, it would be built automatically and deployed in development server.

### test on the dev

+ see your development server. and test there

### change the interface specs if needed 

usually you need to commit and push there. 

### reporting

1. report into ticket ( basecamp ) todo comment ( not git side but in bc ) 
2. change the assignment, to the LineHead ( LH ). don't complete it. give it to Line head . 
