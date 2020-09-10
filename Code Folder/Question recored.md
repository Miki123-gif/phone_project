# Trajectory tracking

## Q1

设置阈值的时候，要让阈值大于某个值才出现。怎么实现？

```
# 直接使用loc[data.imsi_.value_counts()>treshold] ？
# 这样会失败，因为这样的布尔运算。得到的index是imsi。和原始的index是range(100)这样的升序标签
```

解决方式1:

可以使用map函数，map专门针对。可以一一对应。获得每个id的频率

```
data1['Frequency'] = data1.imsi_.map(data1.imsi_.value_counts())
```