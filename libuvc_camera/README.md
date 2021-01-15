# Install
```
sudo cp udev/99-uvc.rules /etc/udev/rules.d/
sudo udevadm control --reload && sudo udevadm trigger
```

# video_format
v4l2-ctl -d /dev/video0 --list-formats-ext

# settings
v4l2-ctl -d /dev/video0 -L 