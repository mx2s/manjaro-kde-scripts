# manjaro-kde-setups

https://wiki.archlinux.org/index.php/Dell_Inspiron_15_(7590)

Disable beep sound
```
sudo echo "blacklist pcspkr" > /etc/modprobe.d/nobeep.conf
```

Wired / WIFI connection not working
```
modprobe r8169
```
