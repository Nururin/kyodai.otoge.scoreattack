# つかいかた
ver1.01
## 会員登録
* 会員登録をする
  - IDは変更できません.
  - 表示名はそのうち変更機能付けます(見て誰かわかる名前にしてね).
  - パスワードですが, 暗号化通信はしてません. なので普段使うようなパスワードは避けるようにお願いします.
  - 認証コードは **ykmkotk** です. 部外者を弾くためのものです.

## 登録後
* ログインする
* スコア登録ボタン もしくは ランキングボタン をクリックする
  - ランキングボタンを押すとランキング表示表示ページに遷移します.
    + そこから大会を選んでください.
  - 点数登録ボタンを押すと点数登録ページに遷移します.
    + 大会を選択し, さらに曲を選択してください.
    + 次に難易度を選択して, スコアを入力してください.
    + 尚、何度でもスコアは登録できます. 以前より低い点数に変更とかもできるので, 入力ミスしてももう一回入力すればいい安心設計です.
    + なお, 期間外の大会にはスコアを登録する事ができません.

## その他
* ログアウトは一応毎回やった方がいい気がします.
* 管理者メニューはそのうち誰かに管理者権限渡します.
* ゲスト参加者のスコアに関しては管理者メニューから登録できるようにします(たぶん).
  - さすがに1月スコアタ終わるまでには実装するから許して.

# 修正内容
## ver1.01
* **大会一覧** を **スコア登録** と **ランキング閲覧** に分割.
    - なんか大会一覧からじゃないとスコア登録できないのクソUIだなって思ったので.
* 期間の終了した大会をスコア登録不可能にできるようにした.
* さすがにそろそろ言い逃れできない気がしたのでハンデ機能を実装した.
    - ただしまだ手入力のみです.
    - 自動化しようにも過去のデータがあるわけじゃないのでまぁそのうち気が向いたら自動化します.
