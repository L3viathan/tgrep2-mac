# Edit this line to point to the directory containing the drutils.h file:
UTIL_DIR= ../DRUtils

UTIL_LIB= ${UTIL_DIR}/${HOSTTYPE}/libdrutils.a
CC= gcc -O2 -Wall -DLITTLE_END -arch i386 -arch x86_64
#CC= gcc -g -Wall

tgrep2: tgrep2.c Makefile
	${CC} -o $@ -I${UTIL_DIR} tgrep2.c ${UTIL_LIB} -lm

clean:
	rm -f *.o tgrep2
