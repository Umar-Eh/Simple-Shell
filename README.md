### Simple Shell Project

**Objectives:**<br><br>
1. Learn to develop software using Git<br><br>
2. Gain experience developing multi-source file projects in C<br><br>
3. Experience using Makefiles and other software build tools<br><br><br>


**Description:**<br>
Design a simple command line shell and implement it on the specified UNIX platform
The Shell or Command Line Interpreter is the fundamental User interface to
an Operating System. The lab project is to write a simple shell - myshell -
that has the following functions:<br><br>

*change working directory<br>
*clear the screen<br>
*list the contents of the directory<br>
*list all the environment string<br>
*display the diaply followed by a new line<br>
*display the user manual using the more filter<br>
*pause operation of the shell<br>
*quit the shell<br><br>

**Usage:**<br>
The shell can be invoked on Windows command line interpreter by typing myshell. It can be invoked on a UNIX based OS<br>
by typing /myshell. The program accepts one argument which can be a batchfile containing user commands. <br>
For example: ./myshell commands.txt <br>
<br>

The following are the commands for the shell: <br><br>

help :  Lists the help menu <br>
dir "directory":  Lists the contents of the directory <br>
environ: Lists all the environment strings <br>
echo "comment": Displays comment on the command line followed by a newline <br>
clr. Clears the screen <br>
cd "path": Changes the working directory to the specified path. <br>
pause: Pauses operation of the shell until the ENTER key is hit <br>
quit: Quits the shell <br>
