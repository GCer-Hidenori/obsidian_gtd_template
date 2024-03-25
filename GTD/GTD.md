# 今日やること
```tasks
(folder does not include archives) AND (folder does not include （没）) AND (not done) AND (happens on or before today) AND (tag does not include waiting)
sort by happens,priority
```

# 次にやること
![[次にやること]]

# 連絡待ち
![[連絡待ち]]

# カレンダー
![[カレンダー]]

# 課題
![[issues]]

# レビュー待ち
![[レビュー待ち]]

# inbox
![[inbox]]

# いつかやること
![[いつかやること]]


# プロジェクト
```dataview
TABLE
WHERE gtd="project" AND project_status != "done" AND contains(file.folder,"Obsidian/Template") = false AND contains(file.folder,"/archives") = false

```

# 参考
## inbox一覧
```dataview
TABLE
WHERE gtd="inbox" AND contains(file.folder,"Obsidian/Template") = false AND contains(file.folder,"/archives") = false

```
