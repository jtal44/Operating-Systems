# Operating-systems

Description of programs -


Program 1-1: The following program forks a parent and child process and counts to 20. 
Program 1-2: The following program forks a parent and child process and counts to 20.


Program 2 - The following program acts as a shell running cd commands, env, history to show the last 10 commands, and handling any other commands via execvp. Upon killing the program, the last 10 commands are saved in audit.log from newest to oldest.

Program 3 - The following program uses POSIX threads to open files in independent threads, count the lines, update the total count of lines, exit each thread individually, and provide a total line count before exiting the program. It also uses a mutex to protect the line total to avoid race conditions. 

Program 4 - The following program opens files entered through the command line and displays directory/file info, user ID, group ID, number of links, time of last modification, status, access, file size in bytes, and inode number. It then closes the file and prints the total user and system CPU time used. If an incorrect name is entered the program will detect that and make an error note, but will continue to run everything else.
