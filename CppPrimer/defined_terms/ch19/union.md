联合（union）是一种和类有些相似的类型。可以包含多个数据成员，但是同一时刻只能一个成员有值。联合可以有包括构造函数和析构函数在内的成员函数。联合不能被用作基类。在C++11新标准中，联合可以含有类类型成员，前提是这些成员自定义了拷贝控制成员。对于这样的联合来说，如果它们没有定义自己的拷贝控制成员，则编译器为它们生成删除的版本。