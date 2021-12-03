[Java Web(一) Servlet详解！！ - 有梦想的老王 - 博客园](https://www.cnblogs.com/whgk/p/6399262.html)
[Servlet 包 | 菜鸟教程](https://www.runoob.com/servlet/servlet-packaging.html)

**Servlet 是属于 JavaEE？ 比如它的 jar 在哪下载等。官方 jar 在哪？**
jakarta ee
[Java Servlet 技术 - Java EE 6 教程](https://docs.oracle.com/javaee/6/tutorial/doc/bnafd.html)
[Java Platform, Enterprise Edition: The Java EE Tutorial Release 7 - Contents](https://docs.oracle.com/javaee/7/tutorial/index.html)
[Java Web项目缺少jsp、servlet jar包 - cxchanpin - 博客园](https://www.cnblogs.com/cxchanpin/p/7225904.html)

jetty 的包里有 jsp 的 jar 包


```xml
<!--        Servlet依赖-->
        <dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>javax.servlet-api</artifactId>
            <version>3.1.0</version>
            <scope>provided</scope>
        </dependency>
<!--        JSP依赖-->
        <dependency>
            <groupId>javax.servlet.jsp</groupId>
            <artifactId>javax.servlet.jsp-api</artifactId>
            <version>2.3.3</version>
            <scope>provided</scope>
        </dependency>
<!--        jstl表达式的依赖-->
        <dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>jstl</artifactId>
            <version>1.2</version>
        </dependency>
<!--        standar标签库-->
        <dependency>
            <groupId>taglibs</groupId>
            <artifactId>standard</artifactId>
            <version>1.1.2</version>
        </dependency>
```

[Java中的java、javax、sun、org包有什么区别_pan_junbiao的博客-CSDN博客_javax](https://blog.csdn.net/pan_junbiao/article/details/85004464)

下载JavaEE为什么是 glassfish5？ Java EE是一个抽象的规范？
[JavaSE、JavaEE 与Spring的概念](https://blog.csdn.net/weixin_44684812/article/details/102718931)

JavaEE 是一种规范？而不是实际的代码？ tomcat 实现了JavaEE？
[JavaEE的13种核心规范_不会英语的程序员不是好开拓者-CSDN博客](https://blog.csdn.net/weienjun/article/details/78883439)

[JAVA的servlet一定要用TOMCAT服务器吗](https://zhidao.baidu.com/question/303830845456390084.html)
[glassfish和tomcat各自的优势和劣势有哪些？ - 知乎](https://www.zhihu.com/question/20039000/answer/102719430)