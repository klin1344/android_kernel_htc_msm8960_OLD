GCC_VERSION      := $(shell $(CONFIG_SHELL) $(PWD)/scripts/gcc-version.sh $(CROSS_COMPILE)gcc)
ifdef CONFIG_MACH_JET
	obj-$(CONFIG_RAWCHIP) += rawchip_spi.o rawchip.o Yushan_API.o yushan_reg.o
else
	obj-$(CONFIG_RAWCHIP) += rawchip_spi.o rawchip.o Yushan_API.o yushan_reg.o yushan_ir_reg.o
endif
