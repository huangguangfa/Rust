# Rust
学习Rust

## MacOS安装
终端输入指令执行、根据提示回车安装!
```rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
检测安装是否成功!

```rust
rustup -V
// info: This is the version for the rustup toolchain manager, not the rustc compiler.
// info: The currently active `rustc` version is `rustc 1.63.0 (4b91a6ea7 2022-08-08)
```

## 创建项目
我们可以通过`cargo` 指令创建一个新项目、指令执行完后会在当前目录层创建一个新的项目
```rust
cargo new hello-rust  // 创建项目

```
目录介绍
```rust
// 目录
|- Cargo.toml  // 依赖描述、包含了你使用的依赖和元数据(元数据暂时不知道什么意思)
|- src
  |- main.rs  // 业务代码
```

运行hello-word

运行指令 `cargo run` 得到终端 输出 `Hello, world!`
