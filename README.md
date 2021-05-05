# Hadoop_The_Definitive_Guide_Notes

 - [第一章 - 初识Hadoop](./ch01.md)
 - [第二章 - 关于MapReduce](./ch02.md)

## Useful Links:

 - https://www.zhihu.com/question/23036370
 - https://blog.csdn.net/s5660gt/article/details/83270705
 - https://blog.csdn.net/s5660gt/article/details/83270705
 
## Some info about Hadoop

 - 解决了看之前的几个问题，这里特别提出来，如果你也在技术选型，可以参考一下：
0. 配置简单、扩展性强、容错性强、生态圈健全（搭配项目较多）、Apache顶级项目更新频繁有保障、等等优点；
1. Hadoop是为大文件（百MB~百TB）设计的；
2. 适合写入次数少但量大，读取次数多且量大（几乎全部数据集），所以是以高数据访问延迟换高数据吞吐量；
3. 海量小文件不合适；
4. 文件只能append，不支持多个写入者的操作；
5. 以大数据块换最小化寻址开销；
6. 不支持多数据中心（就是一定要在一个局域网中）；
7. 没必要再组RAID，硬件要求不高（但也要是商业级服务器）

