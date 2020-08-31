
In the first step you could raid your physical disks e.g in raid level 1 to secure your data against a disk damage.
```
mdadm --create /dev/md/<label> --level=<number(raid level)> --raid-devices=<amount of physical devices> <device1> <device2> ...
```

Partition the raid, you need at least boot and crypt partition because the boot partition must not be encrypted.
```
cfdisk /dev/md/<label>
```

