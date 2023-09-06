# LinuxPracticeProject ___Armstrong___
# File manipulation
## 1. Sudo command
sudo : superuser do performs tasks requiring administartive or root permissions
```
sudo apt upgrade
```
![sudo apt](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/f617f391-e1f9-44d1-b7d7-6a3dffac3668)


## pwd command
this commands finds the path of current working directory
```
pwd
```
environment variable content including symbolic links
```
pwd -l
```
actual path of the current directory
```
pwd -p
```
![pwd](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/8f73ee90-a486-4ff3-bfcc-560a2725b4d4)

## cd command
navigates through the linus files and directories
requies directory name 
```
cd DevOps_folder
```
or full path
```
cd DevOps_folder/liwox
```
moves up one directory
```
cd ..
```
moves to previous directory
```
cd -
```
moves to another user
```
cd ~ username
```
![cd](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/688b6236-e86c-46cd-84e7-07017b5b834d)

## ls command
this command lists files and directories within a system
```
ls DevOps_folder
```
lists all files in a subdirectory
```
ls -R
```
![ls](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/bafb2267-b322-4eb2-936b-110fb8129347)
shows hidden files
```
ls -a
```
shows file sizes
```
ls -lh
```
![ls lh](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/6fad9fb8-7716-4326-bd58-f5f4d93d78fa)

## cat command
this command lists, combines and writes file content to the standard output
Concatenate.
```
cat DevOps
```
![cat](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/d57b01fb-a31f-4f0f-864c-d5c733c32314)

display files in reverse order
```
tac DevOps
```
![tac](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/2f9d2292-04d4-41a1-ba92-854c90da147a)
merges two files into a third file
```
cat
```
## cp command
this command copies files, directories and the content of directories
```
cp test_file DevOps_folder/liwox
```
![cp](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/db3c6008-484f-4369-8c02-062a4cf7d3bb)
copies an entire directory
```
cp -R Desktop DevOps_folder/liwox
```
![cp R](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/b16070f4-6619-4c91-b2ea-b92772a766b4)

 ## mv command
this command moves and renames files and directories
 ```
mv test_file Documents
```
![mv](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/98900a65-9fab-445f-a470-ce2d4b2c4b8f)
renames a files
```
mv DevOps devops
```
![mv rename](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/87fb0b63-fecf-43b9-bcd6-4884b0f9f063)

## mkdir command
this command creates one of more directories
```
mkdir james
```
![mkdir](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/b302c3e5-82b8-4d79-839e-463ee943ef0b)
creates subdirectory
```
mkdir james/songe
```
![mkdir songe](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/1862dd5f-8be4-4b60-a754-fd4116f83978)
create directory in between two directories
```
mkdir -p james/20/songe
```
![mkdir p](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/b7e8fbe8-22eb-462d-afe1-f3b7aa8762d7)

## rmdir command
this command deletes an empty directory
```
rmdir songe
```
![rmdir](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/c0462837-c2ad-4b0d-89fa-072b8b630265)
remove multiple files
```
rmdir 20 songe
```
![rm 1](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/9c9b2557-c17a-4610-9c64-9270f50aed47)
![rm 2](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/0a8fdc65-89ad-44db-956e-c52cfc6708e6)


## touch command
this command creates an empty file
```
touch liwox.html
```
![touch](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/916c1446-7ec5-4051-9024-c86338e25dc5)
![touch 2](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/58334dd5-a7b2-4ad6-a134-129f0ef4affb)

## locate command
>this command finds a file in the datbase system
```
locate
```
![locate](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/5402fe0e-7bb4-4517-89e3-f9f63a142d01)
>command can not be found

## find command
>this command will search for files within a specific directory
```
find james/ liwox.html
```
![find](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/8dfd9a4e-bde8-4863-b6bc-19c650b28911)

## grep command
>this command finds a word by searching through all the text in a particuar file
```
grep blue liwox.html
```
![grep](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/00b8e1ad-7054-4dcf-82d1-4fdadf86d2f0)

## df command
>this command will report the system disk space usage in percentage and kilobyte
```
df
```
```
df -m
```
![df](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/882b89e2-ffaa-41d3-bf7c-1970398c976f)
```
df -k
```
```
df -T
```
```
df -h
```
![df t](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/5276d262-2324-4a50-a349-e90e07daab8b)

## du command
>this command will check how much disk space a file of directory will takes up
>it can also identify which part of the system uses the storage excessively.
```
du DevOps_folder/liwox/Desktop/Liwox_champ
```
![du](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/818cb167-167a-43f5-86dc-8cf544a742f9)

## head command
>this command allows you to view the first ten lines in a text
```
head test.txt
```
![head](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/f0d5e4c1-2877-47f6-b951-082e9543885e)
>specify the number of lines to display
```
head -n5 test.txt
```
![head n](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/6c742ec4-d22f-4bbb-a73c-3af87cd422a8)
## tail command
>this command displays the last ten lines of a text.
```
tail test.txt
```
>specify how many lines to view
```
tail -n5 test.txt
```
![tail](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/f39425e0-8148-49a5-a25d-75c4fc4f19ce)

## diff command
>this command is used to compare two contents of a text line by line, and then display the parts that do not match
```
diff liwox.html test.txt
```
![diff](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/527e5048-004b-4566-99fd-a519b9bb0323)
```
diff -c liwox.html test.txt
```
![diff c](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/5fb22e3f-4d89-4052-8c96-846c01b452aa)
```
diff -u liwox.html test.txt
```
![diff u](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/d42efab1-69c1-4b13-8be4-286711f1ce6d)

