# archimate系列之六逻辑架构-用例图

标签（空格分隔）： archimate 架构 架构图 逻辑架构 用例图

---

我们都知道，UML里详细规定了用例图，是知道需求分析的一个主要工具。但UML的用例图跟其他UML图一样，都是比较细节的设计工具。使用UML的用例图做详细的需求分析，是非常好的一个工具；但是，用它来做全局的需求框架分析，就非常的不合适了。
archimate工具是一个非常适合做整体设计的工作，即我们通常所说的架构设计。而全局的用例分析也是架构设计的一部分，非常适合在项目前期和用户进行沟通。
下面就是一个用archimate做的典型的全局用例图：

![用例图示例][1]

用例图有两个主要的元素-business actor和business role，如下图红框所示：

![常用的两个元素][2]

它们之间的区别也很微妙，一个用来表达内部的用户，一个用来表达外部的用户。
比如上图中，business actor用来表达保险公司的内部用户，如“客户关系”、“中介关系”、“财务部”等等；而business role则用来表达外部用户，如“客户”、“中介”、“客户银行”等等。
下图是actor示例：

![actor示例][3]

下图是role示例：

![role示例][4]

business actor跟business actor有包含关系，比如，“前台服务”这个actor包含了两个actor-“客户关系”和“中介关系”，如下图所示：

![actor之间关系][5]

其他元素，也都很简单，在这里就不再一一细说了。
如果上述用到的元素还不够用，其他用例元素都在这里：

![用例元素面板][6]


  [1]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/usecase.bmp
  [2]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/actorrole.png
  [3]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/actor2.png
  [4]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/role.png
  [5]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/actorr.png
  [6]: https://raw.githubusercontent.com/wiki/wallace1/archimate-learning/allusecase.png