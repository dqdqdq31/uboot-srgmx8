#
# Copyright 2020 LYD Inc.
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += srg_mx8mm.o

ifdef CONFIG_SPL_BUILD
obj-y += spl.o
obj-y += lpddr4_timing.o
else
obj-y += mmc.o
endif
