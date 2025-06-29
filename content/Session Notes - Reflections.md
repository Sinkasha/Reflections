---
title: Session Notes
publish: true
---

# Session Notes

```dataviewjs
for (let group of dv.pages('"Session Notes - Reflections" and -"Templates"').groupBy(a => a.Act)) {
	dv.header(2, "Act " + group.key);
	dv.table(["Session", "Name", "In-Game Date", "Date"], group.rows.sort(a => a.number).map(a => [a.number,dv.fileLink(a.file.path,false,[a.title]),a.gamedate, a.date]))
}
```
