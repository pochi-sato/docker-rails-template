# アセット
- ruby: 2.5.0
- rails: 5.1.5
- mysql: 5.7.17

# starter
```
$ vi docker/mysql/password.env #passwordを設定しておく
$ docker-compose run --rm web rails new . --force --database=mysql --skip-bundle
$ docker-compose build
```

# 参考
- https://qiita.com/nak1114/items/1f7d48ff661555726427
