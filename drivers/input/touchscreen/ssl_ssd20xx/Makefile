#
# Makefile for the Solomon Systech SSD20xx touchscreen driver.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_TOUCHSCREEN_SSL_SSD20xx) += ssd20xx.o

ssd20xx-objs := ssd20xx.o
# ssd20xx_upgrade.o

#ifdef CONFIG_TOUCHSCREEN_SSL_SSD2098
ssd20xx-objs += ssd20xx_mx25v100.o
#endif
