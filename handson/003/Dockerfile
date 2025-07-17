# NVIDIAのPyTorchイメージをベースにする (CUDA, cuDNNインストール済み)
FROM pytorch/pytorch:2.3.0-cuda12.1-cudnn8-runtime

# 作業ディレクトリを設定
WORKDIR /app

# コンテナ起動時にスクリプトを実行
# スクリプトはホストからのボリュームマウントで提供されることを想定
CMD ["python3", "main.py"]