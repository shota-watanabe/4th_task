# README

### version
|name|version|
|--|--|
|Ruby|3.2.2|
|Rails|7.1.1|
|MySQL|8.0.25|

### SetUp
- master.keyを作成し、master keyを設定

```
touch config/master.key
```

#### start server
```
docker-compose up -d
```

[localhost:3001](http://localhost:3001/)

#### Database creation
```
docker-compose exec app rails db:create
```
