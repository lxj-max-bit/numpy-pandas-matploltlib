一.ndarray
1.ndarray的特性
多维性


```python
import numpy as np
```


```python
arr = np.array(5)#创建一个0维的ndarray数组

print(arr)

print('arr的维度：',arr.ndim) #number of dimensions
```

    5
    arr的维度： 0
    


```python
arr = np.array([1 , 2 , 3])#创建一个1维的ndarray数组

print(arr)

print('arr的维度：',arr.ndim) #number of dimensions
```

    [1 2 3]
    arr的维度： 1
    


```python
arr = np.array([1 , 2 , 3])#创建一个1维的ndarray数组

print(arr)

print('arr的维度：',arr.ndim) #number of dimensions
```

    [1 2 3]
    arr的维度： 1
    


```python
arr = np.array([[1 , 2 , 3] ,[4 , 5 , 6 ] ])#创建一个2维的ndarray数组

print(arr)

print('arr的维度：',arr.ndim) #number of dimensions
```

    [[1 2 3]
     [4 5 6]]
    arr的维度： 2
    

同质性


```python
arr = np.array([1 , 'hello'] )#不同的数据类型会被强制转化成相同的数据类型
print(arr)
```

    ['1' 'hello']
    


```python
arr = np.array([1 , 2.5])
print(arr)
```

    [1.  2.5]
    

2.ndarray 的属性



```python
arr = np.array(5)
print(arr)
print('元素的形状',arr.shape)
print('元素的维度',arr.ndim)
print('元素的个数',arr.size)
print('元素的数据类型',arr.dtype)
print('元素的转置',arr.T)
```

    5
    元素的形状 ()
    元素的维度 0
    元素的个数 1
    元素的数据类型 int64
    元素的转置 5
    


```python
arr = np.array([1,2,3])
print(arr)
print('元素的形状',arr.shape)
print('元素的维度',arr.ndim)
print('元素的个数',arr.size)
print('元素的数据类型',arr.dtype)
print('元素的转置',arr.T)
```

    [1 2 3]
    元素的形状 (3,)
    元素的维度 1
    元素的个数 3
    元素的数据类型 int64
    元素的转置 [1 2 3]
    


```python
arr = np.array([[1,2,3],[4,5,6]])
print(arr)
print('元素的形状',arr.shape)
print('元素的维度',arr.ndim)
print('元素的个数',arr.size)
print('元素的数据类型',arr.dtype)
print('元素的转置',arr.T)
```

    [[1 2 3]
     [4 5 6]]
    元素的形状 (2, 3)
    元素的维度 2
    元素的个数 6
    元素的数据类型 int64
    元素的转置 [[1 4]
     [2 5]
     [3 6]]
    


```python

```
