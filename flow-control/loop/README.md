# 循环

## 循环控制语句

循环控制语句将改变执行程序的正常顺序。

| 循环控制语句 | 描述                                               |
| ------------ | -------------------------------------------------- |
| break        | 终止循环语句或 switch 语句（以及 if 语句、函数）   |
| continue     | 跳过当前循环体的剩余部分，强制执行循环的下一次迭代 |
| goto         | 转移控制到带标签的声明                             |

## break 语句

break 语句有两种用法：

* 当 break 语句在循环体时，循环立即终止，程序从循环后的下一个语句开始执行
* 在 switch 语句中终止 case

## continue 语句

continue 语句仅用于循环，不可以用于 switch 等语句。

## goto 语句

**goto** 语句提供了从 `goto` 到同一函数中带标签语句的无条件跳转。

任何编程语言中都建议不要使用 goto 语句，因为它很难跟踪程序的控制流程，使程序难以理解和修改。任何使用 goto 的程序都可以重写或者避免。

* 语法

```c
goto label;          // lable 可以是除关键字以外的任意标识符
...
...
label: statement;
```

**goto** 如果在循环体内会结束本次循环。
label 后的语句块会照常执行，遇到 goto 之后会再次执行一次

* 流程图

```graph
```

* 示例

```c
```

## 死循环（Infinite Loop）

如果循环条件一直不变成 false，循环将成为死循环或无限循环。可以使用 <kbd>Ctrl + C</kbd>（Unix-like 中代表 “Interrupt”）来结束死循环。

```c
for (;;) { // 缺省条件表达式时，C 语言将假定为 true
    ...
}
```

```c
while (1) {
    ...
}
```
