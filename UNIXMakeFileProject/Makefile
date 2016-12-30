# Charles Marcus Whitten
# Pledged -- I worked with Emily Herbert and David Garreston on this assignment.
# This assignment is entirely my own work, except for portions I got from sample programs for the course.

include Makefile-depend

CFLAGS = -Wall -pedantic -std=c99 -O

objects = main.o foo.o bar.o
main = main

main: alldepend $(objects)
	$(CC) -o $@ $(objects) $(LDFLAGS)

.PHONY:  clean
clean:
	$(MAKE) dclean
	rm $(objects)

.PHONY:  xclean
xclean:
	$(MAKE) dclean
	rm $(objects) $(main)
