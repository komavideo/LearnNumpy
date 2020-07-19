切片数组
========

## 知识点

* 使用切片访问数组

## 实战演习

~~~python
import numpy as np

# 1维数组
a = np.arange(12)
print(a)
print(a[:5])
print(a[5:])
print(a[4:7])
print(a[::2])
print(a[1::2])
print(a[::-1])
print(a[::-2])

# 2维数组
b = np.arange(24).reshape(4,6)
print(b)
print(b[:2])
print(b[:2, :3])
print(b[:2,::2])
print(b[:2,::-1])
print(b[::-1,::-1])
print(b[:, 0])
print(b[0, :])
print(b[0, ::-1])
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
