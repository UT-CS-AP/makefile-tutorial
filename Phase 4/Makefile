
CC=g++
CFLAGS=-I.
DEPS = Person.h
OBJ = main.o Person.o 

all: main

%.o: %.cpp $(DEPS)
	$(CC) -c -o $@ $< $(CFLAGS)

main: $(OBJ)
	echo $^
	$(CC) -o $@ $^ $(CFLAGS)

clean:
	rm -f *.o main
