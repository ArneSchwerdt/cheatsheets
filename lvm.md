```
lvs
```

```
lvdisplay
```

```
lvcreate -n data -L<size in GiByte>G <volumegroup>
lvcreate -n data -l<size of total space on volumegroup in procentage>%VG <volumegroup>
lvcreate -n data -l<size in free space on volumegroup in procentage>%FREE <volumegroup>
```

```
lvcreate -l|L <size> -s -n <name of snapshot> <snapshot target, logicalvolume>
```