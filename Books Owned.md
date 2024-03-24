---
date: 2024-03-15 18:52
tags:
  - booksToBrowse
  - inProgress
---
links: [[Books MOC]]

---
```dataview
TABLE WITHOUT ID
	"![|60](" + cover + ")" as Cover,
	link(file.link, title) as Title,
	total as Pages,
	author as Author,
	join(list(publisher, publish)) as Publisher
FROM #📚Book
WHERE contains(owned, "yes")
SORT status DESC, file.ctime ASC
```

---
