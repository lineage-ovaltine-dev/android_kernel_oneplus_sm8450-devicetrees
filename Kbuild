ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY), y)
dtbo-$(CONFIG_ARCH_WAIPIO) += oplus/ovaltine-21841-camera-waipio-overlay.dtbo
dtbo-$(CONFIG_ARCH_CAPE) += oplus/ovaltine-21841-camera-cape-overlay.dtbo
else
$(error CONFIG_BUILD_ARM64_DT_OVERLAY is: $(CONFIG_BUILD_ARM64_DT_OVERLAY))
endif

always-y	:= $(dtbo-y) $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
