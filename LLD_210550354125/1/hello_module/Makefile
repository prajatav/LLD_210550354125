Obj-m :=hello.o
ARCH=arm
CROSS_COMPILE_KDIR=/lib/modules/5.10.52-v7l+/build/
all:

         make -C $(CROSS_COMPILE_KDIR) M=$(PWD) modules
Clean:

         make -C $(CROSS_COMPILE_KDIR) M=$(PWD) clean
