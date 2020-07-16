试试正态分布
===========

## 知识点

使用numpy生成正态分布随机数(numpy.random.*)

* randn():标准正态分布随机数
* 图形化显示(matplotlib)

## 实战演习

### 图形化显示

~~~python
from numpy.random import *

# 标准正态分布(平均:0, 偏差:1)
print(randn())
# 生成5个元素的正态数组
print(randn(5))
# 生成5行5列的正态数组
print(randn(5,5))
~~~

### 图形化显示

~~~python
from numpy.random import *
import matplotlib.pyplot as plt

# 生成1万个标准正态分布数组
R = randn(10000)
# 图形化显示(直方图)
plt.hist(R, bins=100)
plt.show()
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
