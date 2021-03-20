# File System

Please only the command line to execute the following exercises.

## List resources

1.  Show the disks of the VM and their sizes.
2.  List the total inodes of the root partition.
3.  Count all open file handles.
4.  List file descriptors in Kernel memory.

## Increase Disk Size

The VM you have deployed with Vagrant has a virtual hard drive configured with the Logical Volume Manager (LVM), we require you to perform the following operations:

1.  Execute commands in the shell to list the Physical Volumes, Volume Groups and Logical Volumes.
2.  Add a new disk to the VM with any size.
3.  Create a new Physical Volume.
4.  Add the new Physical volume to the existing Volume Group.
5.  Increase the current volume group to the full size of the new disk.
6.  Update the Operative System configuration to reflect the new size of the virtual disk.
