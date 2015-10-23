INSTALL_ROOT = .
CC = gcc
CFLAGS = -Wall -lrt
SOURCE_FILES = jacobi.c jacobi-test.c

all:
	$(CC) $(CFLAGS) \
	$(SOURCE_FILES) \
	-lm \
	-o jacobi-test \
	$(LFLAGS)
clean:
	rm -f jacobi-test
