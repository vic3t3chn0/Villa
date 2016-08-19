[Villa OP Open Project](http://pedrolvicente.wordpress.com)
====================================

Download the Source
===================

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Initiate core trees without any device/kernel/vendor:

    $ repo init -u https://github.com/vic3t3chn0/vic3.git -b mm

Sync the repository:

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    . build/envsetup.sh
    lunch

You can also build for specific devices (eg. Sony Z Ultra) like this:

    . build/envsetup.sh
    lunch aosp_c6833-userdebug
    mka rainbowfarts


Remember to make clobber && make clean every now and so on and on!

