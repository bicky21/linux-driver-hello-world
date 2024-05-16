obj-m += hello_world.o

all:
     make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules EXTRA_CFLAGS="-Wno-deprecated-declarations"

clean:
     make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
