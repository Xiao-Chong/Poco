Poco build Script
=================

Simple build script for Poco C++ library. Supports build for Android, iOS and Mac OS.

Usage:

	build.sh pocoVer iOS_Ver (ALL|Mobile|iOS|Android|MacOS) [CLEAN|CLEAN-ONLY]
		e.g ./build.sh 1.4.6p 6.1 Mobile CLEAN 
		
	The output in build/

Important:
	
	Depends on Xcode's build system(see Platform/iOS/build_ios.sh) and Android's NDK ( you can add a standalone toolchain like the one in Platform/Android/toolchain/bin to your PATH).