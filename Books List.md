---
date: 2024-03-15 21:08
tags:
  - books
  - booksToRead
---
links: [[Books MOC]]

---
```dataview
TABLE WITHOUT ID
	"![|60](" + cover + ")" as Cover,
	link(file.link, title) as Title,
	total as Pages,
	author as Author,
	join(list(publisher, publish)) as Publisher,
	favorite as Favorite
FROM #📚Book and -#MOC and -#home
WHERE contains(status, "unread")
SORT status DESC, file.ctime ASC
```


---
