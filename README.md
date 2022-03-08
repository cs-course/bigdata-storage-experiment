# 大数据存储系统与管理实验

2022春季 @ 华中科技大学

## 文件说明

- [课程背景知识](bigdata-storage-experiment.pptx)
- [实验报告模板](report-template.doc)
- [实验内容说明](https://github.com/cs-course/obs-tutorial)

## 课程涉及的工具环境

### 关于系统环境

- [计算机教育中缺失的一课](https://missing-semester-cn.github.io/)
  - 建议熟悉一下"1/13: 课程概览与 shell"、"1/14: Shell 工具和脚本"与"1/22: 版本控制(Git)"这三部分

### 对象存储系统

- [Minio](https://minio.io/)
- [Ceph](https://ceph.com/)
- [OpenStack Swift](http://www.openstack.org/software/releases/ocata/components/swift)

### 对象存储系统评测工具

- [s3bench](https://github.com/igneous-systems/s3bench), [benchio](https://github.com/giacomoguiulfo/benchio), [s3-benchmark](https://github.com/chinglinwen/s3-benchmark) (Go语言)
- [s3-bench-rs](https://github.com/SKTT1Ryze/s3-bench-rs) (Rust语言，感谢 [@SKTT1Ryze](https://github.com/SKTT1Ryze) 同学提供，欢迎更多同学参与！)
- [COSBench](https://github.com/intel-cloud/cosbench) (Java语言)

### 对象存储系统应用范例

- 个人云 [Nextcloud](https://github.com/nextcloud), [Seafile](https://www.seafile.com/home/), [zfile](https://github.com/zhaojun1998/zfile)
- 图片管理 [Thumbor](http://thumbor.org/), [picfit](https://github.com/thoas/picfit)
- 欢迎感兴趣的同学自行探索...

## 课程涉及的研究背景

### 尾延迟为什么很重要？

- Dean J, Barroso L A. Association for Computing Machinery, 2013. The Tail at Scale[J]. Commun. ACM, 2013, 56(2): 74–80.

### 可以用什么方法来分析？

- Delimitrou C, Kozyrakis C. Association for Computing Machinery, 2018. Amdahl’s Law for Tail Latency[J]. Commun. ACM, 2018, 61(8): 65–72.

### 我们的一些初步探讨

Su Y, Feng D, Hua Y, Shi Z. Understanding the latency distribution of cloud object storage systems[J]. Journal of Parallel and Distributed Computing, 2019, 128: 71–83.
