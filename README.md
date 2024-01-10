[<center><img src="https://raw.githubusercontent.com/sourajitk/STX-Logo/main/stx-2021-kernel.png" height="50%" width="50%;" /></center>](https://github.com/StatiXOS)

## Repo Init ##
```bash
repo init -u https://github.com/TelegramAt25/android_kernel_manifest.git -b android-mtk-selene-4.14-android11 --git-lfs
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags
```
## Building Kernel ##
```bash
BUILD_CONFIG=kernel/xiaomi/selene/build.config.selene build/build.sh
```
### Submitting Patches ###
Please refer to this for submitting patches: https://github.com/StatiXOS/android_manifest#submitting-patches
