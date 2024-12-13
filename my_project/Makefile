CC = g++
CFLAGS = -Wall -g
TARGET = app

all: $(TARGET)

$(TARGET): src/main.cpp
    $(CC) $(CFLAGS) src/main.cpp -o $(TARGET)
    
clean:
    rm -f $(TARGET)
