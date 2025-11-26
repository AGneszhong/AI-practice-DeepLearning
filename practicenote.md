### 1.实例化两个标量

标量由只有一个元素的张量表示。 下面的代码将实例化两个标量
```python
import torch

x = torch.tensor(3.0)
y = torch.tensor(2.0)

print(x + y, x * y, x / y, x ** y)
```
#### 代码解释
代码解释：
导入PyTorch库。
创建两个张量（tensor）x和y，分别赋值为3.0和2.0。
打印x+y, x*y, x/y, x**y的结果。

详细解释torch.tensor：
在PyTorch中，tensor是一个多维数组，类似于NumPy的ndarray，但tensor可以在GPU上使用以加速计算。torch.tensor是PyTorch中用于存储和变换数据的主要工具。
torch.tensor()函数用于创建张量。它可以接受各种数据类型，如列表、元组、NumPy数组等，并可以指定张量的数据类型（dtype）和设备（device，如CPU或GPU）。
在上面的代码中，我们使用torch.tensor(3.0)和torch.tensor(2.0)创建了两个标量（0维张量）。然后对这两个标量进行了加法、乘法、除法和幂运算。

#### 输出结果
```
tensor(5.) tensor(6.) tensor(1.5000) tensor(9.)
```


