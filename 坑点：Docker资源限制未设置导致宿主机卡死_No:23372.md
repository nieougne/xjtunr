最新前沿技术资讯

一、入门教程｜Getting Started
原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.29fr26.asia/arts/784974.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.29fr26.asia/arts/300305.Doc

原标题：优化实践：多级缓存减少下游服务调用压力
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.29fr26.asia/arts/481066.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.29fr26.asia/arts/224580.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.29fr26.asia/arts/639978.Doc

原标题：布隆过滤器数据高效去重实现
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.29fr26.asia/arts/184929.Doc

原标题：后端分页查询逻辑代码实现
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.29fr26.asia/arts/093548.Doc

原标题：Nginx 反向代理路由配置实战
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.29fr26.asia/arts/384928.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.29fr26.asia/arts/773485.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.29fr26.asia/arts/077304.Doc

原标题：超大数据集分页性能优化方案
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.29fr26.asia/arts/256399.Doc

原标题：包管理器依赖冲突解决方案
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.29fr26.asia/arts/847605.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.29fr26.asia/arts/643365.Doc

原标题：前端国际化多语言方案落地
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.29fr26.asia/arts/559378.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.29fr26.asia/arts/939780.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.29fr26.asia/arts/480839.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.29fr26.asia/arts/902823.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.29fr26.asia/arts/733691.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.29fr26.asia/arts/884819.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.29fr26.asia/arts/195410.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.29fr26.asia/arts/679072.Doc

原标题：数据库死锁成因规避方案
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.29fr26.asia/arts/422605.Doc

原标题：入门实践：简单批量处理脚本编写
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.29fr26.asia/arts/636660.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.29fr26.asia/arts/430668.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.29fr26.asia/arts/898250.Doc

原标题：golang 系统设计分布式会话方案对比
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.29fr26.asia/arts/009600.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.29fr26.asia/arts/875171.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.29fr26.asia/arts/010772.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.29fr26.asia/arts/167006.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.29fr26.asia/arts/191665.Doc

原标题：golang docker 运行 etcd 本地测试
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.29fr26.asia/arts/251390.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.29fr26.asia/arts/468889.Doc

原标题：上传接口跨域配置特殊适配
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.29fr26.asia/arts/754309.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.29fr26.asia/arts/715829.Doc

原标题：从零学习简单分页逻辑实现思路
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.29fr26.asia/arts/162781.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.29fr26.asia/arts/268329.Doc

原标题：golang defer panic 异常处理
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.29fr26.asia/arts/485280.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.29fr26.asia/arts/035410.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.29fr26.asia/arts/469253.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/533063.Doc


二、踩坑排错｜Troubleshooting
原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.29fr26.asia/arts/155878.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.29fr26.asia/arts/298122.Doc

原标题：Hands‑on：简易请求转发代理中间件实现
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.29fr26.asia/arts/087339.Doc

原标题：golang es 分页深分页性能优化
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.29fr26.asia/arts/413224.Doc

原标题：golang mysql limit 大分页优化
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.29fr26.asia/arts/114135.Doc

原标题：限流规则误拦截正常请求修复
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.29fr26.asia/arts/952110.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.29fr26.asia/arts/046284.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.29fr26.asia/arts/901108.Doc

原标题：环境变量不生效问题修复
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.29fr26.asia/arts/097623.Doc

原标题：golang k8s 节点污点容忍度配置
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.29fr26.asia/arts/607708.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.29fr26.asia/arts/517415.Doc

原标题：Spring 事务传播机制配置生效
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.29fr26.asia/arts/161102.Doc

原标题：从零搭建简单的健康检查接口示例
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.29fr26.asia/arts/225505.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.29fr26.asia/arts/170276.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.29fr26.asia/arts/313120.Doc

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.29fr26.asia/arts/828423.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.29fr26.asia/arts/931227.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.29fr26.asia/arts/894687.Doc

原标题：golang docker compose 完整语法
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.29fr26.asia/arts/793272.Doc

原标题：golang mongodb 事务多文档使用
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.29fr26.asia/arts/992101.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.29fr26.asia/arts/542582.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.29fr26.asia/arts/842410.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.29fr26.asia/arts/004301.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.29fr26.asia/arts/487392.Doc

原标题：开发生产环境资源路径统一
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.29fr26.asia/arts/525127.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/960633.Doc

原标题：编译打包产物依赖分析解读
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.29fr26.asia/arts/535004.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.29fr26.asia/arts/345584.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.29fr26.asia/arts/128470.Doc

