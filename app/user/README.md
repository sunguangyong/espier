### 用户服务
# 生成user rpc
```
在user.proto文件路径下执行命令 
goctl rpc protoc user.proto --go_out=. --go-grpc_out=. --zrpc_out=.
```

# 生成db model
```
goctl model mysql ddl -src ../../../db/user.sql -dir ./model

```
