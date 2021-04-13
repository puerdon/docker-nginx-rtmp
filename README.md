# nginx rtmp multistream

## 初次使用

```sh
docker-compose build
```

## 接下來每次使用時

1. 更新 files/ig_text.txt 中的標題檔
2. 先用 python 的 itsagramlive 套件獲得 Stream ley
3. 將 Stream key 複製到 conf/nginx.conf 當中
4. 啟動 docker

```sh
docker-compose up -d
```
