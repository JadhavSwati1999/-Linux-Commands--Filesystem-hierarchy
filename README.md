# Linux-Commands--Filesystem-hierarchy.
Linux Basic commands and Filesystem hierarchy.
# 19 Directories & Basic Commands.



# Basic Commands.

1. **pwd** - print/present working directory.
2. **ls(list in series)** - list a file &directory 
3. **ls -a**  to see hidden(.) files
4. **ll(long list) ls** **- ltr** shows in detail
5. **date** -current date ,time, year, seonds
6. **date -s**  used for date set 
7. **cal**  used to view current month calender
8. $echo shell used to view the current shell type.

**cal -s**  Displays sunday as the first day of the week

**cal -m** Displays monday

**cal -J**  Displays Julian dates

**cal  -y** Displays a calender for the year 

**cal  -3** to view 3 months calender (previous,current,next)

1. **lsusb** -usb related information
2. **lspci**  - pheripheral connected device information
3. **clear** - to clear /clean the screen
4. **history** - to see the previous command history
5. **tty** - terminal command information 
6. **man** - to get detailed information of a command it is well structured
7. **free** -storage is visible

**free -h**  the storage is shown in human readable format 

1. **whoami** - to see user
2. **uname** - name of the operating system i.e kernel information.

**uname -v**  to known the version of the kernel 

**uname -a**  all information about the kernel

1. **passwd** -to change the passwd
2. **w** - which user is logged in 
3. **dmidecode** - complete information about system 

**dmidecode| less**  basically less is used to read the file

20.**who** - user & its time

21**.whatis** it provides one line information

22**.echo** - prints message on terminal & also used for file creation 

23.**rm - -help** to known the rm related information 

**rm -rf  r** means recursive which first deletes the last file & then deletes last file and then delete one by one .

**f** means forcefully

**v** verbose → which shows the process of the recursive deletion

**rm -rvf** 

**ex : dir1/dir2/dir3/dir4/file1 —> it will first delete the file1 →dir4 →dir3 →dir2 →dir1**

24.**du** - displays the folder size 

1. **df -hT** - displays storage related information
2. **info** - in a descriptive way( very much in detail)
3. **top -** used to see current running process 
4. **diff filename** - used to find out the difference between two files 
5. **tac  filename** - used to reverse the content of the file 

 


# Directories (Filesystem hierarchy)

**/root**  -  it is the top level directory in linux hierarchy. All other directories are subdirectory of root.

**/bin**  -   it contains essential binary executable , basically used for basic system functionality. They are used to change the system booting and functionality.

**/boot**  - this contains files needed for systems boot process such as kernel and boot loader.

**/dev** -  it contains devices files & provides interface for interaction .

**/etc** - this contains configuration file that consist of various aspect of system, application and services .

**/home**  - it contains local users home directory .

**/lib** - it contains 34 bit library files.

**/lib64**  - 64 bit shared library files.

**/media**  -  it is used as a mounting point for removable are such as usb devices.

**/mnt**  -  it is used as a temporary mounting point.

**/opt**  -  it is the most installed third party software.

**/proc**  - this provides information about currently running software 

**/sbin** - it contains system admin binary executable typically used by root user.

**/temp** - it is used for temporary used file ,which may be deleted at power off .

**/usr**  - it contains user related files like libraries, binary file etc

**/var**  -  variable data file 

**/srv**  -  service contains service related data

**/run**  -  temporary file system , holding data for process since last boot.

**/sys**  -  virtual file system which provides information about device , drives & kernel parameters.
