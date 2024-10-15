---
date: 2024-03-15 21:42
tags:
  - books
---
links: [[Books MOC]]

---
```dataview
TABLE WITHOUT ID
	status as Status,
	"![|160](" + cover + ")" as Cover,
	link(file.link, title) as Title,
	total as Pages,
	author as Author,
	owned as "Owned",
	join(list(publisher, publish)) as Publisher
FROM #📚Book and -#home and -#MOC
```


---
