#
# Makefile for the Solomon Systech SSD20xx touchscreen driver.
#

# Each configuration option enables a list of files.

#
# Build Options
#
ccflags-y += -DDEBUG

obj-$(CONFIG_TOUCHSCREEN_SSD20xx) += ssd20xx_ts.o

# List all the object files that need to be linked for the ssd20xx module
ssd20xx_ts-objs := ssl_ssd20xx.o ssd20xx_upgrade.o ssd20xx_mx25v100.o
