lex threeaddr.l
yacc -d threeaddr.y
g++ lex.yy.c y.tab.c -ll
./a.out < in.txt

