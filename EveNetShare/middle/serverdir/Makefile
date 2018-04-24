CC = g++
IFLAGS = -Wall -O2 -I/usr/local/include
LFLAGS = -L/usr/local/lib -l/usr/bin/openssl
LFLAGS = -lssl -lcrypto -levent_openssl -levent
SRC = MiddleServer.cpp

all:
	$(CC) $(IFLAGS) $(SRC) $(LFLAGS) -o server

clean:
	rm -rf *.o server
