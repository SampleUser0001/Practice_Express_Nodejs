# Practice_Express_Nodejs
Expressの練習

## myapp

本当に普通のHello World。

``` bash
cd myapp
npm install
npm start
```

[http://localhost:3000](http://localhost:3000)

### アクセスする

``` bash
# GET
curl localhost:3000

# POST
curl -d "" localhost:3000

# PUT
curl localhost:3000/user/ -XPUT

# DELETE
curl localhost:3000/user/ -XDELETE

```



## generatorを使う

``` bash
cd myapp_by_express_generator
npm install

DEBUG=myapp_by_express_generator:* npm start
```

## 参考

- [Express:公式](https://expressjs.com/)