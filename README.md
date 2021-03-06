# HankoFramework

平台参考mall-swarm、pig开源项目

## 一、架构设计

![输入图片说明](https://images.gitee.com/uploads/images/2021/0304/194233_9977f5b2_922663.png "HanoFramework-SpringCloud微服务分布式架构.png")

## 二、技术选型
<escape>

|                    | 版本/名称                                  |
| ------------------ | ------------------------------------------ |
| SpringCloud        | SpringCloud Hoxton.SR9                     |
|                    | Springboot 2.3.5.RELEASE                   |
| 数据库             | Mysql                                      |
|                    | Mysql-plus                                 |
|                    | pagehelper                                 |
|                    | mybatis-plus-generator(代码自动生成)       |
| 缓存               | Redis                                      |
|                    | Spring @Cacheable                          |
| 文件存储           | Minio                                      |
| 工具类             | hutool                                     |
| 注册中心、配置中心 | Nacos                                      |
| 网关               | gateway                                    |
| 安全               | springsecurity+oauth2+jwt+gateway(webflux) |
| 前端               | vue                                        |
|                    | vue-router                                 |
|                    | vuex                                       |
|                    | Element                                    |
|                    | Axios                                      |
|                    | mockjs                                     |

</escape>


## 三、表设计

![输入图片说明](https://images.gitee.com/uploads/images/2021/0304/194411_63a9edb8_922663.png "image-20210304193454987.png")
​	

sys_permission 用户权限表(包含资源、操作)

sys_menu菜单表(特殊资源表)

## 四、编码

- 目录 

hankofw

hankofw-admin-web

hankofw-web



- 包目录

com.hankofw



