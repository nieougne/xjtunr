最新前沿技术资讯

一、入门教程｜Getting Started
原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.ajyme2.asia/arts/859251.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.ajyme2.asia/arts/834418.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.ajyme2.asia/arts/721276.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.ajyme2.asia/arts/642670.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/070055.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.ajyme2.asia/arts/906338.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/907443.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/926126.Doc

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.ajyme2.asia/arts/938334.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.ajyme2.asia/arts/423293.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.ajyme2.asia/arts/909774.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.ajyme2.asia/arts/935252.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.ajyme2.asia/arts/752105.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/174669.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.ajyme2.asia/arts/740097.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.ajyme2.asia/arts/310739.Doc

原标题：git stash 代码暂存切换分支
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.ajyme2.asia/arts/331367.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/720000.Doc

原标题：Practice：实现IP黑名单拦截中间件实践
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/855517.Doc

原标题：golang 内存缓存简单实现方案
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/630085.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/666840.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.ajyme2.asia/arts/263560.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.ajyme2.asia/arts/686267.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.ajyme2.asia/arts/353524.Doc

原标题：项目语义化版本号规范管理
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.ajyme2.asia/arts/073347.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.ajyme2.asia/arts/356554.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.ajyme2.asia/arts/911943.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.ajyme2.asia/arts/933980.Doc

原标题：golang goroutine 池任务调度
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ajyme2.asia/arts/401815.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.ajyme2.asia/arts/974739.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.ajyme2.asia/arts/074760.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.ajyme2.asia/arts/314939.Doc

原标题：golang 分布式上下文传递方案
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.ajyme2.asia/arts/075114.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.ajyme2.asia/arts/721581.Doc

原标题：golang 文件上传下载接口开发
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.ajyme2.asia/arts/459593.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.ajyme2.asia/arts/386945.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.ajyme2.asia/arts/264053.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.ajyme2.asia/arts/191074.Doc

原标题：golang gin 路由分组权限管控
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.ajyme2.asia/arts/156528.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.ajyme2.asia/arts/248631.Doc


二、踩坑排错｜Troubleshooting
原标题：golang pprof 线上采集性能数据
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.ajyme2.asia/arts/561649.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.ajyme2.asia/arts/096557.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.ajyme2.asia/arts/590521.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.ajyme2.asia/arts/829187.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.ajyme2.asia/arts/764059.Doc

原标题：环境变量不生效问题修复
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.ajyme2.asia/arts/140537.Doc

原标题：灰度发布策略服务平滑升级
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.ajyme2.asia/arts/312138.Doc

原标题：golang kafka 重试机制配置实操
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.ajyme2.asia/arts/664825.Doc

原标题：时间同步修复令牌提前过期
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.ajyme2.asia/arts/596655.Doc

原标题：golang kafka 死信队列业务落地
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.ajyme2.asia/arts/589359.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.ajyme2.asia/arts/712271.Doc

原标题：golang pprof 线上采集性能数据
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ajyme2.asia/arts/388588.Doc

原标题：GC 垃圾回收优化降低 CPU 占用
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.ajyme2.asia/arts/374584.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.ajyme2.asia/arts/275184.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.ajyme2.asia/arts/378117.Doc

原标题：布隆过滤器数据高效去重实现
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.ajyme2.asia/arts/467476.Doc

原标题：缓存基础原理与简单代码实现
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.ajyme2.asia/arts/496703.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.ajyme2.asia/arts/122149.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.ajyme2.asia/arts/020174.Doc

原标题：golang redis lua 脚本开发调试
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.ajyme2.asia/arts/287294.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.ajyme2.asia/arts/503697.Doc

原标题：从零搭建简单Mock接口服务
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.ajyme2.asia/arts/182322.Doc

原标题：golang gorm 批量插入性能调优
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.ajyme2.asia/arts/827904.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.ajyme2.asia/arts/129256.Doc

原标题：Git 代码冲突正确处理方式
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.ajyme2.asia/arts/087929.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.ajyme2.asia/arts/125041.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.ajyme2.asia/arts/482181.Doc

