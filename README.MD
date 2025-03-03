DOCKER-COMPOSE-TEMPLATE

##  初始化

```bash
mkdirs -p /opt/stacks
```

## 启动

```bash
docker-compose up -d
```

## 启动特定服务

```bash
docker-compose up -d <service_name1> <service_name2>
```

## 停止

```bash
docker-compose down
```

## 停止特定服务

```bash
docker-compose down <service_name1> <service_name2>
```


