Today I learned Linux fundamentals, and it was a super valuable experience for me as an AWS & DevOps Engineer. 🤗 
 I understood how Linux is the backbone of most cloud environments, servers, and container systems like Docker & Kubernetes. It provides a secure, stable, and highly customizable platform, making it essential for automation, troubleshooting, and cloud deployment.
Learning Linux is definitely boosting my confidence in building efficient cloud and DevOps solutions. 🚀
 If you found this helpful, share your thoughts, experiences, or tips in the comments — I’d love to learn from you too! 😊

You can follow and connect with me here:

GitHub:
https://lnkd.in/d2F3JPa3
Dev.to Blog:
https://lnkd.in/dNtgqAME
LinkedIn:
https://lnkd.in/d3NctxFT

#DevOps #AWS #Linux #LearningJourney #CloudComputing #Automation #CareerGrowth #DevOpsEngineer

## Name – Sudarshan Yadav, Contact - 7709877817
## Email Id – sudarshanyadav4080@gmail.com
GitHub: https://github.com/Sudarshanydv
Dev.to Blog: https://dev.to/sudarshan_yadav
LinkedIn: https://www.linkedin.com/in/sudarshan-yadav
Resume (Drive) - https://drive.google.com/file/d/1jas-UeQuCSR6OZCP6pAPTnLiWcJiAVk1/view?usp=drive_link

# Linux Fundamentals And Commands
## 🐧 History of Linux 
Linux was created in 1991 by Linus Torvalds as a free and open-source alternative to UNIX. The first Linux kernel was released publicly, allowing global developers to contribute and improve it. Over time, Linux evolved into a powerful platform used for servers, supercomputers, Android devices, and modern cloud computing systems like AWS.
## 🐧 What is Linux? — Fundamentals
Linux is an open-source, Unix-based operating system widely used in servers, cloud platforms, and DevOps environments. It manages hardware resources and provides a secure, stable, and customizable platform for running applications. Its hierarchical file system and shell interface enable automation and scripting, making Linux essential for cloud and DevOps workflows.

## Pros of Linux
•	Free and open source, reducing operational cost
•	Highly stable and secure for mission-critical systems
•	Best performance for servers and cloud environments
•	Flexible and customizable, supports automation and scripting
•	Large community and enterprise support
## Cons of Linux
•	Learning curve is higher for beginners
•	Software compatibility issues with some commercial apps
•	Requires more manual configuration than Windows
⭐ Why Linux is valuable in AWS DevOps
•	Most AWS compute and container services run on Linux, making it essential for cloud environments.
•	Supports automation, scripting, and CI/CD pipelines for faster and reliable deployments.
•	Provides strong performance, security, and powerful troubleshooting capabilities for production systems.
# *All Usefull Linux Commands*

•	## Colors meaning’s in terminal 
Files – White
Folders – Blue
All permission Granted – Green 
Important Closing Commands
Any editing file close - :q!, ctrl + x - Enter

•	## Package Manager
apt-get : Advanced Package Tools (Debian base pkg mngr)  
yum/dnf : yellowdog updater modified (RPM base pkg mngr)
dpkg : did not finish (Debian base pkg mngr)
rpm : Redhat Package Manager (RPM base pkg mngr)

•	## File System Operation 
ls : list - show files & folders
ls -lt, ls -ltr : files permission and about groups
ls -l : List with detailed information
pwd : Print working directory
cat <filename> : for only reading file
touch <filename> : create empty file
touch file {1..10} : one command create 1 to 10 files
nano <filename> : File create and edit file. Close - ctrl + x - y - enter
vi, vim <filename> : File create an d edit file. Close - esc - :q! - enter
cd : Change current directory
cd .. : Go to Previous Folder
cd ../.. : Go to one time back a 2 Folder
cd /home/paul/desktop/ newfolder/ : absolute path to go
mkdir <foldername> : create folder / directory.
mkdir –p <folder1> / <folder2> : for folder inside folder 
|, &&, ; - execute more then 1 commands
rm : Remove files/directories
rm <filename> : delete file
rm <filename> <filename> <filename> : delete 3 different files.
rmdir <filename> : remove folder / directory
rmdir <filename> <filename>  : multiple remove folder / directory
cp : Copy files/directory
cp mini.csc newfolder/ : copy file to this path
cp mini.csv mini_copy.csv : copy file same folder
mv : Move or rename files
mv newfile newfolder : move / cut paste folder
mv newfile newfiles : rename folder name
less test.csv : search word in file
head -5 test.csv : starting 5 line showing
tail -5 test.csv : ending 5 line showing
sort test.csv : file sort by abcde
split -l 4 sortdemo.txt | uniq : remove duplicate
grep “word” test.csv : search word in file
egrep “ana|shanaya” test.csv : multiple word search
ls x*: x all name search in list 
wc -l <filename> : line count
cmp fileA fileB : check 2 files comparision
diff fileA fileB - 2 files diffrence
diff -u fileA fileB - extra visible 2 file diffrence
find ./ <name> test.csv : find files
updatedb : for update sudo updatedb
locate paul.csv : locate file 
history : show all history
ls --help : for more information about the command 
man ls : manual the command 
bc : use binary calculator
cal : calendar, time, date show
cal 2020 : this year calender
uptime : server how long times to running mode
script : record your activity in terminal
ctrl + d : end script, script done & save file.
gzip -k test.csv : compress file in new file.
gunzip test.csv gz : for unzip file.
tar -czf myfile.tar.gz : my files/ -compress folder
zip myfiles.zip file1 file2 : compress multiple files on zip file.
wget <link> : download any apk file.
rpm -qa | grep sql : showing installed package.
dnf list installed : all packages installed show. 
dnf list installed | grep java : for specific this apt search <package name> 
yum list available : apt available download list.
systemctl status firewalld.service - start - stop : firewall start
truncate -s 10M file.txt : file size shrink or extract.
ssh user@ip.address : remote access on linux server.
scp file user@ip:/folder/home/ : copy 1 server to 2nd server.
chmod a + rwx file.txt : change file permission 
chown root file.txt : ownership change
chgrp root file.txt : change group
pgrep nginx : get PID of a process.
kill -g PID : stop process by PID
pkill nginx : direct kill a process.
ping www.google.com : website is accessible or not.
netstat -putan | grep 80 : check if port open or not.
traceroute www.google.com : path to reach website.
reboot : restart our linux server.
shutdown : shutdown the server.
useradd alex : add new user
password alex : add password alex
su alex : switch user and enter password.
groupadd testing : add new group
cat /etc/group : checking group
userdel <username> : user delete.
groupdel <groupname> : group delete.
at : schedule a script to run on a particular date or time.
at 05:10 PM : this time schedule
Echo “at command ex” > at-demo.txt : ctrl + d for save. 
Then 5:10pm update or create the file this time.

