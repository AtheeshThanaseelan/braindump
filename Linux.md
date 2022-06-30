## Modifying special files
echo {value} | sudo tee {file}

## Enabling USB power during sleep
Run lsusb to find the USB bus
Set enabled: /sys/bus/usb/devices/usb1/power/wakeup

## Change brightness
/sys/class/backlight/intel_backlight
Check max_brightness
Set brightness

## Mousepad Right Click
gnome-tweaks > mouse > emulation > area

## Gnome Animations
gnome-extensions > impatience
