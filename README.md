# macrosilicon-usb-video-capture-in-ubuntu

Capture cards often have problems in Ubuntu and don't work.
Plug it into your computer and type dmesg to check if its ID is the same as the one specified in the file.

The .rules file must be placed in /etc/udev/rules.d/

After that restart the service with the command


udevadm control --reload-rules
