obj-m	:= enable_arm_pmu.o
KDIR    := /home/jcmarsh/research/zybo_linux/linux-Digilent-Dev
PWD	:= $(shell pwd)

all:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) modules
clean:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) clean
