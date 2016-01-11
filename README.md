# raspberry-configuration
Completely automatize raspberry pi configuration by launching commands from any computer. It handles RPI reboot after root FS extension.

## Uses
just `bash raspberry-configuration`. The script will ask you needed data : 
* RPI IP
* New username to create
* New hostname
* SSH port you want to be able to connect with
* Public key to  copy on RPI for further connections
 
It uses [my raspberry configuration script](https://github.com/devgiants/raspberrypi-initialisation-script).

