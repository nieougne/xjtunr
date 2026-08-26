最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计数据库慢请求排查流程
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.17kxx0.asia/blog/338441.Doc

原标题：集成测试业务流程编写示例
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.17kxx0.asia/blog/307395.Doc

原标题：项目语义化版本号规范管理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.17kxx0.asia/blog/205878.Doc

原标题：golang 互斥锁读写锁并发安全
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.17kxx0.asia/blog/290581.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.17kxx0.asia/blog/220868.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.17kxx0.asia/blog/518768.Doc

原标题：golang redis 缓存穿透解决方案
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.17kxx0.asia/blog/014482.Doc

原标题：golang 简易埋点日志上报实现
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://book.17kxx0.asia/blog/697383.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.17kxx0.asia/blog/070976.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.17kxx0.asia/blog/878083.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.17kxx0.asia/blog/085569.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.17kxx0.asia/blog/571796.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.17kxx0.asia/blog/495858.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.17kxx0.asia/blog/347469.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.17kxx0.asia/blog/012447.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.17kxx0.asia/blog/626361.Doc

原标题：提交第一个开源 PR 完整流程
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.17kxx0.asia/blog/418065.Doc

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.17kxx0.asia/blog/292219.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.17kxx0.asia/blog/963806.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.17kxx0.asia/blog/301938.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.17kxx0.asia/blog/698533.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.17kxx0.asia/blog/710332.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.17kxx0.asia/blog/418800.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.17kxx0.asia/blog/144658.Doc

原标题：语义化版本依赖管理防错乱
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.17kxx0.asia/blog/377695.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.17kxx0.asia/blog/900277.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.17kxx0.asia/blog/394555.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.17kxx0.asia/blog/043900.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.17kxx0.asia/blog/873647.Doc

原标题：Docker 容器网络不通排查
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.17kxx0.asia/blog/235703.Doc

原标题：CORS 跨域问题多种解决方案
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.17kxx0.asia/blog/070714.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.17kxx0.asia/blog/179135.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.17kxx0.asia/blog/036499.Doc

原标题：DNS TTL 配置域名切换生效
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.17kxx0.asia/blog/147184.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.17kxx0.asia/blog/288081.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.17kxx0.asia/blog/982228.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.17kxx0.asia/blog/314418.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.17kxx0.asia/blog/442631.Doc

原标题：预编译 SQL 防注入实现
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.17kxx0.asia/blog/922246.Doc

原标题：golang 跨域处理中间件编写
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.17kxx0.asia/blog/410674.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计服务优雅停机完整流程
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.17kxx0.asia/blog/585774.Doc

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.17kxx0.asia/blog/256562.Doc

原标题：代码格式化工具团队统一风格
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.17kxx0.asia/blog/695869.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.17kxx0.asia/blog/724114.Doc

原标题：定时任务重复执行分布式锁
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.17kxx0.asia/blog/592683.Doc

原标题：不必要字符转义关闭业务异常
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.17kxx0.asia/blog/410647.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.17kxx0.asia/blog/331455.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.17kxx0.asia/blog/638875.Doc

原标题：golang kafka 死信队列业务落地
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.17kxx0.asia/blog/789163.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.17kxx0.asia/blog/162759.Doc

原标题：golang 链路追踪简易实现方案
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.17kxx0.asia/blog/856890.Doc

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.17kxx0.asia/blog/106984.Doc

原标题：CLI 工具进度条交互效果开发
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.17kxx0.asia/blog/002792.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.17kxx0.asia/blog/797737.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.17kxx0.asia/blog/289977.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.17kxx0.asia/blog/325422.Doc

原标题：开源源码阅读拆解学习思路
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.17kxx0.asia/blog/550313.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.17kxx0.asia/blog/643803.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.17kxx0.asia/blog/647014.Doc

原标题：golang etcd 配置中心简单使用
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.17kxx0.asia/blog/500729.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://book.17kxx0.asia/blog/529155.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.17kxx0.asia/blog/205914.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.17kxx0.asia/blog/808323.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.17kxx0.asia/blog/822344.Doc

原标题：golang 信号量控制并发数量
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.17kxx0.asia/blog/304857.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.17kxx0.asia/blog/877256.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.17kxx0.asia/blog/923232.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.17kxx0.asia/blog/542861.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.17kxx0.asia/blog/748591.Doc

