最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计最小权限原则落地实践
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.n9orer.asia/arts/353780.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.n9orer.asia/arts/855627.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.n9orer.asia/arts/037291.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.n9orer.asia/arts/631323.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.n9orer.asia/arts/064765.Doc

原标题：从零搭建本地数据库开发环境
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.n9orer.asia/arts/670278.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.n9orer.asia/arts/197558.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.n9orer.asia/arts/322439.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.n9orer.asia/arts/421698.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.n9orer.asia/arts/968489.Doc

原标题：golang k8s secret 加密敏感信息
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.n9orer.asia/arts/257611.Doc

原标题：golang 重试退避机制代码实现
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.n9orer.asia/arts/711072.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.n9orer.asia/arts/785407.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.n9orer.asia/arts/417112.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.n9orer.asia/arts/874841.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.n9orer.asia/arts/718070.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.n9orer.asia/arts/856371.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.n9orer.asia/arts/085306.Doc

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.n9orer.asia/arts/836096.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.n9orer.asia/arts/292099.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.n9orer.asia/arts/030647.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.n9orer.asia/arts/025188.Doc

原标题：新手参与开源社区贡献指南
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.n9orer.asia/arts/385100.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.n9orer.asia/arts/598955.Doc

原标题：程序预加载加快服务启动速度
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.n9orer.asia/arts/672705.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.n9orer.asia/arts/668144.Doc

原标题：golang redis 大 key 识别处理方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.n9orer.asia/arts/208395.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.n9orer.asia/arts/563502.Doc

原标题：数据库主从延迟业务兼容处理
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.n9orer.asia/arts/006025.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.n9orer.asia/arts/016412.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.n9orer.asia/arts/549461.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.n9orer.asia/arts/640252.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.n9orer.asia/arts/007806.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.n9orer.asia/arts/267319.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.n9orer.asia/arts/114670.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.n9orer.asia/arts/795831.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.n9orer.asia/arts/920405.Doc

原标题：极简方式搭建个人技术文档站点
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.n9orer.asia/arts/005796.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.n9orer.asia/arts/573249.Doc

原标题：golang k8s ingress 路由域名转发
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.n9orer.asia/arts/037806.Doc


二、踩坑排错｜Troubleshooting
原标题：全局异常处理器接口返回统一
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.n9orer.asia/arts/305133.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.n9orer.asia/arts/014153.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.n9orer.asia/arts/480303.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.n9orer.asia/arts/349177.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.n9orer.asia/arts/016257.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.n9orer.asia/arts/756526.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.n9orer.asia/arts/022989.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.n9orer.asia/arts/023113.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.n9orer.asia/arts/834369.Doc

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.n9orer.asia/arts/302173.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.n9orer.asia/arts/820614.Doc

原标题：golang docker compose 环境变量
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.n9orer.asia/arts/347688.Doc

原标题：Nginx 反向代理路由配置实战
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.n9orer.asia/arts/424598.Doc

原标题：golang mysql 长连接短连接对比
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.n9orer.asia/arts/207834.Doc

原标题：Cookie Session 会话状态管理
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.n9orer.asia/arts/828431.Doc

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.n9orer.asia/arts/161141.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.n9orer.asia/arts/181858.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.n9orer.asia/arts/040734.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.n9orer.asia/arts/971185.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.n9orer.asia/arts/670114.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.n9orer.asia/arts/748855.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.n9orer.asia/arts/290079.Doc

原标题：nodejs 事件循环机制完整讲解
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.n9orer.asia/arts/121375.Doc

原标题：WSL 文件权限访问异常修复
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.n9orer.asia/arts/384588.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.n9orer.asia/arts/722881.Doc

原标题：golang docker compose 环境变量
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.n9orer.asia/arts/072545.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.n9orer.asia/arts/137369.Doc

原标题：golang pprof 线上采集性能数据
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.n9orer.asia/arts/593386.Doc

原标题：安全复盘：消息队列未授权访问安全加固
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.n9orer.asia/arts/890012.Doc

原标题：golang 静态文件服务搭建教程
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.n9orer.asia/arts/196782.Doc

原标题：极简 API 网关路由转发实现
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.n9orer.asia/arts/866832.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.n9orer.asia/arts/759146.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.n9orer.asia/arts/272351.Doc

