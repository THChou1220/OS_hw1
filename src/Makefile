obj-m += simple.o
obj-m += hello.o
obj-m += seconds.o
obj-m += third_example.o
obj-m += third.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
