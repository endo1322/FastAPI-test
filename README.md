# プロジェクトの起動方法

```
// パッケージのインストール
poetry install

// apiサーバの立ち上げ
// FastAPIサーバーがホスト0.0.0.0でリロードモード（コード変更時に自動で再起動）で動作する
poetry run uvicorn fastapi_test.main:app --host 0.0.0.0 --reload
```
