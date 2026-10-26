lib-y += debug.o
lib-y += common.o bootargs.o bootmode.o recovery.o
lib-y += libc/string.o

lib-$(CONFIG_ENVIRONMENT_SUPPORT) += environment.o
lib-$(CONFIG_SPOOF_SUPPORT) += spoof.o

lib-$(CONFIG_STORAGE_SUPPORT) += storage/storage.o storage/gpt.o
