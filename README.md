# TZON

TZON is a small educational language used for lexer/parser exercises. This starter focuses on the lexical phase and basic syntax examples.

## Grammar in BNF Form

The formal grammar is defined in BNF.txt. It describes a minimal program structure for the starter.

## Syntax

<prog> : <stmt> | <stmts>

<stmt> : <expr> ...

## Explanations about the language

•⁠  ⁠Takes a file with extension .tzon
•⁠  ⁠Has if, while, ...

•⁠  ⁠You can run your program by running the makefile and giving it to myprog as input:

make
./myprog < example.tzon