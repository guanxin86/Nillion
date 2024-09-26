# Nillion
nillion常用命令
### 拉取版本
```
docker pull nillion/verifier:v1.0.1
```
### 重新运行
```
docker run -d --name nillion \
-v ./nillion/accuser:/var/tmp nillion/verifier:v1.0.1 verify \
--rpc-endpoint "https://nillion-testnet-rpc.polkachu.com"
```
