## Deadlines

```dataview 
TASK
WHERE !completed AND date(substring(file.name, 0, 10), "yyyy-MM-dd") >= date(today) AND text != ""
GROUP BY file.name
SORT rows.file.name ASC
```

---

## Unscheduled Tasks

```dataview 
TASK
WHERE !completed AND date(substring(file.name, 0, 10), "yyyy-MM-dd") < date(today) AND text != ""
GROUP BY file.link
SORT rows.file.name ASC
```

---
## Today's tasks
- [ ] 
---
## Meetings

```dataview 
TABLE project, kind, people FROM #Meeting
WHERE date = this.file.link
```
---
## Log
