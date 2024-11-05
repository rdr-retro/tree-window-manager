PREFIX?=/usr/X11R6
CFLAGS?=-Os -pedantic -Wall

all:
	$(CC) $(CFLAGS) -I$(PREFIX)/include tree.c -L$(PREFIX)/lib -lX11 -o tree

clean:
	rm -f tree

