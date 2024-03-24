---
date: 2024-03-15 21:10
tags:
  - books
  - reference
---
links: [[Books MOC]]

---
```dataview
TABLE WITHOUT ID
	"![|60](" + cover + ")" as Cover,
	link(file.link, title) as Title,
	author as Author,
	join(list(publisher, publish)) as Publisher
FROM #📚Book
WHERE contains(reference, "yes")
SORT status DESC, file.ctime ASC
```
---
