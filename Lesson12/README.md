通用函数
========

## 知识点

numpy提供了简单的数组算术运算符

* +：np.add
* -：np.subtract
* *：np.multiply
* **：np.power
* /：np.divide
* %：np.mod

## 实战演习

~~~python
import numpy as np

a = np.arange(10)

print(a)
print(a+5)
print(a-5)
print(a*5)
print(a**2)
print(a/2)
print(-a)
print(a%2)

print(np.add(a, 5))
print(np.subtract(a, 5))
print(np.multiply(a, 5))
print(np.power(a, 2))
print(np.divide(a, 2))
print(np.negative(a))
print(np.mod(a, 2))
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
