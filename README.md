FamigoROM
==========
Getting Started
---------------

To get started with FamigoROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Setup build environmnet - http://forum.xda-developers.com/showthread.php?t=2224142

To initialize your local repository using the PAC-man trees, use a command like this:

    repo init -u git://github.com/FamigoROM/manifest.git -b pac-4.4

Then to sync up:

    repo sync

Then to build:

    ./build-pac.sh <device_name>
