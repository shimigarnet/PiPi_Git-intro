# PiPi_Git-intro
## 0. はじめに
今回の実習で使うものの準備をします！
### 0.1 事前設定
Git-GitHub講習会では事前に以下の環境が整っている前提で進められます。
 - Visual Studio Code
 - GitHubアカウント


> [!WARNING]
> この資料では{}で括られているところは自分の情報に合わせて書き換えてください  
> 例：
> ```
>git config --global user.name {userName}
>↓
>git config --global user.name mehm8128
> ```

> [!IMPORTANT]
> 何か問題が起きたら気軽に相談しましょう！

### 0.2.1 GitHubリポジトリのクローン
リポジトリとは：
リモートリポジトリをローカルにコピーする作業です。  
1. GitHubで作成したリポジトリのページにて`HTTPS`を選択し、URLをコピー (赤丸の箇所をクリックでコピーできる)
2. VScodeを開いて`Gitリポジトリのクローン > 先のURLをペーストし"Enter"を押す`

### 0.2.2 Gitの設定
ターミナルで以下のコマンドを実行してください。
```
# ユーザー名の設定。GitHubのIDがおすすめ
git config --global user.name {userName}
# メールアドレスの設定。GitHubと同じものがおすすめ
git config --global user.email {userEmail}
# コミットメッセージをVScodeで書けるようにする設定
git config --global core.editor 'code --wait'
# デフォルトのブランチをmasterからmainに変更。
git config --global init.defaultBranch main
```
## 1. 開発の進め方

### 1.0 便利な拡張機能
Git History
Git Graph

### 1.1.1 ブランチの発行

### 1.1.2 変更をステージする

### 1.1.3 変更をコミットする

### 1.1.4 変更をプッシュする

### 1.2.1 プルリクエストを出す

### 1.2.2 プルリクエストを精査する

### 1.2.3 プルリクエストをマージする

### 1.3.1 リモートの変更をローカルに同期する

# 2. 補足説明

### 2.1 GitHubに上げたくない情報があるとき

### 2.2.1 間違えてCommitしたとき

### 2.2.2 ブランチ名を間違えたとき
