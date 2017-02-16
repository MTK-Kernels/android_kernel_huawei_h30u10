###MT6582 Kernel-3.4.67 Source for Huawei H30U10
# Building

		# sudo apt-get install ccache
		# sudo gedit ~/.bashrc
Add:

		export USE_CCACHE=1
		export CCACHE_DIR=~/android/.ccache

Build:

		# export ARCH=arm && export ARCH_MTK_PLATFORM=mt6582 && export TARGET_PRODUCT=huawei82_cwet_kk
		# ./mk r k
