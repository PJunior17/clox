CC = gcc
CFLAGS = -Wall -Wextra -Werror -pedantic

SRCS = main.c chunk.c debug.c memory.c

OBJS = $(SRCS:.c=.o)

TARGET = clox

all : $(TARGET)

$(TARGET): $(OBJS)
	$(CC) -o $@ $^

%.o: %.c
	$(CC) $(CFLAGS) -c -o $@ $<

