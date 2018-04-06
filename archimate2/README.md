# archimate系列之总体架构

标签（空格分隔）： archimate 概念架构 总体架构 架构设计

---

在架构设计中，概念架构、或者说总体架构，是很重要的。它基本上可以和方方面面的干系人打交道。不管是客户、设计师、开发、测试、还是实施、运维，甚至是领导，都可以通过概念架构来理解这个项目的设计。
概念设计一般完成是架构设计早期，往往比较注重识别重大需求、特色需求和高风险需求，根据这些来设计概念架构。
通过概念架构设计，来阐述“客户关心的价值如何实现”和“担心的问题如何解决”。
先看一张概念架构图：
![概念架构图示例][1]

在概念架构中，有以下图标比较常用：

 - 位置
通常用来表达“服务器”、“服务”或者“组件”的部署位置，项目涉及机构所在位置，项目用户使用项目的办公场所，等待。
如示例图中，右侧托盘中用红框标注的是“位置图标”，点击该图标，就可以画到工作区去。
左侧工作区的有多个“位置”示例，如红框标注的两个：
![位置示例][2]

 - 组件包或组
这个好理解，是多个组件或其他标注的集合。
在示例图中也大量用到：
![包示例][3]
右侧托盘中用红框标注的是“包图标”，点击该图标，就可以画到工作区去。
示例图中，应用到多个包：“业务层”、“基础设施”和“大数据接入层”等。

 - 组件
组件也是概念架构中常用的一种图标 ，一个组件，通常用来完成一定的功能，可大可小。
示意图中也应用到多个组件，下图中，右侧托盘中用红框标注的是“组件图标”，点击该图标，就可以画到工作区去。
![组件示例][4]

 - 设备
设备通常用来描述非自己开发的，引入的第三方硬件或者软件设施。
在示例图中也被广泛使用，如引入的大数据系统-HDFS、Hive、spark、关系数据库、FTP服务器，这些都是第三方软件系统；而点钞机、清分机、ATM机等，都是第三方硬件系统。
下图中，右侧托盘中用红框标注的是“组件图标”，点击该图标，就可以画到工作区去。
![设备示例][5]

 - 角色
指用到该系统的用户分类。
概念架构需要跟用户打交道，角色图标应该是必不可少的。
下图中，右侧托盘中用红框标注的是“角色图标”，点击该图标，就可以画到工作区去。
![角色示例][6]

 - 连接线
用来表示各种图标之间的关系，在概念架构图中，常用到的连接线主要有四种：

 - 服务关系 表示提供服务的一种关系；
 - 访问关系 表示两者有访问关系；
 - 触发关系 表示由什么事件触发；
 - 流向关系 表示数据的流向。

如下图所示：
![常用连接线示例][7]

红框表示“服务关系”，黄框表示“访问关系”，绿框表示“触发关系”，蓝框表示“数据流向关系”。

以上是在概念架构设计中常用到的一些图标，需要我们熟练掌握。
 


  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/overallarchitectural.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/location.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/group.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/component.png
  [5]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/equipment.png
  [6]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/actor.png
  [7]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/connector.png