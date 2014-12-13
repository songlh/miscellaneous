
CXX=gcc
CFLAGS=-g
TARGET=gengeo


gengeo: gengeo.o
	${CXX} ${CFLAGS} gengeo.o -o ${TARGET} -lm

gengeo.o: gengeo.c
	${CXX} ${CFLAGS} -c gengeo.c -o gengeo.o

clean:
	rm -rf *.o ${TARGET} *.output
