---
date: 2024-03-19 22:20
tags:
  - MOC
  - notes
---
Links: [[000 Home|Home]]

---
# Active Notes
```dataview
table without id
file.link as "Note", (date(today) - file.cday).day as "Created"
from #active  and -#MOC and -#home
```
# All Notes
```dataview
table without id
file.link as "Notes", (date(today) - file.cday).day as "Created", complete as "Complete"
FROM #notes OR #newNotes AND -"Template" AND -#MOC and -#journal
SORT file.name DESC
```
# In Progress
```dataview
LIST
FROM #notes AND #inProgress OR #newNotes AND #inProgress 
```
# Not Completed
```dataview
table without id
file.link as "Note", (date(today) - file.cday).day as "Created"
where contains(complete, "No")
```
# Completed
```dataview
TABLE WITHOUT ID
file.link as "Note",
completeDate as "Completed"
FROM #notes AND #complete OR #newNotes AND #complete and -#journal
WHERE contains(complete, "Yes")
SORT file.name ASC
```
---