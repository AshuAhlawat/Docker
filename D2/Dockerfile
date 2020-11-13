arg version=latest

from gcc:${version}

copy . /usr/src/c_test

workdir /usr/src/c_test

run gcc -o Test main.c

cmd ["./Test"]