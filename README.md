Mycat IPC
---
Mycat java进程间通信服务


####使用方式
	1. 启动 io.mycat.ipc.Reader
	2. 启动 io.mycat.ipc.Writer

    可以在进程间传输数据
####限制
	1. 消费方速度要高于生产者
	2. JDK 要求 SunJDK 1.8
	