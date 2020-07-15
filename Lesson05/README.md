随机数生成
==========

## 知识点

使用numpy生成随机数(numpy.random.*)

* rand
* randint
* choice

## 实战演习

~~~python
from numpy.random import *

# 生成1个0-1的随机数
print(rand())
# 生成5个0-1的随机数数组
print(rand(5))
# 生成3行2列的0-1的随机数数组
print(rand(3,2))

# 生成1个0-99的随机数
print(randint(100))
# 生成1个10-19的随机数
print(randint(10,20))
# 生成5个10-19的随机数数组
print(randint(10,20,5))
# 生成2行3列的10-19的随机数数组
print(randint(10,20,(2,3)))

# 随机选择数组元素
players = ["curry", "harden", "lebron", "durant", "antetokounmpo", "westbrook", "McGee"]
# 随机抽出一个球员
print(choice(players))
# 随机抽出3个球员(有重复)
print(choice(players, 3))
# 随机抽出3个球员(无重复)
print(choice(players, 3, replace=False))
~~~

## 课程文件

https://github.com/komavideo/LearnNumpy

## 小马视频频道

http://komavideo.com
