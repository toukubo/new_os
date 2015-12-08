About LineHeadTodo Matching
=================================================================
In Assignment, matching is needed between skill & role, Free time & operating time and task sequence.
This might look simple but internally, this is thought to be a very complicated matter, also, at the very most of intellectual products happens at this point.

In the New OS, [By Name Assignment](/OS/Assigner/AssignbynameAndTodo.md) is completed at the end by the following procedures:



### 1. Garbage Collection and Triage
In unassigned tasks, OS/LineHead Assign ToDo's to LineHead. OS assign to LineHead Todo that has no Global location.
OS checks all unassigned todo once in 3 days. This is refered to as [GarbageCollection](/OS/Assigner/GarbageCollection.md)(GC). [Triage](/Workflow/Tasking) occurs when GC are performed on INBOX tasks.




### 2. TaskChaining for Assignment of LineHead and DRI
LineHead and DRI distributes the Assignment process.
This is [TaskChaining](/Workflow/TaskChaining.md), that only occurs between DRI and LineHead, in the end concluded by Operator and Specialist。



DRI is also said to be a ToDo specialist. They create Todo, and they have understanding on which person possesses what skillset and who can fulfill the role of performing certain tasks.

LineHead is not always a specialist in regards to which skillset is needed for the Team or Project. OS Assigner does Dual Roles.

If LineHead claims the specialization in the Team Project to some extent in regards to below Role Assignment and ByNameAssignment, LineHead can perform both. LH will perform the configuration and ReviewRequest it to DRI.

#### 2.1. AssignmentToRoleAccount
In regard to ToDo, Assignment to [RoleAccount](/Workflow/RoleAccount.md) will occur.

For example, for Senior FrontEndDeveloper, the latter is requested to perform a difficult front-end common parts development and so on.

Unassigned ToDo's are expected to be ZeroBox.

#### 2.2. ByNameAssignment
Refer to [ByNameAssignment](/OS/Assigner/ByNameAssignment.md) for details. If there are no candidates (Qualified staff and resource) that can be assigned in that Role, LH will raise the [NullPointerException](/OS/Patrol/NullPointerException.md) to  [ReportLine](/Workflow/Vertical/ReportLine.md).

```
Example: In the AlertMap screen under Todo List that became like this: “there is no screen itself, create a mock HTML then place it in Dropbox, make it accessible in zxc.cz/secual_mockup/: assign: junior frontend developer（RoleAccount）”, test assign. 
Aside from this person, around 5 others are suited for a project as Front-end Junior dev, so check their availability, check other available assigned tasks for the day and urge them by asking “can you do next” and “when can you do?”.
```


Using RoleAccount information and assign information towards RoleAccount,  LineHead and OS individually, diversively and cooperatively make ByNameAssignment possible. Because these 2 staged Assignment occurs, RoleAccount is treated as a very important information.

-------

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

```
例：AlertMap画面Todo List配下に「画面自体がまだないのでhtmlのモック作ってDropboxに配置し、zxc.cz/secual_mockup/でアクセス可能にする：アサイン：junior frontend developer（RoleAccount）」となっているものについて、アサインを試みます。
この人以外に５名くらいFrontendのJunior devが当該プロジェクトにいるはずですので、アベイラビリティ情報をみ、この日とのほかアサインタスクの空き状況をみ、そこから「これお願いできるか次。」と「いつできる？」とを催促します。
```


RoleAccount の情報、及び RoleAccount へのアサイン情報を利用して、LineHead及びOSは自立分散協調的に ByNameAssignment が可能であるという、2段階での Assignment を行うため、RoleAccount は非常に重要な情報として機能します。

