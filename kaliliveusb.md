### Boot into kali Live Persistance

Open kali terminal and then type ```fdisk -l```

then find for your usb drive and see its name like ```/dev/sd?```

after that type

```mkdir -p /mnt/iamnull```

```mount /dev/sdb2 /mnt/iamnull```

```echo "/ union" > /mnt/iamnull/persistence.conf```
