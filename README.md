# Helium-Lex

 Personal lexical analyzer by James Zhang, as an individule assignment of the course *COMP450305*: "形式语言与编译——赵银亮", XJTU.



## Author Information

计算机试验班 91 学生 张骏扬



## Building and Testing the Project

This project is made with `CMake` tools, and tested in `Ubuntu-Linux`. Also this project can be built by `MSVC` in `Windows` environments.



### Linux

First you need to install `cmake` and `gcc` tools.

```bash
sudo apt install cmake build-essential
```

Then in the `Helium-Lex` directory, use cmake to generate the makefile, and build the project.

```bash
cmake .
make
```

Then run the executable file `HeliumLex`, with sample input given in `./tests/test.py`. The preprocessed files and output files can be the attributes of the executable file.

```bash
HeliumLex ./tests/test.py ./tests
```



The result could be checked by comparing with the python language tokenizer.

```bash
python -m tokenize tests/test.py
```





### Windows

Using WSL in Windows is encouraged, but MSVC can also be used to build this project.





### MacOS

Building in MacOS is not yet tested, but using the `cmake` tool in MacOS is similar using in Linux.