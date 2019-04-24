# daoismframework框架介绍

daoismframework是一个基于springcloud全家桶技术的微服务框架，支持灰度发布、API网关、全链路压测、负载均衡、支持读写分离、轻量级的后台框架。

框架的组成：
1.daoism-service-common。
2.daoism-service-gateway。


daoism-service-gateway需要具备的特性：
1.动态路由，即系统可以动态配置路由。
2.热运维，运维时候，要永远在线，不能影响线上业务。
3.鉴权机制
4.限流
5.降级，熔断
6.灰度发布支持
7.测试沙箱考虑
8.防刷
9.ACL（安全）
10.分布式日志收集
11.非阻塞
12.监控
13.操作日志审计
14.黑白名单
