NumPy基础
=========

## 知识点

* NumPy数组的基础

### Python数组(array)

* 1维数组
* 多维数组

#### 1维数组

~~~python
myarray = [1,2,3,5,8,13]
~~~

#### 多维数组

~~~python
# 2维数组
myarray = [
    [1, 2, 3],
    [10,20,30]
]
# 3维数组
myarray = [
    [[1, 2, 3],[4, 5, 6]],
    [[10,20,30],[40,50,60]]
]
~~~

### NumPy的数组(ndarray)

与Python数组对象(array)不同, NumPy数组提供了更多的维数和功能, 类型为：ndarray, 拥有更多的属性。

* ndarray.ndim: 数组维数
* ndarray.shape: 数组维数(元组tuple类型:行列形式)
* ndarray.size: 数组元素个数
* ndarray.dtype: 数组元素类型
* ndarray.itemsize: 数组单个元素占用内存字节

~~~python
# NumPy数组(ndarray)
import numpy as np
myarray = [1,2,3,5,8,13]
nparray = np.array(myarray).reshape(2,3)
print(nparray)
print('数组维数:', nparray.ndim)
print('数组维数(元组tuple类型:行列形式)', nparray.shape)
print('数组元素个数', nparray.size)
print('数组元素类型', nparray.dtype)
print('数组单个元素占用内存字节', nparray.itemsize)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
