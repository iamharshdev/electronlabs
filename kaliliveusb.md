### Create Bootable using Linux

1.type ```lsblk``` and look for your usb size and you will see something like dev/sdb

2.type ```sudo dd if=path-to-your-iso of=/dev/sdb or pathtoyourusb bs=512K status=progress```

3.type ```reboot```

### Boot into kali Live Persistance

Open kali terminal and then type ```fdisk -l```

then find for your usb drive and see its name like ```/dev/sd?```

after that type

```mkdir -p /mnt/iamnull```

```mount /dev/sdb2 /mnt/iamnull```

```echo "/ union" > /mnt/iamnull/persistence.conf```
