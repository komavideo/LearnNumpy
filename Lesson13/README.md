数组绝对值
==========

## 知识点

numpy提供了取数组绝对值的函数

* abs
* absolute

## 实战演习

~~~python
import numpy as np

a = np.arange(10) - 5
print(a)

def f1():
    return abs(a)
def f2():
    return np.abs(a)

# Python函数
print(f1())

# numpy函数
print(f2())
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
