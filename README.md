# 黑马商城微服务
## 项目简介
黑马商城微服务项目是基于Spring Cloud微服务架构开发的一套电商系统，采用前后端分离的模式，前台采用Vue.js，后台采用Spring Boot、Spring Security、Spring Data JPA、MyBatis等技术实现。

## 项目架构
![架构图](https://i.loli.net/2021/07/15/2y2y27y27y27y27y.png)

## 项目模块
- **hm-common** 公共模块，包含一些工具类、常量、公共配置等。
- **hm-gateway** 网关模块，基于Spring Cloud Gateway实现，负责请求的转发、权限校验、限流、熔断等。
- **hm-auth** 认证模块，基于Spring Security实现，负责用户认证、鉴权、权限管理等。
- **hm-user** 用户模块，负责用户信息的管理、订单管理、收货地址管理等。
- **hm-product** 商品模块，负责商品的管理、分类管理、品牌管理等。
- **hm-order** 订单模块，负责订单的管理、支付管理、发货管理等。
- **hm-search** 搜索模块，负责商品的搜索、推荐等。
- **hm-message** 消息模块，负责用户消息的管理、推送管理等。
- **hm-chat** 聊天模块，负责用户间的聊天功能。
- **hm-admin** 后台管理模块，基于Spring Boot、Spring Security、Spring Data JPA、MyBatis等技术实现，负责后台管理系统的开发。

## 项目部署
### 环境准备
- JDK 1.8+
- MySQL 5.7+
- Redis 3.0+
- Maven 3.6+
- Nacos 1.4.1+
- Spring Cloud Hoxton.SR8+
- Node.js 12.16+
- Vue.js 2.6+

### 项目启动
1. 启动Nacos注册中心，下载地址：https://github.com/alibaba/nacos/releases
2. 启动Redis，下载地址：https://redis.io/download
3. 启动MySQL，下载地址：https://dev.mysql.com/downloads/mysql/
4. 启动hm-gateway微服务，运行hm-gateway模块下的Application.java
5. 启动hm-auth微服务，运行hm-auth模块下的Application.java
6. 启动hm-user微服务，运行hm-user模块下的Application.java
7. 启动hm-product微服务，运行hm-product模块下的Application.java
8. 启动hm-order微服务，运行hm-order模块下的Application.java
9. 启动hm-search微服务，运行hm-search模块下的Application.java
10. 启动hm-message微服务，运行hm-message模块下的Application.java
11. 启动hm-chat微服务，运行hm-chat模块下的Application.java
12. 启动hm-admin微服务，运行hm-admin模块下的Application.java
13. 启动hm-gateway微服务，运行hm-gateway模块下的Application.java

## 项目演示
- 前台演示地址：http://localhost:8080
- 后台演示地址：http://localhost:8081/login
- 用户名：admin
- 密码：admin123

## 开发进度
- [x] 微服务网关hm-gateway