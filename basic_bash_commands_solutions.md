**Exercise 1**

ceyhunklc0@ceyhunklc0-virtualbox:~$ cd ~
ceyhunklc0@ceyhunklc0-virtualbox:~$ ls -l
total 32
drwxrwxr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:55 Desktop
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Documents
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Downloads
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Music
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Pictures
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Public
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Templates
drwxr-xr-x 2 ceyhunklc0 ceyhunklc0 4096 sty 22 14:30 Videos

**exercise 2***
ceyhunklc0@ceyhunklc0-virtualbox:~$ sudo du -h /var/log/* | sort -h
[sudo] password for ceyhunklc0: 
Sorry, try again.
[sudo] password for ceyhunklc0: 
0       /var/log/apport.log
0       /var/log/btmp
0       /var/log/faillog
0       /var/log/lastlog
0       /var/log/README
0       /var/log/sddm.log
4,0K    /var/log/cups-browsed
4,0K    /var/log/dist-upgrade
4,0K    /var/log/gpu-manager.log
4,0K    /var/log/hp/tmp
4,0K    /var/log/openvpn
4,0K    /var/log/private
4,0K    /var/log/speech-dispatcher
4,0K    /var/log/unattended-upgrades
4,0K    /var/log/vboxadd-install.log
4,0K    /var/log/vboxadd-setup.log
4,0K    /var/log/vboxadd-setup.log.1
4,0K    /var/log/vboxadd-setup.log.2
4,0K    /var/log/wtmp
4,0K    /var/log/wvdialconf.log
8,0K    /var/log/cups
8,0K    /var/log/hp
16K     /var/log/dmesg.1.gz
16K     /var/log/fontconfig.log
16K     /var/log/sysstat
20K     /var/log/auth.log
28K     /var/log/Xorg.0.log
32K     /var/log/Xorg.0.log.old
36K     /var/log/boot.log
44K     /var/log/alternatives.log
52K     /var/log/dmesg
52K     /var/log/dmesg.0
116K    /var/log/bootstrap.log
200K    /var/log/apt
360K    /var/log/kern.log
644K    /var/log/installer
696K    /var/log/syslog                                                                                          
1,1M    /var/log/dpkg.log                                                                                        
45M     /var/log/journal                                                                                         
45M     /var/log/journal/4fcc635e52bb4faaab9ba6814d890eab 

**exercise 3 **
                                                                                                                        
ceyhunklc0@ceyhunklc0-virtualbox:~$ nano ceyhun.txt                                                               
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat ceyhun.txt                                                              
ceyhun


**exercise 4 **
ceyhunklc0@ceyhunklc0-virtualbox:~$ echo "Kilic" > Kilic.txt
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat Kilic.txt
Kilic

**exercise 5 **
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat ceyhun.txt Kilic.txt
ceyhun
Kilic

**exercise 6 **
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat Kilic.txt >> ceyhun.txt
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat ceyhun.txt
ceyhun
Kilic

**exercise 7 **
ceyhunklc0@ceyhunklc0-virtualbox:~$ ls -d ~/*/ > folder_list.txt
ceyhunklc0@ceyhunklc0-virtualbox:~$ cat folder_list.txt
/home/ceyhunklc0/Desktop/
/home/ceyhunklc0/Documents/
/home/ceyhunklc0/Downloads/
/home/ceyhunklc0/Music/
/home/ceyhunklc0/Pictures/
/home/ceyhunklc0/Public/
/home/ceyhunklc0/snap/
/home/ceyhunklc0/Templates/
/home/ceyhunklc0/Videos/



