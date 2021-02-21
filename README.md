# High Order Calculator (HOC)
An implementation of the program described in chapter 8 of the book, "The Unix Programming Environment." The program, "Hoc" is made up of a parser  which generates the action code from a context-free grammar. A lexical analyzer is also included to interpret user input and provide user output.

## To Run
Pre-requisites: your machine must include yacc or bison, gcc and make.

1. Clone the repo in your local repository
2. Run `yacc hoc.y`
3. Run `gcc y.yab.c -o hoc1`
4. To execute, run `./hoc1`
