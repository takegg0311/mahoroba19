# ダイエットを褒めてくれる音声アシスタントを作ってみた
https://docs.google.com/presentation/d/13ZG5IxjKMes4sXozlWhHbufUGKcOTNFhQ0PNNtZlQ38/edit?usp=sharing

## LightningTalk 実施先
- まほろバ#19 (2025.01.10)
  - https://mahoroba.connpass.com/event/338761/

## ファイル構成
- README.md
  - このドキュメント
- mahoroba19_demo.ipynb
  - GoogleColab用Notebookファイル
  - シークレットを設定し、あすけんのアドバイスを転記して実行すると、アドバイス要約→にじボイス音声合成まで実行出来ます

## 使用サービス
- あすけん
  - https://www.asken.jp/
  - 会員登録し、食事記録を入力のうえ、「アドバイスを見る」から各種アドバイスを参照してください
- OpenAI API
  - https://platform.openai.com/
  - サインアップし、課金設定のうえ、OrganizationIDとAPIキーを発行してください
- にじボイスAPI
  - https://platform.nijivoice.com/
  - アカウント登録し、APIキーを発行してください
  - ボイス一覧から、任意のボイスモデルのIDを控えてください
