This repository is for my Xbox Linux kernel shenanigans

The branch this README is in serves no other purpose but to provide information about this repository

The actual kernels are in other branches.

The db-5.6 branch is an Android x86 compatible kernel for the og Xbox. It should in theory work with Android 4.4 and lower
It has been confirmed to work with 2.3.7 in an Xbox emulator (XEMU). It has not been tested on hardware yet.
It is not pure 5.6, it has the Android binder driver from 5.0 transplanted in, and a patch to reenable the 32 bit binder IPC

The linux-5.8 branch is the stock xbox-linux 5.8.1 kernel
