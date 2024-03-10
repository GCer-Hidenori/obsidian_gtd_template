# obsidianでのGTDテンプレート

# 必要なもの
- Tasksプラグイン
- DataViewプラグイン

# 導入
- リポジトリのGTDフォルダ下のファイル一式をダウンロードし、ObsidianのVault内の任意のフォルダに展開
- リポジトリのObsidian/Templateフォルダ下のgtd_templateファイルダウンロードし、Obsidianのテンプレートプラグインのテンプレートフォルダの下に展開
- レビュー待ち.mdを、テンプレートプラグインのテンプレートフォルダに合わせて編集
`(((gtd="project" AND project_status != "done" AND contains(file.folder,"Obsidian/Template") = false) OR gtd="waiting" or gtd="calendar")`
- 既存プロジェクトがある場合は、gtd_projectテンプレートを導入する
	- 終了しているプロジェクトの場合は、 
