## go-kerno 用go实现操作系统kernel

这是个go语言练手项目。最近在看《一个64位操作系统的设计与实现》，打算用go重新写一下C部分。网上看了很多关于go不适合写操作系统的说法，主要是关于gc的讨论，这里不评说，因为只是个练手项目。



> 开发环境：

```
deepin 15.5 sp2
nasm 2.12.01
as 2.28
gcc 6.3.0
gccgo 6.3.0
ld 2.28
make 4.1
```

