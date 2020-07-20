数组连接
========

## 知识点

使用numpy连接数组的方法

* concatenate
* vstack
* hstack

## 实战演习

~~~python
import numpy as np

# 1维数组
a = np.arange(5)
b = np.arange(10, 15)
print(a)
print(b)
# 数组连结
print(np.concatenate([a, b]))

c = np.arange(20, 25)
print(c)
print(np.concatenate([a, b, c]))

# 2维数组
a1 = np.array([
    [1,2,3],
    [7,8,9]
])
a2 = np.array([
    [10,20,30],
    [70,80,90]
])
print(a1)
print(a2)
print(np.concatenate([a1, a2])) # 竖向拼接
print(np.concatenate([a1, a2], axis=1)) # 横向拼接

# vstack
print(np.vstack([a1, a2]))
# hstack
print(np.hstack([a1, a2]))
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
