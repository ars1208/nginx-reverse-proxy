# nginxを使ったリバースプロキシのテスト

## 実行コマンド
```
docker-compose up
```

Webサーバ2台とリバースプロキシのコンテナが立ち上がる
ブラウザから `http://localhost/dog` もしくは `http://localhost/cat` にアクセスすると、それぞれの `index.html` を確認することができる。


## 参照
- [実践編ーDockerを使ってnginxでリバースプロキシを立ててみる](https://qiita.com/zawawahoge/items/d58ab6b746625e8d4457)