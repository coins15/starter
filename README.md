# Hello COINS15!

## 登録方法

* GitHubアカウントを作って、Membersの誰かにIDを教えると`invite`してもらえる。

## MacbookでGit使って管理したいマン

1.鍵を作成する

`ssh-keygen -f ~/.ssh/hoge`

2.公開鍵をGithubに登録する

* 自分のSettings&rarr;SSH and GPG keysにて \[New SSH key\] にhoge.pubの内容をそのまま書き込む

3.秘密鍵とかidentifyする

`ssh-add ~/.ssh/hoge`

* Gitの使い方とかに関しては自分で調べてね

## 二段階認証してる人がログインできない問題

* パスワードにSettings&rarr;Personal access tokensにて \[Generate new token\] で生成したトークンを入れる

## とりあえず生成物を上げたい(gitコマンドでやる方法)

* 生成物が入ったフォルダで以下のコマンドを叩く

```
	git init
	git add ./うpしたいもの
	git commit -m "ここに雑なコメント"
	git remote add origin git@github.com:coins15/リポジトリ名.git
	git push -u origin master
```

最後のコマンドでこける場合は前述の設定を見直してください。
