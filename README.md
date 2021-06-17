# transfer
币安智能链（BSC）命令行转账工具，支持BNB和合约token转账

### 使用说明

到这下载二进制文件    
https://github.com/zhaozilong88/transfer/releases/tag/v1.0.0  


查看帮助
```
transfer -h
```

BNB转账
 
```
./transfer -token=BNB -private_key=发送方私钥 -to=接收地址 -amount=数量（wei）
```

token转账
```
./transfer -token=合约地址 -private_key=发送方私钥 -to=接收地址 -amount=数量
```

