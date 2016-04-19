# Hello COINS15!

## 登録方法

* GitHubアカウントを作って、Membersの誰かにIDを教えると`invite`してもらえる。

## MacbookでGit使って管理したいマン

1. 鍵を作成する

`ssh-keygen -f ~/.ssh/hoge`

2. 公開鍵をGithubに登録する

* 自分のSettings&rarr;SSH and GPG keysにて\[New SSH key\]にhoge.pubの内容をそのまま書き込む

3. 秘密鍵とかidentifyする

`ssh-add ~/.ssh/hoge`

* Gitの使い方とかに関しては自分で調べてね
