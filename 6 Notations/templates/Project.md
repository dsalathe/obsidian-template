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
## Meetings
```dataview 
TABLE project, kind, people FROM #Meeting
WHERE project = this.file.link
```
---