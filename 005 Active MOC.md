---
date: 2024-03-15 15:10
tags:
  - active
  - MOC
---
links: [[000 Home|Home]]

---
Welcome to the Active MOC. It's purpose is to quickly see what's "Top Of Mind". Sometimes I use this a lot, sometimes (like lately) I just use Dynalist. 

But it's nice to have a place to put to new/relevant stuff you don't want to forget.

- Current Reminder
- Current Reminder
- Current Project
- Current Idea
- [[Quote - Count of Monte Cristo]]
- Current Goal

### IM tasks
- [ ] clean up [[Concepts MOC]]
- [ ] https://vimeo.com/275530205 - this was suggested to watch, might be apropos to take notes on it
# New Notes
```dataview
table without id
file.link as "Notes",
(date(today) - file.cday).day as "Created",
complete as "Progress"
From -"Templates" and #newNotes 
```
# In Progress
```dataview
TABLE WITHOUT ID
file.link as "Notes", (date(today) - file.cday).day as "Created"
From #inProgress 
where
Sort file.cday DESC
```

---

