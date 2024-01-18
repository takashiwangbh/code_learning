# 开发环境
Visual Studio 

> 编程不是学出来的，而是练出来的

# C#编写的各类应用程序(编写hello world)

* **console**

```c#
Console.WriteLine("hello world")；
```

* **Windows Forms Application**
  
设置一个文本框和一个按钮（按钮名：buttonSayHello）
```c#
textBoxShowHello.Text = "Hello World":
```

* **WPF Application**
对比 Windows Forms Application，设计师可以直接设计然后自动生成代码，是升级版的Windows Forms Application

* **ASP.NET Web Form**
* **ASP.NET MVC**
上面两个是写网页用的
* **windows Store Application**
平板的开发
* **windows Phone Application**
手机的开发
* **Cloud(Window Azure)**
* **WF(Workflow Foundation)**
* **WCF (windows Communication Foundation)**
  
# 类（class）与名称空间（namespace）

* 类构成程序的主体
* 名称空间以树型结构组织类（和其他类型）
```c#
System.Console.WriteLine("hello world");
```
其中System是名称空间，Console是类，WriteLine是类里面的方法
System也可以在最开始引用
```c#
using System；
```
一个类可能在多个名称空间有不同的作用

# 类库的引用
* 类库引用是使用名称空间的物理基础
* DLL引用（黑盒引用，无需源码）
  可以用别的类库，也可以用自己编写的类库，但是无法修改源代码
* 项目引用（白盒引用，有源代码）
  可以自己创建项目，然后加到类库里，这样可以改源码

# 依赖关系
* 类（或对象之间的耦合关系）
* 优秀的程序追求“高内聚，低耦合”
* UML（通用建模语言）类图

# 排除关系
* 仔细阅读编译器的报错
* MSDN文档与搜索引擎结合

# 类
* 类（class）是现实世界事物的模型
  
# 类与对象的关系
* 对象也叫实例，是类经过实例化后得到的内存中的实体
现实世界称作对象，程序世界称作实例
* 依照类，我们可以创建对象，这就叫“实例化”
* 使用new操作符创建类的实例
* 引用变量与实例的关系
孩子与气球，气球不一定有孩子牵着，多个孩子可以通过各自的气球牵一个气球，也可以通过一只绳子牵一个气球
```c#
using System.Windows.Forms;
Form myform; /* 创建引用变量myform，可以对同一个form进行操作 */
myform = new Form(); //创建一个实例（对象）
myform.Text = "My Form!";
myform.ShowDialog(); 
```
# 类的三大成员
* 属性Property
  存储数据，这些数据组合起来表示类或对象当前的状态
* 方法Method
  由C语言里方法（function）进化而来，表示类或对象能做什么
* 事件Event
* 
  
