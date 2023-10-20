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
 ![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/270b240e-e694-44fb-9e29-b5f4a1656f1c)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/fecc2f64-cab0-433f-b825-7b8a47b2cfbd)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/175e9e7e-1018-4469-b8b0-05f4d17be5c4)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/ab3663ec-fe39-4dfd-89cd-120343cab172)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/91b32106-9156-4adf-a5e0-18a00419bc53)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 ![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/b64bf3ca-3ce5-4f21-b7a8-fc6e66acd4ed)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/eb95a5f3-0227-4dab-ae56-5e11547e65ac)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/c6924048-b64b-41e2-b70d-4ed9bca38def)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/b8f2476e-03ed-4ea1-8c5e-f78fb5f2f82d)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/8f748707-fcfc-4de1-ba54-5b458f1d14fd)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/9fcb768c-dacc-4b2d-8d82-9f7ea9c62e03)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/a79738b9-df8e-463d-8f25-e854e95bb3a0)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 ![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/4f6e3f30-bdaf-46c5-8eb8-b102238bc59d)

### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/5e31fc60-aa3a-4a55-81a6-63ad2222f07c)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/3fd5662e-505e-42ba-9e19-6a7ec2864a49)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/8d601229-bff9-4826-b67f-9e75a76b3905)

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
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/8adea3b4-bce8-4811-ad0f-db7a0e61d825)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/4fb01f60-077a-4a3f-9916-8bfcb54eccbf)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/58da70e0-5eb6-4248-a5b9-dd351cb84140)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/c9cc70c4-cf6a-4c8b-b0b4-eb564291a0e8)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/82983ba5-80d5-4f98-afda-80e036d0083e)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/3c226062-0961-4f4c-b68f-f504ef020024)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/e8645841-6515-48a9-b5ed-895d34e60a34)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/8babd758-65ee-4c33-a7a3-a01aa595ebca)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/cdc9fc89-837d-44a5-9c99-c2e99cbb1717)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/DrMalathiSaravanan/Ex-01-Linux-Commands/assets/113017853/f69f3141-d54e-4421-88f6-91faf9ee3b7a)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
