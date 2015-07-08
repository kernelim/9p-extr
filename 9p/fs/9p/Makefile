LINUXINCLUDE := \
  -I${ORIG_PWD}/. \
  -I${ORIG_PWD}/include \
  -I${ORIG_PWD}/include/uapi \
  -I${ORIG_PWD}/arch/x86/include \
  -I${ORIG_PWD}/arch/x86/include/uapi \
  -include ${ORIG_PWD}/include/config.h \
  ${LINUXINCLUDE} \

obj-m := 9p.o

9p-objs := \
	vfs_super.o \
	vfs_inode.o \
	vfs_inode_dotl.o \
	vfs_addr.o \
	vfs_file.o \
	vfs_dir.o \
	vfs_dentry.o \
	v9fs.o \
	fid.o  \
	xattr.o \
	xattr_user.o
