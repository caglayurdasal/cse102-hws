all: clean compile run

clean:
	@echo "Cleaning compiled files...\n"
	@rm -f test

compile: main.c wordlist.txt
	@echo "Compiling the source file...\n"
	@gcc main.c -o test

run:
	@echo "Running tests...\n"
	@./test
	@echo "\n*******************************\n*** Finished running tests. ***\n*******************************\n"

