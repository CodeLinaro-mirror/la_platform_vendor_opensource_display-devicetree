ifneq ($(CONFIG_ARCH_QTI_VM), y)
dtbo-$(CONFIG_ARCH_YUPIK) += display/yupik-sde.dtbo \
		display/yupik-sde-display-idp-pm7250b-overlay.dtbo \
		display/yupik-sde-display-idp-overlay.dtbo

endif

always-y    := $(dtb-y) $(dtbo-y)
subdir-y    := $(dts-dirs)
clean-files    := *.dtb *.dtbo
