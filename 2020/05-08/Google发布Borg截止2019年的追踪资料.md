Borg系统这样的规模以及应用，使其追踪资料极具研究价值，在8年前，Google发布了为期29天的Borg集群追踪纪录，包含了Borg运算集群中的所有作业提交、调度决定和资源使用情况资料，这份追踪资料被广泛地用在集群以及云端研究上，例如集群调度程序以及云端运算的技术发展上。

而现在技术的发展，已经与8年前不可同日而语，为了供研究人员探索这些变化，Google发布了新的2019年5月追踪资料，这次发布的资料集比2011年的还大，涵盖八个Google运算集群，包括：
每5分钟一次的CPU使用率直方图，而不像之前点样本

有关分配集的相关资料，包括作业用的预留共享资源等

Master和Worker关系信息。


这些追踪资料重点在于资源的请求和使用上，不会包含终端用户资料，或存储存系统和服务的模式。现在这些资料已经放在Google BigQuery上，让研究人员存取以及分析

参考：

- [https://mp.weixin.qq.com/s/nKLAPFnj3OgS-IPDXtuZTg](https://mp.weixin.qq.com/s/nKLAPFnj3OgS-IPDXtuZTg)
- [https://ai.googleblog.com/2020/04/yet-more-google-compute-cluster-trace.html](https://ai.googleblog.com/2020/04/yet-more-google-compute-cluster-trace.html)