Tags: #MOC

```dataview
table file.mtime as Edited, file.ctime as Created, file.size as Size
FROM #000-Maths/M1/Chapters OR #000-Maths/P1/Chapters OR #000-Maths/P2/Chapters OR #000-Maths/S1/Chapters 
AND !#000-Maths/P1/Chapters/Sub-chapter AND !#000-Maths/M1/Chapters/Sub-chapter AND!#000-Maths/S1/Chapters/Sub-chapter 
SORT file.name ASC
```