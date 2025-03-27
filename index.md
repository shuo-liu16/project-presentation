---
title: Welcome to my blog
---

# Dream New Kilo - 轻量级文本编辑器

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

![Demo Screenshot](src/images/image.png)  

基于经典项目 [kilo](https://github.com/antirez/kilo) 的现代化再造，一个用纯 C 语言开发的轻量级终端文本编辑器。

## ✨ 特性亮点

### 核心功能

- **极简设计**：<500 行代码实现完整编辑功能
- **即时响应**：基于原始终端控制的快速渲染引擎
- **跨平台**：支持 Linux/macOS 的现代终端环境
- **无依赖**：仅需标准 C 库（C99 标准）

### 编辑功能

- 基本文本操作（插入/删除/移动光标）
- 多行滚动支持
- 行号显示系统
- 智能状态栏（显示光标位置/文件状态）
- 文件保存与加载（支持覆盖/另存为）
- 跨行编辑能力

## 🚀 快速开始

### 编译安装

```bash
git clone https://github.com/shuo-liu16/dream-new-kilo.git
cd dream-new-kilo
make
sudo cp kilo /usr/local/bin
```

### 基本使用

```bash
kilo [filename]  # 打开现有文件或新建
```

**快捷键参考**：

| 组合键          | 功能                 |
|-----------------|----------------------|
| Ctrl + Q        | 退出编辑器           |
| Ctrl + S        | 保存文件             |
| 方向键          | 光标移动             |
| PageUp/PageDown | 快速滚动             |
| Ctrl + F        | 搜索模式（开发中）   |

## 🛠️ 开发指南

### 代码架构

TODO

## 🌟 未来愿景

### 近期路线图

- [ ] 完成复刻

## 🙏 致谢

本项目基于以下优秀资源构建：

- [kilo](https://github.com/antirez/kilo) by Salvatore Sanfilippo (antirez)
- [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/) 教程
- The C Programming Language (K&R 经典著作)

## 📜 开源协议

本项目采用 [MIT License](LICENSE)，欢迎自由使用和二次开发。如用于商业项目，建议保留原始作者署名。

---

> "Any application that can be written in C, will eventually be rewritten in C." — 程序员的递归哲学

---
