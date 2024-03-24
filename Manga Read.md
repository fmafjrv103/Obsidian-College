---
date: 2024-03-21 14:50:01
tags:
  - books
  - manga
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
WHERE contains(status, "Read")
SORT status DESC, file.ctime ASC
```


---
