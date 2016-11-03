backup-bash
===========

Real time file syncing daemon using Rsync and Inotify written in Bash 


Change the below variables in the backup file as per your requirement

Directory or file to watch or backup :
backup_dir="/data"

Path to the server to copy changes:
server_backup_dir="user@yourserver.com:/path/to/storebackup"

Path to directory to log errors and events:
log_dir="backuperrors.txt"

Your email id, you will receive an email if the backup succeeded or failed:
email="you@youremail.com"



In case you want to use the init script move the initscript.bash to /etc/init.d/  directory

and change the 
exec="/path/to/executable" to your executable directory


Tutorial on how original author built it is at http://techarena51.com/index.php/inotify-tools-example/
