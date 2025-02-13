# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0733springboot财务管理系统--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=84)


# 第一章 概述
## 1.1研究背景
我国早在上世纪就已普及互联网信息，互联网对人们生活中带来了无限的便利。像大部分的企业、公司等机构都有自己的管理系统，由传统的管理模式向互联网发展，如今开发自己的系统是时代发展的必然产物。那么开发财务管理系统意义和用处有哪些呢？

首先提升工作效率：这是很多企业、公司建设系统的目的之一。财务管理系统对于企业或者公司来说，可以摆脱传统手写记录的管理模式。利用计算机系统，进行员工信息、管理员信息的管理，其中包含首页，个人中心，员工管理，部门管理，员工工资管理，工资调整管理，资产类别管理，固定资产管理，经营信息管理，序时账管理，年度利润管理，系统管理等功能的管理，不只是节省了人力和物力，还提高了工作的效率，让管理员和员工可以更加高效地工作。

其次，对于员工来说，不需要到公司进行办公，在家里就可以通过计算机查看个人信息、员工工资管理，工资调整管理，系统管理等内容，并进行新增、修改或删除，有些还能进行导出，非常的便利。

一个好的系统能将财务管理手段提上一个新的台阶。系统内容可以随时更新，这点对于财务管理者来说是很重要，但这是传统的管理方式都无法做到的。财务管理系统就可以每天更新，随时了解财务管理的最新情况。

财务管理系统能够通过互联网得到广泛的、全面的宣传，让尽可能多的员工了解和熟知财务管理系统的便捷高效，为管理者和员工提供了服务，节省人力、物力和时间，提高工作效率。
## 1.2开发意义
人类的进步带动信息化的发展，使人们生活节奏越来越快，所以人们越来越重视信息的时效性。以往的管理方式已经满足不了人们对获得信息的方式、方便快捷的需求。即财务管理系统慢慢的被人们关注。首先，网上获取信息十分的实时、便捷，只要系统在线状态，无论在哪里都能第一时间查找到理想的信息。

计算机技术在管理中成为人们的重要工具。可以有效快捷的解决想要获取的信息，提高工作效率。
## 1.3 研究现状
在国外很多发达国家，软件产业早已得到全面普及，但我国经济已不断发展，不断引进国外信息化建设，使国内软件行业得以不断发展，在摸索中进步，最终也得到一些成果，我国的软件业迎来了高速的发展，使更多的软件系统得以开发出来，从此逐渐地改变人们的生活工作方式。但是，对于信息化的建设，与很多发达国家相比，由于信息化程度的落后以及经费的不足，我国的财务管理系统开发方面还是相对落后的，因此，要不断的努力探索，争取开发出一个实用的信息化的财务管理系统，来实现财务管理的信息化。因此本课题以财务管理为例，目的是开发一个实用的财务管理系统。

财务管理系统的开发运用java技术、springboot框架，MIS的总体思想，以及Mysql等技术的支持下共同完成了该系统的开发，实现了财务管理的信息化，使员工体验到更优秀的财务管理，管理员管理操作将更加方便，实现目标。 
## 1.4 研究内容
财务管理系统的需求和管理上的不断提升，财务管理系统的潜力将无限扩大，财务管理系统在业界被广泛关注，本系统及对此进行总体分析，将财务管理信息管理的发展提供参考。财务管理系统对财务管理有着明显的带动效应，尤其对企业、公司的管理帮助更大。

根据现有的模块，管理员对系统所有的信息进行管理。

本文将按以下步骤进行开发；

` `(1)绪论

系统的开发背景，意义和系统状况等，详细讲述了系统的用处，对本章进行总结。

(2)系统开发技术的介绍

分别对java技术、Springboot框架、Mysql和B/S进行详细介绍。

(3)系统分析

本章主要是对系统可行性、系统性能、还有系统功能需求进行分析。

(4)系统设计

对系统系统功能和数据库等进行详细讲解。

(5)系统的实现

主要对首页，个人中心，员工管理，部门管理，员工工资管理，工资调整管理，资产类别管理，固定资产管理，经营信息管理，序时账管理，年度利润管理，系统管理的实现。

(6)系统的测试

在系统编码实现后，就需要对系统进行检测，检测的方法有黑盒测试和白盒测试两种方式，本系统采用的是黑白盒测试方法对不同组的数据进行功能模块测试。


