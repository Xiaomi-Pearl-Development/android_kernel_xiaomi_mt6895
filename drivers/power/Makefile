# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_POWER_RESET)	+= reset/
obj-$(CONFIG_POWER_SUPPLY)	+= supply/
obj-$(CONFIG_XM_POWER)         += xm_power/
obj-$(CONFIG_XM_POWER_DEBUG)   += xm_power_debug/
ifeq ($(CONFIG_BUILD_PRODUCT_NAME),"plato")
obj-y += xm_charge/
endif
