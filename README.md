# springmvc
Spring MVC框架是一个开源的Java平台，为开发强大的基于Java的Web应用程序提供全面的基础架构支持非常容易和非常快速。

Spring框架最初由Rod Johnson撰写，并于2003年6月根据Apache 2.0许可证首次发布。

本教程是基于2015年3月发布的Spring Framework版本4.1.6编写的。

Spring web MVC框架提供了MVC(模型 - 视图 - 控制器)架构和用于开发灵活和松散耦合的Web应用程序的组件。 MVC模式导致应用程序的不同方面(输入逻辑，业务逻辑和UI逻辑)分离，同时提供这些元素之间的松散耦合。

模型(Model)封装了应用程序数据，通常它们将由POJO类组成。
视图(View)负责渲染模型数据，一般来说它生成客户端浏览器可以解释HTML输出。
控制器(Controller)负责处理用户请求并构建适当的模型，并将其传递给视图进行渲染。
## DispatcherServlet组件类
Spring Web模型 - 视图 - 控制器(MVC)框架是围绕DispatcherServlet设计的，它处理所有的HTTP请求和响应。 Spring Web MVC DispatcherServlet的请求处理工作流如下图所示：
