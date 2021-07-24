# Spring5

- IOC 解耦对象，对象间无直接联系，有 IOC 容器进行管理-
- 类创建对象有 IOC 完成，这就是控制反转 IOC

---





IOC 与 DI 是同一件事情的不同描述。

-  DI 应用程序依赖容器创建并注入他所需要的外部资源
- IOC  容器控制程序



---





Spring 框架主要功能是通过其核心容器来实现的。

- spring 提供的两种核心容器分别是 BeanFactory 和 ApplicationContext.
- IOC/DI 通常有 setter 注入和构造方法注入两种实现方式
- spring 中编辑配置文件管理 Bean 又称为 Bean 的装配
- 实际上装配就是告诉容器需要哪些 Bean ,以及容器是如何使用 IOC 将他们配合起来的。



---



Beans 是指项目中提供业务功能的 Bean ,即容器要管理的 Bean . Beans 就是一个常见的 JavaBean ,Java类

- spring 中管理 Bean 是在配置文件中进行的