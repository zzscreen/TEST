

### 一、README


iosgj

ios搞基

纯个人兴趣爱好，自用整理。

不接受任何内容性建议。（内容均从网络学习，部分内容来源于网络，若有侵权，请联系删除）。


![输入图片说明](https://9078f2a4.telegraph-image-7ff.pages.dev/file/4b6c99f759ca2b71c3734.jpg)


tg群：https://t.me/oncar2

需要科学网才能进，详情可在群内了解！


————————————————————

  
  
### 二、QX小白教程

新人，建议随便选一个导入QX即可，懒人配置。（[懒人配置导入QX教程](https://m2y.fun/quantumult-x-shi-yong-zhi-nan/#2.2.2%E5%AF%BC%E5%85%A5%E9%A2%84%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6)）

***提示：可以先保证自个能用上，正确的配置。然后慢慢看教程进行学习。一开始自个配置，容易失败，增强挫败感。有基础的忽视这句***


分享几个大神懒人配置：



- [matrix 配置](https://raw.githubusercontent.com/Centralmatrix3/Scripts/master/QuantumultX/matrix.conf)

- [Lucky 配置](https://raw.githubusercontent.com/As-Lucky/Lucky/main/Lucky-qx.conf)

- [小白配置](https://raw.githubusercontent.com/Orz-3/QuantumultX/master/Orz-3.conf)

- [墨鱼配置](https://github.com/ddgksf2013/Profile/raw/master/QuantumultX.conf) 

- [可莉配置](https://gitlab.com/lodepuly/vpn_tool/-/raw/master/Tool/QuantumultX/Config/Quantumult_X_Sample_Configuration_By_iKeLee.conf)

- [懒人配置](https://raw.githubusercontent.com/Sonmbs/quantumult_X/main/coconut.conf)

- [耳东橙配置 ](https://raw.githubusercontent.com/erdongchanyo/Rules/main/Quantumult%20X/LazyConf/QuantumultX_EDC-Lazy.conf)

- [彭于晏配置](https://raw.githubusercontent.com/89996462/Quantumult-X/main/py.conf)

- [奇心大陆配置](https://raw.githubusercontent.com/zwf234/rules/master/QuantumultX/qixin.conf)

- [毒奶配置](https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf)

- [莫离配置](https://raw.githubusercontent.com/GodMoli/QuanX/main/File/Auto.conf)


————————————————————



### 三、QX分流正则写法


资源来源网络，打不开需科学上网。

[QX使用指南（入门科普）](https://m2y.fun/quantumult-x-shi-yong-zhi-nan/)




分流策略组中，正则表达公式。(不白一般不太能理解几个组合一起的字样)

> 直白意思就是，**以某种规则，从众多选项中，按你的条件筛选并得出结果。**。

-  （模糊选择） ^(?=.*Gpt)，表示只要内容中包含Gpt字样就算，无论Gpt在这段话中的哪个位置，如节点，美国高速-加州-Gpt。
 
-  （模糊选择） ^(?=.*tiktok)，表示只要内容中包含tiktok字样就算。

-  （精确选择） ^*美国， 表示，必须以美国开头的内容。

> 如果我用chatgpt账号，只能登美国ID，那我就要对chatgpt进行分流，并把所有的chatgpt访问的网站，全部指向美国IP节点。我想找美国所有的节点，设置策略组。可以参考下列这样写:[（参考教程）](https://m2y.fun/quantumult-x-shi-yong-zhi-nan/)

-  ^*美国｜^(?=.*美国)｜^(?=.*us)｜^(?=.*US)


**各符号解释如下：**

> ^: 匹配字符串的开始。

> (?=.*xx): 正向零宽断言，确保有"xx"存在于字符串中。白话就是，括号内的，xx，你换成你想选择的内容就可以了，其它复制。



以上是常用的两类，后续有新更新，再科普。


————————————————————



### 四、QX自用（小白勿进）

Quantumult X 自用流程（非教程）

http://jiasuplus.com/fenxiangfuli/jiaocheng/quantumultx.html


***1、下载准备***
- [ ] Apple ID：美国ID
（路径商店：支付宝-选兑换码-境外-美国，购买一张10美元，充入自己ID中）
- [ ] 上网节点链接（1.1.1.1或其它白嫖节点也可）
- [ ] 手机上登ID，搜Quantumult X 下载安装到手机。


***2、配置***
- [ ] 1）如何添加资源解析器？
打开Quantumult X 配置文件（打开左下角，编辑按键，进入代码界面），找到 [general] 位置，添加以下代码并保存：

> resource_parser_url=https://raw.githubusercontent.com/KOP-XIAO/QuantumultX/master/Scripts/resource-parser.js

*（加完解析器保存时，如果出现服务器无法连接，用其他科学工具先连上梯子，再打开QX）*


- [ ] 2）加入节点（自行买）
在节点资源-加入订阅节点-打开资源解析器

- [ ] 3）证书安装
生成证书-配置证书-信任证书（两个位置）
切换到规则分流模式

4）测试节点连通性


***3、启动qx开关***
- [ ] 选择对应的节点，连上即可

***4、资源***
- [ ] 手机打开下链接 ，选QX资源，直接安装。
https://whatshub.top/


***5、享受***

——————————————————————

***同步设备***
如果是换手机或登入iPad之类的，都是自个的设备。

- [ ] A设备：先在QX里，进入设置，右上角-拷贝配置-icloud盘，记住改好名字，以便在另外一台设置中，导入时快速识别找到文件。
- [ ] B设备：登入美区ID，进入商店中，下载QX，然后进入QX设置的右上角，选关联配置，如果打开icloud的话，在icloud中选刚才A设备中拷贝的那个配置文件。（如果同步完后，没有出现节点等信息，请打开其它科学工具，先连一下梯子，同步上信息后，就可以全部同步了。无需任何手动）。



————————————————————


### 五、Shadowrocket共享ID



公益共享Sh ado wro ck et 小火见帐号网站。

（如果提示账号异常，说明用不了，就切换一个网站找）


[https://id.xxin325.cn/](https://id.xxin325.cn/)

[https://idshare.me/](https://idshare.me/)

[https://app.idshare.xyz/](https://app.idshare.xyz/)

[https://apple.iosshop.xyz/](https://apple.iosshop.xyz/)

[https://id.fcjs.xyz](https://id.fcjs.xyz)

[https://shadowrocket.top/ios](https://shadowrocket.top/ios)

[https://free.iosapp.icu](https://free.iosapp.icu)

[https://idfree.top](https://idfree.top)

[https://apple.laogoubi.net/s/c7d1e73290a646f2513f6f0b75843b0b](https://apple.laogoubi.net/s/c7d1e73290a646f2513f6f0b75843b0b)

[https://appleid.iossid.com](https://appleid.iossid.com)

[https://aunlock.laogoubi.net/s/df4ab9de842ce5f0abefcc560cf504f0](https://aunlock.laogoubi.net/s/df4ab9de842ce5f0abefcc560cf504f0)


Shadowrocket 懒人配置
[Lucky 配置](https://raw.githubusercontent.com/As-Lucky/Lucky/main/Lucky-Shadowrocket.conf)


————————————————————



### 六、Appstore 无法下载




***解决AppStore无法下载应用BUG***

自从巨魔商店发布以来，出现 AppStore 无法下载+更新的情况越来越多。

原因基本都是使用 AppsManager 或者轻松签恢复别人的备份数据后出现的，之前我也中招过：AppStore不能安装App了只能抹机解决

现在，终于有方法了，亲测有效！

首先必须是设备越狱或者巨魔用户，下载并安装了 Filza


打开Filza，一直返回到根目录，进入这个路径： /usr/bin/

单击 vm_stat －点继续，把输入法切换为英文
复制以下代码：

chown 0:0 /var/tmp && chmod 777 /var/tmp && chown 501:0 /var/tmp/com.apple.appstored && chmod 700 /var/tmp/com.apple.appstored


在输入的地方长按－点击Paste(粘贴)－点击右下角的return(回车)

返回设备桌面，去AppStore下载APP试试，已经成功了！

如果桌面出现一堆App待下载是正常的，直接删除就行了，可能是之前在不能下载的时候尝试下载的那些App


————————————————————



### 七、Sileo源



#复制以下所有地址，打开并添加进sileo里，自动添加所有。
#源地址：

https://wwg135.github.io/
https://rootless.zq666.eu.org/
https://0xkuj.yourepo.com/
https://byg.iosios.net/
https://xiangfeidexiaohuo.github.io/
http://apt.htv123.com/
https://apt.wxhbts.pro/
https://laileld.github.io/repo/
https://apt.25mao.com/
https://repo.snailovet.com/
https://lclrc.github.io/repo/
https://flyx099.github.io/repo/
https://lenglengyu.com/
https://alias20.gitlab.io/apt/
https://repo.anamy.gay/
https://apt.cydia.pro/
http://apt.thebigboss.org/repofiles/cydia/
https://repo.chariz.com/
http://dcsyhi1998.github.io/
https://dhinakg.github.io/repo/
https://ellekit.space/
https://havoc.app/
https://huayuarc.cn/
http://limneos.net/repo/
https://repo.niceios.com/
https://opa334.github.io/
https://repo.palera.in/
https://apt.procurs.us/
https://roothide.github.io/
https://iosjb.top/
https://skitty.xyz/repo/

/免责声明：所有资源均来自网络搜集，如有不便公开的请联系删除。


————————————————————


### 八、tg解除-限制
 

tg解除 敏感内容 限制：

必须先设置用户名id

**Telegram 手机版** 

> https://web.telegram.org

浏览器打开官网 登陆账号
（验证码 在app内）

**成功登入Telegram 网页版后，点选左上角“选单”按钮**

- 点选“Settings” 
- Privacy and Security
- Sensitive Content 
- 开启Disable filtering  √
- 重启app 重新加群


享受高c吧


————————————————————



### 九、斗图-WX插件


本设置，仅用于WC插件-斗图助手。

**第一步 - 斗图设置**
开启斗图功能 
开启允许超长关键字 
开启自定义API 
开启自定义接口，填入以下接口地址: 
> https://doutu.lccyy.com/doutu/all 
顺带复制一下微信原始ID [微信ID很重要请勿忽视！]

**第二步 - 准备设置自定义字体**
- 首次使用 
> https://doutu.lccyy.com/doutu/all 
接口 请在微信搜索框
任意输入关键词点击[斗]按钮搜索！ 

- 请使用微信浮窗或自带浏览器打开本页面网址: 
> https://doutu.lccyy.com/static/font.html 

在微信ID输入框中，黏贴刚刚复制的微信ID 
点击获取按钮！ 

- 获取成功后，会出现[保存配置]按钮！如匹配失败，请严格按此说明重新操作！ 

- 开启你的自定义字体吧~！

- 你已完成所有的操作，选择你的字体样式，保存配置。 

- 在斗图搜索关键词，第一个表情就是字转图表情啦！

**非主流闪光字体**

无需插件，网页打开，进去勾选即可。
**[点击设置](http://jiqie.zhenbi.com/g/m14.htm)**



————————————————————


### 十、电池去除维修提示




目前仅支持_TrollStore_或者_越狱环境_操作，可以去除原装电池正常使用低于80健康的维修提示
​这里需要注意的是并不是去掉换了第三方电池显示维修(这个是因为无法验证正品才显示)

1. [ ] 实际操作方法： 首先打开TrollStore 巨魔商店或者越狱环境下安装Filza
然后打开Filza找到路径：

> /var/MobileSoftwareUpdate/Hardware/Battery/Library/Preferences/``com.apple``.batteryhealthdata.plist


1. [ ] 最后找到这个路径并打开

> com.apple``.batteryhealthdata.plist

1. [ ] 把Battery Service Flags值改成**“3”**
1. [ ] 把Battery Service State值改成**“0”**

1. [ ] 把Maximum Capacity Percent值改成大于80的数字

**修改以后点击右上角储存，关机重启就可以了。**


————————————————————

 

### 十一、运营商ipcc

一般不建议改。[教程](https://www.i4.cn/news_detail_37404.html)

[iPCC下载地址](https://wwk.lanzoue.com/b01vpi8xc)


不要随便乱改，容易没有信号。


