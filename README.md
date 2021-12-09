# tempo-docker-compose
docker-compose for tempo
### 1.安装插件
```shell
 docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
```

### 2.创建grafana目录并赋权
```shell
mkdir -p grafana/data &&  sudo chown 472:472 grafana/data -R
```
### 3.创建docker-network
```shell
docker network create app
```

### 4.启动服务
```shell
docker-compose up -d
```
