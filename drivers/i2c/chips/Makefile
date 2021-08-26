#
# Makefile for miscellaneous I2C chip drivers.
#
# Do not add new drivers to this directory! It is DEPRECATED.
#
# Device drivers are better grouped according to the functionality they
# implement rather than to the bus they are connected to. In particular:
# * Hardware monitoring chip drivers go to drivers/hwmon
# * RTC chip drivers go to drivers/rtc
# * I/O expander drivers go to drivers/gpio
#
#proximity-objs := cm3629.o

ifeq ($(CONFIG_INPUT_CAPELLA_CM3629),y)
proximity-objs := cm3629.o
obj-$(CONFIG_INPUT_CAPELLA_CM3629)      += proximity.o
endif
obj-$(CONFIG_SENSORS_AK8963_DOE_PLUS)    += akm8963_doe_plus.o
obj-$(CONFIG_BOSCH_BMA250)      += bma250_bosch.o

