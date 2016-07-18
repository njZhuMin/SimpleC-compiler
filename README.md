# Simplec-compiler
A simple C interpreter that interpretes itself.

## How to Run the Code

1.clone source code `SimpleC.c` to your dir.
```bash
git clone https://github.com/njZhuMin/SimpleC-compiler
```

2.Compile
```bash
gcc -o SimpleC SimpleC.c (you may need the -m32 option on 64-bit machines)
./SimpleC hello.c
./SimpleC -s hello.c
```

3.Try this out
```bash
./SimpleC SimpleC.c hello.c
./SimpleC SimpleC.c SimpleC.c hello.
```

# About

This project is inspired by [project c4](https://github.com/rswier/c4) and is largely based on it.

However, I rewrited them all to make it more understable and help myself to understand it.

Despite the complexity we saw in books about compiler design, writing one is not that hard. You don't need that much theory though they will help for better understanding the logic behind the code.

# Tutorial
http://sunnywr.com/blog/categories/project/SimpleC

# Resources
Further Reading:
[Let's Build a Compiler](http://compilers.iecc.com/crenshaw/): An excellent starting material for building compiler.
