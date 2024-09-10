# **Basic Linux Commands - Part 4**

## Commands

### 21. **ps**

The `ps` command displays information about running processes.


**Usage:** 
```bash
$ ps aux
```
**Output:**
```
USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         1  0.0  0.1  16956  4380 ?        Ss   Sep10   0:00 /sbin/init
user      1093  0.1  0.2  27224  9448 pts/0    S+   10:03   0:00 bash
```

**Explanation:**  
The `ps` command displays information about currently running processes. For example, `ps aux` shows a detailed list of all processes.

### 22. **unzip**

The `unzip` command extracts files from a ZIP archive.


**Usage:**
```bash
$ unzip archive.zip
```

**Output:**
```
Archive:  archive.zip
  inflating: file1.txt
  inflating: file2.txt
```

**Explanation:**  
The `unzip` command extracts files from a ZIP archive. For example, `unzip archive.zip` extracts the contents of "archive.zip".

### 23. **mkdir**

The `mkdir` command creates a new directory.


**Usage:**
```bash
mkdir new_directory
```
**Output:**
```
<No output, but a new directory named 'new_directory' is created>
```
**Explanation:**  
 The `mkdir` command creates a new directory. For instance,  `mkdir new_directory` creates a directory named "new_directory".

### 24. **rm**

The `rm` command removes files or directories.


**Usage:**
```bash
$ rm file.txt
```

**Output:**
```
<No output, but 'file.txt' is deleted>
```

**Explanation:**  
 The `rm` command deletes files or directories. For example, `rm file.txt` removes "file.txt" from the current directory.

### 25. **file**

The `file` command determines the type of a file.


**Usage:**
```bash
$ file file.txt
```

**Output:**
```
file.txt: ASCII text
```

**Explanation:**  
The `file` command identifies the file type. For instance, `file file.txt` shows that "file.txt" is an ASCII text file.

### 26. **shred**

The `shred` command securely deletes files by overwriting them.


**Usage:**
```bash
$ shred -u file.txt
```

**Output:**
```
<No output, but 'file.txt' is securely deleted>
```

**Explanation:**  
The `shred` command securely deletes files by overwriting them multiple times. For instance, `shred -u file.txt` securely deletes "file.txt".

### 27. **sha256sum**

The `sha256sum` command computes the SHA-256 hash of a file.


**Usage:**
```bash
$ sha256sum file.txt
```

**Output:**
```
e99a18c428cb38d5f260853678922e03  file.txt
```

**Explanation:**  
The `sha256sum` command calculates the SHA-256 hash of a file, which can be used for file integrity verification.

### 28. **md5sum**

The `md5sum` command computes the MD5 hash of a file.


**Usage:**
```bash
$ md5sum file.txt
```

**Output:**
```
5eb63bbbe01eeed0934cc731d71c1d6d  file.txt                ext.
```

**Explanation:**  
The `md5sum` command calculates the MD5 hash of a file. This hash value can be used to verify the integrity of the file.

---

**Creator: Shashank Naik | Cloud Computing Intern, WEBXELA**

- [LinkedIn](https://www.linkedin.com/in/shashank-naik09061319)
- [GitHub](https://github.com/Shashank693)
---

