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

## Day 7 2022/7/10
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

## Day 8 2022/7/11
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


## Day 9 2022/7/12
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