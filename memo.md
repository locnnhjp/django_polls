## Gitコマンド早見表
- 参考：https://qiita.com/kohga/items/dccf135b0af395f69144

### 初期設定を行う
- `$ git config --global user.name "XXXX"`
- `$ git config --global user.email "XXXX@sample.com"`

### ローカルにリポジトリを作成し、リモートにプッシュ
- `$ git init`
- `$ git add --all .` または `$ git add .`
- `$ git commit -m "コミットメッセージ"`
- `$ git remote add origin https://github.com/<github_username>/<github repo name>`
- `$ git push`

### リモートから変更を取得
- `$ git pull` または `git fetch`

### バージョン管理を対象外としたい時
- `.gitignore`ファイルを作成
- 管理対象外としたいファイル名を記載
- git addした後に、対象外としたい場合
  `$ git rm --cached <filename>`
  
