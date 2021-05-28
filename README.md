# ccu3-backup
Backup your CCU3 to a [NFS](https://en.wikipedia.org/wiki/Network_File_System) share.

This is a clone of Jens Maus' [createBackup.sh](https://github.com/jens-maus/RaspberryMatic/blob/master/buildroot-external/overlay/base-raspmatic/bin/createBackup.sh), 
extended with verbose messages for better debugging.

## Usage
### Manual usage
1. Edit [nfs-backup](/nfs-backup) and adjust it to your needs
1. Call `sh nfs-backup`
1. Profit

### Automatic usage via CCU3 Programm
1.  Edit [nfs-backup](/nfs-backup) and adjust it to your need
1.  Follow the Zyklisches speichern instructions from [technikkram.net](https://technikkram.net/blog/2020/02/10/ccu-raspberrymatic-zyklisches-automatisches-backup-auf-synology-nas/), 
    but use your path to `nfs-backup` instead of `/usr/local/addons/backup.sh`

## Bugs & Suggestions

Feel free to use the [issue tracker](/issue).

## License
[Apache License 2.0](/LICENSE)