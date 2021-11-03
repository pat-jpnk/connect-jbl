#!/bin/bash  

MAC="E8_D0_3C_C8_A2_B3"

sudo service bluetooth start

rfkill unblock bluetooth &

dbus-send --system --print-reply --dest=org.bluez /org/bluez/hci0/dev_$MAC org.bluez.Device1.Connect

