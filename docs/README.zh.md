# Repoo

[→ English Version](../README.md)

Repoo 是另一款不同于 Git 的版本控制工具, 提供一种更简单的版本管理方式。

> *Repo* O\_o\~

## 构建和运行

Repoo 使用 C++20 写成。确保您拥有下列工具:

| 工具 | 版本要求 | 描述 |
| :--- | :--- | :--- |
| `CMake` | 3.17+ | 构建系统。 |
| `GCC` | 须支持 C++20 | 项目编译器。其它支持 C++20 标准的编译器, `Clang` 或 `MSVC` 均可。 |

准备完成后, 通过下列命令克隆 Repoo 的仓库:

```sh
git clone https://github.com/zirtian/Repoo.git
cd Repoo
```

然后, 运行下列命令构建 Repoo:

```sh
cmake -S . -B build
cmake --build build
```

这会生成构建目录 `build` 并产出名为 `repoo` 的可执行文件。

## 用法

敬请期待! (\^\~\^)

## 许可证

Repoo 遵循 [Apache 2.0 许可证](../LICENSE)。