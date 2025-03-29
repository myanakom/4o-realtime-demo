# GPT-4o リアルタイムデモ

OpenAIのGPT-4oリアルタイムAPIを使用した音声チャットアプリケーションです。このアプリケーションを使用すると、マイクを通じてAIとリアルタイムで会話することができます。

## セットアップ方法

```bash
python -m venv uv
.\uv\Scripts\activate
pip install -r requirements.txt
```

## 実行方法

1. `.env`ファイルを作成し、OpenAI APIキーを設定します。

```
OPENAI_API_KEY=あなたのAPIキー
```

2. アプリケーションを実行します。

```bash
python -m main
```

3. マイクを通じてAIと会話します。

## 機能

- リアルタイム音声認識と応答
- 東雲コンシェルジェとして設定されたAIとの対話
- 会話の途中で割り込み可能