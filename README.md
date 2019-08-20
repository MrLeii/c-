# c-
c#基础知识
C# 是一个现代的、通用的、面向对象的编程语言，它是由微软（Microsoft）开发的，由 Ecma 和 ISO 核准认可的。C#的特点是：
a、现代化，通用的编程语言
b、面向对象，面向组件
c、容易学习，结构化语言
d、高效率，多平台编译
e、.net框架的一部分。
其主要的一些功能：
1、布尔条件，
2、自动垃圾回收，
3、标准库，
4、组件版本，
5、属性和事件，
6、易于使用的泛型，
7、索引器，
8、条件编译，
9、简单的多线程，
10、LINQ和Lambda表达式，
11、集成Windows。

.Net 框架应用程序是多平台的应用程序。框架的设计方式使它适用于下列各种语言：C#、C++、Visual Basic、Jscript、COBOL 等等。所有这些语言可以访问框架，彼此之间也可以互相交互。
.Net 框架由一个巨大的代码库组成，用于 C# 等客户端语言。下面列出一些 .Net 框架的组件：
•	公共语言运行库（Common Language Runtime - CLR）
•	.Net 框架类库（.Net Framework Class Library）
•	公共语言规范（Common Language Specification）
•	通用类型系统（Common Type System）
•	元数据（Metadata）和组件（Assemblies）
•	Windows 窗体（Windows Forms）
•	ASP.Net 和 ASP.Net AJAX
•	ADO.Net
•	Windows 工作流基础（Windows Workflow Foundation - WF）
•	Windows 显示基础（Windows Presentation Foundation）
•	Windows 通信基础（Windows Communication Foundation - WCF）
•	LINQ

一个 C# 程序主要包括以下部分：
•	命名空间声明（Namespace declaration）
•	一个 class
•	Class 方法
•	Class 属性
•	一个 Main 方法
•	语句（Statements）& 表达式（Expressions）
•	注释

程序的第一行 using System; - using 关键字用于在程序中包含 System 命名空间。 一个程序一般有多个 using 语句。namespace 声明。一个 namespace 里包含了一系列的类。class 声明：类一般包含多个方法。方法定义了类的行为。定义了 Main 方法，是所有 C# 程序的 入口点。Main 方法说明当执行时 类将做什么动作。Console.ReadKey(); 是针对 VS.NET 用户的。这使得程序会等待一个按键的动作，防止程序从 Visual Studio .NET 启动时屏幕会快速运行并关闭。需要注意的是：
•	C# 是大小写敏感的。
•	所有的语句和表达式必须以分号（;）结尾。
•	程序的执行从 Main 方法开始。
•	与 Java 不同的是，文件名可以不同于类的名称。

标识符是用来识别类、变量、函数或任何其它用户定义的项目。在 C# 中，类的命名必须遵循如下基本规则：
•	标识符必须以字母、下划线或 @ 开头，后面可以跟一系列的字母、数字（ 0 - 9 ）、下划线（ _ ）、@。
•	标识符中的第一个字符不能是数字。
•	标识符必须不包含任何嵌入的空格或符号，比如 ? - +! # % ^ & * ( ) [ ] { } . ; : " ' / \。
•	标识符不能是 C# 关键字。除非它们有一个 @ 前缀。 例如，@if 是有效的标识符，但 if 不是，因为 if 是关键字。
•	标识符必须区分大小写。大写字母和小写字母被认为是不同的字母。
•	不能与C#的类库名称相同。

关键字是 C# 编译器预定义的保留字。这些关键字不能用作标识符，但是，如果您想使用这些关键字作为标识符，可以在关键字前面加上 @ 字符作为前缀。
在 C# 中，变量分为以下几种类型：
值类型（Value types）如int，char，float等
引用类型（Reference types）如object，dynamic，string。当一个值类型转换为对象类型时，则被称为 装箱；另一方面，当一个对象类型转换为值类型时，则被称为拆箱。字符串（String）类型的值可以通过两种形式进行分配：引号和 @引号。
指针类型（Pointer types）

c#中类型转换包括隐式类型转换和强制类型转换，强制类型转换如：（double d = 11.11； int i；i = （int）d）。c#中内置的类型转换方法：ToBoolean(转换为布尔型)，ToByte(转换为字节类型)，ToChar（转换为单字符类型），ToDateTime（转换成日期——时间结构），ToDecimal（把int、float转换成十进制类型），ToDouble（转换为双精度浮点型），ToInt16（转换为16为整数类型），Tosbyte(转换为有符号字节类型)，ToSingle（转换为小浮点数类型），ToString（转换为字符串类型），ToType（转换为指定类型），ToUInt16（转换为16位无符号整数类型），ToUInt32（32位），ToUInt64（62位）。
