## workflow: branching and pushing your work to us

git flow ちっくです。

### 共通
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




## apiのビルド先

+ zxc.cz:5000がgatewayを用になっているのでここで試験 
+ 該当するAPI Interface仕様書の箇所を修正してmasterにcommit


