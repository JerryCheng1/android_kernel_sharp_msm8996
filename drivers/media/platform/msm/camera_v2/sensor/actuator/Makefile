ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
ifeq ($(CONFIG_ARCH_PA32),y)
obj-$(CONFIG_BU63164GWL_ACT) += bu63164gwl_actuator.o
else
obj-$(CONFIG_MSMB_CAMERA) += msm_actuator.o
endif
