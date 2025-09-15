# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## OUTPUT:
<img width="334" height="117" alt="uname" src="https://github.com/user-attachments/assets/b41f1f72-23ac-44f8-a0eb-2a5819c8f5cb" />
<br> <br> <br>
<img width="441" height="85" alt="ls" src="https://github.com/user-attachments/assets/0bf806b6-8d30-4305-9809-1d866409e7ef" /> 
<br> <br> <br>
<img width="490" height="105" alt="pwd" src="https://github.com/user-attachments/assets/e1778059-9d03-47bc-b29e-c750e9df70d0" /> 
<br> <br> <br>
<img width="261" height="50" alt="mkdircomm" src="https://github.com/user-attachments/assets/9f2bad9e-4e06-43f3-bec6-5fb032283c91" />
<br><br><br>
<img width="391" height="54" alt="cd" src="https://github.com/user-attachments/assets/d0f829a6-f389-46c9-acf9-6fb02b62fce9" />
<br><br><br>
<img width="376" height="67" alt="cat" src="https://github.com/user-attachments/assets/e324b7c1-096c-4f8d-808e-297e70959a4c" />
<br><br><br>
<img width="388" height="42" alt="cp" src="https://github.com/user-attachments/assets/d7f9596f-08f0-4fd3-93f8-7214a001b635" />
<br><br><br>
<img width="341" height="57" alt="chmod" src="https://github.com/user-attachments/assets/35cca12b-2db5-4987-b194-445941d4710a" />
<br><br><br>
<img width="830" height="208" alt="df" src="https://github.com/user-attachments/assets/d219c51a-9203-433a-8aad-3e6afe1c10e0" />
<br><br><br>
<img width="342" height="208" alt="head" src="https://github.com/user-attachments/assets/b0668767-0600-4158-b53d-3321ab7f1d38" />
<br><br><br>
<img width="312" height="195" alt="tail" src="https://github.com/user-attachments/assets/8a05638c-7afe-4925-89e5-cfcce723981e" />
<br><br><br>
<img width="405" height="69" alt="tr" src="https://github.com/user-attachments/assets/9f94cc93-e088-4c3c-901c-2e8d13adc430" />
<br><br><br>
<img width="343" height="154" alt="mv" src="https://github.com/user-attachments/assets/ae27d987-b05a-4917-9547-06a8d0091924" />
<br><br><br>
<img width="637" height="105" alt="id" src="https://github.com/user-attachments/assets/98352c8c-d759-4546-a925-077a9e302ad9" />
<br><br><br>
<img width="381" height="95" alt="rmdir" src="https://github.com/user-attachments/assets/27532ba8-6019-46dd-a471-a044e7b65d3f" />
<br><br><br>
<img width="610" height="52" alt="clear" src="https://github.com/user-attachments/assets/e1552524-6add-4a5c-9c36-610490a983b3" />
<br> <br>
<img width="339" height="178" alt="cal" src="https://github.com/user-attachments/assets/6d3adea9-167a-4ec7-ab36-38e3e6f9754b" />



















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.



















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
