# archimate系列之三逻辑架构-分层架构

标签（空格分隔）： archimate 逻辑架构 分层架构 架构设计

---

在架构设计中，逻辑架构又是重要的架构设计之一。
因为逻辑架构也是面众广泛的设计，需要面对客户、分析人员、设计人员、开发人员、测试人员、实施人员、运维人员和维护人员，是相关干系人理解系统的一个最重要的方面。
逻辑架构设计也涉及到架构设计的方方面面，包括如下等各方面：

 1. 分层设计；
 2. 包和接口设计；
 3. 数据流设计；
 4. 协作设计；
 5. 用例设计；
 6. 业务流程设计；
 7. 其他。
逻辑设计主要是对功能的设计，以完成用户功能为主。 
本文主要讲讲分层设计的一些注意事项。
下面是一个分层架构设计的示例：
![分层架构设计示例][1]

分层架构设计的核心元素是“包”元素：
![包示例][2]

上图中，红框内的都是包元素。
一个包元素至少要包含一个组件或其他包，一般都包含多个包或组件。
分层架构设计中，第二重要的元素是“组件”元素。
在架构设计中，组件基本上是最小的元素了。
![组件示例][3]

上图中，红框中的元素都是组件元素。
![其他常用元素][4]

上图中，被框起来的元素依次是“应用组合”、“功能”、“应用交互”和“事件”，这些元素也是常用的元素。
分层架构设计主要以功能分层为主，不宜以技术分层为主。分层的方法主要包括横向切割和纵向切割。
关于这些，不是本文所涉及的内容，就不再详述。



  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/layer.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/package.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/component1.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/component2.png