<%*
const projectNames = [... new Set(app.vault.getMarkdownFiles().map(f => f.path).filter(path => path.startsWith("1 Projects")).map(path => path.split("/")[1]))];
const projectName = (await tp.system.suggester((item) => item, projectNames, true, "Select Project Name"));
const chosenDate = await tp.system.prompt("Day of Meeting:", tp.date.now("YYYY-MM-DD"));
const title = tp.file.title.trim()
%>---
project: '[[<% projectName %>]]'
date: '[[<% chosenDate %>]]'
people:
  - "[[David Salathé]]"
kind: <% title.replace(" ", "/") %>
tags:
  - Meeting
aliases:
---
---

<% await tp.file.move("/1 Projects/" + projectName + "/Meetings/" + chosenDate + " " + title) %>
## What I bring

- 
---
## Discussion

- 
--- 
## Next actions
- [ ] 