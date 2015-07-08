KDIR := /lib/modules/`uname -r`/build

all:	
	+make -C $(KDIR) ORIG_PWD=`pwd` M=`pwd`/net/9p modules
	+make -C $(KDIR) ORIG_PWD=`pwd` M=`pwd`/fs/9p modules KBUILD_EXTRA_SYMBOLS=`pwd`/net/9p/Module.symvers



