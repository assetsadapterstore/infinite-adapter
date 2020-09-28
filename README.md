# infinite-adapter

本项目适配了openwallet.AssetsAdapter接口，给应用提供了底层的区块链协议支持。

## 如何测试

openwtester包下的测试用例已经集成了openwallet钱包体系，创建conf文件，新建IF.ini文件，编辑如下内容：

```ini

#wallet api url
ServerAPI = "http://127.0.0.1:10001"

# fix gas limit
fixGasLimit = ""

```

## 区块链浏览器

https://www.if.vin/browser/