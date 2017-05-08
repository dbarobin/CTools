# CTools
Python常见工具集合！欢迎Star本项目，将不定期更新各种小工具；

1.NLP/T_S_transform_CN

简介：中文繁体与简体转换代码，极简调用；

使用方法：将 `TS_transform.py` 文件拷贝到工作目录即可；使用例子见`Example.py`文档；

特点：
* 支持包括，单行转换，列表转换以及文档转换；
* 支持多线程并行转换，经测试为单线程转换速度的4倍左右；
* 支持去除标点符号操作；

调用实例：
```python
from TS_transform import *
print T2S('天好藍要和你一起看，起風時由你来温暖。')
```
 