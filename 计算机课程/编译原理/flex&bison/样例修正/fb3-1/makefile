fb3-1:*.l  *.y  *.h
	bison -d *.y
	flex -o$@.lex.c *.l
	cc -o $@ *.c  -ll
	