Rust 官网 : https://www.rust-lang.org/zh-CN/

Rust 官方文档: https://www.rust-lang.org/zh-CN/learn

Rust 官方文档中文教程: https://rustwiki.org/

设置国内源 https://rsproxy.cn/

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh #安装命令

rustup update #更新Rust:

rustup self uninstall #卸载Rust

rustup component add rustfmt #添加Rust组件

rustup --version #查看Rust版本

# Rust两种版本 Stable 稳定版本,生产使用 Nightly 夜版,每天构建最新版

restup install stable/nightly #安装

restup default stable/nightly #切换

rustup show #查看安装版本
```

Rust 包管理工具Cargo , 底层会隐式的使用rustc进行编译

Cargo.toml : https://course.rs/cargo/reference/manifest.html

```shell

cargo new project_name #创建

cargo new --lib project_name #创建一个新的Rust库项目

cargo build #构建

cargo build --release #生成优化的可执行文件,常用语生产环境

cargo check #检测

cargo run #运行

catgo test  #测试

cargo install cargo-edit # cargo 插件

cargo add dependency_name@123 # 指定版本

cargo add --dev dev_dependency_name # 添加开发时需要的依赖

cargo add --build bulid_dependency_na-me # 添加构建时需要的依赖

cargo rm dependency_name # 删除库
```
