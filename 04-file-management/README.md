# File management in Linux

### File and Directory Management
1. **`ls`** – Lists files and directories in the current location.
2. **`cd /path/to/directory`** – Changes the working directory.
3. **`pwd`** – Prints the current working directory.
4. **`mkdir new_folder`** – Creates a new directory.
5. **`rmdir empty_folder`** – Removes an empty directory.
6. **`rm file.txt`** – Deletes a file.
7. **`rm -r folder`** – Deletes a folder and its contents.
8. **`cp file1.txt file2.txt`** – Copies a file.
9. **`cp -r dir1 dir2`** – Copies a directory recursively.
10. **`mv old_name new_name`** – Moves or renames a file or directory.

### File Viewing and Editing
11. **`cat file.txt`** – Displays file content.
12. **`tac file.txt`** – Displays file content in reverse order.
13. **`less file.txt`** – Opens a file for viewing with scrolling support.
14. **`more file.txt`** – Similar to `less`, but only moves forward.
15. **`head -n 10 file.txt`** – Displays the first 10 lines of a file.
16. **`tail -n 10 file.txt`** – Displays the last 10 lines of a file.
17. **`nano file.txt`** – Opens a simple text editor.
18. **`vi file.txt`** – Opens a powerful text editor.
19. **`echo 'Hello' > file.txt`** – Writes text to a file, overwriting existing content.
20. **`echo 'Hello' >> file.txt`** – Appends text to a file without overwriting.

Important interview Questions? 

1. What is the difference between "useradd" and "adduser" in Linux?

Ans: Both the "useradd" and "adduser" commands do the same work, but the "adduser" command is used to create a home directory for the user and also asks for user information like full name, email address, etc. While the "useradd" command can be considered as a quick way to create a user and it also does not prompt for any user information.

2. Then, what is the use of the "useradd" command, as the " add user " command seems to be more powerful and interactive?

Ans: The "useradd" command will be very useful when you are writing scripts because here we don't want the terminal to ask input from the user. This command just creates the user, which is the desired result while writing scripts.

3. Can you restore the password of a Linux user if you forget the password, in case it is not stored?

Ans: No, we cannot restore the password of the Linux user; thus, it is very essential to store them in files. However, only the encrypted password can be obtained from " /etc/shadow " file.
