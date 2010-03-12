
CC=gcc
CFLAGS := $(shell getconf LFS_CFLAGS) -Wall -O2 -g $(shell pkg-config --cflags plymouth-1)
LDFLAGS=$(shell pkg-config --libs plymouth-1) -lplybootclient

casper-md5check: casper-md5check.c md5.c

clean:
	rm -f *.o casper-md5check
