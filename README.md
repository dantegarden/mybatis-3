MyBatis SQL Mapper Framework for Java
=====================================
克隆自[官方仓库](https://github.com/mybatis/mybatis-3) 3.4.x分支，目前版本是3.4.7

根据本人阅读源码的理解，对关键的组件添加了注释信息

可在根目录运行以下命令，将jar包安装到本地仓库
```
mvn clean install -Dmaven.test.skip=true 
```
然后通过在pom中添加以下信息，引入此依赖
```
<dependency>
    <groupId>org.mybatis</groupId>
    <artifactId>mybatis</artifactId>
    <version>3.4.7-mine</version>
</dependency>
```

![mybatis](http://mybatis.github.io/images/mybatis-logo.png)

The MyBatis SQL mapper framework makes it easier to use a relational database with object-oriented applications.
MyBatis couples objects with stored procedures or SQL statements using a XML descriptor or annotations.
Simplicity is the biggest advantage of the MyBatis data mapper over object relational mapping tools.

Essentials
----------

* [See the docs](http://mybatis.github.io/mybatis-3)
* [Download Latest](https://github.com/mybatis/mybatis-3/releases)
* [Download Snapshot](https://oss.sonatype.org/content/repositories/snapshots/org/mybatis/mybatis/)
"# mybatis-3" 
