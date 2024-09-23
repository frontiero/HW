main: main.o HW.o
	gcc main.o HW.o -o main

main.o: main.c
	gcc main.c -c -o main.o

HW.o: HW.c
	gcc HW.c -c -o HW.o

.PHONY : run clean

run: main
	./main

clean:
	del *.o main.exe



