CC=gcc
SRCS=$(wildcard *.c)
EXES=$(SRCS:.c=)

all: $(EXES)

%: %.c
	$(CC) -o $@ $<

clean:
	rm $(EXES)