原标题：golang base64 编码解码实操
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.17kxx0.asia/blog/655038.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.17kxx0.asia/blog/031139.Doc

原标题：集成测试业务流程编写示例
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.17kxx0.asia/blog/501672.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.17kxx0.asia/blog/626835.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.17kxx0.asia/blog/950627.Doc

原标题：接口限流逻辑简单模拟实现
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.17kxx0.asia/blog/513826.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.17kxx0.asia/blog/097816.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://book.17kxx0.asia/blog/237820.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.17kxx0.asia/blog/972968.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.17kxx0.asia/blog/524407.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.17kxx0.asia/blog/894931.Doc

三、实战开发｜Practice
原标题：设计思考：API网关和BFF职责边界划分
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.17kxx0.asia/blog/789882.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://book.17kxx0.asia/blog/384144.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.17kxx0.asia/blog/066903.Doc

原标题：hosts 配置本地回环访问修复
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.17kxx0.asia/blog/356979.Doc

原标题：数据库死锁成因规避方案
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.17kxx0.asia/blog/331305.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.17kxx0.asia/blog/353448.Doc

原标题：golang 系统设计埋点数据上报方案
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.17kxx0.asia/blog/786742.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.17kxx0.asia/blog/994690.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.17kxx0.asia/blog/563575.Doc

原标题：golang md5 sha 加密工具实现
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.17kxx0.asia/blog/339809.Doc

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.17kxx0.asia/blog/881337.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.17kxx0.asia/blog/313879.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.17kxx0.asia/blog/489850.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.17kxx0.asia/blog/500283.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.17kxx0.asia/blog/466880.Doc

原标题：golang 系统设计对象池复用减少内存分配
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.17kxx0.asia/blog/960369.Doc

原标题：简易网关请求路由过滤模拟
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.17kxx0.asia/blog/699489.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.17kxx0.asia/blog/097045.Doc

原标题：快速入门简单签名校验实现思路
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://book.17kxx0.asia/blog/673051.Doc

原标题：golang redis 发布订阅简单示例
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.17kxx0.asia/blog/199580.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.17kxx0.asia/blog/522563.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.17kxx0.asia/blog/775100.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.17kxx0.asia/blog/925769.Doc

原标题：golang 分页查询封装通用工具
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.17kxx0.asia/blog/008906.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.17kxx0.asia/blog/529118.Doc

原标题：golang kafka 死信队列业务落地
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.17kxx0.asia/blog/339179.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.17kxx0.asia/blog/711629.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.17kxx0.asia/blog/376543.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.17kxx0.asia/blog/307579.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.17kxx0.asia/blog/009854.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.17kxx0.asia/blog/025765.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.17kxx0.asia/blog/071796.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.17kxx0.asia/blog/893136.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.17kxx0.asia/blog/896658.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.17kxx0.asia/blog/125841.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.17kxx0.asia/blog/888162.Doc

原标题：文件监控服务自动重启开发
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.17kxx0.asia/blog/141864.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.17kxx0.asia/blog/012109.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.17kxx0.asia/blog/729957.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.17kxx0.asia/blog/787145.Doc

四、架构设计｜Architecture
原标题：golang 系统设计读写穿透更新缓存几种方案
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://book.17kxx0.asia/blog/963254.Doc

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.17kxx0.asia/blog/342862.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.17kxx0.asia/blog/028508.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.17kxx0.asia/blog/514463.Doc

原标题：新手参与开源社区贡献指南
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.17kxx0.asia/blog/418570.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.17kxx0.asia/blog/394468.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.17kxx0.asia/blog/673452.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.17kxx0.asia/blog/389201.Doc

原标题：golang http client 连接池调优
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.17kxx0.asia/blog/903781.Doc

原标题：服务健康检查告警监控体系
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://book.17kxx0.asia/blog/859259.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.17kxx0.asia/blog/536361.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.17kxx0.asia/blog/272101.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.17kxx0.asia/blog/169086.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.17kxx0.asia/blog/334146.Doc

原标题：golang 开发环境快速搭建指南
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.17kxx0.asia/blog/963801.Doc

原标题：文件锁正确使用避免死锁
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://book.17kxx0.asia/blog/316517.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.17kxx0.asia/blog/307227.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.17kxx0.asia/blog/884251.Doc

?
