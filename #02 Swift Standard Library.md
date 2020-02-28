## 数组（Array)

- 特点： 有序，zero-base index

- 遵从 **`Sequence & Collection & RandomAccessCollection`** 协议

- **获取数组尺寸 `count`**: **O(1)** 常量时间

- 随机访问（**Random-access**）是数据结构可以在常数 **O(1)** 时间内处理元素检索的特性，能够确保性能。链表和树访问元素的时间不固定

- 获取元素时间：**`O(1)`**

- 查询元素时间：**`O(n)`**

- 插入：依据插入的位置不同，消耗的时间不同。理解方式：插入第n位置（从后往前算），n位置后面的元素需要在内存中向后挪动，给插入的元素腾出位置

  - 插入数组最尾部最快，为 **`O(1)`**
  - 插入数组头最慢，为 **`O(n)`**


## 字典（Dictionary）

- 特点： 无序，key-value形式，key必须服从 **`Hashable`** 协议(swift大部分类型都服从Hashable类型，自定义实现也比较简单)

- 查询元素时间： **`O(1)`**


来源：

- Data Structures and Aligorithms in Swift - Chapter02 Swift Standard Library