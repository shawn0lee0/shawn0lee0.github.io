---
layout: post
title: 《程序员编程思维训练》完结笔记
category: opinion
description: 产品狗大脑调教手册
---


> 范围：全书
> 
| 开始| 更新（碎片） |
|--------|--------|
|   2016年2月1日08:52:41 | 2016年2月1日16:53:20  |

_ _ _

经过14天的阅读体验，汇总成文以飨读者。《程炼》此书阐述的问题有：

+ 大脑原理与bug,鼓励开发R思维
+ 活用敏捷方法，不要追求形式；
+ 告诉你如何制定目标；
+ 告诉你应该如何读书；
+ 告诉你如何学习、如何笔记；
+ 如何积累经验；
+ 如何构建环境观察知识内增长；

本书的遗憾：

+ 提出了的问题所在，但没有给出解决方案；
+ 一直强调情境思维，但是没有细化，案例太少；
+ 隐喻概念还是偏程序猿理性思维，没有考虑读者的非理工背景；

## 认识你的大脑
把人脑比作电脑

+ 低主频CPU：普通计算机的CPU主频高达几Ghz，连小米手机都是4核2.5Ghz了。相比之下，人大脑最高主频才几Khz，不及小米手机千分之一。

+ 低内存：大部分手机有2G的内存，可以同时用来听音乐、下载电影和玩极品飞车等；但是根据Miller的研究，人大脑的工作记忆（相当于手机内存）最多只能同时处理5-9个条目（平均是7个--马云直属事业部也是7）。这意味着你几乎不可能同时专注好几件事情。

+ 小硬盘：很多电脑有1T（1024G）的存数量，但是大脑大致只能存储1G左右的数据，而且大部分还是无法被我们有意识地访问的。

+ 低功耗：超级计算机“红杉”有8兆瓦的功率，相当于16万个家庭的用电量；而更强运算能力的人脑只有20瓦功率，只相当于一盏点灯。

+ 冲突的总线：电脑数据靠铜导线传输，速度快、性能稳定、传输数据量大；而相比之下，人类神经元不断漏电、信息传输失误多、数据量小，还经常冲突。




**纳尼~这么low的配置怎么改变世界呢？？**

>神经学专家保罗.麦克里恩曾经提出著名的“3大大脑”的假设—按照进化的先后，人类大脑分为3大不同的功能区，并且相对独立地运行：

+ 爬行脑：最先被进化出来的部分（爬行动物就有），控制人的吃饭、性等几乎所有欲望和本能，也掌管着人类大部分的决策。它是呆板、冲动、缺乏远见并渴望立刻满足的。

+ 边缘系统：后来被进化出的部分，保护下丘脑、海马状突起和杏仁核体，控制人的情绪、情感和长期记忆，它决定了“喜欢什么”和“不喜欢什么”。它规避危险，情绪化。

+ 新皮层：最后被进化出来的部分，包括左右两个脑半球，控制思维、语言、想象力等所有的“高级”功能。（L/R型思维）

