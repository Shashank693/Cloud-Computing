# **Basic Linux Commands - Part 3**

## Commands

### 11. **grep**

The `grep` command Searches for patterns in files. Find content from a specific file.


**Usage:** 
```bash
$ grep "sample" file.txt
```
**Output:**
```
This is a sample line.
```

**Explanation:**  
The `grep` command searches for lines in a file that match a given pattern. For example, `grep "sample" file.txt` finds lines containing "sample" in "file.txt".

### 12. **whoami**

The `whoami` command displays the current logged-in user.


**Usage:**
```bash
$ whoami
```

**Output:**
```
user
```

**Explanation:**  
The `whoami` command shows the username of the currently logged-in user.

### 13. **sudo**

The `sudo` command executes commands with superuser privileges.


**Usage:**
```bash
sudo ls /root
```
**Output:**
```
file_in_root
```
**Explanation:**  
The `sudo` command allows you to execute commands with superuser (root) privileges. For example, `sudo ls /root` lists files in the root directory.

### 14. **chmod**

The `chmod` command changes file permissions.


**Usage:**
```bash
$ chmod 755 file.txt
```

**Output:**
```
<No output, but permissions are changed>
```

**Explanation:**  
The `chmod` command changes the permissions of a file. For example, `chmod 755 file.txt` sets read, write, and execute permissions for the owner, and read and execute permissions for others.

### 15. **wget**

The `wget` command downloads files from the web.


**Usage:**
```bash
$ wget http://example.com/file.txt
```

**Output:**
```
--2024-09-11 10:00:00--  http://example.com/file.txt
Resolving example.com (example.com)... 93.184.216.34
Connecting to example.com (example.com)|93.184.216.34|:80... connected.
HTTP request sent, awaiting response... 200 OK
Length: 12345 (12K) [text/plain]
Saving to: ‘file.txt’
```

**Explanation:**  
The `wget` command downloads files from the internet. For instance, `wget http://example.com/file.txt` downloads "file.txt" from the specified URL.

### 16. **date**

The `date` command displays or sets the system date and time.


**Usage:**
```bash
$ date
```

**Output:**
```
Tue JULY 11 10:00:00 IST 2024
```

**Explanation:**  
The `date` command shows the current date and time. It can also be used to set the system date and time.

### 17. **curl**

The `curl` command transfers data from or to a server.


**Usage:**
```bash
$ tail -n 5 file.txt
```

**Output:**
```
<!doctype html>
<html>
<head>
<title>Example Domain</title>
</head>
<body>
<p>This domain is for use in illustrative examples in documents...</p>
</body>
</html>
```

**Explanation:**  
The `curl` command transfers data to or from a server. For example, `curl http://example.com` retrieves the content of the specified URL.

### 18. **7z**

The `7z` command compresses and decompresses files in 7z format.


**Usage:**
```bash
$ 7z x archive.7z
```

**Output:**
```
Everything is Ok                      ext.
```

**Explanation:**  
The `7z` command is used to handle 7z archive files. For instance, `7z x archive.7z` extracts files from "archive.7z".
### 19. **zip**

The `zip` command compresses files into a ZIP archive.


**Usage:**
```bash
$ zip archive.zip file1.txt file2.txt
```

**Output:**
```
  adding: file1.txt (deflated 58%)
  adding: file2.txt (deflated 60%)
```

**Explanation:**  
The `zip` command creates a compressed ZIP archive. For example, `zip archive.zip file1.txt file2.txt` compresses "file1.txt" and "file2.txt" into "archive.zip".

### 20. **tar**

The `tar` command archives files and directories, and optionally compresses them.


**Usage:**
```bash
$ tar -cvf archive.tar file1.txt file2.txt
```

**Output:**
```
file1.txt
file2.txt
```

**Explanation:**  
The `tar` command creates an archive of files and directories. The `-c` option creates a new archive, `-v` provides a verbose output, and `-f` specifies the filename. For instance, `tar -cvf archive.tar file1.txt file2.txt` creates "archive.tar" containing "file1.txt" and "file2.txt".

---


**Creator: Shashank Naik | Cloud Computing Intern, WEBXELA**

- [LinkedIn](https://www.linkedin.com/in/shashank-naik09061319)
- [GitHub](https://github.com/Shashank693)
---

