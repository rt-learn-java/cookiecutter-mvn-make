help:
	@echo "make -s init - initialize project"
	@echo "make -s test - run unit tests"
	@echo "make -s run - run the main script"
	@echo "make -s clean - delete generated files"
	@echo "-s option hides the Make invocation command (@echo)."

init:
	@echo init

test:
	mvn test

run:
	@echo run

clean:
	rm -rf target/
	rm -rf bin/

.PHONY: help test init clean run
