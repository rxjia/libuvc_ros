sudo cp udev/99-uvc.rules /etc/udev/rules.d/
sudo udevadm control --reload
sudo udevadm trigger