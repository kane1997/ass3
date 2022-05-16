all:  elf32

target: elf32
elf32: a.c
    gcc -O0 -fno-builtin -fno-stack-protector -m32 -Wall -std=c11 -ggdb -z execstack -o a.out a.c
    
target: clean
clean: a.out
    rm a.out
