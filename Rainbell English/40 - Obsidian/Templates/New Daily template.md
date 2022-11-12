---
creation date: <% tp.file.creation_date() %>
modification date: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags: DailyNote

banner: "40 - Obsidian/Attachments/banners/daily-note-banner.gif"
cssclass: noyaml
banner_icon: 💌
banner_x: 0.5
banner_y: 0.35

week: <% tp.date.now("YYYY-WW") %>
---

# <% tp.file.title %>

<< [[<% tp.date.now("DD.MM.YYYY", -1, tp.file.title, "DD.MM.YYYY") %>]] | [[<% tp.date.now("DD.MM.YYYY", 1, tp.file.title, "DD.MM.YYYY") %>]]>>


## Overview
- Summary :: 

Weekly Log: [[<%tp.date.now("YYYY-WW",0, tp.file.title, "DD-MM-YYYY")%>]]

## Agenda
