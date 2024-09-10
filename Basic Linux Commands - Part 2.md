# **Basic Linux Commands - Part 2**

## Commands

### 1. **echo**

The `echo` command outputs the text you provide to the terminal.It is used to for returning any character, word, sentence, it basically returns back whatever we command.


**Usage:** 
```bash
$ echo "Hello, World!"
```
**Output:**
```
Hello, World!
```

**Explanation:**  
The `echo` command is used to display a line of text or a variable's value. In real life, you could use this command to quickly output messages or to check the values of variables in scripts.

### 2. **ls**

The `ls` command outputs Lists directory contents given the currunt directory all the folders and files.


**Usage:**
```bash
$ ls -l
```

**Output:**
```
total 4
drwxr-xr-x 2 user user 4096 Sep 11 10:00 Documents
drwxr-xr-x 2 user user 4096 Sep 11 10:00 Downloads
```

**Explanation:**  
The `ls` command shows the files and directories in the current directory. The `-l` flag provides a detailed listing, including file permissions, owner, group, size, and modification time.

### 3. **cd**

The `cd` command changes the current directory.


**Usage:**
```bash
$ cd pwd 
$ cd Desktop 
$ cd .. 
$ cd ~
```

**Explanation:**  
The `cd` command changes the directory you're currently in. For example, `cd Documents` moves you into the "Documents" directory.

### 4. **cat**

The `cat` command concatenates and displays file contents.


**Usage:**
```bash
$ cat file.txt
```

**Output:**
```
This is the content of file.txt.
```

**Explanation:**  
The `cat` command displays the contents of a file. For instance, `cat file.txt` prints the contents of "file.txt" to the terminal

### 5. **tac**

The `tac` command displays file contents in reverse order.


**Usage:**
```bash
$ tac file.txt
```

**Output:**
```
Last line
Second to last line
First line
```

**Explanation:**  
The `tac` command is `cat` in reverse. It displays the contents of a file starting from the last line and moving upwards.

### 6. **head**

The `head` command displays the first few lines of a file.


**Usage:**
```bash
$ head -n 5 file.txt
```

**Output:**
```
Line 1
Line 2
Line 3
Line 4
Line 5
```

**Explanation:**  
The `head` command shows the first 10 lines of a file by default, or a specified number if using `-n`. For example, `head -n 5 file.txt` shows the first 5 lines of "file.txt".

### 7. **tail**

The `tail` command displays the last few lines of a file.


**Usage:**
```bash
$ tail -n 5 file.txt
```

**Output:**
```
Line 96
Line 97
Line 98
Line 99
Line 100
```

**Explanation:**  
The `tail` command shows the last 10 lines of a file by default, or a specified number if using `-n`. For example, `tail -n 5 file.txt` displays the last 5 lines of "file.txt".

### 8. **xxd**

The `xxd` command creates a hex dump of a file or converts a hex dump back to binary.


**Usage:**
```bash
$ xxd file.txt
```

**Output:**
```
00000000: 5468 6973 2069 7320 7361 6d70 6c65 2074  This is sample t
00000010: 6578 742e 0a                           ext.
```

**Explanation:**  
The `xxd` command creates a hex dump of a file, showing its binary content in hexadecimal format.

### 9. **base64**

The `base64` command encodes or decodes data in base64 format.


**Usage:**
```bash
$ base64 file.txt
```

**Output:**
```
VGhpcyBpcyBhIHNhbXBsZSBmaWxlLg==
```

**Explanation:**  
The `base64` command encodes data into base64 format. This is often used for data transfer and encoding.

### 10. **find**

The `find` command searches for files and directories.


**Usage:**
```bash
$ find . -name "*.txt"
```

**Output:**
```
./file1.txt
./folder/file2.txt
```

**Explanation:**  
The `find` command searches for files and directories that match criteria. For instance, `find . -name "*.txt"`` finds all ``.txt` files in the current directory and subdirectories.


---
---

**Creator: Shashank Naik | Cloud Computing Intern, WEBXELA**

- [LinkedIn](https://www.linkedin.com/in/shashank-naik09061319)
- [GitHub](https://github.com/Shashank693)
---

