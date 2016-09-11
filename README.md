# libmsys - Patch ms-sys source package to shared library

How to build:

* Download the latest ms-sys from here: http://ms-sys.sourceforge.net/#Download
* Extract tarball and change to ms-sys-x.x.x directory
* Copy 0001-Convert-to-shared-library.patch to ms-sys-x.x.x directory
* Run git apply --check 0001-Convert-to-shared-library.patch and see if any errors show up
* If no errors > git apply 0001-Convert-to-shared-library.patch
* make
* make install

To use library:

* Include libmsys.h
* Build with -lmsys cflag
