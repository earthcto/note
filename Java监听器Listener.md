1. 什么是 Java 监听器

2. Listener 接口分类

    1. ServletContextListener 监听 ServletContext 对象
    2. ServletContextAttributeListener 监听对 ServletContext 属性对象的操作，比如增加、修改、删除
    3. HttpSessionListener 监听 Session 对象
    3. HttpSessionActivationListener 监听HTTP会话的 active 和 passivate 情况， passivate 是指非法活动的 session 被写入持久设备（比如硬盘），active相反