积累函数(reduce)
================

## 知识点

* reduce: 数组积累函数
* accumulate: 数组积累函数(保留中间结果)

## 实战演习

~~~python
import numpy as np

a = np.arange(1, 6)
print(a)

b = np.add.reduce(a)
print(b)

c = np.multiply.reduce(a)
print(c)

b = np.add.accumulate(a)
print(b)

c = np.multiply.accumulate(a)
print(c)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
