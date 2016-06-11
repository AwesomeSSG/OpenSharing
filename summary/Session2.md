# Topic: RESTful API简介
## Speaker: 何凯
## Content：
### REST是什么？
1. REST的基本概念：资源的表述性的状态转移。而RESTful是一个轻量级的框架。
2. REST也是基于B/S架构的Web Service的API。
3. REST所有的操作只针对资源，SOAP的操作针对服务而不是资源。
### SOAP和REST的那些事儿
1. Web Service主要有两种描述方式：WSDL/SOAP，REST
2. SOAP只能传递XML格式的通信文件，REST则可以通过XML也可以是JSON
3. SOAP支持多种协议：HTTP/HTTPS，SMTP，MIME，RPC。而REST基本只支持：HTTP/HTTPS
4. SOAP的通信请求都是以POST的形式发送的，即便是GET请求。
5. 相比REST的资源调用，SOAP的方法调用过程更接近远程过程调用的形式。
### REST的操作
1. REST是以链式的形式访问资源信息的。
2. REST的主要功能：过滤，排序，搜索。
3. 超过256的URL，其实可以将很多参数信息放在Request parameter中。
4. REST返回的是HTTP的Status code。
5. curl -X GET http://localhost:8080/api/v1/user/1
6. REST资源定义一般用复数。
### REST安全
### Swagger的介绍和使用
## Question：
1. 状态转移怎么理解？
答：资源的幂等性，资源状态转移后还是自己。
2. REST中PETCH的语义
答：PUT是把资源完整的提交，PETCH是修改了哪部分提交哪部分。但是PETCH存在修改不成功的风险，所以一般都是用PUT整体发送。
3. REST的参数写在哪里？
答：GET请求中的参数是无法放到参数里的，只能跟在URL后面。
4. Catch Server的Catch机制是怎么实现的，信息Catch在那里？
5. Swagger Editor的作用主要是做什么？
## Unfinished Task
1. Live demo
2. 什么是非资源的操作？
## Scheduled Presentation
认证方式相关分享 小白
