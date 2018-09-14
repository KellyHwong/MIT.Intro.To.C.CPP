# MIT.Intro.To.C.CPP
MIT.Intro.To.C.CPP, Introduction to C and C++ on MIT OCW(Open Course Ware)

# Lec 1
要不要main函数：https://www.zhihu.com/question/28360770  
我觉得 MIT 的 Lec 1 就有点误导人，实际上没有 main 函数 gcc 命令会报错。  

Lec 1 课件117页不是gcc -c main.c main.c，应该是 gcc -c main.c answer.c  
以及后面的Link应该是 gcc -o main.o answer.o

<!-- gcc -c main.o answer.o -->

生成.o目标文件
gcc -c main.c
链接.o目标文件，产生.out输出文件
gcc main.o answer.o
或者一步到位
gcc main.c answer.c
gcc -o prog main.c answer.c

## Ref
[GCC Command Options](https://blog.csdn.net/letshi/article/details/70898760)

# Lab 1


# Reference
[MIT OCW Introduction to C and C++](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-s096-introduction-to-c-and-c-january-iap-2013/)
