all : printk.o

printk.o : printk.c
	$(GCC) $(CFLAG) -o printk.o -c printk.c

clean :
	$(shell rm *.o 2>/dev/null)