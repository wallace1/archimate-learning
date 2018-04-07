# archimate系列之四逻辑架构-数据流图

标签（空格分隔）： archimate 逻辑架构 架构 数据流图

---

当一个系统足够大时，通过严格的架构设计，得到的子系统和组件也就相当的多，那么子系统或组件之间的交互也就很复杂了。
对于开发人员和测试人员来说，他们迫切希望知道各个组件的交互关系，在架构设计中，这个功能是由数据流图来解决的。
对于详细设计人员来说，数据流图也是相当重要的，它能帮我们整理清楚各个子系统和组件之间的关系，子系统或组件所拥有的功能，子系统或组件存在的意义，等待。
下面就是一个典型的数据流图示例：
![数据流图示例][1]

在这个示例图中，常用的元素有以下：

 1. 组件
这在本系统以前的文章中都有详细的介绍，在这里就不再复述。

 2. 系统软件
这里用来描述一些第三方软件，如上例中，有“消息服务器”、“关系数据库”，常用的系统软件还有-“FTP服务器”、“代理服务器”、“邮件服务器”、“缓存服务器等等。
下图中，红框所示的就是一些系统软件：
![系统软件示例][2]


 3. 数据流向关系
这是数据流图中最重要的元素，在数据流图中，我们基本上只用一种关系连接线，如下图所示：
![流向关系元素示例][3]


在上图中，我们详细标注了各种数据流向关系，主要有如下的关系：
（1）蓝色箭头表示“需求命令数据的流向关系”；
（2）棕色箭头表示“指令数据的流向关系”；
（3）绿色箭头表示“设备响应数据的流向关系”；
（4）红色箭头表示“监控数据的流向关系”。


 4. 注释
当常用元素描述不清楚设计者想要表达的一些意图时，注释元素便显得相当有用。
如下图红框所示：
![注释元素示例][4]

注释元素在面板这里，请大家注意：
![在面板中的注释元素示例][5]

基本上，当我们熟练使用了上面一些常用元素后，就能描绘出形式丰富的数据流图来 。


  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/dataflow.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/systemsoftware.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/flow.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/comment.png
  [5]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/comment2.png