SRC = main.c\
src/Calculator_Operations.c
INC = inc
all.exe : $(SRC) 
	gcc $^ -I$(INC) -o $@

run : all.exe
	./all.exe

clean:
	del all.exe
