# nsq


## 特性

- 消息不持久(默认情况下):消息默认情况下不持久
- 消息至少传递一次:消息至少传递一次
- 消息是没有顺序的
- nsq节点相对独立，节点与节点之间没有复制或者集群的关系。
- 每个频道都会收到一个主题的所有消息的副本,相同的频道只会接收一份