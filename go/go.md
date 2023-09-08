# fmt是什么包？

`在Go语言中，fmt是一个标准库（standard library）包，它提供了格式化输入和输出的功能。`

- fmt.Printf("Character: %c\n", char)
- 占位符%c

# go有哪些内置数据类型？

## 整数类型（Integer Types）:

- int：根据计算机架构，可以是32位或64位。
- int8、int16、int32、int64：分别表示8位、16位、32位和64位的有符号整数。
- uint：根据计算机架构，可以是32位或64位。
- uint8、uint16、uint32、uint64：分别表示8位、16位、32位和64位的无符号整数。
- uintptr：用于存储指针的整数类型。
`Go语言允许您显式指定整数类型的位数`
### 浮点数类型（Floating-Point Types）:

- float32：32位浮点数。
- float64：64位浮点数（默认的浮点数类型）。
### 复数类型（Complex Types）:

- complex64：由两个32位浮点数构成的复数。
- complex128：由两个64位浮点数构成的复数。
### 布尔类型（Boolean Type）:

- bool：表示布尔值，只有两个值，true或false。
### 字符串类型（String Type）:

- string：表示文本字符串。
### 字符类型（Character Type）:

- rune：表示一个Unicode字符。
### 错误类型（Error Type）:

- error：是一个接口类型，通常用于表示错误信息。
### 字节类型（Byte Type）:

- byte：是uint8的别名，通常用于表示二进制数据。
### 切片类型（Slice Types）:

- []T：表示元素类型为T的切片，用于处理动态长度的序列。
### 数组类型（Array Types）:

- [N]T：表示包含N个元素的数组，其中T是元素的类型。
### 结构体类型（Struct Types）:

- struct：用于定义自定义的复合数据类型，可以包含多个字段。
### 函数类型（Function Types）:

- func：用于定义函数类型，包括函数的参数和返回值类型。
### 通道类型（Channel Types）:

- chan T：表示通道，用于协程之间的通信。
### 映射类型（Map Types）:

- map[K]V：表示映射，用于存储键值对数据。
### 指针类型（Pointer Types）:

- *T：表示指向T类型的指针。
