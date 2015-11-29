LineHeadTodo の Matching について
=================================================================
Assignmentには、技能と役割、空き時間及び稼働時間とタスクの順序、Matchingが必要です。
簡単に見えるかもしれませんが、内部的には、非常に複雑なことがらが決まり、また知的生産物のの非常に多くがこのポイントで行われます。

New OS では以下の手順で最終的に [By Name Assignment](/OS/Assigner/AssignbynameAndTodo.md)を達成します。

### 1. garbage collection and triage
unassignedなタスクはOS/LineHeadが、LineHead に Todo を Assign します。Global な場所にある Todo はOSが、そうではないものは LineHead がアサインします。
OSは3日に一度、すべてのunassigned todoをかくにんしています。これを [GarbageCollection](/OS/Assigner/GarbageCollection.md)(GC) と読んでいます。INBOX のタスクを GC することを [Triage](/Workflow/Tasking) と読んでいます。

### 2. LineHeadとDRIがAssignmentのための TaskChaining をする。
LineHeadと、DRIは Assignment のプロセスを分業します。
これは[TaskChaining](/Workflow/TaskChaining.md) で、DRIとLineHeadの間で行われ、最終的にはOperatorやSpecialistが判断します。

DRIは、そのTodoの専門家でもあります。Todo を作成するのも DRI ですが、DRIは、「どういった技能を有する人、どの役割名の人間であればその作業が実施可能であるかという事を認識できます。

LineHeadは必ずしもその Team やProjectに必要な技能の専門家ではありません。OS Assignerが Dual Role で兼任することもあります。

以下の「役割のAssignment」と「役割へのその役割に属する人へのAssignment」はLineHeadがそのチーム・プロジェクトにある程度の専門性を有する場合には、LineHeadによって両方を行っても構いません。LHが設定を行い、それをDRIにReviewRequestしてください。

#### 2.1. AssignmentToRoleAccount 役割アカウントへのAssignment
Todo に対し、 [RoleAccount](/Workflow/RoleAccount.md) への Assignment を行います。

例えば Senior FrontEndDeveloperに対して、難易度の高いフロント側の共通部品開発を依頼する。といった具合です。

unassigned な Todo が ZeroBoxされることが期待されます。

#### 2.2. ByNameAssignment
詳細は [ByNameAssignment](/OS/Assigner/ByNameAssignment.md) をご確認ください。アサインすることができる候補（人員適任者やリソース）がそのRoleにいない場合は、LHは[NullPointerException](/OS/Patrol/NullPointerException.md) を [ReportLine](/Workflow/Vertical/ReportLine.md) に投げます。

RoleAccount の情報、及び RoleAccount へのアサイン情報を利用して、LineHead及びOSは自立分散協調的に ByNameAssignment が可能であるという、2段階での Assignment を行うため、RoleAccount は非常に重要な情報として機能します。

