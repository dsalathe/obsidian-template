---
company: 
personal start date: 
personal end date: 
tech stack: 
people:
  - "[[David Salathé]]"
aliases: 
tags:
---
---
<% await tp.file.move("/1 Projects/" + tp.file.title + "/" + tp.file.title) %>
## Overview & Objectives

---
## Imputation codes

| **Imputation Code** | **Explanation** |
| ------------------- | --------------- |
|                     |                 |

---
## Acronyms

```dataview 
TABLE WITHOUT ID
aliases[0] as ART, file.link as "Acronym Resolution Table" FROM "3 Concepts/Definitions"
WHERE scopes != null AND (contains(scopes, this.file.link) OR contains(scopes, this.company))
```



---
## Meetings
```dataview 
TABLE project, kind, string(people) as people FROM #Meeting
WHERE project = this.file.link
```
---

## Points of contacts


| **Concept** | **Person** |
| ----------- | ---------- |
|             |            |
