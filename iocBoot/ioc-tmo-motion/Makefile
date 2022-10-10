IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.0

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-tmo-motion
PROJECT_PATH := ../../plc-tmo-motion/plc-tmo-motion.tsproj
PLC = tmo_motion

PYTMC_OPTS :=
PREFIX = PLC:TMO:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base

