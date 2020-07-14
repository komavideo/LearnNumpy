数组计算
========

## 知识点

* 数组的基础计算

## 实战演习

~~~python
import numpy as np

# 数组计算
a1 = np.array([10,20,30,40,50])
print(a1)
print(a1.sum())
print(a1.min())
print(a1.max())

a2 = np.arange(5)
print(a2)

a3 = a1 + a2
print(a3)

a4 = a1 - a2
print(a4)
print(a4 < 30)

a5 = a1 * a2
print(a5)

# 多维数组计算
b = np.arange(12).reshape(3,4)
print(b)
print(b.shape)

print(b.sum(axis=0)) # 垂直列计算
print(b.sum(axis=1)) # 水平行计算

print(b.min(axis=0)) # 垂直列最小值
print(b.min(axis=1)) # 水平行最小值

print(b.max(axis=0)) # 垂直列最大值
print(b.max(axis=1)) # 水平行最大值

# *矩阵相乘*
X = np.array([
    [1,1,0],
    [0,1,1]
])
W = np.array([
    [2,0],
    [3,4],
    [1,2]
])
Y = np.dot(X, W)
print(Y)

# 另一种写法
Y = X @ W
print(Y)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