## tar command
```
tar -cvf newarchive.tar /home/ubuntu
```
>this command achives multiple files into a Tar file
![tar](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/dec4df88-6ca7-47e2-86d2-71e446e7cb21)

# FILE PERMISSION AND OWNERSHIP

## chmod command
>this command changes a file of directory's read, write or execute permissions.
```
chmod 777 test.txt
```
![chmod](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/0ca9acc0-3aa0-4374-b80c-66970faa04c7)

## chown command
>this command will allow you to change the ownership of a file or directory
```
chown vboxuser test.txt
```
![chown](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/fb8aab83-8bc9-4822-8ac6-0b3b17f3b143)

## job command
>this command displays all the running processes along with their statuses.
```
job jobID
```
![job](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/6bcd43d9-fced-42ca-a19c-7626b9af478a)

## kill command
>this command will terminate an unresponsive program manually.
>first identify the PID (program identification number)
```
ps ux
```
![kill ps](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/69427983-2370-4a63-a620-a6bf2191490b)

```
kill SIGKILL 1689
```
![kill sig](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/14028f66-7a59-46a6-a299-dee09c724f21)

## ping command
>this command will check whether a network or server is reachable.
```
ping google.com
```
```
ping RemoteServer
```
![ping](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/3e840cfe-6f1b-45b8-b93b-0415d79cdb3c)

## wget command
>this command lets you download things from the internet using the wget command
```
wget wordpress.org/latest.zip
```
![wget](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/497b4388-de2b-47b9-a41d-9c296a83b00e)

## uname command
>this command will print detailed information about your liinux system and hardware.
```
uname -a
```
```
uname -s
```
```
uname -n
```
![uname](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/7e8b232c-b69e-4983-b063-4c714b873a4b)

## top
>this command will display all the running processes and a dynamic real time view of the current system
```
top
```
![top](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/9bca20b1-78d1-41dc-b010-c7adb71ebf6e)

## history command
>this command will list 500 of previously executed commands allowing you to reuse them without retyping
```
history
```
![history](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/149cf194-d0f6-48c8-a882-b3c8ac2112e6)

## man command
>this command will provide the user manual of any command or utilities you can run in the terminal including name, description and options.
```
man ls
```
```
man 2ls
```
![man ls](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/e76347c2-375c-4e13-a009-96be728bda06)
![man 2ls](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/93f4ee9b-4d68-4531-b78e-a362a8087761)

## echo command
>this command is a built in utility that displays a line of text or string using the standard output.
```
echo -e devops
```
```
echo \a devops
```
```
echo -n devops
```
![echo](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/fd7a1c10-e1f8-4045-bd53-4b206dccb663)

## zip, unzip command
>this command will compress files and directories into a zip file, to archive or reduce disk space usage.
```
zip first.zip test.txt devops
```
![zip](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/0d48ae98-ebba-44e3-98f2-ef225c9ee993)
```
unzip first.zip
```
![unzip](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/028f7efc-8d1d-42d9-8a32-73db18b41f9b)

## hostname command
>this command will show the system's hostname or ip address
```
hostname
```
```
hostname -i
```
```
hostname -A
```
```
hostname -alias
```
![hostname](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/b8eeb467-aadd-4c18-b9c9-df10aa3607e0)

## useradd, userdel commands
>the useradd command will create a new account
>the passwd command allows you to add a password
```
useradd liwox
```
![useradd](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/7947f7fb-c1c7-4013-a9da-ebefb63b2a35)

## apt-get command
>this command handles advanced package tools (APT) in Linux.
>it lets you retrive information and bundles from authenticated sources.
```
apt-get update
```
![apt-get](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/01e2a2d2-905e-4d34-ba69-715aeb205dce)

## nano, vi, jed commands
>the nano command denotes keywords
```
nano liwox.html
```
![nano](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/452509c7-aeb6-4559-9448-6900f8ccf8fb)
>the vi command works in two modes
 >insert and command: this can edit and create a text file
 >perform operations such as copying, saving, openig and pasting a file.
```
vi liwox.html
```
![vi](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/bb0ccc95-73a0-4ef1-be59-eaad6e9697d7)
>the jed has a dropdown interface that allows users to perform tasks without entering keyboard combinations or commands.
```
jed liwox.html
```
![jed](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/825bb395-42e2-42d4-bf8a-7b83af09f84d)

## alias, unalias command
> this command allows you to create a shortcut with the same functionality as a command, file name or text.
```
alias dv='devops'
```
> the unalias command deletes an existing alias
```
unalias dv
```
![alias](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/589b188e-61da-472d-9096-c00df3b35971)

## su command
>the su command allows you to run a program as a different user. it is beneficial for accessing the system through SSH or GUI display when root user is unavailable.
```
su
```
![su](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/8ac50819-ff2a-450e-9d74-34022fa483b6)

## htop command
>this command monitors system resources and server processes
>htop command has additional features and improvements than the top command
```
htop -d
```
```
htop -C
```
```
htop -h
```
![htop](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/f29429ea-b61d-48f9-be13-f5a9b128b072)
![htop 2](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/8938c292-173d-4153-9d27-c9504c16274e)

## ps command
>this command produces a snapshot of all the processes on your system.
```
ps -T
```
```
ps -u
```
```
ps -A
```
```
ps -e
```
![ps](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/6ae7b893-991d-44b0-848f-963d1077fd8d)


# THANK YOU
