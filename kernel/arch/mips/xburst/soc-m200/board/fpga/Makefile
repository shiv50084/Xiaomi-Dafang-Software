
obj-y += misc.o
obj-y += mmc.o

ifdef CONFIG_LCD_TRULY_TFT240240_2_E
obj-y += truly_tft240240.o
else
obj-y += lcd.o
endif

obj-$(CONFIG_SOUND_OSS_XBURST_V1_2)		    += sound.o
obj-$(CONFIG_VIDEO_OVISP) += camera.o

ifdef CONFIG_SLCD_SUSPEND_ALARM_WAKEUP_REFRESH
obj-y += pm_slcd.o
else
obj-y += pm.o
endif
