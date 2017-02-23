### C & C++

- Thrift:用来进行可扩展且跨语言的服务的开发(类似的还有个Avro，Google protobuf)。
- libevent:是一个事件触发的网络库，适用于windows、linux、bsd等多种平台，内部使用select、epoll、kqueue等系统调用管理事件机制。（对了还有个libev呢）
- Boost:不多说了，准C++标准库
- Valgrind\Ptmalloc\Purify: 调试工具
- NetworkServer架构：acceptor->dispatcher->worker(这个不算工具哦)
- [POCO](https://pocoproject.org/) - 开源的C++类库及应用程序框架的集合,它主要提供简单的、快速的网络和可移植应用程序
- breakpad:崩溃转储和分析模块，很多crashreport会用到
- UI界面相关：MFC、BCG和QT这类的就不说了，高端一点的还有Html和DirectUI技术：libcef（基于chrome内核的，想想使用html5开发页面，还真有点小激动呢）、HtmlLayout、Duilib、Bolt，非C++的，还有node-webkit也不错，集成了node和webkit内核。
