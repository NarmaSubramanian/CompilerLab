lex syntree.l
yacc -d syntree.y
gcc lex.yy.c y.tab.c
./a.out < in.txt

