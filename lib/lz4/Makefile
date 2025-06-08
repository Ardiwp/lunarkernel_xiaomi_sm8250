ccflags-y += -O3 \
    -Wframe-larger-than=131072 \
    -DLZ4_FREESTANDING=1 \
    -DLZ4_FAST_DEC_LOOP=1

obj-$(CONFIG_LZ4) += lz4.o
obj-$(CONFIG_LZ4HC) += lz4hc.o

obj-$(CONFIG_ARM64) += $(addprefix lz4armv8/, lz4accel.o lz4armv8.o)
