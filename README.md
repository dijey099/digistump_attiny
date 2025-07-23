# DigiStump ATTiny

Add the following line into `/etc/udev/rules.d/99-arduino.rules`

```
SUBSYSTEM=="usb", ATTR{idVendor}=="16d0", ATTR{idProduct}=="0753", MODE="0660", GROUP="dialout"
```
