


## Broker


* longpolling 长轮询服务端的实现
*

zero copy

IO调度算法:deadline


mmap的原理,MappedByteBuffer

Linux PageCache 机制


RocketMQ目前不支持Slave自动提升为Master,需要手动搞.Kafka可以的.

Q:如何实现对Broker的扩容,不影响原有的顺序消费?

## Consumer

PushConsumer 内部有个线程池，同时在多个线程中执行消息处理逻辑。



PullConsumer

Offset


## TODO

Netty

