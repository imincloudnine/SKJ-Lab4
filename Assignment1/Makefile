all: multiply_numbers

multiply_numbers: multiply_numbers.cpp
	g++ -o multiply_numbers multiply_numbers.s

dump: multiply_numbers
	objdump -d multiply_numbers > multiply_numbers.s

clean:
	rm -f multiply_numbers multiply_numbers.s

run: multiply_numbers
	./multiply_numbers