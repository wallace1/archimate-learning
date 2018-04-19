# archimate系列之六通讯架构

标签（空格分隔）： archimate 架构设计 通讯架构

---

通讯架构主要是阐述系统各组件之间如何通讯，使得开发人员能够能够理解各组件之间的相互关系，这对于微服务架构尤其重要。
以下就是一个典型的通讯架构图：

![通讯架构图demo][1]

通讯方案通常有如下一些：

 1. 普通TCP通讯；
 2. 普通UDP通讯；
 3. 普通HTTP通讯；
 4. MQ消息通讯；
 5. RPC通讯；
 6. RESTful WS通讯；
 7. FTP通讯；
 8. MQTT通讯；
 9. COAP通讯；
 10. 等等。
以上各种方式，都有他们各自的使用场景，这是架构过程中要决策的。
上图中，我们有文件需要传输，当然首选FTP方案。
对于用户界面，我们通常选择BS模式，通过浏览器展示，所以HTTP协议通讯是必不可少的。
对于物联网设备来说，MQTT协议是一个很好的选择，所以上图中也大量使用到了MQTT协议通讯。
后台组件之间的交互，我们首选MQ，所以有了MQ方案。
对于关系数据库的访问，我们通常使用TCP长连接。
除了上述的通讯方式之外，我们还用到了以前没有涉及到几个`archimate`元素：
 1. 接口
接口一般包括用户接口和组件接口。
下图是用户接口示例：

![用户接口示例][2]

下图是组件接口示例：

![组件接口示例][3]

注意，接口元素在面板这里：

![接口元素][4]

 2. 服务
这个概念在软件中最常见了，这里不再多说。
下图是服务示例：

![服务示例][5]


注意，服务元素在面板这里：

![服务元素][6]


  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/communication.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/userintf.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/intf.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/interface.png
  [5]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/service11.png
  [6]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/service12.png