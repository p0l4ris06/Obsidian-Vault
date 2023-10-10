```dataview
table file.mtime as Edited, file.ctime as Created, file.size as Size
FROM #000-Maths 
SORT file.name 
```