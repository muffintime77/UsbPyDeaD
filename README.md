using:

chmod +x usbpydead

sudo ./usbpydead

upt - add new devices to wite list (not deleting old devices, legasy at "hot-plug") 
stopped and starting service in the writed mode (startcon, startext, startsll. anything - no autoruning)

regen - create new white list 
(stopping and rewrite dev.list only pluged devices)

startcon - start daemon in connect undefined devices mode

startext - start daemon in extend defined devisec mode

startall - start daemon in combinnate mode (not extending / not connecting)

restart - no coments

stop - stop daemon

status - status runing the daemon

init - install script in /bin/

rm - remove script and wipe all files 

first start:

install script
sudo ./usbpydead init

enter user for install

generate new list from device (HID, USB flash, etc.)
usbpydead new

starting in your mode working

usbpydead startcon

profit!

