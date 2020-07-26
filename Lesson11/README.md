计时模块
========

## 知识点

使用timeit估算代码执行时间

* timeit

### API文档

https://docs.python.org/zh-cn/3.8/library/timeit.html

## 实战演习

### main.py

~~~python
import numpy as np
import timeit

a = np.random.rand(1000)

def f1():
    b = np.empty(len(a))
    for i in range(len(a)):
        b[i] = 1 / a[i]
    return b

def f2():
    b = 1 / a
    return b

print(timeit.timeit(stmt=f1, number=1000))
print(timeit.timeit(stmt=f2, number=1000))
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
