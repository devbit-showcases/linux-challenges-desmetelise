## Challenge 1: List of System Calls

**Find a list of all the system calls available in the latest stable kernel release.**

(http://man7.org/linux/man-pages/man2/syscalls.2.html)

## Challenge 2: Standard C function wrappers

**Search the Internet for the standard C library functions that allow you to perform the following tasks:**

Open a file: ```fopen("filename", "r")```
Write text to a file: ```fopen("filename", "w")```
Close the file: ```fclose("filename")```
Open an i2c device: 
Write data to an i2c device: 
Close the i2c device: 
Create a child process / copy of current process: 
Create a file: 

**What do you notice about the functions to interact with a file and those to interact with an i2c device?**

## Challenge 3: Groups

**Why would a system such as Linux need groups of users for ?**

Linux uses groups as a way to organize users. Groups organize collections of accounts, primarily as a security measure. 

## Challenge 4: GitHub Repo

**Can you find the GitHub repository that contains the source of the Linux kernel? Who owns the repository? What is the latest release?**

Source of the Linux kernel: [here](https://github.com/torvalds/linux).

Owner: [Linus Torvalds](https://github.com/torvalds).

The latest release: [v5.0-rc6](https://github.com/torvalds/linux/releases/tag/v5.0-rc6).