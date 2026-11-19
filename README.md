# Repoo

[→ 简体中文版](docs/README.zh.md)

Repoo is an alternative to Git that offers a simpler way to manage versions.

> *Repo* O\_o\~

## Building and Running

Repoo is written in C++20. Make sure you have the following tools installed.

| Tool | Version Requirement | Description |
| :--- | :--- | :--- |
| `CMake` | 3.17+ | Build system. |
| `GCC` | Must Support C++20 | C++ compiler. Other compilers with C++20 support, such as `Clang` and `MSVC`, also work. |

Once the tools are installed, clone the Repoo repository:

```sh
git clone https://github.com/zirtian/Repoo.git
cd Repoo
```

Then run following commands to build Repoo:

```sh
cmake -S . -B build
cmake --build build
```

This creates the `build` directory and produces an executable named `repoo`.

## Usage

Stay tuned! (\^\~\^)

## License

Repoo is licensed under the [Apache License 2.0](LICENSE).