原标题：golang prometheus histogram 指标
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.ajyme2.asia/arts/141460.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.ajyme2.asia/arts/154220.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.ajyme2.asia/arts/520036.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.ajyme2.asia/arts/644034.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.ajyme2.asia/arts/061176.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.ajyme2.asia/arts/490649.Doc

原标题：golang 限流熔断降级完整示例
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.ajyme2.asia/arts/430351.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.ajyme2.asia/arts/272252.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.ajyme2.asia/arts/449707.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.ajyme2.asia/arts/377492.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.ajyme2.asia/arts/637392.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.ajyme2.asia/arts/567915.Doc

原标题：设计思考：分布式会话架构选型对比
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.ajyme2.asia/arts/599807.Doc

三、实战开发｜Practice
原标题：新手避坑：第一次提交GitHub项目完整流程
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.ajyme2.asia/arts/527888.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.ajyme2.asia/arts/406655.Doc

原标题：动态定时任务业务调度实现
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.ajyme2.asia/arts/346035.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.ajyme2.asia/arts/058637.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.ajyme2.asia/arts/622241.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.ajyme2.asia/arts/194144.Doc

原标题：实战项目：百万日志文件解析处理脚本实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.ajyme2.asia/arts/506398.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.ajyme2.asia/arts/419498.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ajyme2.asia/arts/376382.Doc

原标题：JWT 令牌过期异常处理
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.ajyme2.asia/arts/455206.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.ajyme2.asia/arts/158327.Doc

原标题：gitignore 文件编写过滤规则
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.ajyme2.asia/arts/125502.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.ajyme2.asia/arts/606608.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.ajyme2.asia/arts/166705.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.ajyme2.asia/arts/558267.Doc

原标题：本地运行正常线上报错排查
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.ajyme2.asia/arts/588342.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.ajyme2.asia/arts/122269.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.ajyme2.asia/arts/233927.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.ajyme2.asia/arts/457480.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.ajyme2.asia/arts/599683.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.ajyme2.asia/arts/328271.Doc

原标题：简易日志收集集中管理方案
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/943079.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.ajyme2.asia/arts/270749.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.ajyme2.asia/arts/113386.Doc

原标题：golang base64 编码解码实操
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.ajyme2.asia/arts/530306.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.ajyme2.asia/arts/307730.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.ajyme2.asia/arts/536045.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.ajyme2.asia/arts/495228.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ajyme2.asia/arts/488459.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.ajyme2.asia/arts/992090.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.ajyme2.asia/arts/300169.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.ajyme2.asia/arts/969292.Doc

原标题：golang docker 网络模式桥接 host
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.ajyme2.asia/arts/084697.Doc

原标题：golang cron 定时任务防并发执行
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.ajyme2.asia/arts/643146.Doc

原标题：程序信号中断退出处理逻辑
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.ajyme2.asia/arts/503301.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.ajyme2.asia/arts/016857.Doc

原标题：golang 系统设计会话共享多实例部署
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.ajyme2.asia/arts/829854.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.ajyme2.asia/arts/680194.Doc

原标题：golang traceId spanId 传递方案
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.ajyme2.asia/arts/974872.Doc

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.ajyme2.asia/arts/651909.Doc

四、架构设计｜Architecture
原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.ajyme2.asia/arts/641889.Doc

原标题：零基础理解进程、线程基础概念区别
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ajyme2.asia/arts/715495.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.ajyme2.asia/arts/128294.Doc

原标题：包管理器依赖冲突解决方案
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.ajyme2.asia/arts/552815.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.ajyme2.asia/arts/880676.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ajyme2.asia/arts/595479.Doc

原标题：golang 简易埋点日志上报实现
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.ajyme2.asia/arts/880073.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.ajyme2.asia/arts/721142.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.ajyme2.asia/arts/909762.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.ajyme2.asia/arts/854411.Doc

原标题：golang redis 位图用户签到统计
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.ajyme2.asia/arts/820170.Doc

原标题：系统字符集统一乱码修复
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.ajyme2.asia/arts/640867.Doc

原标题：开源源码阅读拆解学习思路
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.ajyme2.asia/arts/520709.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.ajyme2.asia/arts/349286.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.ajyme2.asia/arts/714449.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.ajyme2.asia/arts/252465.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.ajyme2.asia/arts/906612.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.ajyme2.asia/arts/892224.Doc

?
