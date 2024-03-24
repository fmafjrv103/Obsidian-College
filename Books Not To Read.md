---
date: 2024-03-15 21:07
tags:
  - books
  - booksNotToRead
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
WHERE contains(status, "read")
SORT status DESC, file.ctime ASC
```

---




