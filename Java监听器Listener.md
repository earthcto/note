1. 什么是 Java 监听器

监听器也叫Listener，是Servlet的监听器，它可以监听客户端的请求、服务端的操作等。通过监听器，可以自动激发一些操作，比如监听在线的用户的数量。

2. Listener 接口分类

    1. ServletContextListener 监听 ServletContext 对象
    2. ServletContextAttributeListener 监听对 ServletContext 属性对象的操作，比如增加、修改、删除
    3. HttpSessionListener 监听 Session 对象
    4. HttpSessionActivationListener 监听HTTP会话的 active 和 passivate 情况， passivate 是指非法活动的 session 被写入持久设备（比如硬盘），active相反
    5. HttpSessionAttributeListener 监听 Session 中的属性操作
    6. ServletRequestListener 监听 Request 中的属性操作 
    7. ServletRequestAttributeListener 监听 Request 中的属性操作