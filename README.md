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
