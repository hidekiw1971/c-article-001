# module（共通部品）

## 概要

- 記事パターン
- 日付、お知らせ、記事タイトル、すべて見るで構成。

## イメージ画像

<img width="438" alt="image" src="https://user-images.githubusercontent.com/99580997/155553295-642f9982-520f-43b1-a8ba-72f2bfaff2ef.png">
<img width="788" alt="image" src="https://user-images.githubusercontent.com/99580997/155553039-6095dc3f-2fb4-40b1-bc27-ce449568f67f.png">
<img width="1310" alt="image" src="https://user-images.githubusercontent.com/99580997/155553178-000eb7d6-e088-470d-b9de-6b88d41f07de.png">

## 更新履歴

- 2022/3/26 模擬案件のヘッダー実装完了 → 細かい調整は後から調整する。
- 2022/3/26 作業開始前に push。
- 2022/3/24 ホバー時、左からスワイプを実装したが、動きがぎこちないので調査する。
- 2022/3/24 ホバー時、アンダーラインを表示する機能を実装 → 済
- 2022/3/23 機能追加
- 2022/2/24 初版　記事パターン 1

## portfolio url:

- https://css-md-0007.wtb.cfbx.jp/

## 参考にしたサイト

- CSS：ホバー時のアンダーラインアニメーションの実装サンプルと mixin を用いた実装方法
- https://www.nxworld.net/css-hover-underline-animation-examples-and-sass-mixin.html
- visibility
- https://developer.mozilla.org/ja/docs/Web/CSS/visibility
- CSS：ボタンホバー時に背景がスライドしたり領域を覆うアニメーションサンプル 10
- https://www.nxworld.net/10-css-hover-fill-animation.html
- リンク：location.href と window.open
- http://www.kogures.com/hitoshi/javascript/link/index.html
- 日付や時刻を属性値で指定する
- https://www.tagindex.com/html5/text/time_datetime.html

## module(共通部品)の使い方

- レスポンシブについては、sp: スマホ、 tb、pc: pc にデザインを合わせてます。
- 見難いので必要最低限の padding、margin のみ設定してます。必要に応じて再設定して下さい。
- 「お知らせ、すべて見る」は sp サイズは「display: block;」、tb、pc サイズは「display: inline-block;」に設定してます。
- html: copy start から copy end を使用。
- css: sass -> module -> article を使用。

## w3c html チェック結果

- https://validator.w3.org/nu/
- エラーあり
  <img width="1127" alt="image" src="https://user-images.githubusercontent.com/99580997/159742523-19e13ab6-01af-427e-bc68-666e89b314c6.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
  <img width="1255" alt="image" src="https://user-images.githubusercontent.com/99580997/159742624-427dffc9-c09c-4165-bec0-baa74a6a124c.png">

## 環境の使い方

- ダウンロードしたフォルダを開く
- ターミナルを開き、 npm i とコマンドを入力
- node_modules と package-lock.json が生成されるのを確認する
- 「 npx gulp 」とコマンドを入力すると動き出します
  å
