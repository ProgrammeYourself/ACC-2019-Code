# ACC-2019-Code

Code [C++] for Level 3 of the Advent Coding Contest, written in C++.

## HOW-TOs

#### Executing:

- There are precompiled binaries that you can just run. If you can't find a matching executable, please go to the section about compiling.

##### Run (Linux):
`./ACC-Andi` make sure you are in the right directory.

If you are using a different OS, it is required to recompile the source code to run it.

#### Description of included files
- `ACC_Andi`: executable file. See chapter above.
- `ACC_Andi.cpp`: Source code.
- `ACC_Andi.cpp`: object file. only needed for compiling process
- `Changelog.log`: as the name it says
- `README.md`: this readme

#### Compiling:

- You can use the C++ compiler of your choice, however official support only covers the g++ command from GCC (GNU Compiler Collection).
- You compile the program using the command `g++ ./ACC_Andi.cpp -o ACC_Andi -pthread`. This will create a file named 'ACC_Andi' which is the desired executable.

#### Bug reporting:

- If you find any bug that isn't already known, please open a new bug report in the bug tracker. We will fix it as soon as possible.
- We realised that numbers higher than 100 won't be calculated; the reason could be an overflow. When you find that error in the code, please create an issue and we will fix it as soon as possible.

## CHANGELOG

See `Changelog.log`

## SOLUTIONS

| 10        | 200         | 500          | 1000         | 10000         | 2000000000 |
| --------- | ----------- | ------------ | ------------ | ------------- | ---------- |
| 432256955 | 61956210911 | 149585554326 | 322833621931 | 3264567774119 | ?          |

