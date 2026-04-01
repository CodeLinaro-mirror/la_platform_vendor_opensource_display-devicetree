ifneq ($(CONFIG_ARCH_QTI_VM), y)
dtbo-$(CONFIG_ARCH_YUPIK) += display/yupik-sde.dtbo \
		display/yupik-sde-display-idp-pm7250b-overlay.dtbo \
		display/yupikp-sde-display-iot-hsp-pm7250b-overlay.dtbo \
		display/yupikp-sde-display-iot-idp-pm7250b-overlay.dtbo \
		display/yupik-sde-display-iot-idp-hsp-pm7250b-overlay.dtbo \
		display/yupikp-sde-display-iot-idps-overlay.dtbo \
		display/yupik-sde-display-iot-idps-overlay.dtbo \
		display/yupik-sde-display-iot-hsp-overlay.dtbo \
		display/yupik-sde-display-iot-idp-overlay.dtbo \
		display/katmai-sde-display-idp-pm7250b-overlay.dtbo \
		display/yupik-sde-display-idp-overlay.dtbo \
		display/yupik-sde-display-iot-qrd-overlay.dtbo \
		display/yupik-sde-display-qrd-overlay.dtbo
endif

ifeq ($(CONFIG_ARCH_SM6150), y)
dtbo-y +=  display/sm6150-sde.dtbo \
	   display/qcs610-sde-display-iot-overlay.dtbo \
	   display/qcs610-sde-display-opk-overlay.dtbo
endif

ifeq ($(CONFIG_ARCH_LAHAINA), y)
		dtbo-y +=  display/lahaina-sde.dtbo \
		display/lahaina-sde-display-mtp-overlay.dtbo \
		display/lahaina-sde-display-mtp-v2.1-overlay.dtbo \
		display/lahaina-sde-display-qrd-overlay.dtbo

endif

always-y    := $(dtb-y) $(dtbo-y)
subdir-y    := $(dts-dirs)
clean-files    := *.dtb *.dtbo
