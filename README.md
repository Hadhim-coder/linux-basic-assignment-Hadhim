# linux-basic-assignment-Hadhim

# SECTION 1 – Write the purpose and an example usage for each command.

1.  pwd-> Show the present directory name.
2.  ls - >List all directorys and files
3.  cd ->Changing the directory
4.  mkdir -> To Create a directorys
5.  rm -rf ->To remove the file
6.  ps -ef -> Show all runing the process id
7.  top -> show high usage of application in cpu
8.  df -h ->show the storage
9.  history ->show histrory
10. uptime ->run time of Server

# SECTION 2 – Write the Linux command for the following tasks.

1.  Create a directory called project-files?
      ans:mkdir project-files

2.  Navigate into the project-files directory
    ans:cd project-files

3.  Create a file called notes.txt using vi
       ans: vi notes.txt

4.  Display the contents of notes.txt
         ans :cat 

5.  Copy notes.txt to backup.txt
       ans: cp notes.txt backup.txt

6.  Show the first 100 lines of a file called logs.txt
     ans: head -n 100 logs.txt

7.  Show the last 100 lines of logs.txt
       ans: tail -n 100 logs.txt

8.  Check the disk storage usage of the server
          ans: df -h

9.  Check the running processes in the system
       ans: ps -ef

10. Delete a file called temp.txt
       ans: rm temp.txt

# SECTION 3 – Concept Questions

1.  What is the difference between > and >> in Linux?
       * > means overwrites the file
      * >> means appent to the file

2.  What is the purpose of the kill -9 command?
        To Terminate the processes

3.  What is the difference between rm and rmdir?
            rm means remove the file.
            rmdir means remove the directory

4.  What information does the netstat -tulpn command provide?
               The command netstat -tulpn is used to display network connections and listening ports

5.  What is the purpose of the ping command?
     It is used to check network connectivity between your system and another host


# SECTION 4 – Scenario based Questions

1.  You want to check the current working directory. Which command will you use?
       ans:  pwd

2.  You want to create a directory called devops inside the home directory. Write the command.
            ans : cd home
                  mkdir devops

3.  You want to check which process is using high CPU in the system. Which command will help?
          ans :top

4.  You want to check whether your server can connect to google.com. Which command will you use?
                   ans: ping google.com

5.  You want to view the last 50 lines of a log file called application.log. Write the command.
               ans: tail -n 50 application.log


