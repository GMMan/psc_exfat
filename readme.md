exFAT Loader for PlayStation Classic
====================================

This package will mount an exFAT filesystem on the second partition of the drive
you install the package on.

Security Notice
---------------
Because anyone can sign a valid update package, please make sure that what you
download is an original version. Otherwise, you may run malicious software that
could damage the software on your console.

A SHA-1 hash will be provided for each release. To check the version of the
release you downloaded, look inside the `diag` file inside the folder in the
download package.

Usage
-----
1. Partition your USB storage device into two partitions. The first partition
   can be relatively small, since this is only used for the loader. The second
   can fill up the rest of the drive.
2. Format the partitions. Format the first parition with FAT32 so the PlayStation
   Classic can read it, and set its volume label to `SONYXF`. Format the second
   partition with exFAT.
3. Extract the release archive into the root of the FAT32 partition.
4. Set up the exFAT partition as normal. Note you do not need to copy over lolhack's
   LUPDATA.BIN, but do copy over lolhack/lolhack.sh if you're using it.
5. Use USB drive on PlayStation Classic as normal.

Credits
-------
exfat-fuse from [Debian Stretch](https://packages.debian.org/stretch/exfat-fuse)
