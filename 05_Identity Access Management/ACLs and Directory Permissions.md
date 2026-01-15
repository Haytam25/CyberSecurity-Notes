### **What are ACLs (Access Control Lists)?**

- **ACLs** define _which users or system processes_ are granted access to objects (like files/directories), and **what operations** are allowed.
- Used by operating systems (Windows, Linux, etc.) to enforce **authorization**.

### 📌 **Basic ACL Permissions**

- **Read**: View the contents
- **Write**: Modify or add content
- **Execute**: Run the file or access the directory

### **Windows ACLs**

- Managed via **NTFS permissions**
- Stored as part of file metadata
- Controlled through the **Security tab** in file/folder properties

**Common NTFS Permissions:**

|Permission|Description|
|---|---|
|Full Control|Read, write, execute, delete|
|Modify|Read/write but not delete perms|
|Read & Execute|Open files and run executables|
|List Folder|View folder contents|
|Write|Add files/folders|
|Read|View contents and attributes|

### **Linux Permissions**

- **Three types of users**:
    
    - `Owner`
    - `Group`
    - `Others`
- **Permission types**:
    
    - `r` = read
    - `w` = write
    - `x` = execute
- - `hmod`: change permissions
    
- `chown`: change file owner
    
- `ls -l`: view permissions

