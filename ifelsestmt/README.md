lex ifelse.l
yacc -d ifelse.y
gcc lex.yy.c y.tab.c
./a.out

