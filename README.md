9P externally buildable kernel modules for CentOS 7.1
-----------------------------------------------------

Based on kernel-3.10.0-229.7.2.el7.src.rpm.

Quick HOWTO:

    sudo install kernel-devel-`uname -r`

    cd 9p
    make

    sudo insmod ./net/9p/9pnet.ko
    sudo insmod ./net/9p/9pnet_virtio.ko
    sudo insmod ./fs/9p/9p.ko

Have fun.
