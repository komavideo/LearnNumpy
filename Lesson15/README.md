指数函数
========

## 知识点

numpy提供了计算指数的函数

* exp: e的指数 -> e^n
* exp2: 2的指数 -> 2^n
* power: 任意数指数 -> m^n

## 实战演习

~~~python
import numpy as np

n = [1, 2, 3, 4, 5]

val = np.e
print(val)

val = np.exp(1)
print(val)

val = np.exp(n)
print(val)

val = np.exp2(1)
print(val)

val = np.exp2(n)
print(val)

val = np.power(3, 4)
print(val)

val = np.power(3, n)
print(val)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
