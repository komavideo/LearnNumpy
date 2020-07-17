访问数组
========

## 知识点

* 访问numpy数组的方法

## 实战演习

~~~python
import numpy as np

# 1维数组
a = np.array([1,2,3,5,8,13,21])
print(a)
print(a[0])
print(a[1])
print(a[-1])
print(a[-2])
print(len(a))
a[0] = 100
print(a)
print(a.dtype) # 元素类型
print(a.itemsize) # 元素字节数
print(a.nbytes) # 数组整体占用字节数

# 2维数组
b = np.arange(24).reshape(4,6)
print(b)
print(b[0])
print(b[1])
print(len(b))
print(b[0,0])
print(b[0,2])
print(b[1,0])
print(b[1,2])
b[0,0] = 100
print(b)
print(b.dtype) # 元素类型
print(b.itemsize) # 元素字节数
print(b.nbytes) # 数组整体占用字节数
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