35
![](/md/blog.009.png)
# `	`第二章 开发技术介绍
此系统的关键技术和架构，Java技术、B/S结构、Springboot框架和Mysql数据库，是本系统的关键开发技术，对系统的整体、数据库、功能模块、系统页面以及系统程序等设计进行了详细的研究与规划。
## 2.1 系统开发平台
在线财务管理系统中，Eclipse能给用户提供更多的方便，其特点一是方便学习，方便快捷；二是有非常大的信息储存量，主要功能是用在对数据库中查询和编程。其功能有比较灵活的数据应用，只需利用小部分代码就能实现非常强大的功能。因此，利用Eclipse 技术进行系统代码管理是该系统数据库的首选。
## 2.2 平台开发相关技术
### 2.2.1  Javar技术
Java是一种网络脚本语言，广泛运用于web应用开发，可以用来添加网页的格式动态效果，该语言不用进行预编译就直接运行，可以直接嵌入HTML语言中，写成js语言，便于结构的分离，支持多种浏览器可以在多平台下运行。它具有三个不同的体系，分别为J2SE、J2EE、J2ME。Java 语言比较容易理解，而且也容易学习和上手，其语法与C语言和C++语言很相似，它可以自动的处理废料，而且不会受到内存的影响。

Java 程序被编译后形成的class 文件，这样就能够实现在多系统中正常运行。Java语言支持多个线程同吋执行，Java程序所需要的类能够动态的或者通过网络被载入到运行环境。Java开发工具支持JavaJDK7\8,开发集成环境IDE为Eclipse。
### 2.2.2  Mysql数据库介绍
利用Mysql的数据独立性、安全性等特点，在软件项目中对数据进行操作，可以保证数据准确无误，并降低了程序员的应用开发时间。

Mysql的特点是支持多线程，能方便的对系统资源充分利用，有效提高速度，还提供多种方式途径来对数据库进行连接；Mysql的功能相对弱小、规模也小，但本系统要求不高，Mysql完全可以满足本系统使用。

利用Mysql建立系统数据库，不仅有利于数据处理业务的早期整合，还能利于发展后两种数据扩展的操作。
### 2.2.3  Mysql环境配置
本系统的数据使用的是Mysql,所以要将Mysql安装到指定目录，如果下载的是非安装的Mysql压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\Mysql\bin\winMysqladmin.exe这个文件其中C:\Program Files\Mysql是Mysql安装目录。输入winMysqladmin的初始用户、密码（注：这不是Mysql里的用户、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动Mysql服务。

修改Mysql数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\Mysql\bin

Mysqladmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空,所以直接回车，此时Mysql 中账号 root 的密码被改为 123 安装完毕。
### 2.2.4  B/S架构
B/S结构是目前使用最多的结构模式，它可以使得系统的开发更加的简单，好操作，而且还可以对其进行维护。使用该结构时只需要在计算机中安装数据库，和一些很常用的浏览器就可以了。浏览器就会与数据库进行信息的连接，可以实现很多的功能，B/S结构是可以直接进行使用的，而且B/S结构在使用中极大的减少了工作的维护。基于B/S的软件，所有的数据库之间都是相互独立的，因此是非常安全的。因为基于B/S结构可以清楚的看到系统正在处理的业务，并且能够及时的让管理人员做出决策，这样就可以避免企业的损失。B/S结构的基本特点是集中式的管理模式，用户使用系统生成数据后，这些数据就可以存储到系统的数据库中，方便日后能够用到，这样就可以满足人们的所有的需求。

![](/md/blog.010.png)

图2-1  B/S模式三层结构图
### 2.2.5  Springboot框架
SpringBoot是一个全新开源的轻量级框架。基于Spring4.0设计，其不仅继承了Spring框架原来有的优秀特性，而且还通过简化配置文件来进一步简化了Spring应用的整个搭建以及开发过程。另外在原本的Spring中由于随着项目的扩大导入的jar包数量越来越大，随之出现了jar包版本之间的兼容性问题，而此时SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性问题得到了很好的解决。

SpringBoot可以看做是Spring的加强版本，但实质上都是Spring的相关技术，有了这些优秀的开源框架，程序员在开发过程中将事半功倍。



# 第三章 系统分析
## 3.1 可行性分析
一个完整的系统，可行性分析是必须要有的，因为他关系到系统生存问题，对开发的意义进行分析，能否通过本系统来补充线下财务管理模式中的缺限，去解决其中的不足等，通过对本系统，不仅能使工作量不断地减少，还能使工作和管理的效率更加高。所以开发该系统能实现更大的意义和价值，系统完成后，能否达到预期效果就要通过可行性分析，分析之后，决定此系统是否开发。该财务管理系统的开发设计中，对技术、经济、操作方面进行了可行性分析。
### 3.1.1技术可行性
本系统开发选择Java语言，它被研究的目的就是在于能够为网页创建等可以看到的信息。随着移动互联网技术的不断发展和创新，Java俨然已成为下一代互联网的Web标准。所以后台设计选择使用Mysql,数据库主要用来的建立和维护信息。对于前台开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。
### 3.1.2操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要员工一定要到公司办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成用户不同的需求，这不仅提高了工作效率还能完成一些客户特定的一些需求。本系统不仅界面简洁明了还采用可视化界面，员工只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
### 3.1.3经济可行性
基于Springboot框架的财务管理系统，该系统软件开发仅需要一台普通的计算机便可完成实现开发，其成本很低。另外，作为毕业设计作品来讲，开发成本基本上可以忽略不计，且该系统软件的投入使用，可以实现更加快速高效的财务管理，同时还能实现对人力资源和管理资源的有效节约，该财务管理系统在经济上完全可行。
## 3.2性能需求分析
对系统的性能，从（功能、运行、界面、安全）等方面进行，下面我们逐一进行分析；

