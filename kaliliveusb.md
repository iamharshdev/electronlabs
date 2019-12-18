### Boot into kali Live Persistance

Open kali terminal and then type ```lsblk```

then find for your usb drive and see its name like ```/dev/sd?```

after that type

```mkdir -p /mnt/fuckyou```

```mount /dev/sd? /mnt/fuckyou```

```echo "/ union" > /mnt/fuckyou/persistance.conf```
