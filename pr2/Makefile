cc = gcc
target = animal.exe
objects = main.o turtle.o blackcow.o dog.o

$(target): $(objects)
	$(cc) -o $(target) $(objects)

$(objects) : animal.h

.PHONY: clean
clean:
	rm $(target) $(objects)
