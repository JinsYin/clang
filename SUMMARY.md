# SUMMARY

- [简介](README.md)
- [简史](brief-history.md)

---

- [compiler](compiler/README.md)

- [docs](docs/README.md)

- [汇编代码（Assembly Code）](docs/asm-code.md)
- [code]()
    - [K&R]()
        - [1]()
    - [custom]()
        - [test]()
- [编译](docs/compilation.md)
- [concepts](docs/concepts/README.md)

    - [class](docs/concepts/class/README.md)

    - [expression](docs/concepts/expression/README.md)

        - [operator](docs/concepts/expression/operator/README.md)

            - [算术运算符（Arithmetic Operator）](docs/concepts/expression/operator/arithmetic-opr.md)
            - [赋值运算符（Assignment Operators）](docs/concepts/expression/operator/assignment-opr.md)
            - [（按）位运算符（Bitwise Operator）](docs/concepts/expression/operator/bitwise-opr.md)
            - [自增（Self-increasing）/自减（Self-decreasing）运算符](docs/concepts/expression/operator/increament&decrement-opr.md)
            - [逻辑运算符（Logical Operators）](docs/concepts/expression/operator/logical-opr.md)
            - [其他运算符（Other operator）](docs/concepts/expression/operator/other.md)
            - [关系运算符（Relational Operators）](docs/concepts/expression/operator/relational-opr.md)
    - [flow-control](docs/concepts/flow-control/README.md)

        - [decision]()
            - [if · else if · else](docs/concepts/flow-control/decision/if.md)
            - [switch 语句](docs/concepts/flow-control/decision/switch.md)
        - [loops](docs/concepts/flow-control/loops/README.md)

            - [do...while 语句](docs/concepts/flow-control/loops/do-while.md)
            - [for 循环](docs/concepts/flow-control/loops/for.md)
            - [while 循环](docs/concepts/flow-control/loops/while.md)
    - [function](docs/concepts/function/README.md)

        - [匿名函数（Anonymous function）](docs/concepts/function/anonymous.md)
        - [函数调用（function call）](docs/concepts/function/call.md)
        - [函数声明（Function declaration）](docs/concepts/function/declaration.md)
        - [函数定义（Function definition）](docs/concepts/function/definition.md)
        - [内联函数（inline function）](docs/concepts/function/inline.md)
    - [keywords](docs/concepts/keywords/README.md)

        - [auto](docs/concepts/keywords/auto.md)
        - [#define](docs/concepts/keywords/define.md)
        - [#ifdef...#endif](docs/concepts/keywords/ifdef-endif.md)
        - [#ifndef ... #endif](docs/concepts/keywords/ifndef-endif.md)
        - [include](docs/concepts/keywords/include.md)
        - [C 关键字 · inline](docs/concepts/keywords/inline.md)
        - [register](docs/concepts/keywords/register.md)
        - [C 关键字 · static](docs/concepts/keywords/static.md)
        - [typedef](docs/concepts/keywords/typedef.md)
    - [lexical](docs/concepts/lexical/README.md)

        - [token](docs/concepts/lexical/token/README.md)

            - [constant](docs/concepts/lexical/token/constant/README.md)

                - [字符常量（Character Constant）](docs/concepts/lexical/token/constant/character-const.md)
                - [枚举常量（Enumeration Constant）](docs/concepts/lexical/token/constant/enumeration-const.md)
                - [浮点常量（Floating Constant）](docs/concepts/lexical/token/constant/floating-const.md)
                - [整型常量（Integer Constants）/整型字面量（Integer Literals）](docs/concepts/lexical/token/constant/integer-const.md)
            - [标识符（Indentifier）](docs/concepts/lexical/token/indetifier.md)
            - [关键字（Keyword）](docs/concepts/lexical/token/keyword.md)
            - [字符串字面量（String literal）/字符串常量（String Constant）](docs/concepts/lexical/token/string-literal.md)
        - [whitespace](docs/concepts/lexical/whitespace/README.md)

            - [注释（Comments）](docs/concepts/lexical/whitespace/comments.md)
    - [宏（Macro）](docs/concepts/macro.md)
    - [pointer](docs/concepts/pointer/README.md)

    - [process-control](docs/concepts/process-control/README.md)

    - [作用域（Scope）](docs/concepts/scope.md)
    - [语句（statement）](docs/concepts/statement.md)
    - [storageclass](docs/concepts/storageclass/README.md)

    - [type](docs/concepts/type/README.md)

        - [数组（Array）](docs/concepts/type/array.md)
        - [字符（char）](docs/concepts/type/char.md)
        - [枚举（Enumeration）](docs/concepts/type/enum.md)
        - [指针（Pointer）](docs/concepts/type/pointer.md)
        - [字符串（Character string）](docs/concepts/type/string.md)
        - [结构体（Structure）](docs/concepts/type/structure.md)
        - [Union](docs/concepts/type/union.md)
    - [variable](docs/concepts/variable/README.md)

- [derective](docs/derective/README.md)

    - [ifdef-else-endif](docs/derective/ifdef-else-endif.md)
    - [ifndef-end-endif](docs/derective/ifndef-else-endif.md)
- [垃圾回收](docs/gc.md)
- [预处理器（Preprocessor）](docs/preprocessor.md)
- [入门](docs/quickstart.md)
- [stdlib](docs/stdlib/README.md)

    - [assert.h](docs/stdlib/assert.h/README.md)

    - [ctype.h](docs/stdlib/ctype.h/README.md)

    - [errno.h](docs/stdlib/errno.h/README.md)

    - [float.h](docs/stdlib/float.h/README.md)

    - [limits.h](docs/stdlib/limits.h/README.md)

    - [locale.h](docs/stdlib/locale.h/README.md)

    - [math.h](docs/stdlib/math.h/README.md)

    - [setjmp.h](docs/stdlib/setjmp.h/README.md)

    - [signal.h](docs/stdlib/signal.h/README.md)

    - [stdarg.h](docs/stdlib/stdarg.h/README.md)

    - [stddef.h](docs/stdlib/stddef.h/README.md)

    - [stdio.h](docs/stdlib/stdio.h/README.md)

        - [getchar & putchar](docs/stdlib/stdio.h/getchar&putchar.md)
        - [库函数 printf](docs/stdlib/stdio.h/printf.md)
    - [stdlib.h](docs/stdlib/stdlib.h/README.md)

    - [string.h](docs/stdlib/string.h/README.md)

    - [time.h](docs/stdlib/time.h/README.md)

- [translation](docs/translation/README.md)

    - [preprocessor](docs/translation/preprocessor/README.md)

- [libc](libc/README.md)

- [POSIX](libc/C-POSIX.md)
- [bionic](libc/bionic/README.md)

- [glibc](libc/glibc/README.md)

    - [](libc/glibc/__attribute__.md)
- [msvc](libc/msvc/README.md)

- [<string.h>](libc/string.md)
- [posix-c](posix-c/README.md)

- [standard](standard/README.md)

- [style-guide](style-guide/README.md)

- [类（Classes）](style-guide/classes.md)
- [注释（Comments）](style-guide/comments.md)
- [格式化](style-guide/formatting.md)
- [头文件（Header Files）](style-guide/header-files.md)
- [命名（Naming）](style-guide/naming.md)
- [作用域（Scoping）](style-guide/scoping.md)
