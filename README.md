# アプリケーション名
CatChat

# アプリケーション概要
猫好きの為のSNSアプリ。
自分の飼っている猫の写真や動画を投稿することが出来る。
他のユーザーと写真や動画を共有でき、共有された写真に対してコメントをつけられる。
チャットルームを作成でき、同じ趣味のユーザーとコミュニケーションが図れる。

# URL
※今後、デプロイ予定


# テスト用アカウント
※ログイン機能実装後、記載予定


# 利用方法


# 目指した課題解決
・他のSNSのアプリでは、猫以外の写真や動画もアップしていて混在してしまっている。
・上記の問題を解決する為に猫専用のアカウントを作成したが、いちいちアカウントを切り替える必要がある。
・猫好きである同じ趣味の人達と繋がりたい。
・可愛い猫の写真や動画を他の人達と共有したい。

# 洗い出した要件
## SNS認証機能
・ユーザーアカウント登録方法の選択肢を増やす。SNSアカウント（Googleアカウン、Facabookアカウント）を利用したログイン方法を選択肢として追加する。
・ユーザーアカウントの登録方法を「手打ち入力」「Googleアカウントを利用」「Facabookアカウントを利用」の3つから選べるようにする。

## ユーザー管理機能
・ユーザー(自分)が投稿したツイートが一覧表示される。
「マイページボタン」をクリックしたら、過去の全てのツイートが新しい順に一覧表示される。
・複数の猫を飼っている前提で、その猫に対してのツイートのみを表示させる。
・ツイートの表示方法を「全てのツイート」「猫１」「猫２」「猫３」のように切替えられるようにする。

## ツイート投稿機能
・登録されたユーザーがツイートを投稿出来る。
・「画像」または「動画」、「タイトル」、「コメント」、「猫の名前」、「タグ」を記載して投稿することが出来る。

## ツイートコメント機能
・登録されたユーザーが1つのツイートに対してコメント出来る。
・トップページまたはマイページのツイート一覧からコメントしたいツイートの「コメント」ボタンをクリックすると「コメント投稿画面」へ遷移する。
・コメント/編集/削除ができるドロップダウン形式のボタンがある。
(ツイートした本人のみ上記３つの表示があるが、他のユーザーのツイートの場合はコメントの表示しかない)
・「コメント投稿画面」には、コメント投稿フォームとコメント一覧の表示がある。
・コメント一覧はどのユーザーがコメントしたのか分かるようになっている。

## チャットルーム作成機能
・登録されたユーザーがチャットルームを作成出来る。
・特定のユーザーとのコミュニケーションを活性化する。
・チャットを行うユーザーを選択出来る。
・ユーザーがチャットルームの名前を決定出来る。
・トップページの「チャットを作成する」ボタンをクリックすると「新規チャットルーム作成画面」へ遷移する。
・チャットルーム名を記入するフォームが表示されている。
・プルダウンの中に、DBに保存されているユーザー名が表示されている。
・「チャットルームを作成する」ボタンをクリックするとチャットルームが作成出来る。

## ツイート検索
・ユーザーが簡単にデータ検索出来るようにする
・複数条件を指定した上で見たい猫のツイート検索を可能にする。
・ユーザー名/タグ/猫の種類などの検索条件を指定する欄を儲ける。
・条件に該当するツイートの検索結果のページで表示する。


# 実装した機能についてのGIFと説明
※今後、記載予定。

# 実装予定の機能


# データベース設計


# ローカルでの動作方法
