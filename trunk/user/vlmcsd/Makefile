THISDIR = $(shell pwd)
all:

clean:

romfs:
	$(ROMFSINST) -p +x $(THISDIR)/vlmcsd-mips32el-uclibc /usr/bin/vlmcsd
	$(ROMFSINST) -p +x $(THISDIR)/vlmcsd.sh /usr/bin/vlmcsd.sh

