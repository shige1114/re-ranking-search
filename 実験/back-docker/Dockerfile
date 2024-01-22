# 使用するPythonの公式イメージをベースにする
FROM python:3.9

# 作業ディレクトリを設定

WORKDIR /back

# ローカルのrequirements.txtをコピー
COPY requirements.txt .

# 依存関係をインストール
RUN pip install --no-cache-dir -r requirements.txt
