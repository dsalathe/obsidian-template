---
project: '[[<% tp.file.title.split(" - ")[1] %>]]'
date: '[[<% tp.date.now("YYYY-MM-DD") %>]]'
people:
  - "[[David Salathé]]"
kind: <% tp.file.title.split(" - ")[0].replace(" ", "/") %>
tags:
  - Meeting
aliases:
---
---
<% await tp.file.move("/1 Projects/" + tp.file.title.split(" - ")[1] + "/Meetings/" + tp.date.now("YYYY-MM-DD") + " " + tp.file.title.split(" - ")[0]) %>
## What I bring

- 
---
## Discussion

- 
--- 
## Next actions
- [ ] 