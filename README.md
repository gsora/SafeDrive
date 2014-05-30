# SafeDrive
## *Create and manage a virtual encrypted drive on Linux with ease*

*TrueCrypt? Tsk, we have dm-crypt*
With SafeDrive you'll be able to create encrypted disk images thanks to the native encryption system inside the Linux kernel.

### Create a drive

	# ./createSafeDrive

### Mount a drive
	
	# ./mountcrypt yourfile mountpoint

### Unmount a drive
	
	# ./umountcrypt yourfile mountpoint

If invoked without any argument `mountcrypt` and `umountcrypt` will print a list containing all the encrypted virtual drive available for mounting/unmounting.
Be sure to have `cryptsetup` in your $PATH.