原标题：版本升级服务启动失败处理
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.29fr26.asia/arts/235408.Doc

原标题：golang 单元测试 mock http 请求
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.29fr26.asia/arts/641072.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.29fr26.asia/arts/562338.Doc

原标题：golang 简易埋点日志上报实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.29fr26.asia/arts/111774.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.29fr26.asia/arts/999623.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.29fr26.asia/arts/945811.Doc

原标题：实践：数据库回滚点业务调试实践
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.29fr26.asia/arts/169980.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.29fr26.asia/arts/557385.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.29fr26.asia/arts/829378.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.29fr26.asia/arts/596479.Doc

原标题：Cookie Session 会话状态管理
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.29fr26.asia/arts/527551.Doc

三、实战开发｜Practice
原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.29fr26.asia/arts/788522.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.29fr26.asia/arts/419385.Doc

原标题：golang 系统设计内部服务调用超时设置要点
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.29fr26.asia/arts/691442.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.29fr26.asia/arts/455194.Doc

原标题：线程池拒绝策略任务丢失防护
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.29fr26.asia/arts/642216.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.29fr26.asia/arts/449980.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.29fr26.asia/arts/558876.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.29fr26.asia/arts/636466.Doc

原标题：golang 文件上传下载接口开发
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.29fr26.asia/arts/993424.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.29fr26.asia/arts/398144.Doc

原标题：golang mock 单元测试编写技巧
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.29fr26.asia/arts/595851.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.29fr26.asia/arts/648548.Doc

原标题：golang 协程泄露问题排查方法
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.29fr26.asia/arts/718869.Doc

原标题：DNS TTL 配置域名切换生效
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.29fr26.asia/arts/939603.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.29fr26.asia/arts/203243.Doc

原标题：内存溢出问题现象识别排查
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.29fr26.asia/arts/932301.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.29fr26.asia/arts/740368.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.29fr26.asia/arts/781065.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.29fr26.asia/arts/167344.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.29fr26.asia/arts/254047.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.29fr26.asia/arts/855402.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.29fr26.asia/arts/566622.Doc

原标题：golang k8s liveness readiness 探针
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.29fr26.asia/arts/051380.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.29fr26.asia/arts/291093.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.29fr26.asia/arts/342197.Doc

原标题：数据库死锁成因规避方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.29fr26.asia/arts/972610.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.29fr26.asia/arts/988864.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.29fr26.asia/arts/719428.Doc

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.29fr26.asia/arts/930531.Doc

原标题：快速入门对象存储基础使用场景
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.29fr26.asia/arts/307945.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.29fr26.asia/arts/260553.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.29fr26.asia/arts/655641.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.29fr26.asia/arts/603380.Doc

原标题：文件读写与异常捕获代码示例
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.29fr26.asia/arts/856860.Doc

原标题：Docker 容器网络不通排查
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.29fr26.asia/arts/753796.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.29fr26.asia/arts/617760.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.29fr26.asia/arts/037980.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.29fr26.asia/arts/751051.Doc

原标题：全平台系统环境变量配置
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.29fr26.asia/arts/311343.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.29fr26.asia/arts/924255.Doc

四、架构设计｜Architecture
原标题：包管理器依赖冲突解决方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.29fr26.asia/arts/931033.Doc

原标题：本地数据库开发环境搭建指南
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.29fr26.asia/arts/073898.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.29fr26.asia/arts/180827.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.29fr26.asia/arts/122832.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.29fr26.asia/arts/996264.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.29fr26.asia/arts/424195.Doc

原标题：业务错误码完整落地实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.29fr26.asia/arts/303608.Doc

原标题：golang es 分页深分页性能优化
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.29fr26.asia/arts/221858.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.29fr26.asia/arts/101869.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.29fr26.asia/arts/977220.Doc

原标题：golang k8s helm chart 简单编写
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.29fr26.asia/arts/888452.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.29fr26.asia/arts/594356.Doc

原标题：异步编程 Promise 执行流程解析
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.29fr26.asia/arts/756808.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.29fr26.asia/arts/758057.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.29fr26.asia/arts/485019.Doc

原标题：入门实践：实现简单文件读写功能
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.29fr26.asia/arts/293538.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.29fr26.asia/arts/078718.Doc

原标题：golang 接口请求日志记录中间件
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.29fr26.asia/arts/636837.Doc

?
