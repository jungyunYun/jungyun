CC = gcc
AR = ar
OBJFILES = func1.o func2.o
OUTPUT= libfuncs.a

$(OUTPUT): $(OBJFILES)
	$(AR) rv $(OUTPUT) $(OBJFILES)
func1.o: func1.c
	gcc -c -I../include func1.c -o func1.o
func2.o: func2.c
	gcc -c -I../include func2.c -o func2.o

