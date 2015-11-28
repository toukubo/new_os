# The Master Workflow.

![the chart](http://f.cl.ly/items/20093U291b1d1H160L2d/IMG_0740.JPG)

the requirement achieved here. 
----------------------------------------------------------------- 
- All the Requests,TodosList, Todo, is trackable, and MECE.
- Map solutions to doumentation organization.
- Concentration. Each of the oprtions just concentrate on keep Box Zero. it makes big flow. 
- Automatic + [Autonomated](https://en.wikipedia.org/wiki/Autonomy).
- New JIT ( just in time ) Microtasking x Crowdy/cloudy.

Steps
-----------------------------------------------------------------
see "the chart" from left -> right -> left direction. 

 [Sales](/Teams/Sales) / [DRIs](Vertical/DRI) generate [Requests](Models/Requests.md) in [Sources](Models/Sources.md). [OS](/Teams/OS) and LineHeads [Watch](Watch) and [Ubiquitous Captures](Ubiquitous Capture) Requests into [Global INBOX](Global INBOX.md), or into [Team INBOX](Team INBOX.md) or [Project INBOX](Project INBOX.md). [Transcriptionists](/Teams/Transcriptionists) Digitalize Requests(*1). [Translaters](/Teams/Translaters) do tranlations on Requests. 

 OS and [LineHeads](Vertical/LineHead) [Triages](Triage) and Organizes INBOX Requets and [Objects](Objects.md) to the [Right Places](/OS/Conventions/RightPlaces/). and do [Tasking](Tasking.md). and [Schedulers](/OS/Schedulers) [Sync Milestones](/OS/Scheduler/Calendar Synchronization Manual.md)

DRIs does [Breakdowns](Breakdown/) and [Assignments](Assignment) to the [RoleAccounts](Models/RoleAccounts.md). and DRI keep doing recursively Breakdowns for the Todos that is Brokendown. 
LineHead  Keep AssigningNegotiations by name and Todos Due are set. and if the Due is delayed,  both [Schedulers](/OS/Schedulers) and LH keep [Poking](/OS/Schedulers/Poke.md). 

Then [Specialists](/Vertical/Specialists) and [Operators](/Vertical/Operators) Executes their Assigned Todos following dues. 
When they have questions or things to Communicate , like when they can't find the Docuemnts and Specs and Materials, they ask ReportLine ( following Vertical Line ), and / or OS [Organizers](/OS/Organizers) for the RightPlaces of the Input materials they need. 

Specialists nad Operators does [TaskChaining](TaskChaining.md) to someone sels ( like designers -> developers, or editors -> designers -> editors -> writers ) using [tag base workflow](WorkflowMethods/Tag base workflow.md), and usually the DRI ,or QA, testers, get the assignemnt, review then #release, this follow the ReportLine ( of Vertical Line ).

Then DRIs do voice memos for the reporting. it is packed with delivery. transcrioptors give the text. and they send the reports. We hope all thikngs are continuesly integarted and report is done smooth. 


### the Patrol and daily opreations. 
We do Patrol. and this is OS works. we do box checks for all the unassignesd Todos, inbox triage checkes, delayed todos, unsynched contents, thigns in wrong place, things violateing the conventions. it increase the productiviy super faster.  if you know the conventions set, then your productivy of the team increase nearly 200-700% at max by this OS support. ( or if you do random work without this new_os, your work productivy goes down to 20%, but this is genral remote workers produtivity. ) 

- OS Head needs to “direction template”  and resource managrement. for all the projects. ( INTERNAL DIRECTOR )


*1 
They do the incoming documents digitalized and treatable.
The text and well formatted digitalized texts are objects, are important objects that we can treat. 



日本語バージョン！
-----------------------------------------------------------------


適応範囲：クライアントワークの制作案件を中心したフローですが、内部開発にも適応可能です。
ここに記載されていることは「マスターワークフロー」といい、大きな要件を実装するものであります。お客さんなどからの依頼をさばき、それがデザインチーム、営業チーム、総務チーム、開発チームと分かれている場合には、それらのチームに枝分かれしていくことになります。
しかしながら、ここで記載されたワークフローは、それぞれのチームにも、適応できます。マスターワークフローから、チームのワークフローが入れ子になっているわけですが、そこでも、Requirement（要件）からレポート・Releaseされるには、同じ経路をたどります。


クライアントワークにおいては、「Request=リクエスト＝要求」はクライアントが記載して、要件に定義していったりは営業がしていきます。
入れ子になった内部や、内部案件では、内部制作案件の場合は、クリエイティブ・ディレクターやマーケ等が「リクエスト」をたてるという違いがありますが、あとは一緒です。


左上にRequestを作る人がいます。実は「RequestInbox」や「INBOX」に、DiscussionやTextDocsにかきこむとこっからタスクを抜き出すことを、LineHeadやOSがしてくれることになっています。

チームにおいてはLineHeadが、全体のINBOXについては、OSが実施します。OSは、各々のチームのProjectのINBOXに依頼を投げ込みます。

ただしこれは1. 簡単な案件や追加要件、2. 英語である。という条件が必要で、今回は日本語で、かつある程度まとまった開発の最初なので、大規模なものでは「内部ディレクター」がTodo Listにする必要があります。
TodoList程度の粒度にタスクをして、そこに文章をぶち込んでいく感じにすると、上村さんに「タスクとかタスクリストにして」というと記載されます。

文章などでContextとして、そのTodoList中のTodoにアサインされた人が理解できるようにしていくと、実行は高速化されます。また、「ProjectDescription」という命名でTextDocsにプロジェクト単位の要求要件を書いておくと、専門家はそれを見ることになっています。（雇用を出す際および試験雇用された人たちはOrientationプロセスを通りますが、その際にそこを見るように記載されています）


「Position Account 」というものが設定されています。「Frontend developer」「TechDirector」「Editor」などです。
なければ「ない！」と叫ぶと、OS（Assigner）が作ってくれます。


大規模な案件の場合は、ディレクターが、要件をアサインされTodoListを作っていきます。人によってはTodoListに「ボイスメモ」をぶち込んでいって、これを「文字起こし」→「タスキング」させていきます。

ディレクターは、「営業」や「クリエイティブ・ディレクター」と役割として分ける前提でいます。要件要求を定義する人と、制作に必要なことに気を使う人は別であると。

TodoListができてからの進行管理は半自動化（自律自働化）されています。
OSがTodoListにリンクされたMilestoneを作ってれくれます。
Milestoneはデフォルトでは作業当日から５日間で作成されてます。内部ディレクター（いない場合はDRI）がこの日程をカレンダー上でドラッグして日程にはめ込んで下さい。

Milestoneが移動されると、自動的に（Zapierで）、Schedulerにタスクが作られます。MilestoneにリンクされたTodoListのTodoのDueをMilestoneの開始日から終了日にセットします。これはリスケされた時にも実施されます。

LineHeadは、フロントエンドなどの役割にあっているもので、アサインされてきた技術者などのSpecialistに「これ、できますか？このDueでできますか？」と「Negotiation」します。また、遅延しているTodoについてはPoking（催促）してください。

TodoのDueはこのようにしてMilestoneから決定されますが、OverdueなTodoがあると、そのMilestoneのDRI、いない場合はProjectのDRI、そしてTodoのAssigneeに対して、Milestoneに遅延されたTodoがあるのでMilestone全体のリスケをするかどうかの通知がきます。リスケしない限り毎日来ます。。。。

また、「タスクをアサインされているものをもっている個人」には、毎日、「これから３日のアベイラビリティを出しといてください」とタスクがたちます。これによって進行管理がなされます。ある程度自働的にアサインされます。

内部ディレクターは「タスクを砕いていく」「専門家ロールにアサインするか専門家個人にアサインする」「マイルストーンを設定したりリスケする」を繰り返し、あとは問題解決に勤しんで下さい。

上流（要求などを決める人）は随時リクエストを投げ込みまくりましょう。場所はTextDocsか、上流Todoリストなどを作って行って下さい。

実際の制作が行われるProjectと、上流策定するプロジェクトを分けるのも得策です。


