# Hew2020 Dockerfile

カケオク用のDockerfile

# 導入手順

Dockerはインストール済みが前提  
作業スペースにクローン後以下のコマンドを同ディレクトリで順に実行  

```bash
$ docker-compose up -d
$ docker-cpmpose exec web bash

root@???/var/www/html# composer update
root@???/var/www/html# chown www-data storage/ -R
```

# Note
 
わからない点があれば連絡ください

# Version
Composer version 2.0.4 2020-10-30 22:39:11  
Node.js v10.22.1  
MySql 5.7  
