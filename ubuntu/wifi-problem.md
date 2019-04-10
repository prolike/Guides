# Wifi-problem

This is a fix I found for the Lenovo Ideapad 530S.

First off run this command in the terminal

`sudo tee /etc/modprobe.d/blacklist-ideapad.conf <<< "blacklist ideapad_laptop"`

then you need to reboot the machine and the wifi should be working!

[source](https://askubuntu.com/questions/1049129/wifi-not-working-on-ubuntu-18-04-lts-lenovo-legion-y520/1049132#1049132)