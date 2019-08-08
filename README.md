# Derp-CAF manifest

[![TG chat](https://img.shields.io/badge/Support-Telegram-%23e52c5f.svg?style=for-the-badge&logo=telegram&&labelColor=121217)](https://t.me/DerpGangDiscussions)

# Initializing the repo:
**repo init -u git://github.com/derp-caf/manifest.git -b p -m default.xml**

# Syncing:
**repo sync -c -f -j$( nproc --all ) --no-tags --no-clone-bundle -q**

# For Compiling:
- source build/envsetup.sh
- lunch derp_devicecodename-userdebug
- mka derp
