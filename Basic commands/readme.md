
# Ubuntu Linux Basic Commands Guide

## **Basic Navigation Commands**
- `pwd` – Print the current working directory  
- `ls` – List files and directories
- `ls -a`– List all including hidden files and directory
- `ls *.sh` – List all the files having .sh extension 
- `cd [directory]` – Change to the specified directory  
- `cd ..` – Move up one directory  

## **File and Directory Management**
- `touch [file_name]` – Create an empty file  
- `mkdir [directory_name]` – Create a new directory  
- `rm [file_name]` – Remove a file  
- `rm -r [directory_name]` – Remove a directory and its contents  
- `cp [source] [destination]` – Copy a file  
- `mv [source] [destination]` – Move or rename a file  

## **File Viewing**
- `cat [file_name]` – View file content  
- `less [file_name]` – View file content one page at a time  
- `head [file_name]` – View the first few lines  
- `tail [file_name]` – View the last few lines  

## **Search with `grep`**
- `grep [pattern] [file_name]` – Search for a specific pattern in a file  
  - Example: `grep "error" log.txt`  
- `grep -i [pattern] [file_name]` – Case-insensitive search  
- `grep -r [pattern] [directory]` – Search recursively in all files within a directory  
- `grep -n [pattern] [file_name]` – Show line numbers with matches  
- `grep -v [pattern] [file_name]` – Show lines that do NOT match the pattern  
- `grep -c [pattern] [file_name]` – Count the number of matches  

## **System Information**
- `uname -a` – Display system information  
- `df -h` – Check disk space usage  
- `free -h` – Check memory usage  

## **User Management**
- `whoami` – Show the current user  
- `sudo [command]` – Run with administrative privileges  
- `passwd` – Change user password  

## **Process Management**
- `ps` – Display running processes  
- `top` – Real-time process monitoring  
- `kill [PID]` – Terminate a process  

## **Package Management**
- `sudo apt update` – Update package lists  
- `sudo apt upgrade` – Upgrade installed packages  
- `sudo apt install [package_name]` – Install a package  
- `sudo apt remove [package_name]` – Remove a package  

## **Networking**
- `ping [website_or_ip]` – Test network connectivity  
- `ip a` – View network interfaces  
- `curl [url]` – Fetch data from a URL  

## **Permissions**
- `chmod [permissions] [file_name]` – Change file permissions  
- `chown [user:group] [file_name]` – Change file ownership  

## **Archive and Compression**
- `tar -czvf archive_name.tar.gz [directory]` – Create a compressed archive  
- `tar -xzvf archive_name.tar.gz` – Extract a compressed archive  

---

This covers essential Ubuntu commands for managing files, directories, processes, and more. Use this as a reference for common tasks on your Linux system.
