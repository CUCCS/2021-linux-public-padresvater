## 实验四
[toc]

### shell脚本仓库地址

https://github.com/padresvater/shell-examples

### 实验要求

* 任务一：用bash编写一个图片批处理脚本，实现以下功能：
    * [x] 支持命令行参数方式使用不同功能
    * [x] 支持对指定目录下所有支持格式的图片文件进行批处理
    * [x] 支持以下常见图片批处理功能的单独使用或组合使用
        * [x] 支持对jpeg格式图片进行图片质量压缩
        * [x] 支持对jpeg/png/svg格式图片在保持原始宽高比的前提下压缩分辨率
        * [x] 支持对图片批量添加自定义文本水印
        * [x] 支持批量重命名（统一添加文件名前缀或后缀，不影响原始文件扩展名）
        * [x] 支持将png/svg图片统一转换为jpg格式图片

---

* 任务二：用bash编写一个文本批处理脚本，对以下附件分别进行批量处理完成相应的数据统计任务：
    * [2014世界杯运动员数据](exp/chap0x04/worldcupplayerinfo.tsv)
        * [x] 统计不同年龄区间范围（20岁以下、[20-30]、30岁以上）的球员**数量**、**百分比**
        * [x] 统计不同场上位置的球员**数量**、**百分比**
        * [x] 名字最长的球员是谁？名字最短的球员是谁？
        * [x] 年龄最大的球员是谁？年龄最小的球员是谁？

---

* 任务三：用bash编写一个文本批处理脚本，对以下附件分别进行批量处理完成相应的数据统计任务：
    * [Web服务器访问日志](exp/chap0x04/web_log.tsv.7z)
        * [x] 统计访问来源主机TOP 100和分别对应出现的总次数
        * [x] 统计访问来源主机TOP 100 IP和分别对应出现的总次数
        * [x] 统计最频繁被访问的URL TOP 100
        * [x] 统计不同响应状态码的出现次数和对应百分比
        * [x] 分别统计不同4XX状态码对应的TOP 10 URL和对应出现的总次数
        * [x] 给定URL输出TOP 100访问来源主机

---

### 实验报告要求

* 继承[第一章：Linux基础（实验）](chap0x01.exp.md.html)的所有实验报告要求
* 上述任务的所有源代码文件必须单独提交并提供详细的**--help**脚本内置帮助信息
* 任务二的所有统计数据结果要求写入独立实验报告

***

### 实验环境

- Ubuntu20.04 LTS,与宿主机的文件传输依靠共享文件夹
- Virtualbox  6.1.18 r142142 (Qt5.6.2)
- vscode remote ssh

***

### 参考资料

- https://hejueyun.github.io/posts/48ec4ca9/
- [imagemagick文档](https://legacy.imagemagick.org/Usage/basics/)
- [shell脚本之输入输出重定向](http://c.biancheng.net/view/942.html)
- [shell脚本之shift和getopts](http://www.361way.com/shell-shift-getopts/4973.html)
- [Zhang1933](https://github.com/CUCCS/2021-linux-public-Zhang1933/blob/ch0x04/ch0x04/%E5%AE%9E%E9%AA%8C%E6%8A%A5%E5%91%8A.md)
- [shell中#*,##*,#*,##*,% *,%% *的含义及用法](https://blog.csdn.net/jiezi2016/article/details/79649382)
- [wget命令](https://www.cnblogs.com/peida/archive/2013/03/18/2965369.html)
- [linux awk命令](https://www.runoob.com/linux/linux-comm-awk.html)

  

master
