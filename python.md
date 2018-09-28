#### 9.26,9.27

### 总结
1. 一定要先记住python的框架，就像学c一样:
> 比如**c大概有：数据类型，表达式，选择，循环，数组，函数，指针，结构体，位运算，文件**这几个重点。

> 而**python大概有：列表，元组（索引，切片），字符串，字典，条件，循环，函数，类，异常，模块（标准库，类似c的预处理命令），文件等**这几个重点。

2. python基础教程的附录是个好东西:
> 比如附录A是python的一个**简明教程**，十分钟学会大部分语法，附录B里面有**表达式**，**重要的内置函数**，**列表，字典，字符串的一些常见方法（函数）**，**常见的语句（如import语句，if，while,for,函数类定义）**等，基本就是python的一些核心知识
3. 当在实际应用的时候发现哪个地方不懂，在去翻书看相应的章节。比如今天列表相关的知识不是很清楚，就翻书把列表这一章好好看看。

### 第十章 module
1. 模块是什么
2. 模块怎么用：help,官方文档等
3. 一些标准的库：rand,time,sys,os,集合，堆，双端队列

```python
# 创建一副牌并发牌,打乱发牌

values = list(range(1, 11)) + 'Jack Queen King'.split()
suits = 'diamonds clubs hearts spades'.split()
deck = ['{} of {}'.format(v, s) for v in values for s in suits]

from pprint import pprint
pprint(deck[:])

from random import shuffle
shuffle(deck)
pprint(deck[:])
while deck:
    input(deck.pop())
```
