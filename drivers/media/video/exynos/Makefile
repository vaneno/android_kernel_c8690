obj-$(CONFIG_EXYNOS_MEDIA_DEVICE)	+= mdev/
obj-$(CONFIG_VIDEO_EXYNOS_MIPI_CSIS)	+= mipi-csis/
obj-$(CONFIG_VIDEO_EXYNOS_FIMC_LITE)	+= fimc-lite/
obj-$(CONFIG_VIDEO_EXYNOS_GSCALER)	+= gsc/

ifeq ($(CONFIG_VIDEO_S5K3H7),y)
obj-$(CONFIG_VIDEO_EXYNOS)		+= fimc-is/
else
obj-$(CONFIG_VIDEO_EXYNOS)	+= fimc-is_external_isp/
endif

obj-$(CONFIG_VIDEO_EXYNOS5_FIMC_IS)	+= fimc-is-mc/
obj-$(CONFIG_VIDEO_EXYNOS_TV)		+= tv/
obj-$(CONFIG_VIDEO_EXYNOS)		+= rotator/

EXTRA_CLAGS += -Idrivers/media/video
