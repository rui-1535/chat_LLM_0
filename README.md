# My LLM Chatbot

## 概要
このプロジェクトは、ローカル環境で動作する簡単なLLM（大規模言語モデル）チャットボットの実装例です。  
Zennの記事「OpenAI APIを使わずにChatGPT風チャットを無料で実装する」を参考にしています。

## 動作環境
- OS: Windows, macOS, Linux
- Python: 3.8以上推奨
- 必要なライブラリ: requirements.txt に記載

## セットアップ方法
1. リポジトリをクローン  
   ```bash
   git clone https://github.com/ユーザー名/my-llm-chatbot.git
   cd my-llm-chatbot

2. ライブラリをインストール
bash
pip install -r requirements.txt

３．モデルのセットアップ
⑴Hugging Face にアクセス：

⑵.bin or .gguf ファイル（モデル）を選んでダウンロード
今回は、「mistral-7b-instruct-v0.1.Q4_K_M.gguf（4.37 GB）」をインストールした。

⑶models フォルダに入れる

##  使い方
⑴まず、cdでコードをクローンしたフォルダのパスの所まで移動する。

⑵コマンドラインで以下を実行して起動
bash
python main.py
起動後、プロンプトに従って質問を入力すると、モデルが回答を返します。

入力の終わりは改行で区切り、複数行入力する場合はバックスラッシュ（\）やスラッシュ（/）を利用してください。

## 注意事項
APIキーなどの秘密情報は公開しないでください。

モデルやデータのライセンスを必ず遵守してください。

ローカル環境によっては動作に時間がかかる場合があります。

## ライセンス
MIT License
