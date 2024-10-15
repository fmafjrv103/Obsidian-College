---
date: 2024-03-20 02:51
tags:
  - books
---
Links: [[Books MOC]]

---
```dataview
TABLE WITHOUT ID
	"![|60](" + cover + ")" as Cover,
	link(file.link, title) as Title,
	total as Pages,
	author as Author,
	join(list(publisher, publish)) as Publisher
FROM #📚Book 
WHERE contains(favorite, "Yes")
SORT status DESC, file.ctime ASC
```

---
