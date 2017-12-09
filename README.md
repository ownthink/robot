# 思知问答机器人
  思知是作者的一个理想国，作者在人工智能方面不断努力着，希望有一天能够出现独立思考的人工智能机器人，虽然明知道短期内不可能实现，但却一直向着他的梦执着前行着。

本项目api永久更新。。。

如果发送消息无反应，那就是服务器正在处理其他任务，暂时关闭api了，想要测试可以联系  help@ownthink.com

示范：https://robot.ownthink.com/

## 项目使用方式
下载到本地，直接用浏览器打开index.html即可使用。
```shell
git clone git@github.com:ownthink/robot.git
```

## 部署属于自己的机器人
(新版本地址，调试中：https://api.ownthink.com/angent/query?token=openbot&info=姚明的身高是多少啊？)
get请求api示范
```shell
https://api.ownthink.com/bot/query?token=openbot&id=yener&info=你好
```

post请求
```shell
https://api.ownthink.com/bot/query

{
    "token": "openbot",
    "id": "yener",
    "info": "你是谁？"
}
```

### api免费申请方式
直接将自己的信息发送邮件到help@ownthink.com即可申请。

或者加入qq群向群主申请 qq群：90780053

### api使用方式

申请后将可获得一个独立的token，将上面示范请求方式中token的openbot替换成自己的key即可。

id功能为robot对应多个用户的标识，暂时还未实现，可以随便填写。