\1. 系统的功能是否完整进行分析：系统的功能，能对应设计出原始代码和算法，以表格同文字的形式进行详细介绍个人信息保证功能完整；

\2. 系统的运行是否通畅进行分析：系统的每个功能都有编写数据的关系和应对的代码，通过需求分析和可行性分析进行分析和显示系统的物理数据，保证其进行通畅；

\3. 系统的界面设计进行分析：对系统中的软件进行处理与分析的方式是由不同代码来进行的；从而使界面容易操作。

4.系统的安全性进行分析：这样才可以每个角色的不同对应的信息也就不同，在登录系统务必使用自己的账号，密码登录，账号与密码错误自然就登录失败了。登录成功可以对自己的信息进行操作，不能对别人的账号的信息进行查看等操作，这样自然保证系统的安全性。


























# 第四章 系统设计
## 4.1功能结构
为了更好的去理清本系统整体思路，对该系统以结构图的形式表达出来，设计实现该财务管理系统的功能结构图如下所示：

![](/md/blog.011.png)

图4-1 系统总体结构图

## 4.2 数据库设计
### 4.2.1 数据库E/R图
ER图是由实体及其关系构成的图，通过E/R图可以清楚地描述系统涉及到的实体之间的相互关系。在系统中对一些主要的几个关键实体如下图：

(1)员工管理E/R图如下所示：

![](/md/blog.012.png)

图4-2员工管理E/R图

` `(2)工资调整管理E/R图如下所示：

![](/md/blog.013.png)

图4-3工资调整管理E/R图

` `(3)固定资产管理E/R图如下所示： 

![](/md/blog.014.png)

图4-4固定资产管理E/R图
### 4.2.2 数据库表
数据库表的设计，如下表：

表4-1：序时账

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|pingzhengdanhao|varchar|200|凭证单号|||
|fapiao|varchar|200|发票|||
|shouzhileixing|varchar|200|收支类型|||
|zhaiyao|varchar|200|摘要|||
|duifangkemu|varchar|200|对方科目|||
|jine|float||金额|||
|dengjishijian|date||登记时间|||

表4-2：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|




表4-3：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-4：年度利润

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|niandutongji|varchar|200|年度统计|||
|zhuyingshouru|float||主营收入|||
|zhuyingyewuchengben|int||主营业务成本|||
|zhuyingyewushuijinjifujia|int||主营业务税金及附加|||
|qitayewulirun|int||其他业务利润|||
|yingyefeiyong|int||营业费用|||
|guanlifeiyong|int||管理费用|||
|caiwufeiyong|int||财务费用|||
|touzishouyi|int||投资收益|||
|butieshouyi|int||补贴收益|||
|yingyewaishouru|int||营业外收入|||
|yingyewaizhichu|int||营业外支出|||
|suodeshui|int||所得税|||
|jinglirun|int||净利润|||
|dengjishijian|date||登记时间|||

表4-5：资产类别

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zichanleibie|varchar|200|资产类别|||

表4-6：员工工资

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gongziyuefen|varchar|200|工资月份|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||
|jibengongzi|int||基本工资|||
|gonglingbutie|int||工龄补贴|||
|jiabangongzi|int||加班工资|||
|jiangli|int||奖励|||
|fakuan|int||罚款|||
|geshui|int||个税|||
|shebaodaijiao|int||社保代缴|||
|jiangchengshuoming|varchar|200|奖惩说明|||
|shifagongzi|float||实发工资|||
|dengjishijian|date||登记时间|||

表4-7：员工

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|mima|varchar|200|密码|||
|yuangongxingming|varchar|200|员工姓名|||
|zhaopian|varchar|200|照片|||
|xingbie|varchar|200|性别|||
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
|lianxifangshi|varchar|200|联系方式|||
|ruzhishijian|date||入职时间|||

