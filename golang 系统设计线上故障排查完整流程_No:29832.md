最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计线上故障排查完整流程
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.mc15zf.asia/blog/4207095.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.mc15zf.asia/blog/0868152.sHtMl

原标题：简易日志收集集中管理方案
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.mc15zf.asia/blog/3171784.sHtMl

原标题：golang redis 热点 key 业务规避
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.mc15zf.asia/blog/4804653.sHtMl

原标题：golang 系统设计压测环境隔离避免影响生产
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://book.mc15zf.asia/blog/5512955.sHtMl

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.mc15zf.asia/blog/6629828.sHtMl

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.mc15zf.asia/blog/4978127.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.mc15zf.asia/blog/4917758.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.mc15zf.asia/blog/6733582.sHtMl

原标题：golang 简单爬虫请求防封禁
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.mc15zf.asia/blog/0421725.sHtMl

原标题：前端防抖节流高频事件处理
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.mc15zf.asia/blog/4110876.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://book.mc15zf.asia/blog/3589670.sHtMl

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.mc15zf.asia/blog/9364243.sHtMl

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.mc15zf.asia/blog/4698405.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://book.mc15zf.asia/blog/5466365.sHtMl

原标题：端口占用释放资源重启服务
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.mc15zf.asia/blog/7683937.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.mc15zf.asia/blog/8710245.sHtMl

原标题：Redis 热点 key 拆分降低集群压力
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.mc15zf.asia/blog/8556985.sHtMl

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.mc15zf.asia/blog/6099610.sHtMl

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.mc15zf.asia/blog/9218033.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.mc15zf.asia/blog/9984136.sHtMl

原标题：调试工具断点调试变量查看技巧
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.mc15zf.asia/blog/0908776.sHtMl

原标题：开源项目本地运行排错完整清单
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.mc15zf.asia/blog/0282902.sHtMl

原标题：零基础理解依赖管理与包管理器
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.mc15zf.asia/blog/3262594.sHtMl

原标题：golang 系统设计日志级别业务使用原则梳理
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.mc15zf.asia/blog/4285767.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.mc15zf.asia/blog/9126474.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.mc15zf.asia/blog/1002458.sHtMl

原标题：golang redis hyperloglog 基数统计
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.mc15zf.asia/blog/0994020.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.mc15zf.asia/blog/8581833.sHtMl

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.mc15zf.asia/blog/9461903.sHtMl

原标题：golang docker compose 部署 minio
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://book.mc15zf.asia/blog/3282493.sHtMl

原标题：快速入门消息通知简单实现方案
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.mc15zf.asia/blog/1074320.sHtMl

原标题：DevOps：容器健康探针livenessreadiness配置
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.mc15zf.asia/blog/8259121.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.mc15zf.asia/blog/7080890.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.mc15zf.asia/blog/5049914.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.mc15zf.asia/blog/7443969.sHtMl

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.mc15zf.asia/blog/4987687.sHtMl

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.mc15zf.asia/blog/4955405.sHtMl

原标题：新手快速上手 Git 版本控制实操指南
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.mc15zf.asia/blog/3332050.sHtMl

原标题：项目脚手架模板生成工具
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.mc15zf.asia/blog/8571104.sHtMl


二、踩坑排错｜Troubleshooting
原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.mc15zf.asia/blog/7097576.sHtMl

原标题：golang 系统设计定时任务动态启停配置方案
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.mc15zf.asia/blog/8168768.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.mc15zf.asia/blog/1667763.sHtMl

原标题：golang 系统设计内网外网服务隔离方案
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.mc15zf.asia/blog/1779047.sHtMl

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.mc15zf.asia/blog/0885281.sHtMl

原标题：golang 系统设计缓存预热缓存降级实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.mc15zf.asia/blog/1613611.sHtMl

原标题：全平台系统环境变量配置
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.mc15zf.asia/blog/4330985.sHtMl

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.mc15zf.asia/blog/8514500.sHtMl

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.mc15zf.asia/blog/1923533.sHtMl

