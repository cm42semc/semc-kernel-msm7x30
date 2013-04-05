#
# Makefile for TI's shared transport line discipline
# and its protocol drivers (BT)
#
obj-$(CONFIG_TI_ST) 		+= st_drv.o
st_drv-objs			:= st_core.o st_kim.o st_ll.o
obj-$(CONFIG_TI_ST)		+= ti_hci_drv.o
ti_hci_drv-objs			:= hci_if_drv.o
