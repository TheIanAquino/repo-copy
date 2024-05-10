---
share: true
title: DATAVIEW-TEST
draft: false
date created: 2024-05-10
last modified: 2024-05-10 03:30:32 PM
---

```dataview
TABLE date-created as "date created", last-modified as "last modified"
FROM "quartz/content/_dailies"
SORT file.name ASC
```