

# syt

##  Introduction

`syt` is an hospital online appointment system. In the past, patients had to go to hospital with no appointment and wait for several hours to meet their doctors. With the help of syt, patients can make an appointment with their doctors before meeting and they will not need to wait for long time. 



### Project Details

#### Backend System

yygh_parent is the backend of syt and includes all backend services of syt, such as patient services, order services, statistic services and spring gateway services. It connnects database and makes operations on database for frontend.



#### Hospital online appointment platform

yygh-site is a vue project and aims to help  patients  make appointment with their doctors. Patients can search for hospital and department on the website and choose the doctor they need to meet. 

![image-20221112004109600](documents/typora-user-images/image-20221112004109600.png)





![image-20221111014548111](documents/typora-user-images/image-20221111014548111.png)

![image-20221111014621236](documents/typora-user-images/image-20221111014621236.png)

#### Hospital management System for the platform

vue-admin-template-master is a vue project and aims to help hospital online appointment platform manager to manage hospital and users information.



![image-20221112001029381](documents/typora-user-images/image-20221112001029381.png)

![image-20221112003417107](documents/typora-user-images/image-20221112003417107.png)

![image-20221112004020687](documents/typora-user-images/image-20221112004020687.png)

#### Hospital management System for the hospital

Hospital-manage is a vue hospital management system . It aims to help hospital manager to manage hospital . Hospital managers can upload their hospital set , department and schedule information to database.They can also show information of hospital set, department and schedule.

![image-20221112003907268](documents/typora-user-images/image-20221112003907268.png)

![image-20221112003838964](documents/typora-user-images/image-20221112003838964.png)

![image-20221112003809613](documents/typora-user-images/image-20221112003809613.png)



### Techiques

#### Backend Technique

| Technique     | Detail         | Official Website                           |
| :------------------- | ------------------- | ---------------------------------------------- |
| SpringBoot           | ??????+MVC??????           | https://spring.io/projects/spring-boot         |
| SpringCloud          | ??????                  | https://spring.io/projects/spring-boot         |
| MyBatis              | ORM??????             | http://www.mybatis.org/mybatis-3/zh/index.html |
| RabbitMQ             | ????????????            | https://www.rabbitmq.com/                      |
| Redis                | ???????????????          | https://redis.io/                              |
| MongoDB              | NoSql?????????         | https://www.mongodb.com                        |
| Nginx                | ?????????????????????      | https://www.nginx.com/                         |
| Docker               | ??????????????????        | https://www.docker.com                         |
| OSS                  | ????????????            | https://github.com/aliyun/aliyun-oss-java-sdk  |
| JWT                  | JWT????????????         | https://github.com/jwtk/jjwt                   |
| Lombok               | ????????????????????????    | https://github.com/rzwitserloot/lombok         |
| Swagger-UI           | ??????????????????        | https://github.com/swagger-api/swagger-ui      |



#### Frontend Technique

| ??????       | ??????                  | ??????                                   |
| ---------- | --------------------- | :------------------------------------- |
| Vue        | ????????????              | https://vuejs.org/                     |
| Vue-router | ????????????              | https://router.vuejs.org/              |
| Element    | ??????UI??????            | https://element.eleme.io               |
| Axios      | ??????HTTP??????          | https://github.com/axios/axios         |
| Nuxt       | ???????????????????????????     | https://zh.nuxtjs.org/                 |

#### Architecture diagram

##### Technical Architecture Diagram

![??????????????????](documents/typora-user-images/??????????????????.png)

##### Business Architecture Diagram

![?????????????????????](documents/typora-user-images/?????????????????????.png)
