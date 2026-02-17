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
                                                                           
┌Create a directory called my_project inside the home folder.                                  
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
└─$ sudo chown fresh file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ ls -la file1_backup.txt
-rw-rw-r-- 1 fresh hope247 12 Feb 17 14:01 file1_backup.txt
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ cat /etc/passwd               
root:x:0:0:root:/root:/usr/bin/zsh
hope247:x:1000:1000:Hope247,,,:/home/hope247:/usr/bin/zsh
fresh:x:1001:1001:,,,:/home/fresh:/bin/bash
                                                                           
┌──(hope247㉿kali)-[~/First-Task/My_project]
└─$ 
