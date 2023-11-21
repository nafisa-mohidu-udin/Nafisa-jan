                       LINUX DIRECTORY COMMANDS
1.pwd command 
The pwd command is used to display the location of the current working directory.
Syntax:
pwd

2.mkdir command.
The mkdir command is used to create a new directory under any directory.
Syntax:
mkdir<directory name>

3.rmdir command
The rmdir command is used to delete a directory.

SYNTAX:
rmdir<directory name>

4.ls Command 
The Is command is used to display a list of content of a direectory.
Syntax:
ls

5.cd Command
The cd command is used to change the current directory.
Syntax:
cd<directory name>


Linux File Command

6.touch Command 
The touch command is used to create empty files.We can create multiple empty files by executing it once.
Syntax:
touch<filename>
touch<file1><file2>

7. cat Command
The cat Command is a multi-purpose utility in the linux system.It can be used to create a file, display content of a file, and more.
Syntax:cat[OPTION]...[FILE]..

To create a file,executes it as follows:
cat><filename>
//Enter file content
cat<filename>

8. rm Command
The rm Command is used to remove a file.
Syntax:
rm<filename>

9.cp Command
The cp command is used to copy a file or directory.
Syntax:
cp<existing filename><new file name>


10. mv Command
The mv command is used to move a file or a directory form one location to another location.
Syntax:
mv<filename><directory path>

11. rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax:
rename’s/old-name/new-name/’files

LINUX FILE CONTENT COMMANDS

12.head command
The head command is used to display the content of a file. 
It displays the first 10 lines of a file.

Syntax:
head<file name>

13. tail command
The tail command is similiar to the head command. The difference between both comands is that it displays the last lines of the file content. It is useful for reading the error message.

Syntax:
tail<filename>

14. tac Command
The tac Command is the reverse of cat command, as its name specified. It displays th file content in reverse order(from the last line)

Syntax: tac<filename>

15.more command
The more command is quite similiar to the cat command, as it is used to display the file content in the same way that the cat command does. The only difference between both commands is that , in case of larger files, the more command displays screenful output at a time. 

In more command, the following keys are used to scrool the page:

ENTER key: To scrool down page by line.
Space bar : To move to the next page.
B key: To move to the previous page.
/key: To search the string.

Syntax:
more<filename>

16. less Command
The less Command is similiar to the more command. It also includes some extra features such as “adjustment in width and height of the terminal”. Comparatively, the more command cuts the output in the width of the terminal.

Syntax:less<filename>

LINUX USER COMMANDS

17.su Command 
The su command provides administrative access to another  user. In other words, it allows access of the Linux shell to another user.

Syntax:
su<username>

18. id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax:
id

19. useradd Command
The useradd Command is used to add or remove a user on a Linux  server.

Syntax:
useradd username

20.passwd Command:
The passwd Command is used to create and change the password for a user.

Syntax: passwd<username>
21. groupadd Command:
The groupadd command is used to create a user group.

Syntax: groupadd<groupname>

LINUX FILTER COMMANDS:

22. cat Command:
The cat command is also used as a filter to filter a file,it is used inside pipes .

Syntax:
cat <fileName|cat or tac|cat or tac|...

23. cut Command:
The cut command is used to select a specific column of a file. The “-d”  option is used as a delimiter, and it can be a space.(“”), a slash (/) , a hyphen(-), or anything else.And the “-f” option is used to specify a column number.

Syntax: 
cut-d(delimiter) -f(columnNumber) <fileName>

24. grep Command
The grep is the most powerful and used filter in a Linux system. The “grip” stands for “golbal regular expression print”. Its useful for searching the content from a file. Generally, its used with a pipe.

Syntax:
command|grep<searchword>
25. comm command:
The “comm” command is used to compare two files or streams. By default, it displays three columns, first displays non-matching items of the first file , second indicates the non-matching item of the second file , and the third column displays the matching items of both files.

Syntax:
comm<file1> <file2>

26. sed command
The sed command is also known as stream editor. Its used to edit files using a regular expression. It does not permanently edit files, instead , the edited content remains only on display. It does not affect the actual file.

Syntax:
command|sed’s/<oldworld>/<newWord>/’

27.Tee Command:
The tee command is quite similar to the the cat command.The only difference between both filters is that it puts standard input on standard output and also write them into a file.

Syntax:
 cat <fileName> | tee<newFile>| cat or tac|.....

28.tr Command:
The tr command is used to translate the file content like from lower case to uppar case.
Syntax:
command | tr <old> < new>

29.Uniq command
The uniq command is used to form a stored list in which every word will occur only once.

Syntax:
command <fileName> |uniq

30.wc command
The wc command is used to count the lines, words,and characters in a file.

Syntax:
wc <file name>

31. od Command
The od command is used to display the content of a file in differnt s , such as hexadecimal, octal, and ASCII characters.
  
Syntax:
od - b <file Name>          //octal format
od -t* 1<file Name>      //Hexa decimal format
od – c <fileName>        //ASCII character format

32. sort command
The sort command is used to sort files in alphabetical order.

Syntax: sort<file name>
33. gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having ‘.gz’ extension.

Syntax:
gzip<file1><>file2<>file3>...

34. gunzip command
The gunzip command is used to decompress a file. It is a reverse operation of gzip command.

Syntax:
gunzip<file1><file2><file3>..


LINUX UTILITY COMMAND:

35. find command:
The find command is used to find a particular file within a directort. It also supports various options to find a file such as byname,by type , by date, and more.
The following symbols are used after the find command:
(.) For current directort name
(/) For root

Syntax:
find.-name “*.pdf” 

36. locate command
The locate command is used to search a file by file name. It is quite similiar to find command; the difference is that it is a background process. It searches the file in the database, whereas the find command searches in the file syatem. It is faster than the find command . To find the file with the locates command , keep your database updated.

Syntax:
locate<filename>

37. date Command
The date command is used to display date , time, timezone and more.

Syntax:
date

38. cal command:
The cal command is used to display the current month’s calender with the current date highlighted.

Syntax:
cal<

39. sleep command
The sleep command is used to hold the terminal by the specified amount of time, By default, it takes in seconds.

Syntax:
sleep<time>

40. time command
The time command is used to display the time to execute a command.

Syntax:
time

41. The zcat command is used to display the compressed files.

Syntax:zcat<filename>

42. The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks and the mounted directory.

Syntax:
df

43. mount command
The mount command is used to conect an external device file system to the system’s file system.

Syntax:
mount-t type <device><directory>

44. exit command
Linux exit command is used to exit from the current shell . It takes a parameter as a number and exits the shell with a return of of status number.
Syntax:exit 
45. clear command
Linux clear command is used to clear the terminal screen.

Syntax: clear

LINUX NETWORKING COMMANDS
 
46. ip Command
Linux ip command is an updated version of the ipconfig command. It is used to assign and ip adress, initialize an interface , disable an interface.

Syntax:
ip a or ip addr

47. ssh command
The mail command is used to send emails from the command line.

Syntax: ssh user_name @host(IP/Domain_name)</p>

48. mail command 
The mail command is used to send emails from the command line.

Syntax: mail-s “Subject” <recipient address>






49. ping command
The ping command is used to check the connectivity between two nodes, that is whether the server is connected.it is a short form of “packet internet groper”.

Syntax:
ping <destination>

50. host command
The host command is used to display the ip adress for a given domain name and vice versa. It performs the DNS lookups for the DNS quary.

Syntax: 
host<domainname>or<ipadress>





# Nafisa-jan
Commands of Linux