![图 文中有彩蛋](http://upload-images.jianshu.io/upload_images/982375-3e421f095a906e7d.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 一、产品狗的基本功

+ 输入：
    + 看过行业中70%竞品，形成了对行业竞品的直觉思考；
    + 拜访过行业中top20巨头中的至少五家公司及其CEO，明白媒体报道之外的更多内隐知识
    + 每周至少实际访谈与接触一位实际用户，并在不同产品周期与不同数量的用户交朋友；
    + 博览群书，优秀设计，配色等；

+ 过滤：
    + 拥有较高的信息架构设计能力，能够将看似很个性的需求整合到一个简单清晰的信息架构之下；
    + 经常在头脑中推演各类不同用户交互与用户使用可能，提前发现产品逻辑可以再打磨的地方；
    + 善于排优先级，能确定需求的关键次序
    + 审美品位好，能够减轻设计师程序员反复修改的时间

+ 输出：
    + 沟通类：生成备忘录，提炼真实需求；
    + 阅读类：生成读书笔记，主动驱动需求；
    + 段子、诗歌：力求风趣、通俗易懂；

+ 补充：
    + 养心
      - 顶住各方伪需求
      - 修改需求的吐槽
    + 修身：`工作日程：周一、周二、周三、周三、周五、周五、周五！` 



## 二、修炼|输入篇：



##### 认清你自己的阶段水平

![新手到专家](http://upload-images.jianshu.io/upload_images/982375-4c185e1218c198ea.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


> 精通者，善于充分利用思考与反馈
> + 模仿
> + 吸收
> + 创新

| 技能        | 现阶段           | 下一步目标  |
| :------------- |:-------------:| :-----|
| 产品调研     | 新手 | 同行功能、客户,信息挖掘效率提升（1小时完成相关素材收集） |
| 竞品分析     | 新手 | 分析BD下载数量、业务流程、功能分类、界面布局、视觉呈现等，产品属性、公司背景、创始人产品经理背景，面基竞品 |
| 需求提炼     | 新手 | 知道自己不知道什么，比什么都不知道要好 |
| 文档输出     | 新手 | 模仿 |
| 原型设计     | 新手 | 先手绘原型再工具 |
| 数据分析    | 高新 | Python Data课程 ,统计学原理|
| 逻辑思考     | 胜任 | 提高阅读写作频率，文章内容干燥度，观察文章分享、评论数量 |
| 沟通能力     | 胜任 | 我期望的结果是怎样的？我需要对方提供怎样的协助才能实现期望的结果？|
| 洞察力     | 高新 | [正念](https://mp.weixin.qq.com/s?__biz=MzA4ODM4ODQ3MQ==&mid=204277318&idx=1&sn=ba7f9bf84dbb9275648c4416cc867298&scene=1&srcid=12315mHf4n3Hkl6Pf9pDKn4Y&pass_ticket=L%2F2i7H4GSEBCmt20RHwWtp%2BCPJjRijCOocCxfDvC4zkIzOc5xDQgNfTnN4ee%2FdIm#rd) ,向内探求生命的本质 |
| 项目管理     | 高新 | 化整为零，颗粒度尽可能小，每个部分之间尽可能保持独立。周计划、日计划，上午计划、时计划，番茄钟计划。对大目标进行解构，将问题分类，记录版本变更。 |


##### 改变|选择主题性阅读

> 阳志平：最便宜的自我修炼是阅读；最容易产生心流体验的娱乐是写作。富人用钱买心流，超一流作家用心流买青史留名。读一本书的最好方法是开始读一本书；

+ 主题阅读 （提倡不要把一本书从头读到尾）


![](http://upload-images.jianshu.io/upload_images/982375-633b4cd47202f8f8.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  -  关注自己的技能圈
  - （总15本）确保哪些是和你的主题相关，并就你的主题建立清楚的概念
  - （剩下10本）快速阅读，找出每本书相关的章节
  -  列出一个中立的主旨，列出一连串的问题。比如用5W1H来进行提问
  -  在每本书相关的章节里面寻找作者的观点，然后引用出来
  -  界定主要和次要的议题



##### SQ3R阅读方法


![SQ3R方法](http://upload-images.jianshu.io/upload_images/982375-0d4788d6fb037938.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

清楚的认知到自己情况，找到某一技能薄弱点突破它，专注，攻克；



#### 内化吸收，分享

>你能想到的点子，全中国估计有1万人能同时想到，然后有1千个人会动手去做，然后100个人会把事给做出来。所以点子不重要，重要的是你要比别人快、比别人好地把产品做出来。
>知识是液体，要形成好的“液态网络”，最好的办法是让不同人、群体对同样的项目进行不断的碰撞与共享

+ 快速分享--身边人、群友（5分钟）介绍观点
+ 中度分享--10-15分钟，群分享：内容，重点是案例；
+ 深度分享：案例，外加个人经历，心得，面向对象分享


## 三、修炼|大脑的过滤器：

+ 培养情境思维；
+ 构建反馈环境；



#### 情境思维

+ 详见[用卡片训练R思维](http://www.jianshu.com/p/d2bdc6295bbe)
![](http://upload-images.jianshu.io/upload_images/982375-7fec9bbb39e409fe.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
+ [构建角色模型](http://book.douban.com/subject/2157554/)
![](http://upload-images.jianshu.io/upload_images/982375-a3d5ce0a208797d3.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### 用[构建环境]方法改善沟通

+ [构建一个虚拟假想环境](http://www.jianshu.com/p/e36a9ee295ed)
 - 环境要求：安全地探索、创造、应用
 - 适合自己的虚拟空间
 - 自由实验--出了问题，卸载重来
 - 快速返回稳定版本
 - 回到可以运行的版本
 - 进展可视化



>沟通并不是“简单把信息告诉别人”，而是预测别人的行动，并且提前影响别人，以达到你想要的效果。
>沟通结束之前，需要不停地问自己：
对方听了我刚刚的一番话，最终最有可能怎么做？这种结果是我想要的吗？如果不是，我如何现在通过沟通来改变这种结果？
>沟通结束前，我们得先假设这次沟通是失败的，然后找出可能导致失败的原因。

举个栗子：
从事硬件产品开发时，某款产品需要与供应商确定元器件选型，
邮件：`您好，我们是XXX公司，我们正在开发一款产品需要一款LED，对应的参数balabala……请您提供支持`
如果对方知道你公司名气，看在大牌的面子上，回复效率也许会高些，如果是不知名小公司，多半回复较慢甚至石沉大海。

+ [构建一个虚拟假想环境](http://www.jianshu.com/p/e36a9ee295ed)
  - 假设他收到邮件，他会回复的内容有啥？
  	- 销售人员收到邮件，邮件转到了FAE（技术支持）手上“好的，小李你跟踪下”
  	- 直接回复了一份选型清单，还是需要我自己考虑，但是我仍不知道哪款是市场最佳供货产品。
  	- “这是我们推荐的产品XXXX”
  - 这是我要的结果吗？如果不是，为什么不在初始邮件提出来！

+ 针对每条原因提前想好对策，比如在邮件中加入这些内容：
（1）明确回复要达到的要求：`针对我司需求，请提供1~2款市场主力产品，并提供相关产品对比报告(与竞品的优势)；`
（2）让对方明确感受到这些要求。`提供标准的回复模板格式`
（3）提高别人认真回复的动机。`这款产品的年产量大概XXX块，单板使用量大概XXX颗,您的回复将会影响采购部门的决策。`（换位思考：对方在乎的是量，互利互惠原则）
（4）减少对方的人际顾虑。`如果某某产品XXX不能满足要求，请推荐最相近产品YYY`
（5）打电话给对方确认这些内容的接受程度，防止对方没有仔细看邮件。`邮件结尾备注截止回复日期`（压力）

+ 再返回思考修改后的内容是我需要的吗？重复该模型，执行

#### [类比思维：清晰表达一个观点](http://mp.weixin.qq.com/s?__biz=MzA5NTMxOTczOA==&mid=201711782&idx=1&sn=96a0f36d3019a0fedaf935bc63fc7572&3rd=MzA3MDU4NTYzMw==&scene=6#rd)
>使用类比—你先推测出对方论断“背后的理论”是什么，然后问自己“如果这个理论成立，会出现哪些显而易见的不合常规的现象？”然后这种现象就可以拿来当做类比。

+ 时间序列的类比
 +  `电子书什么的一点也不爽`
 +  类比`在造纸术刚出来时，也有人说纸书什么的不如绢帛来的爽~`
+ 用对方熟悉的事物做类比
 + `所谓『智能硬件』是什么样的体验`
 + 类比`在你还在用诺基亚3100的时候，有些人在用iPhone`
+ 用类比转移到客观视角
 +  `支付宝的生活圈晒视频是什么感觉`
 +  类比：`在银行取钱时候，看到两个大妈在撒泼是什么感觉？`
+ 引入比较对象
 + `支付宝做社交，简直就是玩笑~`
 + 类比：`支付宝早期解决的个人与商家的支付问题，当人人都有支付宝后，你和朋友间借款转账试问还要跑到ATM机去吗？` 

>很多时候你无法让别人理解你，只是因为你还没有让你的大道理足够“显而易见”。而一个重要的方法就是有效类比。

### 刻意练习|主动求虐
+ [为什么你有10年经验，但成不了专家？](http://mp.weixin.qq.com/s?__biz=MzA5NTMxOTczOA==&mid=208796062&idx=1&sn=a700d18b13ea165431ea66e0056efe58&3rd=MzA3MDU4NTYzMw==&scene=6#rd)
+ [深度练习](http://mp.weixin.qq.com/s?__biz=MzA4ODM4ODQ3MQ==&mid=402110590&idx=1&sn=761e30c58df8db57245ee6092e100017&3rd=MzA3MDU4NTYzMw==&scene=6#rd)，你是否有意挑战新高度来训练自己，积累更多技能，有更多心理、情绪和行为控制来应对更多局面。

举例：早期[新手]做电路设计时，学习各种标准、指标、设计准则,单元测试，泡实验室（可靠性测试、EMC屏蔽）等等。几年下来，再返回来观察新人的作品，一眼就能发现EMI（电磁干扰）等问题，这个时候你的大脑[直觉]已经快速模拟了一遍电路运作过程。
>一切练习，最终都是要把开始的慢速行为，变成不太需要思考的中速行为，最后变成下意识反应的快速行为，甚至是自动行为。





## 四、修炼|输出篇

+ 养成随时记录的习惯
+ 隐喻的应用--不会写段子的产品狗不是好狗；
+ 建立PKM(个人知识管理)，wiki


#### 随时记录

+ Fieldstone方法（养成收集思维卵石的习惯）
   - 不关注计划收集石头（材料）
   -   只需要到处走走
   -   收集好看的石头背用（建立素材库）
   -   挑选收集的石头，构建，组合，堆砌造墙


#### 隐喻|段子手

![](http://upload-images.jianshu.io/upload_images/982375-c6a345c0035137e9.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
还记得文章开头，那幅图片的文字吗？映像最深的是“开智学堂”还是“鸭脖子”？
So，好的段子应该是视觉化（画面感）的~~~



例如：

描述杭州西湖景点的名字

+ 苏堤春晓
+ 曲院风荷
+ 平湖秋月
+ 断桥残雪

![杭州西湖 图片来源：陈饰玻璃工坊](http://upload-images.jianshu.io/upload_images/982375-cbf155d8c233eb2c.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`人生的减法：换掉乳牙是为了新牙；手指受伤了才会认真体验它的感受；迷路了，才看到不一样的风景；人生的减法只是加法的一横罢了`

`老爷子练武十分刻苦，冬天坐火车去西伯利亚，穿着日本相扑的内裤，光着身子，左手拿着大茶缸，冰镇的酸梅汤，右手拿着大蒲扇，迎着风口唱：“这就是二，说也说不清楚…为此练得一身好本事，大冬天从湖上过去连个水星都不沾；曾白天练武，晚上为了防备敌人偷袭，装成植物埋伏在后院，半夜坏人来了，有顶着铁桶的，拿梯子的；`

#### 知识管理
![图片来源Python大妈：Zoom.quiet](http://upload-images.jianshu.io/upload_images/982375-0bb1e43de85b65d1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
获取知识最大的阻碍并不是无知，而是对知识的幻觉—觉得自己很懂，觉得习惯了的就是正确的。
整合资源越来越迅速的今天，与其守着自己有限的资源逡巡不前，不如敞开胸怀，**让自己的知识积累充分地与世界连接，与更多的富有创新意识的头脑进行碰撞，进而产生强大的能量。**
![图片来源Python大妈：Zoom.quiet](http://upload-images.jianshu.io/upload_images/982375-fa5a918b38b9a61a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


+ **开源自己**
+ **做一支蜡烛**
 + 燃烧自己
 + 自身亮度反观自己
 + 让蜡流动



## 五、参考内容来源

《阳志平：工作谈008  产品经理基本功》
《伟大创意的诞生》
《开智学堂微信公众号》
《李叫兽的微信公众号》
[《兰川：谈读书笔记》](http://www.jianshu.com/p/11621814a799)
[《亦周-理想的深度阅读方式》](http://www.jianshu.com/p/88bdb4b9daad)
[《程炼|思维导图笔记》](http://i4.tietuku.com/5982587a7f1ba797.png)

## 六、小结

1、刻意练习，使某一技能并达到专家级别，一旦成为某领域专家，在其他领域成为专家的成本非常低。
2、做产品，别总是只跟L/R模型大脑（皮层）说话，试着多刺激本能（爬行脑）和情绪（边缘系统）说话啊！`微信红包的人性思考`
3、执行！执行！！！执行！！！