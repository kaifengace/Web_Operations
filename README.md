# 网站运营期末项目

#### 基本信息
- 个人网站域名：http://hukaifeng.me
- 网站主题：新闻

#  一、策划
###  策划文档

####  网站建设目标

1. 为用户提供社会 体育 财经的相关信息。
1. 给对社会 体育 财经感兴趣的用户提供一个“信息社区”，并逐渐增强用户粘性。


####  目标用户画像 DVF模型
- 用户需求：我的网站的主要功能是提供实时的社会新闻，体育新闻，财经新闻资讯，因此我们主要用户群是想要了解相关资讯的用户。面向的用户是倾向了解社会，体育，财经新闻的用户群体，因此，我的用户需要的是简单的新闻资讯

- 可行性：新闻信息量丰富,传播范围观，用户群体大。

- 可持续性：可以不断更新文章，凝聚用户。


###  网站地图

- 网站地图地址：http://hukaifeng.me/sitemap_index.xml


###  图片的使用（版权，风格及配色）
### 图片的使用
 #### 非原创图片
##### 1.新建“关于我”的页面，声明网站内容来源非原创性。
![关于我们](https://gitee.com/hukaif/web_operations/raw/master/images/版权说明.PNG "版权说明.PNG")


### 云端架站踩坑图文文章(3篇）
* [架站教程（一）：WordPress用户注册和发送邮件](http://hukaifeng.me/%e4%ba%91%e7%ab%af%e6%9e%b6%e7%ab%99/wordpress%e6%9e%b6%e7%ab%99%e9%97%ae%e9%a2%98%ef%bc%88%e4%b8%80%ef%bc%89/)
* [架站教程（二）：申请DigitalOcean的50刀优惠码](http://hukaifeng.me/%e4%ba%91%e7%ab%af%e6%9e%b6%e7%ab%99/wordpress%e6%9e%b6%e7%ab%99%e9%97%ae%e9%a2%98%ef%bc%88%e4%ba%8c%ef%bc%89/)

* [架站教程（三）：namecheap域名如何绑定IP](http://hukaifeng.me/%e4%ba%91%e7%ab%af%e6%9e%b6%e7%ab%99/wordpress%e6%9e%b6%e7%ab%99%e9%97%ae%e9%a2%98%ef%bc%88%e4%b8%89%ef%bc%89/)


###  平面设计
#### 1. 网站配色，背景及字体的对比度及可读性
- 网站配色：黑白
- 对比度：适中
- 可读性：良好
- 整体风格配置解析：由于网站的主题是新闻，需要比较带有真实感的页面，因此网站主要采用黑白配色。适中的对比度显得我们的网站更加亲切温和，有利于吸引用户，让用户感到舒适。网站整体可读性不错，能够依靠分区设计找到自己想要的内容。
![图库配色](https://gitee.com/hukaif/web_operations/raw/master/images/架站问题.PNG "架站问题.PNG")


#### 2. 插件运用
- Animate ：
（1）网站侧边栏中的小工具近期文章栏添加了 animated bounce duration的动画。

- SiteOrigin：
（1）在网站的分页面中有使用到此功能，并通过此功能建立页面与文章之间的联系，使得可以从页面跳转到文章内容。
（2）在网站首页中设置
（3）在网站地图中设置

# 二、管理

## 1.云端架站
- 正常可用的云端网站，使用域名: http://hukaifeng.me

## 2.网站安全
- 使用Wordfence，相关监控截图，说明通过此监控了解到自己网站的安全性如何
####  1. 使用Wordfence进行监控

![wordfence](https://gitee.com/hukaif/web_operations/raw/master/images/a1.png
"wordfence.png")

#### 2. Wordfence监控工具——live traffic

![监控工具](https://gitee.com/hukaif/web_operations/raw/master/images/live.png
"live.png")

-  通过插件中的“实时交通”工具，可以发现网站最近发生的情况。如上图，可以发现该网站的类型均为“Human/人的”，即都是正常的登录活动，并没有收到相关警告或者出现防火墙阻止的情况，表示网站在安全性能方面尚可。

####  3.阻止攻击的状况
![阻止攻击次数](https://gitee.com/hukaif/web_operations/raw/master/images/阻止攻击次数.png
"阻止攻击次数.png")

-  通过该图，可以实时知道网站24小时内/30天内阻止攻击的次数，可以通过图表了解各时间段网站的阻止攻击次数，发现哪个时间段是遭受过较多攻击的。


## 3.网站性能
- 使用site24x7，相关监控截图，添加8个监控地点，说明通过此监控了解到自己网站的性能如何
####  1. 使用site24x7进行监控
![输入图片说明](https://gitee.com/hukaif/web_operations/raw/master/images/a1.png
"wordfence.png")


####  2.添加8个监控地点
![Site24x7](https://gitee.com/hukaif/web_operations/raw/master/images/Site24x7.png "Site24x7.png")

![监控地点](https://gitee.com/hukaif/web_operations/raw/master/images/监控地点.png "监控地点.png")

-  可以从监控图中了解到8个不同位置的网站可用性与响应时间。6个地区的网站可用性为100%；1个地区的网站可用性为99.8%；只有1的地区的网站可用性为60.92%，可以说明该网站目前的可用性是较高的。

## 4.网站备份
####  1.登录winSCP
####  2.将wp-config.php备份到本地
![php](https://gitee.com/hukaif/web_operations/raw/master/images/php.PNG "php.PNG")


####  3.通过插件备份数据库文件（sql文件）
![插件备份](https://gitee.com/hukaif/web_operations/raw/master/images/插件备份.PNG "插件备份.PNG")

![备份结果](https://gitee.com/hukaif/web_operations/raw/master/images/备份结果.PNG "备份结果.PNG")

####  4.通过WordPress后台导出工具导到本地的文件
![监控地点](https://gitee.com/hukaif/web_operations/raw/master/images/导出.PNG "导出.PNG")

#  三、运营

###  站长工具

###  百度——流量截屏
![流量截图](https://gitee.com/hukaif/web_operations/raw/master/images/流量截图.png "流量截图.png")

####  成果
####  1. 认证后，在百度搜索引擎中可以找到结果：

![百度认证后](https://gitee.com/hukaif/web_operations/raw/master/images/百度认证后.png "百度认证后.png")

####  2. 经过SEO的优化（下文有提及）后，目前排名在第3页中间部分：

![SEO后百度搜索](https://gitee.com/hukaif/web_operations/raw/master/images/SEO后百度搜索.png "SEO后百度搜索.png")


***

###  Bing——流量截屏
![流量截屏](https://gitee.com/hukaif/web_operations/raw/master/images/bing流量截图.PNG "bing流量截图.PNG")
####  成果
####  通过认证后，在Bing搜索引擎中可以找到结果：
![bing认证后](https://gitee.com/hukaif/web_operations/raw/master/images/bing认证后.PNG "bing认证后.PNG")
***





##  SEO

####  SEO中反映的问题：
![SEO优化前](https://gitee.com/hukaif/web_operations/raw/master/images/SEO优化前.PNG "SEO优化前.PNG")


多篇文章中，都存在这以下的问题：
- 无添加元描述或元描述长度不符合规定
- 没有添加内部链接（从你的网站该页面跳转到你网站另一页面的链接）
- 没有出站链接（从你的网站到其他网站的链接）
- 关键字长度评估不好
- 没有图片 字数不够

***
###  以《2019年5G大战揭幕，当今世界谁的实力最强？》为例

![已此篇文章为例.PNG](https://gitee.com/hukaif/web_operations/raw/master/images/已此篇文章为例.PNG "已此篇文章为例.PNG")

***

###  **做了什么改进？** 
**1、在文章中用html添加了出站链接，如下图：**

![加入内链](https://gitee.com/hukaif/web_operations/raw/master/images/加入内链.PNG "加入内链.PNG")
***

**2、为了解决无添加元描述的问题，我在以下的输入框键入可以总结页面内容的文字，元描述的长度应控制在120字符至150字符为佳。如下：**

![meta](https://gitee.com/hukaif/web_operations/raw/master/images/meta.png "meta.png")
***

**3、修改合适的关键词，涉及文章重点，长度适中；**

![关键词](https://gitee.com/hukaif/web_operations/raw/master/images/关键词.PNG "关键词.PNG")
***

**4、给文章添加图片，并编辑图片的替代文本（要含有文章关键词)；**

![输入图片说明](https://gitee.com/hukaif/web_operations/raw/master/images/添加图片.PNG "添加图片.PNG")
***

**5、给文章里面的部分专业术语添加外部链接。**

![添加注释](https://gitee.com/hukaif/web_operations/raw/master/images/添加注释.PNG "添加注释.PNG")

***
以下是多篇文章经过SEO部分优化后的情况：

![SEO后](https://gitee.com/hukaif/web_operations/raw/master/images/SEO后.PNG "SEO后.PNG")
***

####  jetpack流量数据
![jetpack流量统计](https://gitee.com/hukaif/web_operations/raw/master/images/jetpack.PNG  "jetpack.PNG")

**可以发现，在做出SEO优化后，过了几周里，网站的浏览量逐步上升。 其中，6/17-6/24网站浏览量下降的原因是因为这几天未更新新文章。**

***


##  用户研究成果及设计改进

####  用户体验地图

![用户体验地图](https://gitee.com/hukaif/web_operations/raw/master/images/用户体验地图.png "用户体验地图.png")

####  用户访谈

设定的问题：

- 用户偏好暖色网站背景还冷色网站背景？

访谈结果：受访者表明更为喜欢偏暖色的网站背景。他们认为偏明亮的风格可以使网站显得更为鲜明干净，能够增加网站的可读性同时还能让人感到愉悦。也有受访者喜欢冷色网站背景，他们认为冷色使网站适合较长时间浏览网站而不会那么伤眼睛。

解决方法：最终选择了暖色色调的网站模板

- 在目录页面，是喜欢文章只显示概述而不是直接显示全文，还是直接显示全文？

访谈结果：受访者都喜欢在目录页面，文章只显示概述。他们认为这样可以使页面更为简洁以及文章排序更为整齐，这样内容就更容易找到而且增加了可读性。

解决方法：在目录页面，是喜欢文章只显示概述

- 喜欢文章是纯文字的还是带有配图的？

访谈结果：受访者喜欢文章内带有配图的，他们认为如果文章的字数较多，适当的插入几张养眼的图片可以缓解一下视觉疲劳，而且有的配图还能帮助用户理解文章的内容。

解决方法：当文章的字数较多或者文章内容较为难理解，则可适当加入配图帮助用户理解文章内容。

### 成果
####  总结出目前网站各方面存在的一些问题，如下：

####  1.平面设计
***
-  图片尺寸不合适，网站背景颜色偏亮，导致字体对比度不够强、色调不搭，影响用户阅读心情；

![图片尺寸不合](https://gitee.com/hukaif/web_operations/raw/master/images/图片尺寸不合.PNG "图片尺寸不合.PNG")


####  2.内容

-  网站里的文章建议多添加外链，对于对大数据知识不太熟悉的人有些专业名词可能不太清楚，可以放置外链跳转到百度百科让他们了解；

-  如下图所示：
![添加外链](https://gitee.com/hukaif/web_operations/raw/master/images/定制化.PNG "定制化.PNG")



####  如何影响设计

#####  就以上问题，对网站各方面进行修改、改善：
-  更改网站的背景颜色，以提高字体对比度。
-  文章内添加图片、外部链接，使文章的可读性更强；
-  修改文章布局；

####  定制化
#####  方案1
- 使用代码，将重点语句以不同的字体颜色和不同字体尺寸突显出来
![修改字体风格](https://gitee.com/hukaif/web_operations/raw/master/images/修改字体风格.PNG "修改字体风格.PNG")

![修改字体结果](https://gitee.com/hukaif/web_operations/raw/master/images/修改字体结果.PNG "修改字体结果.PNG")
***

#####  方案2
- 修改图片大小，使图片完美切合文章而不显得突兀。
![修改图片](https://gitee.com/hukaif/web_operations/raw/master/images/修改图片.PNG "修改图片.PNG")

![修改图片结果](https://gitee.com/hukaif/web_operations/raw/master/images/修改图片结果.PNG "修改图片结果.PNG")
***




