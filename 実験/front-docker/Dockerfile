# 使用するNode.jsの公式イメージをベースにする
FROM node:latest

# 作業ディレクトリを設定
WORKDIR /front
# 依存関係をインストール
RUN npm cache clean -f && npm install -g npm@latest && npm install create-next-app@latest