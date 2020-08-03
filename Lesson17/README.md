函数输出out
===========

## 知识点

ufunc通用函数的输出指定

* out: 关键字，指定输出变量

## 实战演习

~~~python
import numpy as np

a = np.arange(5)
b = np.empty(5)

np.multiply(a, 10, out=b)
print(b)

np.power(2, a, out=b)
print(b)

b = np.zeros(10)
np.add(a, 100, out=b[::2])
print(np.add(a, 100))
print(b)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
