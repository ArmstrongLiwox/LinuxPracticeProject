# LinuxPracticeProject
# File manipulation
## Sudo command
sudo : superuser do performs tasks requiring administartive or root permissions
```
sudo apt upgrade
```
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

##head command
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
##tail command
>this command displays the last ten lines of a text.
```
tail test.txt
```
>specify how many lines to view
```
tail -n5 test.txt
```
![tail](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/f39425e0-8148-49a5-a25d-75c4fc4f19ce)

##diff command
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

##tar command
```
tar -cvf newarchive.tar /home/ubuntu
```
>this command achives multiple files into a Tar file
![tar](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/dec4df88-6ca7-47e2-86d2-71e446e7cb21)

# LinuxPracticeProject
# File manipulation
## Sudo command
#FILE PERMISSION AND OWNERSHIP

##chmod command

>this command changes a file of directory's read, write or execute permissions.
```
chmod 777 test.txt
```
![chmod](https://github.com/ArmstrongLiwox/LinuxPracticeProject/assets/143335106/0ca9acc0-3aa0-4374-b80c-66970faa04c7)

##