原标题：express 中间件开发业务实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.mc15zf.asia/blog/6630264.sHtMl

原标题：本地简易配置中心动态管理
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.mc15zf.asia/blog/5619823.sHtMl

原标题：方案设计：分布式分页查询架构难点处理
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.mc15zf.asia/blog/2221685.sHtMl

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.mc15zf.asia/blog/9231207.sHtMl

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.mc15zf.asia/blog/2188457.sHtMl

原标题：golang jwt 过期刷新 token 实现
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.mc15zf.asia/blog/7811363.sHtMl

原标题：代理 HTTPS 证书访问异常处理
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.mc15zf.asia/blog/2707657.sHtMl

原标题：golang 协程泄露问题排查方法
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.mc15zf.asia/blog/7503456.sHtMl

原标题：极简 API 网关路由转发实现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.mc15zf.asia/blog/1870209.sHtMl

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.mc15zf.asia/blog/7429896.sHtMl

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.mc15zf.asia/blog/4837903.sHtMl

原标题：文件描述符优化进程卡死修复
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.mc15zf.asia/blog/7898114.sHtMl

原标题：golang 系统设计压测数据构造方法实现
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.mc15zf.asia/blog/8668025.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.mc15zf.asia/blog/9168789.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.mc15zf.asia/blog/7285515.sHtMl

原标题：golang 批量任务协程控制防雪崩
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.mc15zf.asia/blog/4258060.sHtMl

原标题：部署实践：Nginx高可用配置方案实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.mc15zf.asia/blog/5043060.sHtMl

原标题：golang 系统设计并发控制协程池任务池实现
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.mc15zf.asia/blog/3852866.sHtMl

原标题：零基础理解进程、线程基础概念区别
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.mc15zf.asia/blog/8390963.sHtMl

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.mc15zf.asia/blog/2280927.sHtMl

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.mc15zf.asia/blog/9135106.sHtMl

原标题：实战项目：百万日志文件解析处理脚本实践
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.mc15zf.asia/blog/4268120.sHtMl

原标题：golang 系统设计缓存一致性方案对比
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.mc15zf.asia/blog/0461264.sHtMl

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.mc15zf.asia/blog/8865510.sHtMl

原标题：golang redis 缓存更新策略讲解
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.mc15zf.asia/blog/7541261.sHtMl

原标题：golang channel 通道并发处理
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.mc15zf.asia/blog/9701324.sHtMl

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.mc15zf.asia/blog/0543989.sHtMl

原标题：ICMP 放通网络丢包问题修复
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://book.mc15zf.asia/blog/2486978.sHtMl

原标题：nodejs jwt 登录鉴权完整示例
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.mc15zf.asia/blog/8607620.sHtMl

原标题：序列化版本不一致解析失败
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.mc15zf.asia/blog/4749544.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.mc15zf.asia/blog/7427600.sHtMl

三、实战开发｜Practice
原标题：架构思考：单体应用向微服务拆分演进路径
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.mc15zf.asia/blog/2694431.sHtMl

原标题：golang 系统设计接口返回格式统一规范
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.mc15zf.asia/blog/0268555.sHtMl

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.mc15zf.asia/blog/6778410.sHtMl

原标题：前端工程化 webpack 打包优化
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.mc15zf.asia/blog/3038519.sHtMl

原标题：跨库查询性能优化处理
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.mc15zf.asia/blog/4497055.sHtMl

原标题：API 接口调试与异常处理实战
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://book.mc15zf.asia/blog/5941862.sHtMl

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.mc15zf.asia/blog/0542474.sHtMl

原标题：golang redis 缓存雪崩完整处理
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.mc15zf.asia/blog/2061948.sHtMl

原标题：TLS 版本兼容 HTTPS 握手失败
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.mc15zf.asia/blog/8228605.sHtMl

