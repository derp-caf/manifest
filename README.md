# manifest
Initializing the repo:
repo init -u git://github.com/derp-caf/manifest.git -b p -m default.xml

For Syncing:
repo sync -f -c -j8 --force-sync --no-tags --no-clone-bundle

For Compiling:
. build/envsetup.sh
lunch derp_devicecodename-userdebug
mka derp
