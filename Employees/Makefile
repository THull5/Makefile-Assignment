CXX = g++

CXXFLAGS = -std=c++11 -Wall

TARGET = main

SRCS = main.cpp Employee.cpp Officer.cpp Supervisor.cpp

OBJS = $(SRCS:.cpp=.o)

all: $(TARGET)

$(TARGET): $(OBJS)
		$(CXX) $(CXXFLAGS) -o $(TARGET) $(OBJS)

clean:
		rm -f $(OBJS) $(TARGET)