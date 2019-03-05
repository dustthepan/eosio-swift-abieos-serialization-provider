# EosioSwiftAbieos
A Framework that encapsulates all of the C and C++ code for binary <-> JSON conversion using ABIs. Compatible with languages which can interface to C.

This project now can be used as a cocoapod.  

OpenSSL is pulled in as a Pod dependancy using GRKOpenSSLFramework cocoapod.

A physical framework folder is now incorporated into the project. 

The boost framework must be added to this folder upon checkout from the repository.

To build this project now you must do a pod install, then open the created workspace and build the framework there to confirm that it will compile and create a framework binary.

If you are using Xcode 10 and seeing some warnings when running pod install, it may be necessary to run: `gem update xcodeproj`
