# archimate系列之五逻辑架构-流程设计

标签（空格分隔）： archimate 架构 逻辑架构 流程设计

---

业务流程往往隐藏在各个服务接口后面，它往往需要多个用户协作完成，任何一个环节出了问题，都会导致流程最后不能正确执行下去，用户也就得不到想要的结果。
业务流程一般是业务的核心部分，如电子商务的“购物流程”、“支付流程”等等。
因此，流程设计的好坏，决定了系统是否正确的执行了业务和系统的易用性，同时，也决定着一个系统最终的成败。
下图是一个标准的业务流程：
![业务流程图示例][1]

在流程设计中，最重要的元素当然是“流程节点”：
![流程元素示例][2]

流程元素在面板的这里：
![流程元素所在面板位置][3]

其次是“服务元素”，也是在流程设计中经常要用到的：
![服务元素示例][4]

还有就是“实现连接线”：
![实现连接线示例][5]

![实现连接线所在面板的位置][6]

它标识的是某个流程节点实现了某个面向用户的服务。
其他元素，就不再一一细说了。



  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/process.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/pp.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/ppp.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/service.png
  [5]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/releaside.png
  [6]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/rr.png