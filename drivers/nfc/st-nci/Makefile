#
# Makefile for ST_NCI NCI based NFC driver
#

st-nci-objs = ndlc.o core.o se.o vendor_cmds.o
obj-$(CPTCFG_NFC_ST_NCI)     += st-nci.o

st-nci_i2c-objs = i2c.o
obj-$(CPTCFG_NFC_ST_NCI_I2C) += st-nci_i2c.o

st-nci_spi-objs = spi.o
obj-$(CPTCFG_NFC_ST_NCI_SPI) += st-nci_spi.o
