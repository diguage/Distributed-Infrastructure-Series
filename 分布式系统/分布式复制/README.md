# 分布式复制

复制几乎是构成分布式系统，尤其是分布式存储和分布式数据库的关键所在。简单说复制本身可以分为同步复制和异步复制，两者的区别在于前者需要等待所有副本返回写入确认，而后者只需要一个返回确认即可。从用途上，复制可以分为两类，一类用于确保不同副本的表现行为一致（避免 divergence），另一类则用于允许不同副本之间的数据差异（divergence 不可避免，如 Dynomo），先来看看前者。

简单说复制本身可以分为同步复制和异步复制，两者的区别在于前者需要等待所有副本返回写入确认，而后者只需要一个返回确认即可。从用途上，复制可以分为两类，一类用于确保不同副本的表现行为一致（避免 divergence），另一类则用于允许不同副本之间的数据差异（divergence 不可避免，如 Dynomo），先来看看前者。

# 链接

- https://blog.csdn.net/jiafu1115/article/details/53908715
