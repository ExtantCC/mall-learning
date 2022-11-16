# mall学习教程

## 简介
mall学习教程，架构、业务、技术要点全方位解析。mall项目（50k+star）是一套电商系统，使用现阶段主流技术实现。涵盖了SpringBoot 2.3.0、MyBatis 3.4.6、Elasticsearch 7.6.2、RabbitMQ 3.7.15、Redis 5.0、MongoDB 4.2.5、Mysql5.7等技术，采用Docker容器化部署。

## 项目地址
- 后台项目：[https://github.com/macrozheng/mall](https://github.com/macrozheng/mall)
- 前端项目：[https://github.com/macrozheng/mall-admin-web](https://github.com/macrozheng/mall-admin-web)
- 微服务项目：[https://github.com/macrozheng/mall-swarm](https://github.com/macrozheng/mall-swarm)

## 更好的阅读体验
- 文档地址：[https://www.macrozheng.com](https://www.macrozheng.com)
- 备用地址：[https://macrozheng.github.io/mall-learning](https://macrozheng.github.io/mall-learning)

## 序章

> 项目架构及数据库概览，推荐一些项目学习所需知识点。

- [mall架构及功能概览](https://www.macrozheng.com/mall/foreword/mall_foreword_01.md)
- [mall学习所需知识点（推荐资料）](https://www.macrozheng.com/mall/foreword/mall_foreword_02.md)

## 架构篇

> 手把手教你搭建一个mall在使用的项目骨架，带你逐步熟悉mall所使用的技术栈。

- [mall整合SpringBoot+MyBatis搭建基本骨架](docs/architect/mall_arch_01.md)
- [mall整合Swagger-UI实现在线API文档](docs/architect/mall_arch_02.md)
- [mall整合Redis实现缓存功能](docs/architect/mall_arch_03.md)
- [mall整合SpringSecurity和JWT实现认证和授权（一）](docs/architect/mall_arch_04.md)
- [mall整合SpringSecurity和JWT实现认证和授权（二）](docs/architect/mall_arch_05.md)
- [mall整合SpringTask实现定时任务](docs/architect/mall_arch_06.md)
- [mall整合Elasticsearch实现商品搜索](docs/architect/mall_arch_07.md)
- [mall整合Mongodb实现文档操作](docs/architect/mall_arch_08.md)
- [mall整合RabbitMQ实现延迟消息](docs/architect/mall_arch_09.md)
- [mall整合OSS实现文件上传](docs/architect/mall_arch_10.md)

## 业务篇

> 全面解析mall中使用的数据库表结构，带你熟悉mall项目中的电商业务。

- [mall数据库表结构概览](docs/database/mall_database_overview.md)
- [商品模块数据库表解析（一）](docs/database/mall_pms_01.md)
- [商品模块数据库表解析（二）](docs/database/mall_pms_02.md)
- [订单模块数据库表解析（一）](docs/database/mall_oms_01.md)
- [订单模块数据库表解析（二）](docs/database/mall_oms_02.md)
- [订单模块数据库表解析（三）](docs/database/mall_oms_03.md)
- [营销模块数据库表解析（一）](docs/database/mall_sms_01.md)
- [营销模块数据库表解析（二）](docs/database/mall_sms_02.md)
- [营销模块数据库表解析（三）](docs/database/mall_sms_03.md)
- [权限管理功能设计与优化](docs/database/mall_permission.md)

## 技术要点篇

> mall中一些功能的技术要点解析，这些技术要点和业务结合地比较紧密。

- [MyBatis Generator使用过程中踩过的一个坑](docs/technology/mybatis_mapper.md)
- [SpringBoot应用中使用AOP记录接口访问日志](docs/technology/aop_log.md)
- [前后端分离项目，如何解决跨域问题](docs/technology/springboot_cors.md)
- [Java 8都出那么久了，Stream API了解下？](docs/technology/java_stream.md)
- [仅需四步，整合SpringSecurity+JWT实现登录认证！](docs/technology/springsecurity_use.md)
- [前后端分离项目，如何优雅实现文件存储！](docs/technology/minio_use.md)
- [前后端分离项目，引入Spring Cloud Gateway遇到的一个问题！](docs/technology/gateway_cors.md)
- [手把手教你搞定权限管理，结合Spring Security实现接口的动态权限控制！](docs/technology/permission_back.md)
- [手把手教你搞定权限管理，结合Vue实现菜单的动态权限控制！](docs/technology/permission_front.md)
- [商品SKU功能设计与优化](docs/technology/product_sku.md)
- [SpringBoot中处理校验逻辑的两种方式，真的很机智！](docs/technology/springboot_validator.md)
- [使用Redis+AOP优化权限管理功能，这波操作贼爽！](docs/technology/redis_permission.md)
- [Elasticsearch项目实战，商品搜索功能设计与实现！](docs/technology/product_search.md)
- [RabbitMQ实现延迟消息居然如此简单，整个插件就完事了！](docs/technology/rabbitmq_delay.md)
- [给Swagger升级了新版本，没想到居然有这么多坑！](docs/technology/swagger_upgrade.md)
- [Elasticsearch 升级 7.x 版本后，我感觉掉坑里了！](docs/technology/elasticsearch_upgrade.md)
- [搞定Mall项目中的权限管理功能，弄懂这些问题就妥了！](docs/technology/mall_permission_question.md)

## 部署篇

> mall开发及生产环境的搭建，涵盖Windows、Docker、K8S及自动化部署。

- [mall在Windows环境下的部署](docs/deploy/mall_deploy_windows.md)
- [mall在Linux环境下的部署（基于Docker容器）](docs/deploy/mall_deploy_docker.md)
- [mall在Linux环境下的部署（基于Docker Compose）](docs/deploy/mall_deploy_docker_compose.md)
- [mall前端项目的安装与部署](docs/deploy/mall_deploy_web.md)
- [mall-swarm在Windows环境下的部署](docs/deploy/mall_swarm_deploy_windows.md)
- [mall-swarm在Linux环境下的部署（基于Docker容器）](docs/deploy/mall_swarm_deploy_docker.md)
- [mall使用Jenkins实现自动化部署](docs/deploy/mall_deploy_jenkins.md)
- [mall-swarm使用Jenkins实现自动化部署](docs/deploy/mall_swarm_deploy_jenkins.md)
- [mall-swarm微服务项目在K8S下的实践！](docs/deploy/mall_swarm_deploy_k8s.md)

## 参考篇

> mall相关技术的参考教程，每篇都是可以独立学习的教程，学习过程中遇到不懂的知识点可以从这里找找。

- [开发者必备Mysql命令](docs/reference/mysql.md)
- [还在百度Linux命令？推荐一套我用起来特顺手的命令！](docs/reference/linux_command.md)
- [Linux防火墙Firewall和Iptables的使用](docs/reference/linux_firewall.md)
- [还在百度Docker命令？推荐一套我用起来特顺手的命令！](docs/reference/docker_command.md)
- [使用Maven插件为SpringBoot应用构建Docker镜像](docs/reference/docker_maven.md)
- [使用DockerFile为SpringBoot应用构建Docker镜像](docs/reference/docker_file.md)
- [使用Docker Compose部署SpringBoot应用](docs/reference/docker_compose.md)
- [Hutool中那些常用的工具类和方法 ](docs/reference/hutool_start.md)
- [Nginx的这些妙用，你肯定有不知道的！](docs/reference/nginx.md)
- [使用Jenkins一键打包部署SpringBoot应用，就是这么6！](docs/reference/jenkins.md)
- [使用Jenkins一键打包部署前端应用，就是这么6！](docs/reference/jenkins_vue.md)
- [Github标星19K+Star，10分钟自建对象存储服务！](docs/reference/minio.md)
- [Spring Data Redis 最佳实践！](docs/reference/spring_data_redis.md)
- [Elasticsearch快速入门，掌握这些刚刚好！](docs/reference/elasticsearch_start.md)
- [MongoDB快速入门，掌握这些刚刚好！](docs/reference/mongodb_start.md)
- [我常用的自动化部署技巧，贼好用，推荐给大家！](docs/reference/springboot_auto_deploy.md)
- [连RabbitMQ的5种核心消息模式都不懂，也敢说自己会用消息队列！](docs/reference/rabbitmq_start.md)
- [SpringBoot应用整合ELK实现日志收集](docs/reference/mall_tiny_elk.md)
- [你居然还去服务器上捞日志，搭个日志收集系统难道不香么！](docs/reference/mall_elk_advance.md)
- [给Swagger换了个新皮肤，瞬间高大上了！](docs/reference/knife4j_start.md)
- [Docker服务开放了这个端口，服务器分分钟变肉机！](docs/reference/docker_protect_socket.md)
- [居然有人想白嫖我的日志，赶紧开启安全保护压压惊！](docs/reference/elk_security.md)
- [Nginx如何支持HTTPS？手把手教贼简单！](docs/reference/nginx_https_start.md)
- [还在手动整合Swagger？Swagger官方Starter是真的香！](docs/reference/swagger_starter.md)
- [肝了一周总结的SpringBoot实战教程，太实用了！](docs/reference/springboot_start.md)
- [解放双手！MyBatis官方代码生成工具给力！](docs/reference/mybatis_generator_start.md)
- [Lombok有啥牛皮的？SpringBoot和IDEA官方都要支持它！](docs/reference/lombok_start.md)

