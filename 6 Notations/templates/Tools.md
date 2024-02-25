---
kind: 
expertise (0-5): 
last updated: 
aliases:
---
---
<% await tp.file.move("/4 Mastery/Tools/" + tp.file.title) %>
## Overview

---
## Projects

```dataview 
TABLE company as Company, row["personal start date"] as "Time Period", row["tech stack"] as "Tech Stack" FROM #Project
WHERE contains(row["tech stack"], this.file.link)
SORT row["personal start date"] DESC
```

