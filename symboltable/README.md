lex symtab.l
yacc -d symtab.y
g++ lex.yy.c y.tab.c -ll
./a.out < in.txt
