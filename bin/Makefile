SRC=$(wildcard ../src/*.cpp) ../src/glad.c
OBJ=$(SRC:.cpp=.o)

all:
	g++ -g --std=c++17 -I../include -L../lib ../src/main.cpp ../src/glad.c -lglfw3dll -lopengl32 -o main

