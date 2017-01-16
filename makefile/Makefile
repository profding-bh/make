textedit: main.o input.o output.o command.o files.o tools.o
	cc -o textedit main.o input.o output.o command.o \
files.o tools.o

main.o:main.c def.h
	cc -c main.c
input.o:input.c def.h command.h
	cc -c input.c
output.o:output.c def.h buffer.h
	cc -c output.c
command.o:command.c def.h command.h
	cc -c command.c
files.o:files.c def.h command.h buffer.h
	cc -c files.c
tools.o:tools.c def.h 
	cc -c tools.c # -c 通常用于编译不包含主程序的子程序文件。

clean:
	rm textedit main.o input.o output.o 
	rm command.o files.o tools.o
