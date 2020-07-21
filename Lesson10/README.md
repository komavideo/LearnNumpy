数组分割
========

## 知识点

使用numpy分割数组

* split
* vsplit
* hsplit

## 实战演习

~~~python
import numpy as np

# 1维数组
a = np.arange(8)
print(a)
print(np.split(a, [3]))
print(np.split(a, [3, 6]))

# 2维数组
b = np.arange(16).reshape(4,4)
print(b)
# 垂直方向，横向出刀
upper, lower = np.vsplit(b, [2])
print(upper)
print(lower)
# 水平方向，竖向出刀
left, right = np.hsplit(b, [2])
print(left)
print(right)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
