# tg_hot_news
一个能定时发送网络热搜的机器人<br>
效果 https://t.me/github_hot_news<br>
![](https://img30.360buyimg.com/pop/jfs/t1/213833/36/12552/294080/620c576dEf5451178/9fc46b3ee011d9d7.png)

# Github Actions说明
## 一、Fork此仓库
![](http://tu.yaohuo.me/imgs/2020/06/f059fe73afb4ef5f.png)
## 二、设置账号密码

添加名为**TGT**、**TGID**的变量  
值分别为**电报机器人token**、**电报用户(聊天室)id**<br>
TG@userinfobot可查询id<br>
TG@自己设置 通知机器人<br>
TG@BotFather开通<br>

示例：  
**TGT**
```
**********:AAHkzK6TogysoRANRg2vZqD7xEuaEk-****
```
**TGID**
```
1071**1658
```


## 三、启用Action
1 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
2 修改任意文件后提交一次  
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)

## 四、查看运行结果
Actions > TG_news_bot> build  
能看到如下图所示，表示成功  
![](https://img30.360buyimg.com/pop/jfs/t1/216934/12/12298/6124/620c59d5E8d0a2969/a0bb80d75060fddc.png)

此后，将会在每天早晚6:00、12:00开始发送（github当时不一定有机器）
若有需求，可以在[.github/workflows/run.yml]中自行修改

## 可能遇到的问题
- 1.  2025-04-17 1
