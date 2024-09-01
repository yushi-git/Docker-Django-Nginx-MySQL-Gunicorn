FROM nginx:1.21-alpine

# ローカルのdefault.confをコンテナにコピー
COPY containers/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

# 鍵ファイルをコンテナにコピー
COPY containers/nginx/server.crt /home/server.crt
COPY containers/nginx/server.key /home/server.key
