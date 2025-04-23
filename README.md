# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![Screenshot 2025-04-23 150826](https://github.com/user-attachments/assets/67ed9c0e-157d-454b-ba7d-d80260c3a33b)

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![Screenshot 2025-04-23 150820](https://github.com/user-attachments/assets/35189d64-883b-42e7-8efd-ac2addd36ccb)

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![Screenshot 2025-04-23 150813](https://github.com/user-attachments/assets/4282e2db-6261-4f99-bec6-6f742abc82b3)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![Screenshot 2025-04-23 150808](https://github.com/user-attachments/assets/934c7eab-268d-4606-84bb-b37b7c100fb8)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![Screenshot 2025-04-23 150804](https://github.com/user-attachments/assets/debcdf09-95a3-4ef7-b1ca-b77bb94a90d6)

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![Screenshot 2025-04-23 150758](https://github.com/user-attachments/assets/ad6190a8-f137-4c5e-859c-34a128ec41ef)

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![Screenshot 2025-04-23 150754](https://github.com/user-attachments/assets/06c3845d-03df-4d19-92fa-be4d094246d7)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![Screenshot 2025-04-23 150748](https://github.com/user-attachments/assets/25d98436-0f66-45f9-85ec-58c6b39b699e)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
![Screenshot 2025-04-23 150741](https://github.com/user-attachments/assets/4cb1b908-990b-4971-9be0-8b9f405eac30)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
![Screenshot 2025-04-23 150735](https://github.com/user-attachments/assets/81114c66-8b21-47a6-ac1d-b59ac0ddbe03)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![Screenshot 2025-04-23 150729](https://github.com/user-attachments/assets/b42315cc-f821-4c47-8b8f-9d7fb1378eb2)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![Screenshot 2025-04-23 150722](https://github.com/user-attachments/assets/6cba90f4-0b34-4413-a62f-181b1b8c63d4)

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![Screenshot 2025-04-23 150716](https://github.com/user-attachments/assets/5dc46950-6d11-42ca-b132-9604f9b873c0)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![Screenshot 2025-04-23 150711](https://github.com/user-attachments/assets/6e0619d3-91da-45b3-a989-8ac33d3d5acd)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![Screenshot 2025-04-23 150706](https://github.com/user-attachments/assets/6e67d88e-e3a1-4d46-b15f-b2ebb0de7fd2)

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
![Screenshot 2025-04-23 150700](https://github.com/user-attachments/assets/a1991d3f-3dbb-42e2-8104-a052ca33c539)

### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![Screenshot 2025-04-23 150655](https://github.com/user-attachments/assets/b91205e1-0e33-4179-8dc4-46c4889380ab)

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![Screenshot 2025-04-23 150650](https://github.com/user-attachments/assets/e62da597-bc37-4c50-a3f1-c90fcffc4651)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![Screenshot 2025-04-23 150644](https://github.com/user-attachments/assets/b14a7ba0-b81d-4bcb-ba53-7e2510901e9e)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![Screenshot 2025-04-23 150638](https://github.com/user-attachments/assets/4b8a009b-74ca-4c40-9936-a968818ccfd1)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
![Screenshot 2025-04-23 150630](https://github.com/user-attachments/assets/33049d56-474b-468d-8af9-786cd0fd61c3)

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![Screenshot 2025-04-23 150619](https://github.com/user-attachments/assets/a62dcb50-26a5-47ec-842d-71633b778186)

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![Screenshot 2025-04-23 150613](https://github.com/user-attachments/assets/1531af51-dc8d-4ca7-9452-5c628a0cd4fa)

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![Screenshot 2025-04-23 150607](https://github.com/user-attachments/assets/455b52b2-bca2-437a-b30f-4dbe75e9a3eb)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![Screenshot 2025-04-23 150602](https://github.com/user-attachments/assets/3902e39f-8ea9-4ea3-90ad-153b58704d61)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![Screenshot 2025-04-23 150554](https://github.com/user-attachments/assets/90f9fdef-e162-44f9-8572-6ac404b8daaa)

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![Screenshot 2025-04-23 150546](https://github.com/user-attachments/assets/6b91b139-016d-432b-9569-e6da3fa54a1f)

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![Screenshot 2025-04-23 150537](https://github.com/user-attachments/assets/f9d95cb8-1820-459d-9183-7e88329d186f)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![Screenshot 2025-04-23 150528](https://github.com/user-attachments/assets/ed2f3608-bc08-413b-825e-8cd5180306c2)


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![Screenshot 2025-04-23 150537](https://github.com/user-attachments/assets/25f05f8a-8020-4e49-a923-cbd23f0377d8)

## Result
Linux commands are executed in the linux terminal successfully.
