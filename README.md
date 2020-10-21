# 思知问答机器人
  思知是作者的一个理想国，作者在人工智能方面不断努力着，希望有一天能够出现独立思考的人工智能机器人，虽然明知道短期内不可能实现，但却一直向着他的梦执着前行着。

## 项目介绍
机器人采用了基于知识图谱的语义感知与理解。

自然语言处理工具：https://github.com/ownthink/Jiagu

知识图谱项目：https://github.com/ownthink/KnowledgeGraph

语义理解项目：https://github.com/ownthink/Semantic

机器人示范：https://www.ownthink.com/robot.html

## 项目使用方式
下载到本地，直接用浏览器打开index.html即可使用。
```shell
git clone git@github.com:ownthink/robot.git
```

## 部署属于自己的机器人
get请求api示范
```
https://api.ownthink.com/bot?appid=xiaosi&userid=test&spoken=姚明多高啊？
```
post请求api示范
```
curl -XPOST https://api.ownthink.com/bot  -d'
{
	"appid":"xiaosi",
	"userid":"test",
	"spoken":"姚明多高啊？"
}
'
```

### api免费申请方式
```text
注册账号，创建机器人：https://console.ownthink.com/

或者加入qq群向群主申请 
人工智能qq群1：90780053(满)
人工智能qq群2：956936481（满）
人工智能qq群3：1160292084
知识图谱qq群1：55152968（满）
知识图谱qq群2：740104333
```
### api使用方式

申请后将可获得一个独立的appid，将上面示范请求方式中appid的xiaosi替换成自己的appid即可。


