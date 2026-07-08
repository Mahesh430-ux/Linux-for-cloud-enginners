# Linux-for-cloud-enginners

What is linux :-
Linux is an open-source operating system kernel that manages the computer's hardware and software resources.

* Structural architecture  :-

User
   ↓
Applications
   ↓
Operating System (Linux)
   ↓
Hardware

* Why  cloud enginners learn linux :-

1) AWS EC2 mostly run
on Linux
2) Azure virtual machines run on Linux
3) Google cloud VMs run Linux
4) Docker containers mostly run on Linux
5) Kubernetes is built around Linux :

* starts with the basic commands that is essential for cloud enginners :-

* Day 1 :-  linux basics :-

1) How to check the current working directory :-
ans :- pwd (print working directory)  

2) How to display name of the current logged in user
ans :- whoami

3) How to check System date and time
ans :- date + % T

4) How to display files and directory present in the current location
ans :- ls

5) How to clear linux terminal
ans :- Clear or ( ctrl + c  )

6) How to display content of  a file on terminal
ans :- cat <file name>

7) How to read a file and search for a word
ans :- less <file name >

8) How to view content of a file page by page
ans :- more <file name >

9) How to create a directory in a linux
ans :- mkdir <directory  name>

10) How to create a file in a linux
ans :-  touch <file name >

11) How to delete a folder  in a linux :-
ans :- rm -r <folder name>

12) How to edit a file in a Linux  
ans :- vi <file name >

13) How to delete a directory in a Linux
ans :- rmdir <directory name >

14) How to copy and paste a file from one folder to another in linux
ans :- cp <file name > <file name>

15) How to change path in Linux  
ans :- cd ..

Day 2 :- "LINUX PART 2" :-

1) How to display the manual of any Linux command
ans :-man <command>

Example:
man ls

1) How to display the help menu of any command

ans :- `<command> --help`

Example:-
ls --help

1) How to print text on the terminal

ans :- `echo "text"`

Example:
echo "Hello Linux"

1) How to display previously executed commands

ans :- history

1) How to find the location of a command

ans :-which <command>

Example:
which python3

1) How to check disk space usage

ans :- df -h

1) How to check the size of a directory
ans :-du -sh <directory name>

Example:-
du -sh Documents

1) How to check memory (RAM) usage

ans :- free -h

1) How to display all running processes

ans :- ps -ef

 1) How to monitor system processes in real time

ans :- top

 1) How to find a file in Linux

ans :-find <path> -name "<file name>"

Example:
find . -name "notes.txt"

1) How to search for a word inside a file

ans :- grep <word> <file name>

Example:
grep "Linux" notes.txt

1) How to move or rename a file in Linux
ans :- mv < source> <destination >

Example:
mv file.txt Documents/

Rename Example:-
mv file.txt linux_notes.txt

1) How to check the IP address of your system

ans :-ip addr

1) How to test network connectivity

ans :- ping < website or IP address >

Day 3 :-  ADVANCED TOPICS  

1) How to change file permissions :-
ans :- chmod permissions filename

2) How to change the owner of a file or directory :-
ans :- chown username filename

3) How to search for a file or directory :-
ans :- find /path -name filename

4) How to locate a file quickly :-
ans :- locate filename

5) How to display disk space usage of file systems :-
ans :- df -h

6) How to check the size of a file or directory :-
ans :- du -sh filename

7) How to display currently running processes :-
ans :- ps -ef

8) How to monitor system processes in real time :-
ans :- top

9) How to terminate a running process :-
ans :- kill process_id

10) How to forcefully terminate a running process :-
ans :- kill -9 process_id

11) How to check the IP address of the system :-
ans :- ip addr show

12) How to test network connectivity to another host :-
ans :- ping hostname

13) How to display active network connections and listening ports :-
ans :- ss -tuln

14) How to display the routing table :-
ans :- ip route

15) How to display network interface information :-
ans :- ip link show

Day 4 :-

1) How to find files by name
ans :-
find / -name filename

Example:
find /home -name test.txt

1) How to find files by extension
ans :-
find . -name "*.txt"

Example:
find . -name "*.log"
3) How to search for text inside files
ans :-
grep "text" filename

Example:
grep "root" /etc/passwd

1) How to search text recursively in directories
ans :-
grep -r "text" directory

Example:
grep -r "password" /etc

1) How to display the first 10 lines of a file
ans :-
head filename

Example:
head /etc/passwd

1) How to display the last 10 lines of a file
ans :-
tail filename

Example:
tail /var/log/messages

1) How to monitor a log file in real time
ans :-
tail -f filename

Example:
tail -f /var/log/messages

1) How to count words, lines, and characters in a file
ans :-
wc filename

Example:
wc notes.txt

1) How to compare two files
ans :-
diff file1 file2

Example:
diff old.txt new.txt

1) How to sort the contents of a file
ans :-
sort filename

Example:
sort names.txt

1) How to remove duplicate lines from a sorted file
ans :-
uniq filename

Example:
uniq names.txt
