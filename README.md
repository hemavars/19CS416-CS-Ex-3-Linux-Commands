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
<img width="948" height="133" alt="image" src="https://github.com/user-attachments/assets/5aa8c38a-ec2b-45cf-8dbd-f43fc302220f" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```
**Output:**
<img width="1616" height="973" alt="image" src="https://github.com/user-attachments/assets/bc8b3594-611e-43fd-9860-1ca7433e3a3d" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/341a3b42-49fb-4129-bc11-d26c0b6ff0dd" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/92af3d06-e985-468a-bcd8-7fce0f6ff018" />


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

<img width="2154" height="730" alt="image" src="https://github.com/user-attachments/assets/109db7f4-e140-4c80-a03d-e98a5faeea1b" />


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="1670" height="941" alt="image" src="https://github.com/user-attachments/assets/86bf5d76-6fce-47b2-aa66-e2e48b8724de" />


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

<img width="1548" height="1016" alt="image" src="https://github.com/user-attachments/assets/422a82a1-cda5-4d1b-a95a-9398aadce354" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**

<img width="2164" height="727" alt="image" src="https://github.com/user-attachments/assets/aa670c07-f2e0-4c1a-852e-89bffc99e656" />

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**

<img width="2035" height="773" alt="image" src="https://github.com/user-attachments/assets/9764cf60-625f-4a18-aa97-64819c8c309f" />

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**

<img width="1338" height="1176" alt="image" src="https://github.com/user-attachments/assets/f7938326-af82-43d1-819c-a61959a21a6c" />

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/59ae56be-05ea-42e9-af6e-ada1dd1e0fdf" />


### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="1534" height="1025" alt="image" src="https://github.com/user-attachments/assets/2872f7be-cc41-46ba-8987-c66a4b9392cf" />


### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**

<img width="1586" height="992" alt="image" src="https://github.com/user-attachments/assets/c01e2c2f-5ea3-43e8-b728-c948007b8d03" />

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**

<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/28726e28-7ffc-403a-9589-4da9f5daaa99" />


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**

<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/d05ffcd2-23aa-45dc-a041-8f498be779fb" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/909bbf0b-ff4b-4582-9ea3-83d383926341" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/ecdf9822-3e74-4522-ade1-c85f12ffc926" />


### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="2170" height="725" alt="image" src="https://github.com/user-attachments/assets/74b1a60a-520a-4813-a054-6dd90d6bd8bf" />



### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="2169" height="725" alt="image" src="https://github.com/user-attachments/assets/717da0e1-f848-4368-be5a-cec1f63e9d77" />


### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**

<img width="2063" height="762" alt="image" src="https://github.com/user-attachments/assets/7ed44e1d-9fce-440c-a5b7-b8b3c20de908" />

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**

<img width="1991" height="790" alt="image" src="https://github.com/user-attachments/assets/a305cd6d-b885-43cf-8502-ac03647f5e4b" />

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**

<img width="2168" height="725" alt="image" src="https://github.com/user-attachments/assets/b6024103-8451-4f6e-93ee-33db8c25f9af" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**

<img width="2169" height="725" alt="image" src="https://github.com/user-attachments/assets/76ac1a36-61da-47e7-b52e-081f55c246a4" />

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**

<img width="1945" height="808" alt="image" src="https://github.com/user-attachments/assets/33003e03-262d-46b6-a3e8-a77ee3a894a2" />

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="1613" height="975" alt="image" src="https://github.com/user-attachments/assets/25ee5e9b-be42-4f8a-aaf6-2388e6732c40" />


### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```


**Output:**
<img width="1815" height="867" alt="image" src="https://github.com/user-attachments/assets/9646ed2e-ae16-42c5-9431-ce076cd738ba" />



### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**

<img width="1600" height="533" alt="WhatsApp Image 2026-09-06 at 9 56 11 PM" src="https://github.com/user-attachments/assets/e2695d8c-078b-4df0-a8ec-599b2f664789" />

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**

<img width="1600" height="533" alt="WhatsApp Image 2026-09-06 at 9 53 48 PM" src="https://github.com/user-attachments/assets/d803139b-57a2-4f2c-af6a-258b4f0e61fe" />

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**

<img width="1600" height="533" alt="WhatsApp Image 2026-09-06 at 9 51 50 PM" src="https://github.com/user-attachments/assets/a5a146e8-cf16-4df7-a0d4-2b4a7123c5f1" />

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="1600" height="769" alt="WhatsApp Image 2026-09-06 at 9 49 45 PM" src="https://github.com/user-attachments/assets/7ed59ad3-4457-435c-9b16-5af4768ff8ab" />

## Result

Linux commands are executed in the linux terminal successfully.

**NAME:** HEMAVARSHINI A

**REGNO:** 212225040127
