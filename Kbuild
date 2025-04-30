ifneq ($(CONFIG_ARCH_QTI_VM), y)
dtbo-$(CONFIG_ARCH_YUPIK) += display/yupik-sde.dtbo \
		display/yupik-iot-hsp-pm7250b.dtbo
endif


ifeq ($(CONFIG_ARCH_SM6150), y)
dtbo-y +=  display/sm6150-sde.dtbo \
	   display/qcs610-sde-display-iot-overlay.dtbo \
	   display/qcs610-sde-display-opk-overlay.dtbo
endif

always-y    := $(dtb-y) $(dtbo-y)
subdir-y    := $(dts-dirs)
clean-files    := *.dtb *.dtbo
