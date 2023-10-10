```dataview
table file.mtime as Edited, file.ctime as Created, file.size as Size
FROM #000-Maths/M1/Chapters  OR #000-Maths/P1/Sub-chapter 
SORT file.name ASC
```