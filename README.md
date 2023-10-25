### 使い方

#### ドキュメント閲覧方法
https://github.com/yuna1001/tbls-learning/blob/main/database/docs/README.md

#### スキーマ作成方法
1.  ルート階層で以下コマンド実行
```
tbls doc -f
```
2. `databases/doc`にファイルが作成される
3. `git push`し`main`ブランチにmergeする

#### excel出力方法
1.  ルート階層で以下コマンドを実行
```
tbls out -t xlsx -o ./docs/schema/shema.xlsx
```

