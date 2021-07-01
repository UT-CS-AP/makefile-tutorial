CC=g++
CFLAGS=-I.
DEPS = Person.h

%.o: %.cpp $(DEPS)
	echo $@
	echo $<
	$(CC) -c -o $@ $< $(CFLAGS)

main: main.o Person.o 
	$(CC) -o main main.o Person.o
