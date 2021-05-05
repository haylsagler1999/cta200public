CC=gcc
DEPS=
OBJ=main.o
CFLAGS=-std=c99

%.o: %.c $(DEPS)
	$(CC) $(CFLAGS) -c -o $@ $<

main: $(OBJ)
	$(CC) -o $@ $^ $(CFLAGS)
