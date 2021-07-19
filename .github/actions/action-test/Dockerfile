FROM alpine:3.10

COPY entrypoint.sh /entrypoint.sh

RUN chmod +x entrypoint.sh

# イメージを実行される時のコマンド
ENTRYPOINT ["/entrypoint.sh"]