原标题：react 状态管理方案选型对比
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.n9orer.asia/arts/063512.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.n9orer.asia/arts/185477.Doc

原标题：golang kafka offset 提交策略
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.n9orer.asia/arts/126844.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.n9orer.asia/arts/539170.Doc

原标题：静态资源 404 路径打包修复
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.n9orer.asia/arts/639575.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.n9orer.asia/arts/695828.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.n9orer.asia/arts/782211.Doc

三、实战开发｜Practice
原标题：部署实践：服务器防火墙安全组配置实践
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.n9orer.asia/arts/737411.Doc

原标题：golang kafka 生产者参数调优
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.n9orer.asia/arts/722945.Doc

原标题：golang 大文件 http 下载服务
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.n9orer.asia/arts/371407.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.n9orer.asia/arts/930631.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.n9orer.asia/arts/292711.Doc

原标题：golang context 上下文传参讲解
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.n9orer.asia/arts/230626.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.n9orer.asia/arts/974313.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.n9orer.asia/arts/820161.Doc

原标题：golang redis lua 脚本开发调试
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.n9orer.asia/arts/693024.Doc

原标题：浏览器内存泄漏排查前端页面
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.n9orer.asia/arts/482124.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.n9orer.asia/arts/376652.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.n9orer.asia/arts/993055.Doc

原标题：macOS 脚本执行权限开启
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.n9orer.asia/arts/933003.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.n9orer.asia/arts/913218.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.n9orer.asia/arts/960395.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.n9orer.asia/arts/044528.Doc

原标题：golang etcd 配置中心简单使用
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.n9orer.asia/arts/471476.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.n9orer.asia/arts/315114.Doc

原标题：百万数据 Excel 导出内存优化
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.n9orer.asia/arts/123328.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.n9orer.asia/arts/315858.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.n9orer.asia/arts/312455.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.n9orer.asia/arts/867661.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.n9orer.asia/arts/966950.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.n9orer.asia/arts/345397.Doc

原标题：限流组件计数器令牌桶模式实现
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.n9orer.asia/arts/045397.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.n9orer.asia/arts/373812.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.n9orer.asia/arts/552842.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.n9orer.asia/arts/745777.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.n9orer.asia/arts/167664.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.n9orer.asia/arts/881354.Doc

原标题：golang 表单文件大小限制配置
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.n9orer.asia/arts/055585.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.n9orer.asia/arts/535258.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.n9orer.asia/arts/714940.Doc

原标题：简易日志收集集中管理方案
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.n9orer.asia/arts/297437.Doc

原标题：golang etcd 配置中心简单使用
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.n9orer.asia/arts/947177.Doc

原标题：前端虚拟列表大数据渲染优化
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.n9orer.asia/arts/631601.Doc

原标题：golang kafka 消费者偏移量管理
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.n9orer.asia/arts/270493.Doc

原标题：服务器时钟同步任务错乱修复
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.n9orer.asia/arts/478846.Doc

原标题：数据库分表路由写入分片修正
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.n9orer.asia/arts/178400.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.n9orer.asia/arts/273856.Doc

四、架构设计｜Architecture
原标题：入门实践：本地简单代理服务搭建
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.n9orer.asia/arts/001727.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.n9orer.asia/arts/614113.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.n9orer.asia/arts/903095.Doc

原标题：实战：对象存储断点续传下载实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.n9orer.asia/arts/280077.Doc

原标题：Cookie Session 会话状态管理
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.n9orer.asia/arts/711105.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.n9orer.asia/arts/441196.Doc

原标题：布隆过滤器误判问题修正
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.n9orer.asia/arts/941304.Doc

原标题：容器资源限制防止宿主机过载
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.n9orer.asia/arts/781274.Doc

原标题：入门实战：搭建简易静态网页项目
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.n9orer.asia/arts/292528.Doc

原标题：nodejs 中间件模式原理剖析
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.n9orer.asia/arts/074359.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.n9orer.asia/arts/515822.Doc

原标题：大文件导出内存溢出防护
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.n9orer.asia/arts/677011.Doc

原标题：依赖安装失败全方位排错
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.n9orer.asia/arts/071080.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.n9orer.asia/arts/491797.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.n9orer.asia/arts/623888.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.n9orer.asia/arts/909169.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.n9orer.asia/arts/457067.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.n9orer.asia/arts/596838.Doc

?
