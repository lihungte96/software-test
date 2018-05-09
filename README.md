# software-test-class-sample
[![Build Status](https://travis-ci.org/lihungte96/software-test-class-sample.svg?branch=master)](https://travis-ci.org/lihungte96/software-test-class-sample)
Software test class sample code

support CI Jenkins file

Use google test as framework

## Makefile
make [all]  - makes googletest executable file.

make TARGET - makes the given target.

make clean  - removes all files generated by make.

make test   - run googletest executable file.

make gcov   - run gcov to get coverage informtion.

## steps
### How to judge
	cd make
	make
	make test
	make gcov
