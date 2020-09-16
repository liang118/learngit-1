  

# java笔记

## 2020年9月11日

1. SSH：struts2+spring+Hibernate（传统企业架构）
2. SSM：springMVC + spring + mybatis（现在互联网架构）
3. spring全家桶架构：springMVC + spring springDate系列



## 2020年9月12日

1. bean的singlton和prototype类型：
   - singlton是加载配置文件的时候就创建，但是prototype是每次调用的时候在创建，有jvm回收。

## 2020年9月14日

1. 构造javabean的三种方法
   - <!--方法1：交给容器管理，默认调用无参构造方法-->
   - <!--方法2：静态工厂-->
   - <!--方法三：实例化工厂-->
2. DI的中方法
   - 属性的set方法注入：在类中下好set方法，配置中<b>property</b>注入
   - 属性的构造方法注入：在类中写好构造方法，配置中<b>constructor-arg</b>注入
   - 集合属性的注入