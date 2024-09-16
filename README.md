# ①課題番号-プロダクト名

予約アプリ〜更新・削除〜

## ②課題内容（どんな作品か）

- ユーザー登録することでお客様番号が払い出される
- カレンダーの日付を押下することで予約が登録できる
- カレンダーにある予約を押下することで、予約日時の更新とキャンセルができる<br />
※お客様番号を間違えないように更新・削除を行う

## ③DEMO

デプロイしている場合はURLを記入（任意）
https://challenge-netsu.sakura.ne.jp/reserve-app-2/
## ④作ったアプリケーション用のIDまたはPasswordがある場合

- ID: なし
- PW: なし

## ⑤工夫した点・こだわった点

- DB操作をクラス化して各ソース上でインスタンスを作ってクエリを実行させた
- お客様番号の払い出しと確認を一つのコンポーネント上で実現した（UX改善）
- カレンダーの日付を押下することで予約登録ができるように改善した（UX改善）
- カレンダーの予約を押下することで、予約日時の変更、予約キャンセルを行えるようにした

## ⑥難しかった点・次回トライしたいこと(又は機能)

- カレンダーの日付押下で日付の値を取得して、POSTパラメータに入れること
- カレンダーの予約を押下することで、予約日時とお客様番号を取得して、POSTパラメータに入れること
- 日付、予約押下時にデフォルトで該当するデータを入力フォームに格納するように処理を行なったこと
- クライアント側で全予約に対して、更新・削除が行えてしまうので、ログイン機能をつけて操作しているユーザーのみの予約状況の更新・削除が行えるようにしたい
- カレンダーの休日も黒文字なので、休日と祝日を取得してカレンダーの文字色を変更したい
- DB操作でトランザクションを意識した開発を次は行なってみたい

## ⑦質問・疑問・感想、シェアしたいこと等なんでも

- [質問]
- [感想]更新の時に講義で教えてもらった失敗例（WHERE句の指定ミス）を見事にやってしまった。あまり時間が取れず、UIにこだわれなかった。。。
- [参考記事]
  - 1. https://qiita.com/OtsukaTomoaki/items/0fa05e0d408cccf4d187
  - 2. https://fumiononaka.com/Business/html5/FN2107001.html
  - 3. https://qiita.com/BRS_matsuoka/items/ebcc8ab655bb373e36c7