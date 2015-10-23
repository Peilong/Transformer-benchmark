INSTALL_ROOT = .
CC = gcc
CFLAGS = -Wall -lrt 
SOURCE_FILES = segmentation_acc.c seg-test.c

all:
	$(CC) $(CFLAGS) \
	$(SOURCE_FILES) \
	-lm \
	-o seg-test \
	$(LFLAGS)
clean:
	rm -f seg-test
