## 使用方法

### 方法一：本地安装Node.js，下载本库脚本

  - 教程请见：[EvineDeng/jd-base](https://github.com/EvineDeng/jd-base)

### 方法二：腾讯云函数

  - 腾云云函数使用 [简要说明](iCloud.md)
        
### 方法三：GitHub Action（自用的是此方法）

 - 使用教程暂且可看 [这里](githubAction.md)
 
### 方法四：Docker（NAS或VPS用户）

 - 可以精确控制任务运行时间，有三种办法：[docker办法一](https://github.com/lxk0301/scripts/tree/master/docker)、[docker办法二（和本地安装Node.js有点类似）](https://github.com/EvineDeng/jd-base)、[docker办法三](https://github.com/chinnkarahoi/jd-scripts-docker)

#### 注：以上四种运行机制都是Node.js，故您需仔细阅读下面几点

  - 如果使用方法一与方法二，需自行提供京东cookie填写到 [jdCookie.js](https://github.com/lxk0301/scripts/blob/master/jdCookie.js) 里面

  - 方法三京东cookie不要填写到 [jdCookie.js](https://github.com/lxk0301/scripts/blob/master/jdCookie.js) 里面，填写到secret中

  - 方法四Docker安装Cookie请见各自的说明。

### 方法五：iOS系统的代理软件（QuantumultX, Surge, Loon）

#### 以下内容只针对iOS用户

#### ios使用多个京东账号，需要使用BoxJs保存多会话进行切换 

##### BoxJs简单说明可看作者[BoxJs仓库地址](https://github.com/chavyleung/scripts/)

使用box可以实现远程订阅助力好友(需订阅此 [链接](https://raw.githubusercontent.com/lxk0301/scripts/master/lxk0301.boxjs.json))

- [BoxJs使用教程](https://chavyleung.gitbook.io/boxjs/)

- [BoxJs教程视频](https://youtu.be/eIpBrRxiy0w)


【用box订阅的好处】

 1、脚本也可以远程挂载。京东活动助力功能的分享码只需在box里面填写。以后只需远程更新就行。

 2、所有脚本的cookie都可以备份，方便你迁移到其他支持box的软件。

 3、box可以支持多账号