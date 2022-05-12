# C --notes

[TOC]



## .h & .c

### principle

- compiler's work
  1. preprocess
  2. analysis of morphology and grammar
  3. compilation
  4. link
- a compiler compiles in .c files
- main() is the entry of a C/C++ program , which means compilor will always find the file containing main() first
- when compilor finds #include ".h" , it will copy the codes in .h to this position
- a linker links in .o(object) files
- which object files to link needs programer to choose (some edit tools will auto write makefiles)

### division of the work

- declaration of vars, funs, structs is in .h
- definition of vars, funs is in .c

## reference

1. https://www.cnblogs.com/laojie4321/archive/2012/03/30/2425015.html