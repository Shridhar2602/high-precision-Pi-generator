#OBJS specifies which files to compile as part of the project
OBJS = main.cpp add.cpp sub.cpp mul.cpp div.cpp karatsuba.cpp helper.cpp sq_root.cpp pi.cpp

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
COMPILER_FLAGS = -w -Wall

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = pi

#This is the target that compiles our executable
all : $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) -o $(OBJ_NAME)