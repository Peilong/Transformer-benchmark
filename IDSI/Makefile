INSTALL_ROOT = .
CC = gcc
CFLAGS = -Wall -lrt 
SOURCE_FILES = IDSI.c IDSI-test.c

all:
	$(CC) $(CFLAGS) \
	$(SOURCE_FILES) \
	-lm \
	-o IDSI-test \
	$(LFLAGS)
clean:
	rm -f IDSI-test
