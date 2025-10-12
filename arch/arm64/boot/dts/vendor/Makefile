vendor := $(srctree)/$(src)
ifeq ($(strip $(CONFIG_CHG_FOR_OP9_PRO)), y)
        subdir-y += oplus/lemonadev
else ifeq ($(strip $(CONFIG_OPLUS_CHG_OP9RT_PMIC_VOOCPHY)), y)
        subdir-y += oplus/martini
else
	subdir-y += oplus/porsche

endif
