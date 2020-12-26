# [Configs](https://py.loafing.cn/Configs)

## 这是一个公开仓库，用于备份各类非隐私的配置文件
*若发现任何不合适的内容请帮忙提醒 😶* 

### [Share](https://www.coolapk.com/apk/com.hengye.share) 微博屏蔽词
屏蔽理由包括但不限于：
- 舔美、精日、哈韩……恨不得东食西宿的精神肉体双分裂患者
- 低俗烂俗无限反刍无营养恶意钓鱼引战引流哗众取宠阴阳人谣棍歪屁股降智营销号
- 低龄幼稚疯狂无脑的流量明星粉丝群体。
- 疯狂刷屏的广告、头条怪
- 不感兴趣的话题：减肥、健身、美妆、低俗搞笑、乱搞男女关系极其衍生话题……

关于部分用户的屏蔽，不针对其本人，只是为了避免遭受相关群体/话题的精神污染

### [药方YAWF](https://tiansh.github.io/yawf/) 配置文件

还网页版微博一个清爽界面   
屏蔽词理由同上
支持正则表达式，例如屏蔽所有涉及张三的微博：/(?=.*张)(?=.*三)^.*$/mu

### banAD.ACL

粉灰机可用的ACL文件
 
屏蔽常用网站、视频、手机rom广告&运营商劫持广告&数据跟踪&开屏广告

### 其它应用配置备份
TBD...

## 添加至本地
**使用 Termux**
```
termux-setup-storage
cd ~/storage/downloads
git clone https://github.com/forliuyifei/Configs.git
cd
ln -s /storage/emulated/0/Download/Configs/ Configs
```
*或者 `git clone git@github.com:forliuyifei/Configs.git`*


