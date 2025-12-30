Task:
Mount a new disk permanently on /data

Scenario:
- Checked available disks using lsblk
- Created filesystem using mkfs.ext4
- Created mount directory /data
- Mounted the disk 
- Added entry in /etc/fstab

Commands Used:
lsblk
mkfs.ext4
mount
df -h
vim /etc/fstab

Result:
Disk mounted successfully and persists after reboot.
