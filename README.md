# linux
Linux is an open-source, Unix-like operating system that has gained immense popularity since its inception in 1991 by Linus Torvalds. It is designed to be versatile and can run on various hardware platforms, including servers, desktops, and embedded devices
Linux is a community-developed operating system that serves as the foundation for numerous distributions (distros), such as Ubuntu, Fedora, and Debian. It operates under the GNU General Public License (GPL), which allows users to run, study, modify, and redistribute the source code freely.
# basics of shell 
The shell is a command-line interface that allows users to interact with the operating system by executing commands. In Linux, the shell provides a powerful environment for managing files, running programs, and performing system administration tasks. This overview will cover the basics of the shell, including its types, common commands, and functionalities.
shell simply executes the commands, shell instructs the kernals. 
# top shells
# 1 Bash, short for Bourne Again Shell,
is a command-line interface and scripting language used primarily in Unix-based operating systems, including Linux and macOS.
 In other words, it provides users with a simple and efficient way to interact with the system and perform a variety of tasks, such as creating files, editing text, and managing processes.
 It serves as a shell that allows users to interact with the operating system by executing commands and running script
shell .....> a shell intreprets the commands you have entered usoing a keyboard and sends it to the OS to perform them 
# bash history
Bash was created by Brian Fox in 1987 as a free software replacement for the original Unix shell- the Bourne shell (often referred to as 'sh').
It was developed as part of the GNU Project and was designed to be a versatile shell that could be used in a variety of Unix environments
The Linux shell is based on the Bash scripting language and provides a wide range of built-in commands and features
# bash scripting
Bash scripting refers to the process of writing shell scripts using the Bash shell
These scripts are essentially a series of commands that are executed sequentially and can be used to automate repetitive tasks or perform complex operations.
bash scripts are executed by typing the name of the script in the terminal window.
# shebang
Shebang: The first line of a Bash script is known as the "shebang" and specifies the interpreter to be used to run the script
It is basically an absolute path to the bash interpreter.
#!--this represents which enterpreter a script should be interpreted with
 The shebang for Bash scripts is usually-
# !/bin/bash 
this is a header command which reprsents it is a bash /shell script
To create and run a simple Bash script that prints "Hello, World!", follow these steps:
 # Step 1: Create the Script File
Open your terminal and create a new file named hello_world.sh using the touch command:
touch hello_world.sh
 # Step 2: Edit the Script
Open the file in a text editor, such as nano:
nano hello_world.sh
In the editor, add the following lines to your script:
#!/bin/bash
echo "Hello, World!"
 # Step 3: Save and Exit
If you are using nano, save the file by pressing CTRL + O, then press Enter, and exit by pressing CTRL + X.
# Step 4: Make the Script Executable
Before running the script, you need to give it execute permissions. Run:
chmod +x hello_world.sh
 # Step 5: Run the Script
Now you can run your script by executing:
./hello_world.sh
# Expected Output
When you run the script, you should see:
text
Hello, World!
