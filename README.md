# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)


# パソコミzenn記事管理リポ
## 記事作成方法
1. パソコミのGitHub組織アカウントにアクセス権がない場合はパソコミで[@kurages](https://github.com/kurages)をメンションして貰ってください。  
2. cloneしてローカルリポジトリに新しくブランチを作成してください。
3. ローカルリポジトリで`npx zenn new:article`を実行します。
4. 作成された記事テンプレのヘッダーを埋めてコミット&pushします。
5. GitHubでdraftなプルリクエストを作ってください。(baseはmainでおkです)
6. 記事を書きます。
7. 書き終えたらcommit & pushしてプルリクエストの画面で`ready for review`を押して反映されるのを待ってください。広報委員会から修正依頼があれば対応してください。  

## zenn-cli入れてないよって人はこちら
[workflow](https://github.com/pc-com/zenn/actions/workflows/init_article.yml)の
run workflowをクリックしてブランチ名と記事タイトルを入力することで、上記2~5を自動で行うことが可能です。  
少し待ってたらプルリクエストの作成も完了するのでローカルにcloneかcheckoutして記事を書いてください。  

```
# cloneする場合
git clone git@github.com:pc-com/zenn -b ブランチ名

# checkoutする場合(既にclone済みの場合はこっち)
git fetch
git checkout ブランチ名
```

