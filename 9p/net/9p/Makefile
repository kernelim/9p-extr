LINUXINCLUDE := \
  -I${ORIG_PWD}/. \
  -I${ORIG_PWD}/include \
  -I${ORIG_PWD}/include/uapi \
  -I${ORIG_PWD}/arch/x86/include \
  -I${ORIG_PWD}/arch/x86/include/uapi \
  -include ${ORIG_PWD}/include/config.h \
  ${LINUXINCLUDE} \
                  
obj-m := 9pnet.o
obj-m += 9pnet_virtio.o

obj-$(CONFIG_NET_9P_RDMA) += 9pnet_rdma.o

9pnet-objs := \
	mod.o \
	client.o \
	error.o \
	util.o \
	protocol.o \
	trans_fd.o \
	trans_common.o \

9pnet_virtio-objs := \
	trans_virtio.o \

9pnet_rdma-objs := \
	trans_rdma.o \
