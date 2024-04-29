---
title: <% tp.file.title %>
draft: false
date created: <% tp.file.creation_date("YYYY-MM-DD") %>
last modified: <% tp.file.last_modified_date("YYYY-MM-DD hh:mm:ss A") %>
date: <% tp.date.now("YYYY-MM-DD") %>
type: entry
---
<% await tp.file.move("/quartz/content/_dailies/" + tp.file.title) %>