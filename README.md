# Compile Boost Windows

## Boost C++ Libraries

The Boost project provides free peer-reviewed portable C++ source libraries.

How to compile Windows

```bash
cd C:\
git clone https://github.com/boostorg/boost.git
```

```bash
cd boost
git submodule update --init --recursive
```

```bash
boostrap.bat
./b2
```
