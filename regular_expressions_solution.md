**exercise 1 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls ~ | grep '^[A-Z]'
Desktop
Documents
Downloads
Kilic.txt
Music
Pictures
Public
Templates
Videos


**exercise 2 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls -A ~ | grep '^\.'
.bash_history
.bash_logout
.bashrc
.cache
.config
.local
.profile
.sudo_as_admin_successful
.vboxclient-clipboard-tty2-control.pid
.vboxclient-clipboard-tty2-service.pid
.vboxclient-draganddrop-tty2-control.pid
.vboxclient-draganddrop-tty2-service.pid
.vboxclient-hostversion-tty2-control.pid
.vboxclient-seamless-tty2-control.pid
.vboxclient-seamless-tty2-service.pid
.vboxclient-vmsvga-session-tty2-control.pid
.vboxclient-vmsvga-session-tty2-service.pid
.xsession-errors


** exercise 3 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls -A ~ | grep '^\. ' | wc -l
0

** exercise 4 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls ~ | grep '^[a-zA-Z]*$'
Desktop
Documents
Downloads
Music
Pictures
Public
snap
Templates
Videos

** exercise 5 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls ~ | grep -v '[A-Z]'
ceyhun.txt
folder_list.txt
snap

** exercise 6 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls ~ | grep -v '\.[a-zA-Z]\{3\}$'
Desktop
Documents
Downloads
Music
Pictures
Public
snap
Templates
Videos

** exercise 7 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls /etc | grep '^c.*y$'
cron.daily
cron.hourly
cron.monthly
cron.weekly
cron.yearly

** exercise 8 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls /etc | grep 'ss'
gss
issue
issue.net
nsswitch.conf
passwd
passwd-
ssh
ssl
sysstat

** exercise 9 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ grep '^.\{1\}[A-Z].\{1\}[A-Z].\{1\}e$'

** exercise 10 **

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls ~ | grep '^[a-zA-Z0-9]\{4\}$'
snap

** exercise 11 ** 

ceyhunklc0@ceyhunklc0-virtualbox:~$ ls /var/log | grep '\.log$'
alternatives.log
apport.log
auth.log
boot.log
bootstrap.log
dpkg.log
fontconfig.log
gpu-manager.log
kern.log
sddm.log
vboxadd-install.log
vboxadd-setup.log
wvdialconf.log
Xorg.0.log


