# DigiStump ATTiny

1- Add the following line into `/etc/udev/rules.d/99-arduino.rules`

```
SUBSYSTEM=="usb", ATTR{idVendor}=="16d0", ATTR{idProduct}=="0753", MODE="0660", GROUP="dialout"
```

2- Go to `File -> Preferences -> Additional boards manager URLs` and paste the following URL
```
https://raw.githubusercontent.com/dijey099/digistump_attiny/refs/heads/master/package_digistump_index.json
```

3- Go to `Tools -> Board -> Boards Manager` and look for `Digistump AVR Boards` and install it

4- Enjoy :)
