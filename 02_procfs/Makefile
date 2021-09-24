obj-m += hello_proc.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=/usr/src/hello_module modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=/usr/src/hello_module clean
