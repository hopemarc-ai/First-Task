# First-Task
performing my first task 

                      Create a directory called my_project inside the home folder.                                                     
┌──(hope247㉿kali)-[~/First-Task]
└─$ mkdir My_project                    
                                                                           
┌──(hope247㉿kali)-[~/First-Task]
└─$ cd My_project 
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ touch file1.txt file2.txt file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls
file1.txt  file2.txt  file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ echo 

                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ echo "Hello World" >file1.txt 
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cat file1.txt 
Hello World
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ touch file1_backup.txt             
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls
file1_backup.txt  file1.txt  file2.txt  file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cp file1.txt file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls
file1_backup.txt  file1.txt  file2.txt  file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la
total 16
drwxrwxr-x 2 hope247 hope247 4096 Feb 17 13:59 .
drwxrwxr-x 4 hope247 hope247 4096 Feb 17 13:46 ..
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 14:01 file1_backup.txt
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 13:57 file1.txt
-rw-rw-r-- 1 hope247 hope247    0 Feb 17 13:50 file2.txt
-rw-rw-r-- 1 hope247 hope247    0 Feb 17 13:50 file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ mkdir Backup     
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls    
Backup  file1_backup.txt  file1.txt  file2.txt  file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ mv file2.txt Backup
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la
total 20
drwxrwxr-x 3 hope247 hope247 4096 Feb 17 14:10 .
drwxrwxr-x 4 hope247 hope247 4096 Feb 17 13:46 ..
drwxrwxr-x 2 hope247 hope247 4096 Feb 17 14:10 Backup
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 14:01 file1_backup.txt
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 13:57 file1.txt
-rw-rw-r-- 1 hope247 hope247    0 Feb 17 13:50 file3.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cd Backup                    
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project/Backup]
└─$ ls    
file2.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project/Backup]
└─$ chmod -u+rw file1.txt
chmod: cannot access 'file1.txt': No such file or directory
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project/Backup]
└─$ cd ..                
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod -u+rw file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod -u+rw file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cat file1_backup.txt        
Hello World
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ world file4.txt                       
world: command not found
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ world >file4.txt
world: command not found
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls
Backup  file1_backup.txt  file1.txt  file3.txt  file4.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cat file4.txt       
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la                      
total 20
drwxrwxr-x 3 hope247 hope247 4096 Feb 17 14:53 .
drwxrwxr-x 4 hope247 hope247 4096 Feb 17 13:46 ..
drwxrwxr-x 2 hope247 hope247 4096 Feb 17 14:10 Backup
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 14:01 file1_backup.txt
-rw-rw-r-- 1 hope247 hope247   12 Feb 17 13:57 file1.txt
-rw-rw-r-- 1 hope247 hope247    0 Feb 17 13:50 file3.txt
-rw-rw-r-- 1 hope247 hope247    0 Feb 17 14:53 file4.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
-rw-rw-r-- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod -r file1.txt          
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
--w--w---- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod -w file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
---------- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod o+r         
chmod: missing operand after ‘o+r’
Try 'chmod --help' for more information.
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod o+r file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
-------r-- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod g+r file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
----r--r-- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod u+r file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
-r--r--r-- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chmod u+w file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1.txt
-rw-r--r-- 1 hope247 hope247 12 Feb 17 13:57 file1.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chown hopemarc file1.txt
chown: invalid user: ‘hopemarc’
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chown hope247@kali             
chown: missing operand after ‘hope247@kali’
Try 'chown --help' for more information.
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ chown hope247 file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1_backup.txt
-rw-rw-r-- 1 hope247 hope247 12 Feb 17 14:01 file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ sudo adduser fresh                             
[sudo] password for hope247: 
New password: 
Retype new password: 
passwd: password updated successfully
Changing the user information for fresh
Enter the new value, or press ENTER for the default
        Full Name []: 
        Room Number []: 
        Work Phone []: 
        Home Phone []: 
        Other []: 
