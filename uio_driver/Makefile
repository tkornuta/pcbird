obj-m += pcbird_uio.o

all:	
	#make -C /lib/modules/`uname -r`/build/usr/src/linux-2.6.27-gentoo-r8 M=$(PWD) modules
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
