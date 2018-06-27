# 思知问答机器人
  思知是作者的一个理想国，作者在人工智能方面不断努力着，希望有一天能够出现独立思考的人工智能机器人，虽然明知道短期内不可能实现，但却一直向着他的梦执着前行着。

## 项目介绍
机器人采用了基于知识图谱的语义感知与理解。知识图谱项目：https://github.com/ownthink/KnowledgeGraph

示范：https://robot.ownthink.com/

## 项目使用方式
下载到本地，直接用浏览器打开index.html即可使用。
```shell
git clone git@github.com:ownthink/robot.git
```

## 部署属于自己的机器人
get请求api示范
```
https://api.ownthink.com/bot?token=openbot&info=姚明多高啊？
```
post请求api示范
```
curl -XPOST https://api.ownthink.com/bot  -d'
{
	"token":"openbot",
	"info":"姚明多高啊？"
}
'
```

### api免费申请方式
直接将自己的信息发送邮件到help@ownthink.com即可申请。

或者加入qq群向群主申请 qq群：90780053

### api使用方式

申请后将可获得一个独立的token，将上面示范请求方式中token的openbot替换成自己的key即可。


