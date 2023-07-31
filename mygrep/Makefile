mygrep: grep.o source.o stack.o
	cc -Wall grep.o source.o stack.o -o mygrep
grep.o: grep.c source.h stack.h header.h
	cc -c grep.c
stack.o: stack.c stack.h
	cc -c stack.c
source.o: source.c source.h
	cc -c source.c
