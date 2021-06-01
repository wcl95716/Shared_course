build:
	bison -d fb3-1.y
	flex fb3-1.l
	
run:
	cc -o  test *.yy.c *.tab.c -ll
clean:
	rm -rf *.tab.c  *.yy.c *.tag.h