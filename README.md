# sparkstreamin-kafka-8
sparkstreamin与kafka0.8集成

    在企业里面Spark我们一般分为两种版本：

    那，这两个版本，我们是不是只需要学最新的那个版本就可以了？

不是，两个版本都要掌握，因为现在企业里面很多公司还在使用着0.8的版本，或者说一个公司里面有多个kafka集群，老一点的集群
用的是0.8的版本，只是后来新的集群上了新的版本。所以两个版本大家都要掌握。比如我们公司里面就有多个kafka集群。其中有一个大的
kafka集群就是0.8版本的，其余的就是后来上的，所以是1.0版本的。

1.1 基于receiver的方式（了解就可以了，性能不好）
    这种了解一下就可以了。因为性能不好，所以企业里面不使用。
1.2 direct方式（就是要掌握的）
    程序里面是没有receiver，是我们的程序自己去读取kafka分区里面的数据。
