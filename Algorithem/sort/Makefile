
OUT_PATH := $(shell pwd)/out

all: bubblesort selectsort insertsort shellsort mergesort fastsort
	test -d ${OUT_PATH} || mkdir -p ${OUT_PATH}
	mv $^ ${OUT_PATH}

clean:
	rm -f ${OUT_PATH}/*


bubblesort:
	@gcc -g -o bubblesort bubblesort.c

selectsort:
	@gcc -g -o selectsort selectsort.c

insertsort:
	@gcc -g -o insertsort insertsort.c

sheelsort:
	@gcc -g -o shellsort shellsort.c

mergesort:
	@gcc -g -o mergesort mergesort.c

fastsort:
	@gcc -g -o fastsort fastsort.c
