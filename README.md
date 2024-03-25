# obsidianでのGTDテンプレート

# 必要なもの
- Tasksプラグイン
- DataViewプラグイン

# 導入
- リポジトリのGTDフォルダ下のファイル一式をダウンロードし、ObsidianのVault内の任意のフォルダに展開
- リポジトリのObsidian/Templateフォルダ下のgtd_templateファイルダウンロードし、Obsidianのテンプレートプラグインのテンプレートフォルダの下に展開
- レビュー待ち.md,GTD.md,issues.mdに下のように書かれたテンプレートフォルダのパスをお使いの環境に合わせて編集  
`(((gtd="project" AND project_status != "done" AND contains(file.folder,"Obsidian/Template") = false) OR gtd="waiting" or gtd="calendar")`
- 既存プロジェクトがある場合は、gtd_projectテンプレートを導入する
	- 終了しているプロジェクトの場合は、 project_status属性の値をdoneにする。もしくはarchivesないし（没）フォルダを作りその下に入れる
