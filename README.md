# vic3

Initializing Repository

1. ) repo init -u http://github.com/vic3t3chn0/vic3.git -b mm

Sync the tree source code

2. ) repo sync

BUILDING - Can be used for build the source code

After the sync is finished, please read the instructions from the Android site on how to build.

. build/envsetup.sh
lunch


You can also build for specific devices (eg. hammerhead) like this:

. build/envsetup.sh
lunch aokp_togari-userdebug
mka rainbowfarts


Remember to make clobber && make clean every now and so on and on!

