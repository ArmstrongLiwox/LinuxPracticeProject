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
