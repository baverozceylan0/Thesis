FILE1 = basicmath_small.c   rad2deg.c  cubic.c   isqrt.c
FILE2 = basicmath_large.c   rad2deg.c  cubic.c   isqrt.c
FILE3 = basicmath_app.c   rad2deg.c  cubic.c   isqrt.c

all: basicmath_small basicmath_large basicmath_app

basicmath_small: ${FILE1} Makefile
	gcc -static -O3 ${FILE1} -o basicmath_small -lm
basicmath_large: ${FILE2} Makefile
	gcc -static -O3 ${FILE2} -o basicmath_large -lm
basicmath_app: ${FILE3} Makefile
	gcc -static -O3 ${FILE3} -o basicmath_app -lm

clean:
	rm -rf basicmath_small basicmath_large basicmath_app output*
