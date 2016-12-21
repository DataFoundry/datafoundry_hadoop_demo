#hdfs bsi demo

首先先创建一个hdfs的bsi，名字一定要叫hdfsdemo（小写）

pod起来以后oc rsh进去容器运行程序

程序现在支持三个参数

```
./hadoop_demo -ls /     是查看自己目录下面的文件

./hadoop_demo -mkdir  name   在自己的目录下创建目录

./hadoop_demo -load s3url  在数据集成里面的下载地址复制到该出可以把s3上的文件上传到hdfs上
```
如果程序执行的时候没有cookie，执行一下./start.sh文件初始化一下用户

