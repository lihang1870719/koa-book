序XIV
前言XV
第1章初识Express
1.1JavaScript革命
1.2初识Express
1.3Express简史
1.4升级到Express4.0
1.5Node：一种新型Web服务器
1.6Node的生态系统
1.7授权

第2章从Node开始
2.1获取Node
2.2使用终端
2.3编辑器
2.4npm
2.5用Node实现的简单Web服务器
2.5.1HelloWorld
2.5.2事件驱动编程
2.5.3路由
2.5.4静态资源服务
2.6走向Express

第3章省时省力的Express
3.1脚手架
3.2草地鹨旅行社网站
3.3初始步骤
3.3.1视图和布局
3.3.2视图和静态文件
3.3.3视图中的动态内容
3.4小结

第4章工欲善其事，必先利其器
4.1最佳实践
4.2版本控制
4.3针对本书如何使用Git
4.3.1如果你要自己动手
4.3.2如果你要使用官方存储库
4.4npm包
4.5项目元数据
4.6Node模块

第5章质量保证
5.1QA：值得吗
5.2逻辑与展示
5.3测试的类型
5.4QA技术概览
5.5运行你的服务器
5.6页面测试
5.7跨页测试
5.8逻辑测试
5.9去毛
5.10链接检查
5.11用Grunt实现自动化
5.12持续集成

第6章请求和响应对象
6.1URL的组成部分
6.2HTTP请求方法
6.3请求报头
6.4响应报头
6.5互联网媒体类型
6.6请求体
6.7参数
6.8请求对象
6.9响应对象
6.10获取更多信息
6.11小结
6.11.1内容渲染
6.11.2处理表单
6.11.3提供一个API

第7章Handlebars模板引擎
7.1唯一一条绝对规则
7.2选择模板引擎
7.3Jade：不走寻常路
7.4Handlebars基础
7.4.1注释
7.4.2块级表达式
7.4.3服务器端模板
7.4.4视图和布局
7.4.5在Express中使用（或不使用）布局
7.4.6局部文件
7.4.7段落
7.4.8完善你的模板
7.4.9客户端Handlebars
7.5小结

第8章表单处理
8.1向服务器发送客户端数据
8.2HTML表单
8.3编码
8.4处理表单的不同方式
8.5Express表单处理
8.6处理AJAX表单
8.7文件上传
8.8jQuery文件上传

第9章Cookie与会话
9.1凭证的外化
9.2Express中的Cookie
9.3检查Cookie
9.4会话
9.4.1内存存储
9.4.2使用会话
9.5用会话实现即显消息
9.6会话的用途

第10章中间件
10.1常用中间件
10.2第三方中间件

第11章发送邮件
11.1SMTP、MSA和MTA
11.2接收邮件
11.3邮件头
11.4邮件格式
11.5HTML邮件
11.6Nodemailer
11.6.1发送邮件
11.6.2将邮件发送给多个接收者
11.7发送批量邮件的更佳选择
11.8发送HTML邮件
11.8.1HTML邮件中的图片
11.8.2用视图发送HTML邮件
11.8.3封装邮件功能
11.9将邮件作为网站监测工具

第12章与生产相关的问题
12.1执行环境
12.2环境特定配置
12.3扩展你的网站
12.3.1用应用集群扩展
12.3.2处理未捕获的异常
12.3.3用多台服务器扩展
12.4网站监控
12.4.1第三方正常运行监控
12.4.2应用程序故障
12.5压力测试

第13章持久化
13.1文件系统持久化
13.2云持久化
13.3数据库持久化
13.3.1关于性能
13.3.2设置MongoDB
13.3.3Mongoose
13.3.4使用Mongoose连接数据库
13.3.5创建模式和模型
13.3.6添加初始数据
13.3.7获取数据
13.3.8添加数据
13.3.9用MongoDB存储会话数据

第14章路由
14.1路由和SEO
14.2子域名
14.3路由处理器是中间件
14.4路由路径和正则表达式
14.5路由参数
14.6组织路由
14.7在模块中声明路由
14.8按逻辑对处理器分组
14.9自动化渲染视图
14.10其他的路由组织方式

第15章RESTAPI和JSON
15.1JSON和XML
15.2我们的API
15.3API错误报告
15.4跨域资源共享
15.5我们的数据存储
15.6我们的测试
15.7用Express提供API
15.8使用REST插件
15.9使用子域名

第16章静态内容
16.1性能方面的考虑
16.2面向未来的网站
16.2.1静态映射
16.2.2视图中的静态资源
16.2.3CSS中的静态资源
16.3服务器端JavaScript中的静态资源
16.4客户端JavaScript中的静态资源
16.5提供静态资源
16.6修改静态内容
16.7打包和缩小
16.8关于第三方库
16.9QA
16.10小结

第17章在Express中实现MVC
17.1模型
17.2视图模型
17.3控制器
17.4小结

第18章安全
18.1HTTPS
18.1.1生成自己的证书
18.1.2使用免费的证书颁发机构
18.1.3购买证书
18.1.4对你的Express应用启用HTTPS
18.1.5关于端口的说明
18.1.6HTTPS和代理
18.2跨站请求伪造
18.3认证
18.3.1认证与授权
18.3.2密码的问题
18.3.3第三方认证
18.3.4把用户存在数据库中
18.3.5认证与注册和用户体验
18.3.6Passport
18.3.7基于角色的授权
18.3.8添加更多认证提供者
18.4小结

第19章集成第三方API
19.1社交媒体
19.1.1社交媒体插件和站点性能
19.1.2搜索推文
19.1.3渲染推文
19.2地理编码
19.2.1用谷歌的地理编码
19.2.2对你的数据做地理编码
19.2.3显示地图
19.2.4提升客户端性能
19.3天气数据
19.4小结

第20章调试
20.1调试的首要原则
20.2利用好REPL和控制台
20.3利用Node内置的调试器
20.4Node探查器
20.5调试异步函数
20.6调试Express

第21章正式启用
21.1域名注册和托管服务
21.1.1域名系统
21.1.2安全
21.1.3顶级域名
21.1.4子域名
21.1.5域名服务器
21.1.6托管
21.1.7部署
21.2小结

第22章维护
22.1维护的原则
22.1.1有长远规划
22.1.2使用源码控制系统
22.1.3使用问题追踪系统
22.1.4良好的卫生习惯
22.1.5不要拖延
22.1.6做常规的QA检查
22.1.7监测分析
22.1.8性能优化
22.1.9潜在用户追踪优先
22.1.10防止出现"不可见的"错误
22.2代码重用及重构
22.2.1私有npm库
22.2.2中间件
22.3小结

第23章其他资源
23.1在线文档
23.2期刊
23.3StackOverflow
23.4为Express做贡献
23.5小结
关于封面
关于作者
