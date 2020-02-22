# SchoolBus

## 引言

> 所涉及的技术包含：
>
> - 后端：
>   - Springboot
>   - MyBatis
>   - Dubbo
>   - Mysql
>   - Redis
>   - RocketMQ
>   - 持续补充...
> - 前端：
>   - vue
>   - vuex
>   - vue-router
>   - axios
>   - mint-ui
>   - 持续补充...


## 架构图

### 架构思考

- **我也是第一次做这样的项目，没有什么经验，希望大家提供一些建议和经验，我也在这条坎坷的路上不断的去尝试和总结。希望大家多多支持，🙏**
- **注意：**由于学生，没有能力买好一点的服务器，因此采用内网穿透技术将本地服务映射个人的阿里云。
- 根据本校小程序的页面：[pages](https://www.processon.com/view/link/5e4eb17ae4b0e415c2756fd5)，由于疫情期间，下单模块的页面暂时无法分析。日后会补充...
- 根绝仅有的页面：**班车预约主页**、**车次列表页面**、**我的车票页面**、**用户登陆注册修改页面**和待定的**订单和下单页面**
- 暂时采用的[架构技术图](https://www.processon.com/view/link/5e4eb5cde4b0a802afb2787c)，后续会改善其中的所采用的技术，并且会针对每一个所涉及的技术的**使用场景**。
- 后端环境搭建，暂时没有采用分布式，数据库忽略，后续补充。[后端搭建](https://www.processon.com/view/link/5e4f7c6ce4b0d4dc87667203)
- 后端部分启动测试，包括Zookeeper、Dubbo、Tomcat、RocketMQ、RocketMQ-Console等[启动图及命令](https://www.processon.com/view/link/5e500788e4b0cc44b5a570eb)
  - [全网最全frp内网穿透(ssh及web)]([https://github.com/DreamCats/JavaBooks/blob/master/Tools/frp/%E5%85%A8%E7%BD%91%E6%9C%80%E5%85%A8frp%E5%86%85%E7%BD%91%E7%A9%BF%E9%80%8F(ssh%E5%8F%8Aweb).md](https://github.com/DreamCats/JavaBooks/blob/master/Tools/frp/全网最全frp内网穿透(ssh及web).md))
  - [centos7安装dubbo环境]([https://github.com/DreamCats/JavaBooks/blob/master/Tools/dubbo/centos7%E5%AE%89%E8%A3%85dubbo%E7%8E%AF%E5%A2%83.md](https://github.com/DreamCats/JavaBooks/blob/master/Tools/dubbo/centos7安装dubbo环境.md))
  - [centos7安装rocketmq环境及配置]([https://github.com/DreamCats/JavaBooks/blob/master/Tools/rocketmq/centos7%E5%AE%89%E8%A3%85rocketmq%E5%8F%8A%E9%85%8D%E7%BD%AE.md](https://github.com/DreamCats/JavaBooks/blob/master/Tools/rocketmq/centos7安装rocketmq及配置.md))
