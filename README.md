# Miui Gallery Editor Magisk Module

## DISCLAIMER
- Miui apps are owned by Xiaomi™.
- The MIT license specified here is for the Magisk Module only, not for Miui apps.

## Descriptions
Gallery Editor app by Xiaomi Inc. ported and integrated as a Magisk Module for all supported and rooted devices with Magisk

## Sources
- https://apkmirror.com com.miui.mediaeditor by Xiaomi Inc.
- libmagiskpolicy.so: Magisk (stable) 30.7 (30700)

## Changelog

v0.4
- Fix video editor auto/templates (Prepare /storage/emulated/"$UID"/Android/data/com.miui.mediaeditor/files directories)
- Update libmagiskpolicy.so from Magisk (stable) 30.7 (30700)
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v0.3
- Modify MiMediaEditor.apk to fix crash
- Using ro.gallery.device and ro.gallery.manufacturer instead of ro.product.device and ro.product.manufacturer

v0.2
- Add Action button to clear app caches
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh
- Fix selinux denials
- Update MiGalleryEditor.apk arm64-v8a v1.10.0.0.6

v0.1
- Initial release

## Screenshots
https://t.me/ryukimodsscreenshots/21

## Requirements
Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs or https://github.com/KernelSU-Modules-Repo/magic_mount_rs or https://github.com/KernelSU-Modules-Repo/hybrid_mount or https://github.com/maxsteeel/nomount first depending on ROM compatibility
- Install Miui Core Magisk Module first if you are in non-Miui ROM: https://github.com/reiryuki/Miui-Core-Magisk-Module
- Install Miui Gallery AI Magisk Module: https://github.com/reiryuki/Miui-Gallery-AI-Magisk-Module
- Download the right module according to your device architecture and Android version:
  - arm64-v8a Minimum SDK 30: https://devuploads.com/5ohs1d9t1vj2
  - arm64-v8a or armeabi-v7a Minimum SDK 26: https://devuploads.com/t9lstufybtnk
- Install the module via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards
- Go to app info of Gallery and Gallery Editor app and allow the network access to be able to download the online features

## Optionals
- https://t.me/ryukinotes/42
- Global: https://t.me/ryukinotes/35

## Troubleshootings
- https://t.me/ryukinotes/19
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


