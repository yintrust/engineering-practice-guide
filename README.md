# 工程化实践指南

![workflow badge](https://github.com/yintrust/engineering-practice-guide/workflows/github-pages/badge.svg)
[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/yintrust/engineering-practice-guide)
![GitHub repo size](https://img.shields.io/github/repo-size/yintrust/engineering-practice-guide)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Keep a Changelog v1.1.0 badge](https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.1.0-%23E05735)](https://keepachangelog.com/zh-CN/1.0.0/)

文档托管在 GitHub Pages，在线访问地址：<https://yintrust.github.io/engineering-practice-guide>

此文档由 [mdBook](https://github.com/rust-lang/mdBook) 生成，
使用 [Markdown](https://guides.github.com/features/mastering-markdown/) 语法编写，
想要在本地构建并预览此文档，你需要先安装 mdBook，
进一步的，在安装 mdBook 之前，你需要先安装 [Rust](https://www.rust-lang.org/zh-CN/) ，
Rust 的安装可参考其[官网指南](https://www.rust-lang.org/zh-CN/tools/install) 。

安装完 Rust 之后便可以使用其自带的 `cargo` 命令来安装 `mdbook`，如下：

```bash
cargo install mdbook
```

自此以后，每次要在本地构建并预览此文档，只需执行以下命令：

```bash
mdbook serve
```
