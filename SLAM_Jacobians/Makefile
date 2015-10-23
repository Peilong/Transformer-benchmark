INSTALL_ROOT = .
CC = gcc
CFLAGS = -Wall -lrt 
SOURCE_FILES = Jacobians.c SLAM-test.c

all:
	$(CC) $(CFLAGS) \
	$(SOURCE_FILES) \
	-lm \
	-o SLAM-test \
	$(LFLAGS)
clean:
	rm -f SLAM-test
