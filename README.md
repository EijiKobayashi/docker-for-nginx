# docker-for-nginx

docker
nginx + PHP7-fpm + mysql + phpMyAdmin の環境構築

- docker
- nginx
- php-fpm
- mysql
- phpMyAdmin

## 設定

Docker Desktop をインストールしてください。

[Docker Desktop](https://www.docker.com/products/docker-desktop)

---

## 使い方

#### 起動

- Web: [localhost:3000](http//localhost:3000)
- phpMyAdmin: [localhost:8080](http://localhost:8080)

```
$ docker-compose up -d
```

#### 状態

```
$ docker-compose ps
```

#### 終了

```
$ docker-compose down
```
