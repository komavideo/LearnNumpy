美国总统比身高
============

## 知识点

利用统计系列函数算出历届美国总统的身高数据

* mean
* max
* min
* percentile
* median

### 其他库

* pandas:读取csv文件
* matplotlib:绘制棒状图

## 实战演习

~~~python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

data = pd.read_csv('./president_heights.csv')

heights = np.array(data['height(cm)'])
print(heights)
print(heights.mean())
print(heights.min())
print(heights.max())
print(heights.std())

print(np.percentile(heights, 25)) # 25%分位值
print(np.percentile(heights, 50)) # 50%分位值
print(np.median(heights))         # 中位数
print(np.percentile(heights, 75)) # 75%分位值

plt.hist(heights)
plt.title("Height of US Presidents")
plt.xlabel("height(cm)")
plt.ylabel("number")
plt.show()
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
