最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计容器健康检查设计思路
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.etx3og.asia/arts/931828.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.etx3og.asia/arts/392877.Doc

原标题：golang 熔断降级简易组件开发
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.etx3og.asia/arts/546915.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.etx3og.asia/arts/293718.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.etx3og.asia/arts/834579.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.etx3og.asia/arts/921965.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/574809.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.etx3og.asia/arts/334113.Doc

原标题：接口幂等性防重复请求实现
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.etx3og.asia/arts/167373.Doc

原标题：限流组件计数器令牌桶模式实现
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.etx3og.asia/arts/864351.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.etx3og.asia/arts/900733.Doc

原标题：golang 简单爬虫请求防封禁
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.etx3og.asia/arts/934792.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.etx3og.asia/arts/154058.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.etx3og.asia/arts/159532.Doc

原标题：数据库索引重建提升查询速度
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.etx3og.asia/arts/537054.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.etx3og.asia/arts/395542.Doc

原标题：前端错误监控上报系统搭建
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.etx3og.asia/arts/896108.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.etx3og.asia/arts/266249.Doc

原标题：多规则数据脱敏组件开发
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.etx3og.asia/arts/715662.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.etx3og.asia/arts/485560.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.etx3og.asia/arts/537433.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.etx3og.asia/arts/937930.Doc

原标题：快速入门异步编程基础模型
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.etx3og.asia/arts/937404.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.etx3og.asia/arts/904442.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.etx3og.asia/arts/815183.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.etx3og.asia/arts/966106.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.etx3og.asia/arts/485549.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.etx3og.asia/arts/638585.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.etx3og.asia/arts/147929.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.etx3og.asia/arts/934361.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.etx3og.asia/arts/717220.Doc

原标题：程序日志分级输出规范实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.etx3og.asia/arts/434100.Doc

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.etx3og.asia/arts/592583.Doc

原标题：git rebase 整理提交历史实操
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.etx3og.asia/arts/930076.Doc

原标题：包管理器依赖缓存清理
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.etx3og.asia/arts/963022.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.etx3og.asia/arts/738430.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.etx3og.asia/arts/900025.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.etx3og.asia/arts/290690.Doc

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.etx3og.asia/arts/997047.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.etx3og.asia/arts/891593.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 信号量控制并发数量
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.etx3og.asia/arts/925768.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.etx3og.asia/arts/936081.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.etx3og.asia/arts/534285.Doc

原标题：golang docker 部署 es 本地开发
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.etx3og.asia/arts/687098.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.etx3og.asia/arts/142661.Doc

原标题：从零搭建简单定时任务demo
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.etx3og.asia/arts/804303.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.etx3og.asia/arts/729810.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.etx3og.asia/arts/630742.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.etx3og.asia/arts/885400.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.etx3og.asia/arts/786001.Doc

原标题：golang redis zset 延时队列实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.etx3og.asia/arts/590627.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.etx3og.asia/arts/297611.Doc

原标题：golang mysql 避免 select * 查询
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.etx3og.asia/arts/816576.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.etx3og.asia/arts/896742.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.etx3og.asia/arts/747641.Doc

原标题：依赖安装失败全方位排错
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.etx3og.asia/arts/711966.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.etx3og.asia/arts/345735.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.etx3og.asia/arts/345720.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.etx3og.asia/arts/950905.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.etx3og.asia/arts/508283.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.etx3og.asia/arts/495482.Doc

原标题：快速入门简单签名校验实现思路
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.etx3og.asia/arts/551766.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.etx3og.asia/arts/616856.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.etx3og.asia/arts/961305.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.etx3og.asia/arts/909472.Doc

原标题：golang mongodb 文档结构设计原则
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.etx3og.asia/arts/906942.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.etx3og.asia/arts/231308.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.etx3og.asia/arts/456983.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.etx3og.asia/arts/263043.Doc

原标题：系统字符集统一乱码修复
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.etx3og.asia/arts/185713.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.etx3og.asia/arts/512994.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.etx3og.asia/arts/909750.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.etx3og.asia/arts/374391.Doc

