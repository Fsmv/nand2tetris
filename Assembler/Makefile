CC=gcc
CFLAGS=-g
SOURCES=main.c assembler.c parser.c symbolTable.c
EXECUTABLE=hackasm

all: $(EXECUTABLE)

$(EXECUTABLE): $(SOURCES)
	$(CC) $(CFLAGS) -o $(EXECUTABLE) $(SOURCES)

clean:
	rm -f $(EXECUTABLE)
