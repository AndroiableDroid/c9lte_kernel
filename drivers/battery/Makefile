ifeq ($(CONFIG_BATTERY_SAMSUNG),y)
ifeq ($(CONFIG_BATTERY_SAMSUNG_V2),y)
obj-y += sec_battery_v2.o
else
obj-y += sec_battery.o
endif
endif
obj-$(CONFIG_MULTI_CHARGING)	+= sec_multi_charger.o
obj-$(CONFIG_STEP_CHARGING)	+= sec_step_charging.o
ifeq ($(CONFIG_OF),y)
obj-$(CONFIG_ARCH_MSM)			+= sec_board-msm.o
endif
obj-$(CONFIG_FUELGAUGE_MAX17042)	+= max17042_fuelgauge.o	sec_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_MAX17048)	+= max17048_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_MAX17050)	+= max17050_fuelgauge.o	sec_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_MAX77823)	+= max77823_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_MAX77843)	+= max77843_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_SM5705)		+= sm5705_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_S2MU005)        += s2mu005_fuelgauge.o
obj-$(CONFIG_FUELGAUGE_SM5703)		+= sm5703_fuelgauge.o

obj-$(CONFIG_CHARGER_MAX8903)	+= max8903_charger.o
obj-$(CONFIG_CHARGER_SMB328)	+= smb328_charger.o
obj-$(CONFIG_CHARGER_SMB347)	+= smb347_charger.o
obj-$(CONFIG_CHARGER_SMB358)	+= smb358_charger.o
obj-$(CONFIG_CHARGER_SMB1357)	+= smb1357_charger.o
obj-$(CONFIG_CHARGER_BQ24157)	+= bq24157_charger.o sec_charger.o
obj-$(CONFIG_CHARGER_BQ24190)	+= bq24190_charger.o
obj-$(CONFIG_CHARGER_BQ24191)	+= bq24190_charger.o
obj-$(CONFIG_CHARGER_BQ24260)	+= bq24260_charger.o
obj-$(CONFIG_CHARGER_MAX77693)	+= max77693_charger.o
obj-$(CONFIG_CHARGER_MAX77803)	+= max77803_charger.o
obj-$(CONFIG_CHARGER_MAX77804K)	+= max77804k_charger.o
obj-$(CONFIG_CHARGER_MAX77888)  += max77888_charger.o
obj-$(CONFIG_CHARGER_MAX77823)	+= max77823_charger.o
obj-$(CONFIG_CHARGER_MAX77843)	+= max77843_charger.o
obj-$(CONFIG_CHARGER_SM5705)	+= sm5705_charger.o sm5705_charger_oper.o
obj-$(CONFIG_CHARGER_S2MU005)   += s2mu005_charger.o
obj-$(CONFIG_CHARGER_SM5703)    += sm5703_charger.o
obj-$(CONFIG_CHARGER_DA9155)    += da9155_charger.o