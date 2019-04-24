# DaoismFramework框架介绍

DaoismFramework是一个基于springcloud全家桶技术的微服务框架，支持灰度发布、API网关、全链路压测、负载均衡、支持读写分离、轻量级的后台框架。<br>

框架的组成：<br>
1.daoism-service-common。<br>
2.daoism-service-gateway。<br>


daoism-service-gateway需要具备的特性：<br>
1.动态路由，即系统可以动态配置路由。<br>
2.热运维，运维时候，要永远在线，不能影响线上业务。<br>
3.鉴权机制<br>
4.限流<br>
5.降级，熔断<br>
6.灰度发布支持<br>
7.测试沙箱考虑<br>
8.防刷<br>
9.ACL（安全）<br>
10.分布式日志收集<br>
11.非阻塞<br>
12.监控<br>
13.操作日志审计<br>
14.黑白名单<br>
