ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_CAPE) +=  \
	ovaltine-21841-cape-overlay.dtbo \
	ovaltine-21845-cape-overlay.dtbo \

ovaltine-21841-cape-overlay.dtbo-base := ../qcom/cape.dtb ../qcom/cape-v2.dtb
ovaltine-21845-cape-overlay.dtbo-base := ../qcom/cape.dtb ../qcom/cape-v2.dtb
endif

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
