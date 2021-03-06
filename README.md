# Daily Schedule for Open-Source OS Training

## Day 1 2022/7/1

主要参考资料：[Rust语言圣经](https://course.rs/about-book.html)

- 了解Rust 发展历程
- 安装Rust环境（VSCode + rust-analyzer）
- 认识Cargo
- Hello world | "世界，你好"


## Day 2 2022/7/2

- 修改Rust的下载镜像地址
- 变量绑定与解构


## Day 3 2022/7/3

- 基本类型
    - 类型推导与标注
- setup-env-run-os1


## Day 4 2022/7/4

- 基本类型
    - 整数类型
    - 浮点类型
    - 数字运算
    - 位运算
    - 序列(Range)
    - 有理数和复数

## Day 5 2022/7/5

- 开源操作系统学习训练营开幕式
- 基本类型
    - 字符、布尔、单元类型
    - 语句与表达式
    - 函数

## Day 6 2022/7/8
- 所有权和借用
    - 所有权
        - 栈(Stack)与堆(Heap)
        - 所有权原则
        - 变量绑定背后的数据交互
        - Copy 特征  
        - 函数传值与返回值的所有权 
    - 引用与借用
        - 引用与解引用

## Day 7 2022/7/9
- 所有权和借用
    - 所有权
        - 栈(Stack)与堆(Heap)
        - 所有权原则
        - 变量绑定背后的数据交互
        - Copy 特征  
        - 函数传值与返回值的所有权 
    - 引用与借用
        - 引用与解引用
        - 不可变引用
        - 可变引用
        - 可变引用与不可变引用不能同时存在
        - Non-Lexical Lifetimes(NLL)
        - 悬垂引用(Dangling References)
        - 借用规则总结
- 复合类型
    - 字符串
        - 字符串字面量是切片
    - 切片(slice)

## Day 8 2022/7/10
- 字符串
    - String 与 &str 的转换
    - 操作字符串
        - 追加
            - put()
            - put_str()
        - 插入
            - insert()
            - insert_str()
        - 替换
            - replace()
            - replacen()
            - replace_range()
        - 删除
            - pop()
            - remove()
            - truncate()
            - clear()
        - 连接
            - + 或 += 连接字符串
            - format! 连接字符串

## Day 9 2022/7/11
- 字符串
    - 字符串转义
    - 操作 UTF-8 字符串
        - 按字符遍历 chars()
        - 按字节遍历 bytes()
        - 获取子串
- 元组
    - 用模式匹配解构元组
    - 用 . 来访问元组
    - 使用元组返回多个值
- 结构体


## Day 10 2022/7/12
- 结构体
    - 定义结构体
    - 创建结构体实例
    - 访问结构体字段
    - 简化结构体创建
    - 结构体更新语法
    - 结构体的内存排列
    - 元组结构体(Tuple Struct)
    - 单元结构体(Unit-like Struct)
    - 结构体数据的所有权
    - dbg!
- 枚举
    - 枚举值
    - 同一化类型
    - Option 枚举用于处理空值


## Day 11 2022/7/13
- 数组
    - 创建数组
    - 访问数组元素
    - 越界访问
    - 数组切片
- 流程控制
    - 使用 if 来做分支控制
    - 使用 else if 来处理多重条件
    - 循环控制
        - for 循环
        - continue
        - break
        - while 循环
        - loop 循环

## Day 12 2022/7/16
- 模式匹配
    - match 匹配
        - 模式绑定
        - 穷尽匹配
        - _ 通配符
    - if let 匹配
    - while let 条件循环
    - matches!宏
    - 变量覆盖
    - 解构Option
        - 匹配 Option<T>
    - 可驳模式和不可驳模式


## Day 13 2022/7/17
- 模式匹配
    - 全模式列表
        - 匹配字面量
        - 匹配命名变量
        - 单分支多模式
        - 通过序列 ..= 匹配值的范围
        - 解构并分解值
            - 解构结构体
            - 解构枚举
            - 解构嵌套的结构体和枚举
            - 解构结构体和元组
        - 忽略模式中的值
            - 使用 _ 忽略整个值
            - 使用嵌套的 _ 忽略部分值
            - 使用下划线开头忽略未使用的变量
            - 用 .. 忽略剩余值
        - 匹配守卫提供的额外条件


## Day 14 2022/7/23
- 方法 Method
    - 定义方法
    - self、&self 和 &mut self
    - 允许方法名跟结构体的字段名相同
    - 带有多个参数的方法
    - 关联函数
    - 多个 impl 定义
    - 为枚举实现方法
- 泛型和特征
    - 泛型 Generics
        - 泛型详解
        - 结构体中使用泛型
        - 枚举中使用泛型(Option<T>、Result<T, E>)
        - 方法中使用泛型
        - 为具体的泛型类型实现方法
        - const 泛型
        - const 泛型表达式
        - 泛型的性能
    - 特征 Trait
        - 定义特征
        - 为类型实现特征
        - 特征定义与实现的位置(孤儿规则)
        - 默认实现
        - 使用特征作为函数参数
        - 特征约束(trait bound)
            - 单个约束条件
            - 多重约束
            - Where 约束
        - 使用特征约束有条件地实现方法或特征
        - 函数返回中的 impl Trait
        - 通过 derive 派生特征
        - 调用方法需要引入特征
        - 几个综合例子
            - 为自定义类型实现 + 操作
            - 自定义类型实现 std::fmt::Display 特征