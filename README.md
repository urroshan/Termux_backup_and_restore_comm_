# Termux_backup_and_restore_comm_
Commands for Backup and restore of termux.

To backup :- 
$ cd /data/data/com.termux/files
$ tar -cvzf /sdcard/Download/termux.tgz –owner=0 –group=0 home usr

To Restore :- 
$ cd /data/data/com.termux/files
$ tar -xvzf /sdcard/Download/termux.tgz
