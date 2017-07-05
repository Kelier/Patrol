### Patrol--高校巡查后台管理系统

这是大二时期我们的实训项目，一个4人小组在6周内的小小成果

你可以先看看基本效果，我摘了两个出来，更多界面你还是down下来比较好，直接的暴力演示可能导致部分效果失效，而与实际部署不同

[登录](https://htmlpreview.github.io/?https://github.com/Kelier/Patrol/blob/master/Patrol/WebRoot/login.jsp) | [列表](https://htmlpreview.github.io/?https://github.com/Kelier/Patrol/blob/master/Patrol/WebRoot/table_work.html)

项目目标有下面几个
* 实现角色权限的划分。不同角色对应不同的管理任务
* 高校各个年级的出勤情况/老师的管理程度
* 对比班级、学科、成绩，进行数据分析

#### 技术栈
>IDE：Myeclipse<br>
>服务器：Tomcat7以上<br>
>java环境：java1.7以上<br>
>数据库: Mysql<br>
>组件框架：Bootstrap/Easyui/Hui/Aui Jquery/Angular(我没用，组长用了)/Echarts

本项目我主要负责管理员登录页面、后台管理界面构建，数据分析模块以及后台部分接口的编写，回顾整个项目，发现自己写的代码冗长，效率较低，封装性不好，给后期维护带来了不少麻烦，算是我get的一个经验，另外在后台接口的编写中，我们采用了structs2+jdbc来写，里面的类没有进行分层，可能看起来业务很乱，也是同样的问题，所以给这项目减分不少，好在功能点是全的，成功完成了任务
