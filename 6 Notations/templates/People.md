---
first name: <% tp.file.title.split(' ')[0] %>
last name: <% tp.file.title.split(' ')[1] %>
company: 
location: 
title: 
email: 
website: 
aliases: 
tags:
---

---
## <% tp.file.title %>
<% await tp.file.move("/3 Concepts/People/" + tp.file.title) %>

---
## Notes

---

## Projects

```dataview 
TABLE company as Company, row["personal start date"] as "Time Period", string(people) as people FROM #Project
WHERE contains(people, this.file.link)
SORT row["personal start date"] DESC
```
---

## Meetings

```dataview 
TABLE project, kind, string(people) as people FROM #Meeting
WHERE contains(people, this.file.link)
```