原标题：golang redis 位图用户签到统计
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.etx3og.asia/arts/590964.Doc

原标题：golang redis zset 延时队列实现
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.etx3og.asia/arts/181001.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.etx3og.asia/arts/459760.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.etx3og.asia/arts/044724.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.etx3og.asia/arts/999802.Doc

原标题：设计思考：系统容量评估架构前期估算思路
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.etx3og.asia/arts/947768.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.etx3og.asia/arts/472217.Doc

三、实战开发｜Practice
原标题：golang 系统设计传输加密 tls 配置要点
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.etx3og.asia/arts/829563.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.etx3og.asia/arts/439009.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.etx3og.asia/arts/159235.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.etx3og.asia/arts/436631.Doc

原标题：golang 系统设计监控告警阈值设置思路
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.etx3og.asia/arts/858554.Doc

原标题：多规则数据脱敏组件开发
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.etx3og.asia/arts/310725.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.etx3og.asia/arts/538447.Doc

原标题：日志驱动异常日志不输出修复
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.etx3og.asia/arts/626611.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.etx3og.asia/arts/120377.Doc

原标题：golang context 上下文传参讲解
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.etx3og.asia/arts/015101.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.etx3og.asia/arts/401731.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.etx3og.asia/arts/080846.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.etx3og.asia/arts/421636.Doc

原标题：golang 单例模式实现几种方式
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.etx3og.asia/arts/602689.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.etx3og.asia/arts/688989.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.etx3og.asia/arts/910250.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.etx3og.asia/arts/254941.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.etx3og.asia/arts/808185.Doc

原标题：golang 熔断降级简易组件开发
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.etx3og.asia/arts/454368.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.etx3og.asia/arts/407920.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.etx3og.asia/arts/644179.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.etx3og.asia/arts/985706.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.etx3og.asia/arts/916875.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.etx3og.asia/arts/491083.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.etx3og.asia/arts/609542.Doc

原标题：Git 代码冲突正确处理方式
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.etx3og.asia/arts/127272.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.etx3og.asia/arts/643291.Doc

原标题：灰度发布策略服务平滑升级
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.etx3og.asia/arts/522166.Doc

原标题：零基础理解读写分离基础思想
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.etx3og.asia/arts/348090.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.etx3og.asia/arts/357111.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.etx3og.asia/arts/855365.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.etx3og.asia/arts/775915.Doc

原标题：跨域偶现失败配置修复
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.etx3og.asia/arts/014033.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.etx3og.asia/arts/560425.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.etx3og.asia/arts/524311.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.etx3og.asia/arts/715094.Doc

原标题：系统文件描述符上限调大
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.etx3og.asia/arts/539419.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.etx3og.asia/arts/535432.Doc

原标题：内存广播本地进程消息通知
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.etx3og.asia/arts/602550.Doc

原标题：golang 结构体深拷贝几种实现
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.etx3og.asia/arts/990072.Doc

四、架构设计｜Architecture
原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.etx3og.asia/arts/472016.Doc

原标题：大事务拆分防止连接池耗尽
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.etx3og.asia/arts/678772.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.etx3og.asia/arts/059744.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.etx3og.asia/arts/266256.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.etx3og.asia/arts/633917.Doc

原标题：内存泄漏定位分析完整流程
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.etx3og.asia/arts/047449.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.etx3og.asia/arts/612405.Doc

原标题：golang ci 流水线单元测试集成测试
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.etx3og.asia/arts/279746.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.etx3og.asia/arts/834317.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.etx3og.asia/arts/853661.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.etx3og.asia/arts/159975.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.etx3og.asia/arts/907176.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.etx3og.asia/arts/857403.Doc

原标题：golang kafka 同步异步消费对比
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.etx3og.asia/arts/492644.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.etx3og.asia/arts/846271.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.etx3og.asia/arts/006972.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.etx3og.asia/arts/226808.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.etx3og.asia/arts/257530.Doc

?