•	## Networking
ifconfig : Configure network interfaces
ping : Test network connectivity
netstat : Network statastics display
traceroute : Tracing the path an IP packet takes across one or many networks
iptables : Configure firewall rules
dig : a flexible toold for interrogating DNS name server
ip : Check IP


•	## System Service
Systemctl : Control system service 
Service : Manage system service 
Chkconfig : Service runlevel management 

•	## Process Management
ps : Display running processes
ps -ef | grep java : for check specific service.
ps –u :display technical all information about the processes
ps –A : This command lists even those processes that are currently not running.
top : System performance monitor
du : how much memory use in specific folder 
kill : Terminate a process
killall : Terminate processes by name

•	## Shell Scripting
bash : Bourne Again Shell
sh : Bourne Shell
awk : is a “general scanning and processing language”
tac : tac does the same thing as cat (in that it concatenates files)
grep : used to search lines containing a specific keyword in a file
sed : Stream editor for transformations
wc : Word Count was detailed in section 5 but has another often overlooked behaviour
tr : tr is used to “translate characters”
sort : used to rearrange lines of text in files or from standard input
diff : diff is used to find differences between two byte streams
tee : to split the output of a program so that it can be both displayed and saved in a file.

•	## System Information 
uname : Display System information 
df, df -h : Disk space usage, mounted, size
free : Memory usage information 
hostname : show/set system hostname
nslookup : command is used to troubleshoot network connectivity issues in the system.
systeminfo : shows your pc's details.
lscpu : cpu, core, thread info in server.
lsblk : disk partition, storage devices.
uname -a, cat /etc/os-release : showing OS related info.

•	## File Permission 
chmod : To change file permissions
chmod +x : Add execute permission to a file
Usage: To make a file executable.
Syntax: chmod +x [file]
Example: chmod +x script.sh
chown : To change file ownership
Syntax: chown [owner] [file]
Example: chown john myfile.txt
chgrp : To change group ownership
Syntax: chgrp [group] [file]
Example: chgrp admin myfile.txt
umask : Set default file creation permissions
Syntax: umask [mask]
Example: umask 022
getfacl : Get file access control lists (ACL)
Syntax: getfacl [file]
Example: getfacl myfile.txt
Displays the ACLs of myfile.txt.


u Means – User, g Means – Group, o Menas – Owner 
File Level permissions : These control permissions on the file level. 
r – read, w – write, x – execute…
Access 	Symbolic Mode	Octal Mode
Read	r	4
Write	w	2
Execute	x	1
	



Octal Value 	File Permissions Set 	Permissions Description 
0	---	No permissions 
1	--x	Execute permission only 
2	-w-	Write permission only 
3	-wx	Write and execute permissions 
4	r--	Read permission only 
5	r-x	Read and execute permissions 
6	rw-	Read and write permissions 
7	rwx	Read, write, and execute permissions 


•	## User And Group Management 
useradd : Add a new user
Syntax: useradd [options] username
Example: useradd john
usermod : Modify Existing user
Syntax: usermod [options] username
Example: usermod -aG sudo john
userdel : Remove existing user 
Syntax: userdel [options] username
Example: userdel john
groupadd : Create a new group
Syntax: groupadd [options] groupname
Example: groupadd admins 
groupmod : Modify existing group
Syntax: groupmod [options] groupname
Example: groupmod -n developers devs
groupdel : Remove existing group
Syntax: groupdel groupname
Example: groupdel devs

… Thank You …

