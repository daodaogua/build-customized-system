## 已有window系统的情况下，安装linux系统。
[参考资料](https://blog.csdn.net/flyyufenfei/article/details/79187656)

### 准备材料
* 启动U盘([制作方法](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows#0))

### 安装步骤

* #### [磁盘分区](http://jingyan.baidu.com/article/425e69e6bbd0c7be14fc164a.html)
压缩出一个新的分区就行，可以不需要后面新建分区的内容。

* #### 从U盘启动[从BIOS设置U盘启动](http://www.udashi.com/jc/2.html)

* #### 为系统分区(需要选择自定义**！！！**)

**/boot**:  实际需求大约 100 ~ 200MB，如果有多个内核/启动镜像同时存在，建议分配 200 或者 300 MB。(个人建议:200MB ~ 300MB)，**300MB**<br>
**/**: 15-20 GB 对于大多数用户来说是一个比较合适的取值。(个人建议：15G短时间用不完，长期使用的话，建议20GB~25GB)，**35GB**<br>
**/home**: [不定] 通常用于存放用户数据，下载的文件和媒体文件。在桌面系统中，/home 通常是最大的文件系统。(个人建议: 多多益善)，''<br>
**swap**: [不定] 在拥有不足 512 MB 内存的机器上，通常为 swap 分区分配2倍内存大小的空间。如果有更大的内存（大于 1024 MB），可以分配较少的空间甚至不需要swap 分区。(个人建议：感觉现在电脑的配置可以不要swap，但是也会用的着的，所以还是建议多少分点)，**5GB**<br>

## coming soon
