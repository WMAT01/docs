# Filesystems

helloSystem uses the OpenZFS for the boot disk.

Additionally, the following filesystems are supported in helloSystem, but it cannot be started from those:

* exFAT (Windows)
* NTFS (Windows; read-write support)
* EXT4 (Linux)
* HFS+ (Macintosh)
* XFS (SGI)
* MTP (Android)

Supported filesystems are automatically mounted by [automount](https://github.com/vermaden/automount).

To see how they are mounted, open the Logs utility and attach a disk.