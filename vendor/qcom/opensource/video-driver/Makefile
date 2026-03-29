# SPDX-License-Identifier: GPL-2.0-only

VIDEO_ROOT = $(KERNEL_SRC)/$(M)
KBUILD_OPTIONS+= VIDEO_ROOT=$(VIDEO_ROOT)

VIDEO_COMPILE_TIME = $(shell date)
VIDEO_COMPILE_BY = $(shell whoami | sed 's/\\/\\\\/')
VIDEO_COMPILE_HOST = $(shell uname -n)
