
Sync machine clock with internet
--------------------------------

https://www.tecmint.com/synchronize-time-with-ntp-in-linux/

``` sh
pacman -S chrony
systemctl enable --now chronyd
systemctl status chronyd
```
