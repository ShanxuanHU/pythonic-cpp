# Pythonic C++

> Modern C++ for people who already know Python.

《Pythonic C++》是一本面向 Python 学习者的现代 C++ 入门书。它不假设读者从零开始学习编程，而是把 Python 中已经熟悉的概念迁移到 C++：从 `list` 到 `std::vector`，从 `dict` 到 `std::unordered_map`，从 `import` 到 `#include`、编译和链接，从自动内存管理到 RAII。

本项目的目标不是写一本更短的传统 C++ 教材，而是回答一个更具体的问题：

> 一个已经会写 Python 的学生，怎样用已有经验快速理解现代 C++？

## 项目定位

这本书主要面向：

- 已经学过 Python，准备学习 C++ 的学生
- 需要从 Python 过渡到系统编程、竞赛、工程开发或高性能计算的学习者
- 希望理解 C++ 工具链、内存模型、类型系统和现代开发流程的读者

本书会以“差异”和“迁移”为主线，而不是按照传统教材从变量、分支、循环完全重讲一遍。

## 内容主线

- Python 思维如何映射到 C++ 思维
- 静态类型、编译、链接和构建系统到底解决什么问题
- `std::vector`、`std::string`、`std::unordered_map` 等标准库容器如何对应 Python 常用数据结构
- RAII、所有权、引用、指针与 Python 自动内存管理的关系
- 面向对象、泛型、模板与 Python duck typing 的联系
- CMake、clangd、包管理、测试和 GitHub Actions 等现代 C++ 开发流程
- pybind11 与 Python/C++ 混合工程

## 文件说明

- `main.tex`：书稿主体，使用 `ctexbook` 编写
- `.gitignore`：忽略 LaTeX 构建产物和常见编辑器缓存
- `chat with GPT.md`：项目早期讨论记录，仅作为创作参考

## 编译方式

推荐使用 XeLaTeX：

```bash
xelatex main.tex
```

如果使用 TeX Live、MiKTeX 或 Overleaf，请选择 XeLaTeX 或 LuaLaTeX 编译。

## 贡献方向

欢迎围绕以下方向补充内容：

- 增加 Python 与 C++ 的概念对照示例
- 补充练习题和迁移任务
- 改进现代 C++ 工具链章节
- 增加真实工程案例
- 修正术语、代码和排版问题

## 许可

许可协议待定。
