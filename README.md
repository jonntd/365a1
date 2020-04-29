# 用Azure的github部署实现自助创建365子号
# https://365a1.azurewebsites.net


1 进入azure AD新建一个app，获取tenant id和client id
![image.png](https://i.loli.net/2020/01/26/57GcEDYlQFTOMBL.png)

2 新建一个client secret
![image.png](https://i.loli.net/2020/01/26/qUeV2x8abHlDPO3.png)

3 获取订阅的 skuid，自行谷歌一下方法吧，用powershell之类的

修改相应数据
tenant_id = ''
client_id = ''
client_secret = ''
skuId = '314c4481-f395-4525-be8b-2ec4bb1e9d91'
# skuId = '94763226-9b3c-4e75-a931-5c89701abe66'
domain = ''

