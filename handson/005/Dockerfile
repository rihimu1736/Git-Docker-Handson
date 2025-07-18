# ベースイメージを指定
FROM python:3.11-slim

# 作業ディレクトリを設定
WORKDIR /app

# 依存関係ファイルをコンテナにコピー
COPY requirements.txt .

# 依存ライブラリをインストール
RUN pip install -r requirements.txt

# コンテナ起動時に実行されるデフォルトのコマンド
CMD ["/bin/bash"] 