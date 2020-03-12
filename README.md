# C 语言知识库

[![website][website-image]][website-href]

[website-image]: https://img.shields.io/website-up-down-green-red/https/githome.io/clang/.svg
[website-href]: https://githome.io/clang/

C 语言是一种相对 “低级” 的语言（没有贬义），意味着它可以处理大部分计算机能够处理的对象，比如字符、数字和地址。这些对象可以通过具体机器实现的算术运算符和逻辑运算符组合在一起并移动。

C 语言不提供直接处理诸如字符串、集合、列表或数组等复合对象的操作。虽然可以将整个结构作为一个单元进行拷贝，但 C 语言没有处理着整个数组或字符串的操作。除了由函数的局部变量提供的静态定义和堆栈外，C 语言没有定义任何存储器分配工具，也不提供堆和无用内存回收工具。最后，C 语言本身没有提供输入输出功能，没有 READ 或 WRITE 语句，也没有内置的文件访问方法。所有这些高层的机制必须由显示调用的函数提供。C 语言的大部分实现已合理地包含了这些函数的标准集合。

类似地，C 语言只提供了简单的单线程控制流，即测试、循环、分组和子程序，它不提供多道程序设计、并行操作、同步和协同例程。

## 翻译过程

1. 预处理（preprocessing）
2. 编译（compilation）
3. 汇编（assembly）
4. 链接（linking）

## LICENSE

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](LICENSE)

## 参考

* [ANSI C](https://en.wikipedia.org/wiki/ANSI_C)
