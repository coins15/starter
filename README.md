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

## コミットしていく方法

```
        <u>クローンを作る</u>
    git clone https://github.com/coins15/ぽよぽよ
    ディレクトリ「ぽよぽよ」に入る
        <u>あなたのブランチを作る</u>
    git checkout -b あなたの名前等
    ファイルの編集作業を行う
        <u>「ぽよぽよ」内のファイルをステージに追加する</u>
    git add .
        <u>あなたのブランチにコミットする</u>
    git commit -m "ここに雑なコメント"
        <u>GitHubにあなたのブランチを誕生させ、そこにファイルをコミットする</u>
    git push origin あなたの名前等(checkoutしたのと一緒)
```

最後のコマンドでこける場合は前述の設定を見直してください。

## とりあえず生成物を上げたい

```
    自分のブランチを作る(Switch branches -> create a branch)
    Upload Filesから上げたいファイルを選択
```
