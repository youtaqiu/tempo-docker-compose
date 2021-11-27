# tempo-docker-compose
docker-compose for tempo
### 1.安装插件
```shell
 docker plugin install grafana/loki-docker-driver:latest --alias loki --grant-all-permissions
```

### 2.启动服务
```shell
docker-compose up -d
```
