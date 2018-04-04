lex for.l
yacc -d for.y
g++ lex.yy.c y.tab.c -ll
./a.out < in.txt
