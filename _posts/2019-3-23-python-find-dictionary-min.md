---
layout: post
title: 查找python的dictionary中的最小值
---
    
## 题目    
如何找到python的字典，比如`d={320:1, 321:0, 322:3}`中value部分的最小值，并返回key？

可以使用这个方法：
```
min(d, key=d.get) 
```

## 解释
python的built-in函数`min`的用法，请参考这个链接 [python中min函数用法](https://www.programiz.com/python-programming/methods/built-in/min)

在本用法中，函数`min`接收了2个参数，第一个参数是dictionary，第二个参数是一个iterator。如果没有第二个参数，`min`函数将会对字典给的key进行搜索，返回最小的key值。第二个参数`key`是一个方法，用于对第一个参数中的元素进行处理，`min`函数对这个返回值进行检索，得到最小值。


## 参考
[原始题目链接](https://stackoverflow.com/questions/3282823/get-the-key-corresponding-to-the-minimum-value-within-a-dictionary)

