# data模块

## 安装

把Chdata文件夹中的所有文件复制到之前那个放代码的文件夹里

## 用法

```python
from data import read

data = read()
```

```python
data.train.datas  # 训练集数据(1333,400)
data.train.labels  # 训练集标签(1333,2)
data.test.datas  # 测试集数据(3191,400)
data.next_batch(batches)  # 迭代
```

详见demo.py
