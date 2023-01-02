# Introduction

This repository serves as our homework for the topic: compiler in HUST.

Using the programing language C to create a compiler of KPL (Kyoto  Programming Language)

## Run

1. Check your compiler of C installation: gcc/g++.   
    If you don't have, you can install it by following the instructions on the [MSYS2 website](https://www.msys2.org/)
2. open command line and change direction to folder "completed" and enter:  
    gcc main.c reader.c parser.c scanner.c symtab.c token.c debug.c error.c charcode.c semantics.c

3. file a.exe (on Window) or file a.out (on linux) is compiler of KPL

4. you can test compiler with command line: .\a.exe .\completed\example6.kpl
