# manjaro-kde-setups

Related arch wiki: https://wiki.archlinux.org/index.php/Dell_Inspiron_15_(7590)

All notes related to Dell G3 3590 (G315-6769) laptop, keep that in mind

Disable beep sound
```
sudo echo "blacklist pcspkr" > /etc/modprobe.d/nobeep.conf
```

Wired / WIFI connection not working
```
modprobe r8169
```