表4-8：公司公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-9：经营信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tongjiyuefen|varchar|200|统计月份|||
|yingshoujine|int||营收金额|||
|yuechanliang|varchar|200|月产量|||
|qianyikehu|varchar|200|前一客户|||
|qianyibaifenbi|float||前一百分比|||
|qianerkehu|varchar|200|前二客户|||
|qianerbaifenbi|float||前二百分比|||
|qiansankehu|varchar|200|前三客户|||
|qiansanbaifenbi|float||前三百分比|||
|dengjishijian|date||登记时间|||

表4-10：固定资产

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zichanmingcheng|varchar|200|资产名称|||
|fengmian|varchar|200|封面|||
|zichanleibie|varchar|200|资产类别|||
|zichanzhuangtai|varchar|200|资产状态|||
|zichanjiazhi|int||资产价值|||
|fengxianjiti|int||风险计提|||
|jitiyuanyin|varchar|200|计提原因|||
|dengjishijian|date||登记时间|||

表4-11：工资调整

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|diaozhengyuanyin|varchar|200|调整原因|||
|diaozhengedu|int||调整额度|||
|diaozhengshijian|date||调整时间|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||

表4-12：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-13：部门

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|bumen|varchar|200|部门|||













# 第五章 系统功能实现
系统登录，管理员和员工进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-1所示。

![](/md/blog.015.png)

图5-1系统登录界面图
## 5.1管理员功能模块

管理员登录系统后，可以对首页，个人中心，员工管理，部门管理，员工工资管理，工资调整管理，资产类别管理，固定资产管理，经营信息管理，序时账管理，年度利润管理，系统管理等功能进行相应的操作管理，如图5-2所示。

![](/md/blog.016.png)

图5-2管理员功能界面图

员工管理，在员工管理页面可以对索引，员工工号，员工姓名，图片，性别，部门，职位，联系方式，入职时间等内容进行详情，修改和删除等操作，如图5-3所示。

![](/md/blog.017.png)

图5-3员工管理界面图

部门管理，在部门管理页面可以对索引，部门等信息进行详情，修改和删除等操作，如图5-4所示。

![](/md/blog.018.png)

图5-4部门管理界面图

员工工资管理，在员工工资管理页面可以对索引，工资月份，员工工号，部门，基本工资，工龄补贴，加班工资，奖励，罚款，个税，社保代缴，奖惩说明，实发工资，登记时间等内容进行详情，修改，删除等操作，如图5-5所示。

![](/md/blog.019.png)

图5-5员工工资管理界面图

工资调整管理，在工资调整管理页面可以对索引，调整原因，调整额度，调整时间，员工工号，员工姓名，部门等内容进行详情，修改，删除等操作，如图5-6所示。

![](/md/blog.020.png)

图5-6工资调整管理界面图

固定资产管理，在固定资产管理页面可以对索引，资产名称，封面，资产类别，资产状态，资产价值，风险计提，计提原因，登记时间等内容进行详情，修改，删除等操作，如图5-7所示。

![](/md/blog.021.png)

图5-7固定资产管理界面图

经营信息管理，在经营信息管理页面可以对索引，统计月份，营收金额，月产量，前一客户，前一百分比，前二客户，前二百分比，前三客户，前三百分比，登记时间等内容进行详情，修改，删除等操作，如图5-8所示。

![](/md/blog.022.png)

图5-8经营信息管理界面图

序时账管理，在序时账管理页面可以对索引，凭证单号，发票，收支类型，摘要，对方科目，金额，登记时间等内容进行详情，修改，删除等操作，如图5-9所示。

![](/md/blog.023.png)

图5-9序时账管理界面图

年度利润管理，在年度利润管理页面可以对索引，年度统计，主要收入，只要业务成本，只要业务税金及附加，其他业务利润，营业费用，管理费用，财务费用，投资收益，补贴收益，营业外收入，营业外支出，所得税，净利润，登记时间等内容进行详情，修改，删除等操作，如图5-10所示。

![](/md/blog.024.png)

图5-10年度利润管理界面图

系统管理，在公司公告页面可以对索引，标题，图片等内容进行详情，修改和删除等操作；如图5-11所示。

![](/md/blog.025.png)

图5-11系统管理界面图


## 5.2员工功能模块
员工登录进入系统可以对首页，个人中心，员工工资管理，工资调整管理，系统管理等功能进行相应操作，如图5-12所示。

![](/md/blog.026.png)

图5-12员工功能界面图

个人中心，在个人信息页面通过填写员工工号，员工姓名，照片，性别，职位，联系方式，入职时间等内容进行个人信息修改操作，如图5-13所示。

![](/md/blog.027.png)

图5-13个人中心界面图

工资调整管理，在工资调整管理页面可以对索引，调整原因，调整额度，调整时间，员工工号，员工姓名，部门等内容进行详情操作，如图5-14所示。

![](/md/blog.028.png)

图5-14工资调整管理界面图


























