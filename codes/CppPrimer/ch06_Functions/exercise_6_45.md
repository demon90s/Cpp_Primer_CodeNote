> 练习6.45：回顾在前面的练习中你编写的那些函数，它们应该是内联函数吗？如果是，将它们改写成内联函数；如果不是，说明原因。

---

可以使用正则表达式`grep 'return .*[<>=]' *`查询一些带有逻辑运算表达式的return语句，这些函数很可能很短。

举例而言，可以是内联函数的有：

- [练习6.21](./exercise_6_21.cpp)中的比较函数。

- [练习6.42](./exercise_6_42.cpp)中的make_plural函数。

而像下面这样的函数，由于内容比较多，不适合作为内联函数：

- [练习6.30](./exercise_6_30.cpp)中的str_subrange函数。

改写忽略。