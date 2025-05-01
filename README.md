# git-exercise

## 1. gitの概要
> 協業のために、複数の開発者が、コードを共有し総合する。

### 機能一覧
* ソース合併
* ソースリビジョン管理
* ソースのリリース
* ソースのタギング
* ソースの変更チェック

## 2. 初期設定

### 初期設定の流れ
1．git config でgithub IDを設定
2．SSH設定
3．git initで、gitファイルを指定

### 2.1 git config 
```git config```はgitの環境設定をするための命令語

> 下記のアカウントの情報を設定する。   
> user name : coffee   
> user email : coffee@example.com   

*git config [範囲] user.name "coffee"*   
*git config [範囲] user.email coffee@example.com*

* ここで、範囲とは？ 

    * localとglobalがある。
    * 特定のフォルダのみに設定を使うか、全体の設定を使うかの違い
#### 2.1.1 local
> 特定フォルダだけ適用される設定   

該当するフォルダ.git/config が設定ファイル

### 2.3 SSH設定

#### 2.1.2 global
> git 全体に適用される基本設定   

~/.gitconfig (フォルダではなくファイル)

## 3. git 

名前をつけてレポジトリ指定　⇒　ブランチの生成

### 2.2.1 git init
レポジトリを設定する。作業する領域を指定する命令語。
### 2.2.2 git remote
git remoteは外部ののURL(githubなど)に名前をつけて管理する命令語

git remote add [名前]　[url]

名前はローカルで扱うためのもの。
urlは外部のレポジトリのURL
### 2.2.3 cloneした場合は？

cloneで持ってきたレポジトリのURLは自動的に登録されている。

-vは？
すべての内容を出力する。

### git push

git push [名前]　[ブランチ]


