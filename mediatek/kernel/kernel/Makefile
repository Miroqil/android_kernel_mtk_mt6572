ifeq ($(MTK_INTERNAL), yes)
ifeq ($(MTK_USE_RESERVED_EXT_MEM), yes)
KBUILD_CFLAGS += -DMTK_USE_RESERVED_EXT_MEM
endif
endif

obj-$(CONFIG_KGDB_KDB) += kdb_enhance.o
obj-y += mt_storage_logger.o
obj-y += mt_io_logger.o
obj-$(CONFIG_MT65XX_TRACER) += trace_mt65xx_mon.o

obj-y += sched/
