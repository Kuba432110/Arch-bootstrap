# Arch boostrapping script
My script for auto-installing Arch Linux. It provides some level of configurability via variables, but for now it just leaves you with barebones installation. 
## Usage
All you need to do after booting into the CD, is to make the partitions (Only the EFI and root are mandatory, home and swap can be skipped), assign their location to their variables in script and just run it. And remember, it's important that you assign the partitions with their types while creating them, systemd-boot won't install if it doesn't find partition with "EFI system" type.
## Troubleshooting
If you run into any problems during the installation you are on your own. At this moment this script doesn't provide any error logging functionality. If something breaks, you have to figure out what is wrong yourself. Everything should run just fine if you're running standard hardware with UEFI support and you're performing clean installation.
