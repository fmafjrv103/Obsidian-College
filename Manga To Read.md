---
date: 2024-03-20 07:31:41
tags:
  - manga
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
	join(list(publisher, publish)) as Publisher,
	favorite as Favorite
FROM #📚Book and #manga 
WHERE contains(status, "unread")
SORT status DESC, file.ctime ASC
```

---
