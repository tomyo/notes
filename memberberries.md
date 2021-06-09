
## Sync machine clock with internet

https://www.tecmint.com/synchronize-time-with-ntp-in-linux/

``` sh
pacman -S chrony
systemctl enable --now chronyd
systemctl status chronyd
```

### Fix old Asus monitor hdmi zoom with xrand

`xrandr --output LVDS1 --off --output HDMI1 --set audio force-dvi`
