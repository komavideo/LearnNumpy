创建数组
========

## 知识点

* 用NumPy创建数组

## 实战演习

~~~python
# NumPy数组(ndarray)
import numpy as np

# 整数数组
myarray = [1, 2, 3, 5, 8, 13]
nparray = np.array(myarray)
print(nparray)
print(nparray.dtype)

# 浮点数数组
myarray = [1.1, 2.1, 3.1, 5.1, 8.1, 13.1, 20.]
nparray = np.array(myarray)
print(nparray)
print(nparray.dtype)

# 多维数组
myarray = [
    [1, 2, 3],
    [10,20,30]
]
nparray = np.array(myarray)
print(nparray)
print(nparray.shape)

# 全0数组
nparray = np.zeros((5))
print(nparray)
nparray = np.zeros((4, 6))
print(nparray)

# 全1数组
nparray = np.ones((5))
print(nparray)
nparray = np.ones((4, 6))
print(nparray)

# 指定数值数组
nparray = np.full((3,5), 3.14)
print(nparray)

# 生成顺序数组
nparray = np.arange(10)
print(nparray)
nparray = np.arange(5, 10)
print(nparray)
nparray = np.arange(1, 10, 2)
print(nparray)
nparray = np.arange(0, 10, 2)
print(nparray)

# 线段分数组
nparray = np.linspace(0, 24, 5)
print(nparray)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
