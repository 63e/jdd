
## 京东部分活动薅羊毛
### （活动入口：京东app->我的->休闲游戏->更多工具）

| 活动名 |  相关文件 | 备注 |
| :----: | :----: | :----: |
| 东东农场 | [jd_fruit.js](jd_fruit.js) |    |
| 东东萌宠 | [jd_pet.js](jd_pet.js) |    |
| 种豆得豆 | [jd_plantBean.js](jd_plantBean.js) |    |
| 天天加速 | [jd_speed.js](jd_speed.js) |    |
| 摇钱树 | [jd_moneyTree.js](jd_moneyTree.js) |    |
| 取关京东店铺和商品 | [jd_unsubscribe.js](jd_unsubscribe.js) |    |
| 东东超市 | [jd_superMarket.js](jd_superMarket.js) |    |
| 东东超市兑换奖品 | [jd_blueCoin.js](jd_blueCoin.js) |    |
| 进店领豆 | [jd_shop.js](jd_shop.js) |    |
| 摇京豆 | [jd_club_lottery.js](jd_club_lottery.js) |    |
| 全名开红包 | [jd_redPacket.js](jd_redPacket.js) | 能运行，但无效果 |
| 京东多合一签到 | [jd_bean_sign.js](jd_bean_sign.js) | IOS软件用户请使用NobyDa的 [JD_DailyBonus.js](https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js) |

**脚本兼容: [QuantumultX](https://apps.apple.com/us/app/quantumult-x/id1443988620), [Surge](https://apps.apple.com/us/app/surge-4/id1442620678), [Loon](https://apps.apple.com/us/app/loon/id1373567447), JSBox, Node.js**

**PS：**
1.  修改了通知方式sever酱变为qmsg酱，函数名字没改
2.  secret中的PUSH_KEY为qmsg酱的KEY
3.  修改接收消息的qq以及发送人数需去有发送要求的js中修改
4.  各个sharecode需要去相应的sharecode.js中修改添加
5.  移除了宠汪汪相关，无法使用
6.  修改京东多合一签到发送的通知只显示概览
7.  京小超助力暂时无法使用

## 更多功能请参考[Saver233/joy-jd_scripts](https://github.com/Saver233/joy-jd_scripts)  本仓库自用为主

## 修改通知方法
### 例如：
	if($.index ===1){
		await notify.sendNotify(`${$.name}cookie已失效`, `京东账号${$.index} ${UserName}\n请重新登录获取cookie`, 你需要接收的qq1);
	}else if($.index ===2){
		await notify.sendNotify(`${$.name}cookie已失效`, `京东账号${$.index} ${UserName}\n请重新登录获取cookie`, 你需要接收的qq2);
	}
	······以此类推
	}
	
  - 暂时是[jd_pet.js](jd_pet.js)、[jd_fruit.js](jd_fruit.js)、[jd_shop.js](jd_shop.js)、[jd_unsubscribe.js](jd_unsubscribe.js)、[jd_superMarket.js](jd_superMarket.js)、[jd_blueCoin.js](jd_blueCoin.js)、[jd_bean_sign.js](jd_bean_sign.js)、[jd_club_lottery.js](jd_club_lottery.js)这8个文件需要修改通知。


### 特别感谢(排名不分先后)：
* [@NobyDa](https://github.com/NobyDa)

* [@chavyleung](https://github.com/chavyleung)

* [@liuxiaoyucc](https://github.com/liuxiaoyucc)

* [@Zero-S1](https://github.com/Zero-S1)

* [@uniqueque](https://github.com/uniqueque)

* [@nzw9314](https://github.com/nzw9314)
