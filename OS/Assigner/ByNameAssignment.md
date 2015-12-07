1.	[LineHead](/Workflow/Vertical/LineHead) will check the [RoleAccount' s](/Workflow/RoleAccount.md) role that ToDo assigned and Individual belonging to the same group by BC's Everyone screen, then assign candidates. Or, check if relevant project as assigned candidates. *1
2. Check Availability in the Assign candidate's AvailabilityReport movement table.
3. Check that assign candidate's claiming status.
4. Check assign candidate's Due.
5. Taking account of 1, 2, and 3, [AssignmentNegotiation](AssignmentNegotiation.md) will be performed on appropriate assign candidate.

When there are candidates that can be assigned that has no Role, bring this [NullPointerException](/OS/Patrol/NullPointerException.md)  to [ReportLine](/Workflow/Vertical/ReportPath.md).

*1 This can be skipped if this is already checked in Project/Workflow.

---

1. [LineHead](/Workflow/Vertical/LineHead) はその Todo が Assign されている [RoleAccount](/Workflow/RoleAccount.md) の 役割と同名のGroup に属する個人を BC のEveryone画面から確認し、アサイン候補とします。また、該当するProjectに アサイン候補が含まれていることを確認してください。 *1
2. アサイン候補の AvailabilityReportの稼働表からAvailabilityを確認する。
3. アサイン候補保有状況を確認
4. アサイン候補のDueを確認。 
5. 1,2,3を鑑み、適切なアサイン候補に、 [AssignmentNegotiation](AssignmentNegotiation.md) を行います。

アサインすることができる候補がそのRoleにいない場合は、[NullPointerException](/OS/Patrol/NullPointerException.md) を [ReportLine](/Workflow/Vertical/ReportPath.md) に投げてください。

*1 Project/Workflowについてすでに確認されている場合はスキップしてOK。
