# Project on 0x16. C - Simple Shell  

## Description
 In this project, we have coded it from scratch to create a simple Unix shell. A shell is an interactive > command-line interpreter.  
 We created a shell that would utilize the command line > interface (CLI). It allows users to type in a defined set of > commands (e.g. "rm" to remove files, "cat" to combine word documents, etc) and have the > operating system run the appropriate function. It is slightly different from a graphical user > interface (GUI).   
 For instance, instead of using a mouse to click to open folders and delete files, a user > can type in a command (i.e. "ls" or "rm") and have the files be displayed or > modified in a list on the command line.  
 GUI and CLI both have the same purpose to interact > with the operating system but their input methods are different and some developers > prefer the CLI to interact with the shell because their typing is quicker than > clicking and dragging. There are a few > versions of Unix shells, from the very first (Ken Thompson's) shell that can > be activated by typing ```sh``` in the terminal to today's most popular Bash > (Bourne Again Shell).  
 Later versions of the shell handle memory leaks better and > have more functionality. Our shell is a simple version that handles memory leaks > very well and has basic functionality. You can create/write/read/open/remove > folders, print things to the terminal, change directories, print where you are > in the system, etc.

# Compile and run

gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

./hsh

# Usage

Prints a prompt and waits for a command from the user
Creates a child process in which the command is checked
Checks for built-ins, aliases in the PATH, and local executable programs
The child process is replaced by the command, which accepts arguments
When the command is done, the program returns to the parent process and prints the prompt
The program is ready to receive a new command
To exit: press Ctrl-D or enter "exit" (with or without a status)
Works also in non interactive mode

# Examples

$ /bin/ls
foo main.c coquille.c README.md tests croissant.c

$ pwd 
/home/vagrant/simple_shell

$ ls -l
total 60
drwxrwxr-x 7 vagrant vagrant  4096 Aug  25 01:48 foo
-rw-rw-r-- 1 vagrant vagrant   148 Aug  25 00:00 main.c
-rwxrw-r-- 1 vagrant vagrant    28 Aug  25 15:35 coquille.c

$ baguette
./hsh: No such file or directory

Authors
Nadduli Dan
Github - Twitter - LinkedIn

I am a Full-Stack Software Engineer, and I currently learning the foundation of Computer Science at Holberton School. I currently live in Kampala, Uganda, but I am always open to opportunities to travel abroad.

I am most proficient in Python and Javascript, and am curious about learning more Node.js, and Javascript frameworks like Vue.js as I move forward.

I am mission-driven and always excited about helping others, which is why I took a role to join other Software Engineers at ALX and Holberton School. I value inclusivity, equality and kindness more than anything else.

Namubiru Barbie
Github - Twitter - LinkedIn

