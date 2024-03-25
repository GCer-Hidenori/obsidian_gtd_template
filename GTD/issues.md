# 課題
```tasks
(folder does not include archives) AND (folder does not include （没）) AND (not done) AND (tag includes issue)
sort by happens
```

```dataview
TABLE 内容,対策
WHERE gtd="issue" AND project_status != "done" AND contains(file.folder,"Obsidian/Template") = false AND contains(file.folder,"/archives") = false

```
