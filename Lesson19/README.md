通用函数
========

## 知识点

numpy提供了多个数组通用函数

* sum:求和
* max:最大值
* argmax:最大值索引
* any:任意满足条件判断
* all:全部满足条件判断

## 实战演习

~~~python
import numpy as np

X = np.array([1,2,3,5,8,13,21])

print(np.sum(X))
print(np.max(X))
print(np.argmax(X))

print(X<10)
print(np.any(X<10))
print(np.all(X<10))
~~~

### 其他函数

**sum, prod, mean, std, var, min, max, argmin, argmax, median, percentile, any, all**

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
