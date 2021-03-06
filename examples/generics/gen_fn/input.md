同样的规则也可以适用于函数：在使用前给出 `<T>` 后，类型 `T` 就变成了泛型。

使用泛型函数有时需要显式地指明类型参量。这种可能的情况包括，调用返回类型是泛型的函数，或者编译器没有足够的信息来推导类型参量。

函数调用使用显式指定的类型参量，如下所示：
`fun::<A, B, ...>()`.

{fn.play}

### 参见：

[函数][fn] 和 [`struct`s][structs]

[fn]: ../fn.html
[structs]: ../custom_types/structs.html
