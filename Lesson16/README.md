对数函数
========

## 知识点

numpy提供了计算对数的函数

* log: 自然对数
* log2: 2的对数
* log10: 10的对数

## 举个栗子

```python
2^3=8
↓
log2(8)=3
```

## 实战演习

~~~python
import numpy as np

n = [1, 2, 3, 4, 5]

# e^0=1
val = np.log(1)
print(val)

val = np.log(n)
print(val)

# 2^4=16
val = np.log2(16)
print(val)

n = [1, 2, 4, 8, 32, 128]
val = np.log2(n)
print(val)

# 10^2=100
val = np.log10(100)
print(val)

n = [1, 10, 100, 1000, 10000]
val = np.log10(n)
print(val)
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