原标题：批量异步处理系统业务落地
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.mc15zf.asia/blog/0222175.sHtMl

原标题：零基础理解会话、Cookie、Session基础
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.mc15zf.asia/blog/4244460.sHtMl

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://book.mc15zf.asia/blog/6405285.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.mc15zf.asia/blog/2599889.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.mc15zf.asia/blog/2541785.sHtMl

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.mc15zf.asia/blog/4174975.sHtMl

原标题：安全复盘：Redis命令注入风险防护手段
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.mc15zf.asia/blog/5151288.sHtMl

原标题：golang redis 布隆过滤器安装使用
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.mc15zf.asia/blog/0321780.sHtMl

原标题：golang k8s 镜像拉取密钥配置
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.mc15zf.asia/blog/3889019.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.mc15zf.asia/blog/0129166.sHtMl

原标题：golang dockerfile 多阶段构建详解
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.mc15zf.asia/blog/3491184.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.mc15zf.asia/blog/2046847.sHtMl

原标题：短信服务封装失败自动重试
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.mc15zf.asia/blog/4433730.sHtMl

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.mc15zf.asia/blog/1449541.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.mc15zf.asia/blog/1756077.sHtMl

原标题：从零搭建简单的身份登录模拟示例
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://book.mc15zf.asia/blog/1981970.sHtMl

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.mc15zf.asia/blog/2321972.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.mc15zf.asia/blog/8362051.sHtMl

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.mc15zf.asia/blog/1321578.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.mc15zf.asia/blog/5318575.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.mc15zf.asia/blog/7834574.sHtMl

原标题：nodejs 事件循环机制完整讲解
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.mc15zf.asia/blog/3634725.sHtMl

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.mc15zf.asia/blog/2495183.sHtMl

原标题：golang redis 五种数据结构实战
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.mc15zf.asia/blog/2969397.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.mc15zf.asia/blog/3584773.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.mc15zf.asia/blog/5724428.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.mc15zf.asia/blog/3418559.sHtMl

原标题：golang 系统设计分表分页排序业务实现难点
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.mc15zf.asia/blog/9954856.sHtMl

原标题：golang grafana 面板变量模板制作
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.mc15zf.asia/blog/6815295.sHtMl

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://book.mc15zf.asia/blog/6131390.sHtMl

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.mc15zf.asia/blog/7764970.sHtMl

四、架构设计｜Architecture
原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.mc15zf.asia/blog/1812804.sHtMl

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.mc15zf.asia/blog/6613057.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.mc15zf.asia/blog/9095930.sHtMl

原标题：Security：Web常见安全漏洞原理与修复清单
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.mc15zf.asia/blog/6330464.sHtMl

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.mc15zf.asia/blog/3052339.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.mc15zf.asia/blog/2367261.sHtMl

原标题：定时任务周期调度 demo 开发
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.mc15zf.asia/blog/2309826.sHtMl

原标题：安全实践：防止重放攻击接口签名方案
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.mc15zf.asia/blog/1269852.sHtMl

原标题：golang 链路追踪简易实现方案
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.mc15zf.asia/blog/8607272.sHtMl

原标题：golang 优雅关闭 grpc 服务示例
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.mc15zf.asia/blog/5654952.sHtMl

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.mc15zf.asia/blog/5563706.sHtMl

原标题：集成测试业务流程编写示例
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.mc15zf.asia/blog/0136887.sHtMl

原标题：Practice：模拟网络抖动验证服务容错能力
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.mc15zf.asia/blog/2778538.sHtMl

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.mc15zf.asia/blog/5000530.sHtMl

原标题：golang kafka 消息丢失重复消费
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.mc15zf.asia/blog/4571982.sHtMl

原标题：内存广播本地进程消息通知
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.mc15zf.asia/blog/0596686.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.mc15zf.asia/blog/1198240.sHtMl

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.mc15zf.asia/blog/5962404.sHtMl

?
