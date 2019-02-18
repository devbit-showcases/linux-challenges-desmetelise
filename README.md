# Solutions to Challenges

Name: Elise De Smet

## Instructions

Place the solutions to the course challenges in this file. Document them thoroughly as they are also subject material for the exam and you will be graded on the content of this file. The challenges are meant to practice the material, so make sure to do them yourself unless instructed otherwise.

Some tips:

* Structure the challenges and solutions so this makes for nice report
* Also add the instructions of the challenge to this file.
* You are free to add screenshots or images, just make sure to place them inside a subdirectory.
* For the more advanced challenges you can also add scripts to this repository. Make sure to place them inside a subdirectory as well.

Happy Hacking.

# Chapter 1: Introduction to Linux

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
