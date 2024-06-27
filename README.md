# c00148-Springboot-Thymeleaf
基于Springboot+Thymeleaf的大学生实习管理系统-有报告（JavaWeb、程序设计）

@[TOC](基于Springboot+Thymeleaf的大学生实习管理系统-有报告（JavaWeb、程序设计）)

## 项目简介
本项目是基于Springboot+Thymeleaf的大学生实习管理系统，项目分为三种权限：管理员、教师和学生；

管理员功能：学生信息管理、教师信息管理、生产实习信息管理、顶岗实习信息管理；生产实习申请、我的生产实习、我的成绩、我的申请、顶岗实习申请、我的顶岗实习、我的成绩、我的申请、生产实习管理、生产实习过程管理、生产实习成绩统计、顶岗实习管理、系统管理（用户管理、角色管理、菜单管理）、分享等；
教师功能：学生信息管理、生产实习信息管理、顶岗实习信息管理、生产实习管理、生产实习过程管理、生产实习成绩统计、顶岗实习管理，分享等；
学生功能：生产实习、顶岗实习、实习申请、实习成绩以及分享等；


## 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=148)

 
## 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）、vscode、redis、node环境（16.X）；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：是

>登录：
管理员：账户 admin  密码  admin123
教师：账户 163401010314  密码 123456
学生：账户 163401010319  密码 123456


## 项目技术
 
后端：SpringBoot、MybatisPlus、mysql
前端：thymeleaf、html、bootstrap、jquery、ajax


## 运行截图



  0.功能结构图 

![0.功能结构图](https://img-blog.csdnimg.cn/img_convert/847a3d6d64fbf23fcdfa0f0be4612cb9.png)

  1.数据库模型图 

![1.数据库模型图](https://img-blog.csdnimg.cn/img_convert/efc4dbca67c68fce8ece622d6f49f77c.png)

  -1.项目报告 

![-1.项目报告](https://img-blog.csdnimg.cn/img_convert/4f3df8a8f0f2a593bb7c45b83fe501f7.png)

  2.数据库表 

![2.数据库表](https://img-blog.csdnimg.cn/img_convert/1022f711c54b3bb5f27bdc04e5b115d1.png)

  -2.下载所得 

![-2.下载所得](https://img-blog.csdnimg.cn/img_convert/564565cba394a5a89530e03d7e746013.png)

  3.项目结构 

![3.项目结构](https://img-blog.csdnimg.cn/img_convert/13fbc5635819c3c6022215a41fbd11cd.png)

  4.登录页面 

![4.登录页面](https://img-blog.csdnimg.cn/img_convert/693fe4e91f5e4c8aaa144c415483c2b0.png)

  5.管理员首页 

![5.管理员首页](https://img-blog.csdnimg.cn/img_convert/1fb66a271b9acedfc4ec5048e2d67bb1.png)

  6.管理员-学生信息管理 

![6.管理员-学生信息管理](https://img-blog.csdnimg.cn/img_convert/237811bab22e82078d4b5d774890a2db.png)

  7.管理员-教师信息管理 

![7.管理员-教师信息管理](https://img-blog.csdnimg.cn/img_convert/0ad8ee974475020be69c80950bcabe26.png)

  8.管理员-生产实习信息管理 

![8.管理员-生产实习信息管理](https://img-blog.csdnimg.cn/img_convert/8708e8048a7395762ce06bd94461036e.png)

  9.管理员-顶岗实习信息管理 

![9.管理员-顶岗实习信息管理](https://img-blog.csdnimg.cn/img_convert/bad0b9f05468a33e69e8af0633cc0e5c.png)

  10.顶岗实习-申请 

![10.顶岗实习-申请](https://img-blog.csdnimg.cn/img_convert/51b04bf88d7ae54eb05c5345fe375fcb.png)

  11.我的顶岗实习 

![11.我的顶岗实习](https://img-blog.csdnimg.cn/img_convert/fc601d66410f32d994d22dc8268e5782.png)

  12.我的实习成绩 

![12.我的实习成绩](https://img-blog.csdnimg.cn/img_convert/9413081a6c81e92a4c9877409caf31a2.png)

  13.我的实习申请 

![13.我的实习申请](https://img-blog.csdnimg.cn/img_convert/60c214e25aaeac7732e065e756ed9fd3.png)

  14.生产实习 

![14.生产实习](https://img-blog.csdnimg.cn/img_convert/4873c203e33ed795ab81a78e13685579.png)

  15.管理员生产实习审核 

![15.管理员生产实习审核](https://img-blog.csdnimg.cn/img_convert/894674968cdb708db82f708c5b2f9c4e.png)

  16.管理员-实习过程管理 

![16.管理员-实习过程管理](https://img-blog.csdnimg.cn/img_convert/c06aa045ec3c3250089feb45de2c41fe.png)

  17.管理员-实习成绩统计 

![17.管理员-实习成绩统计](https://img-blog.csdnimg.cn/img_convert/906dc342a281dcf1d1a6e441e536364d.png)

  18.论坛部分 

![18.论坛部分](https://img-blog.csdnimg.cn/img_convert/20d2e44d2ffe98edb28bb5301f9f27a3.png)

  19.系统管理-用户管理 

![19.系统管理-用户管理](https://img-blog.csdnimg.cn/img_convert/c5f6684e4ba047275f9c642bba37c847.png)

  20.菜单管理 

![20.菜单管理](https://img-blog.csdnimg.cn/img_convert/c04948864e2e42a7b1c7a8c88f9fe3c0.png)

  21.角色信息管理 

![21.角色信息管理](https://img-blog.csdnimg.cn/img_convert/6823e40948fcc0ed08eafcb30dffa5f3.png)

  22.个人信息 

![22.个人信息](https://img-blog.csdnimg.cn/img_convert/cab5ee3997e2bc2003bc08c9d2c1569b.png)

  23.教师登录页面-信息管理 

![23.教师登录页面-信息管理](https://img-blog.csdnimg.cn/img_convert/fef4fd6d349fd755e7c1960482de38ff.png)

  24.教师-实习管理 

![24.教师-实习管理](https://img-blog.csdnimg.cn/img_convert/c6e2f8f332ae175f5b15a32179a9a41e.png)

  25.学生-生产实习 

![25.学生-生产实习](https://img-blog.csdnimg.cn/img_convert/3afaddd2f681438a91cfc649913f5656.png)

  26.学生顶岗实习 

![26.学生顶岗实习](https://img-blog.csdnimg.cn/img_convert/caf15be34e48aa7205419919b267823b.png)
