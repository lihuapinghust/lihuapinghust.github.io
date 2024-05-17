---
title: Integrate MindTheGapps into AOSP
date: 2024-05-18 01:25:00 +0800
categories: [Tech Inteview Prep]
tags: [Fullstack]
pin: false
---

# Edit .repo/manifests/default.xml

`<remote name="MindTheGapps" fetch="https://gitlab.com/MindTheGapps/" />`

`<project path="vendor/gapps" name="vendor_gapps" remote="MindTheGapps" revision="sigma" />`

# Edit device/oneplus/lemonade/device.mk

`include vendor/gapps/arm64/arm64-vendor.mk`

# Edit device/oneplus/lemonade/BoardConfig.mk

`BUILD_BROKEN_ELF_PREBUILT_PRODUCT_COPY_FILES := true`