Is the information correct? [Y/n] y
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ id                     
uid=1000(hope247) gid=1000(hope247) groups=1000(hope247),4(adm),20(dialout),24(cdrom),25(floppy),27(sudo),29(audio),30(dip),44(video),46(plugdev),100(users),101(netdev),103(scanner),116(bluetooth),121(lpadmin),124(wireshark),132(vboxsf),133(kaboxer)
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ sudo chown fresh file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1_backup.txt
-rw-rw-r-- 1 fresh hope247 12 Feb 17 14:01 file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cat /etc/passwd               
root:x:0:0:root:/root:/usr/bin/zsh
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/run/ircd:/usr/sbin/nologin
_apt:x:42:65534::/nonexistent:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
systemd-network:x:998:998:systemd Network Management:/:/usr/sbin/nologin
dhcpcd:x:100:65534:DHCP Client Daemon:/usr/lib/dhcpcd:/bin/false
mysql:x:101:102:MariaDB Server:/nonexistent:/bin/false
tss:x:102:104:TPM software stack:/var/lib/tpm:/bin/false
strongswan:x:103:65534::/var/lib/strongswan:/usr/sbin/nologin
systemd-timesync:x:991:991:systemd Time Synchronization:/:/usr/sbin/nologin
_gophish:x:104:106::/var/lib/gophish:/usr/sbin/nologin
iodine:x:105:65534::/run/iodine:/usr/sbin/nologin
messagebus:x:990:990:System Message Bus:/nonexistent:/usr/sbin/nologin
tcpdump:x:106:107::/nonexistent:/usr/sbin/nologin
miredo:x:107:65534::/var/run/miredo:/usr/sbin/nologin
_rpc:x:108:65534::/run/rpcbind:/usr/sbin/nologin
redis:x:109:110::/var/lib/redis:/usr/sbin/nologin
mosquitto:x:110:113::/var/lib/mosquitto:/usr/sbin/nologin
redsocks:x:111:114::/var/run/redsocks:/usr/sbin/nologin
stunnel4:x:989:989:stunnel service system account:/var/run/stunnel4:/usr/sbin/nologin
sshd:x:988:65534:sshd user:/run/sshd:/usr/sbin/nologin
dnsmasq:x:999:65534:dnsmasq:/var/lib/misc:/usr/sbin/nologin
Debian-snmp:x:112:115::/var/lib/snmp:/bin/false
sslh:x:113:117::/nonexistent:/usr/sbin/nologin
postgres:x:114:118:PostgreSQL administrator:/var/lib/postgresql:/bin/bash
avahi:x:115:119:Avahi mDNS daemon:/run/avahi-daemon:/usr/sbin/nologin
speech-dispatcher:x:116:29:Speech Dispatcher:/run/speech-dispatcher:/bin/false
_gvm:x:117:120::/var/lib/openvas:/usr/sbin/nologin
usbmux:x:118:46:usbmux daemon:/var/lib/usbmux:/usr/sbin/nologin
cups-pk-helper:x:119:121:user for cups-pk-helper service:/nonexistent:/usr/sbin/nologin
nm-openvpn:x:120:122:NetworkManager OpenVPN:/var/lib/openvpn/chroot:/usr/sbin/nologin
inetsim:x:121:123::/var/lib/inetsim:/usr/sbin/nologin
pipewire:x:986:986:system user for pipewire:/nonexistent:/usr/sbin/nologin
nm-openconnect:x:122:125:NetworkManager OpenConnect plugin:/var/lib/NetworkManager:/usr/sbin/nologin
geoclue:x:123:126::/var/lib/geoclue:/usr/sbin/nologin
lightdm:x:124:127:Light Display Manager:/var/lib/lightdm:/bin/false
statd:x:125:65534::/var/lib/nfs:/usr/sbin/nologin
saned:x:126:128::/var/lib/saned:/usr/sbin/nologin
polkitd:x:985:985:User for polkitd:/:/usr/sbin/nologin
rtkit:x:127:129:RealtimeKit:/proc:/usr/sbin/nologin
colord:x:128:130:colord colour management daemon:/var/lib/colord:/usr/sbin/nologin
hope247:x:1000:1000:Hope247,,,:/home/hope247:/usr/bin/zsh
fresh:x:1001:1001:,,,:/home/fresh:/bin/bash
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ 
