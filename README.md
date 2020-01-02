## Fix time with dualboot
```bash
timedatectl set-local-rtc 1
```

## Setup GRUB for HiDPI screen
```bash
sudo vim /etc/default/grub
GRUB_GFXMODE=640x480
sudo update-grub
```
