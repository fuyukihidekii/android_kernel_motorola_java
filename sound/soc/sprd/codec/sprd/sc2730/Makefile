#SPRD CODEC

SPRD_SOUND_TREE := sound/soc/sprd/
ccflags-y += -I$(SPRD_SOUND_TREE)/codec/sprd

ifeq ($(MOTO_FACTORY_SUPPORT),true)
ccflags-y += -DCONFIG_MOTO_FACTORY
endif

snd-soc-sprd-codec-sc2730-objs   := sprd-codec.o sprd-audio-power.o  sprd-headset-sc2730.o
obj-$(CONFIG_SND_SOC_SPRD_CODEC_SC2730)        += snd-soc-sprd-codec-sc2730.o
