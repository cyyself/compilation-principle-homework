grammar_analyzer: src/*
	g++ -std=c++17 src/main.cpp -o grammar_analyzer -fsanitize=address

.PHONY: test1 test2 test3 test clean
test1: grammar_analyzer testcase1.c plot.py
	@echo "Testing Testcase1.c"
	@./grammar_analyzer < testcase1.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt


test2: grammar_analyzer testcase2.c plot.py
	@echo "Testing Testcase2.c"
	@./grammar_analyzer < testcase2.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

test3: grammar_analyzer testcase3.c plot.py
	@echo "Testing Testcase3.c"
	@./grammar_analyzer < testcase3.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

test4: grammar_analyzer testcase4.c plot.py
	@echo "Testing Testcase4.c"
	@./grammar_analyzer < testcase4.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

test5: grammar_analyzer testcase5.c plot.py
	@echo "Testing Testcase5.c"
	@./grammar_analyzer < testcase5.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

test6: grammar_analyzer testcase6.c plot.py
	@echo "Testing Testcase6.c"
	@./grammar_analyzer < testcase6.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

test7: grammar_analyzer testcase7.c plot.py
	@echo "Testing Testcase7.c"
	@./grammar_analyzer < testcase7.c > tmp.txt
	@cat tmp.txt
	@python3 plot.py < tmp.txt

clean:
	rm grammar_analyzer