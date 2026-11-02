# test_ai

## 如何学习 Rust

### 1. 安装 Rust

使用官方工具链管理器 `rustup` 安装：

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

安装完成后，`rustc`（编译器）和 `cargo`（包管理器）即可使用。

### 2. 阅读官方书籍

- **[The Rust Programming Language](https://doc.rust-lang.org/book/)**（俗称"The Book"）：最权威的入门教材，免费在线阅读。
- **[Rust By Example](https://doc.rust-lang.org/rust-by-example/)**：通过可运行的示例学习，适合边看边练。

### 3. 动手练习

- **[Rustlings](https://github.com/rust-lang/rustlings)**：一系列小练习，帮助熟悉编译器报错和基本语法。
  ```bash
  cargo install rustlings
  rustlings
  ```
- **[Exercism Rust Track](https://exercism.org/tracks/rust)**：在线题目，有社区 mentor 反馈。

### 4. 重点理解所有权（Ownership）

Rust 最独特的概念是所有权、借用和生命周期。遇到编译错误不要跳过，认真阅读错误信息——编译器的提示非常详细，是最好的老师。

### 5. 写真实项目

学完基础后，用 Cargo 创建一个小项目（CLI 工具、简单 Web 服务等），在实战中巩固知识：

```bash
cargo new my_project
cd my_project
cargo run
```

### 6. 参考资源

- 标准库文档：`rustup doc --std` 或 [doc.rust-lang.org/std](https://doc.rust-lang.org/std/)
- 社区论坛：[users.rust-lang.org](https://users.rust-lang.org/)
- 中文社区：[rustcc.cn](https://rustcc.cn/)
