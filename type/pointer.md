# 指针（Pointer）

指针提供了与具体机器无关的地址算术运算。

指针可以执行函数吗？

## 指针类型

* `T * variable`
* `T* variable`
* `T *variable`

## 运算符

$$
pointer = \&(*pointer)
$$

| 运算符 | 描述                                           | 示例                           |
| ------ | ---------------------------------------------- | ------------------------------ |
| `&`    | 获取数据的内存地址                             | `&arr[1]` 获取 `arr[1]` 的地址 |
| `*`    | 对内存地址进行取反，即获取该内存地址存储的数据 | `*arr` 获取 `arr[0]` 的值      |
