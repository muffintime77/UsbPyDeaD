# usbpydead

using: 
sudo ./usbpydead <argument>

upt - add new devices to wite list (not deleting old devices, legasy at "hot-plug")
stopped and starting service in the writed mode (startcon, startext, startsll. anything - no autoruning) 
regen - create new white list (stopping and rewrite dev.list only pluged devices)
startcon - start daemon in connect undefined devices mode
startext - start daemon in extend defined devisec mode
startall - start daemon in combinnate mode (not extending / not connecting)
restart - no coments
stop - stop daemon

first start:
generate new list from device (HID, USB flash, etc.)
./usbpydead new
starting in your mode working
sudo ./usbpydead startcon
profit!

files: 
_.pid - temp file PID to this process not delete!
daemon.py - module demonize for working in background 
dev.list - file defined device. generation from running script at key <new> or update at key <gen>
usbpydead - script
