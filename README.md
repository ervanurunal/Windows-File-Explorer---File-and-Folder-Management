## Windows File Explorer — File and Folder Management

### Overview

This lab demonstrates basic Windows file and folder management using **File Explorer**.

The tasks completed in this lab include:

* Creating folders and files
* Renaming files and folders
* Copying files and folders
* Moving files and folders
* Deleting files and folders
* Searching for files based on their contents

These are fundamental Windows IT support skills that are useful when troubleshooting user files, organizing data, and managing Windows systems.

### Tools & Resources
**Tools Used**
- Windows Virtual Machine
- Windows File Explorer
- Windows Search
- File and Folder Management tools
- Windows Desktop
- C:\ drive
- File Explorer search functionality

**Lab Type**
- Hands-on Windows File and Folder Management Lab

**Operating System**
- Windows

---

## 1. Opening File Explorer

Windows provides **File Explorer** as the graphical interface for managing files and folders.

File Explorer can be opened in two ways:

1. Click the **File Explorer** icon on the Windows taskbar.
2. Search for **File Explorer** using the Windows search bar and press **Enter**.

![Opening File Explorer](https://i.imgur.com/ruPxOnk.png)
![Opening File Explorer](https://i.imgur.com/OD2yafl.png)

**You can add folders to or remove folders from Quick access.**

![Quick Access](https://i.imgur.com/wHx4c5T.png)
![Quick Access](https://i.imgur.com/PETyRnz.png)

---

## 2. Understanding the Windows File System

Windows organizes files and folders in a hierarchical structure. The Windows virtual machine used in this lab stores its files under the `C:\` drive.

Windows drives are identified using letters.

The most common system drive is: `C:\`

---

## 3. Creating a Folder

### Objective

Create a new folder on the Desktop.

#### Steps

1. Open **File Explorer**.
2. Navigate to the **Desktop**.
3. Right-click an empty area.
4. Select **New**.
5. Select **Folder**.
6. Enter the folder name.
7. Press **Enter**.

For this lab, the example folder is:

```text
Ervanur's New Folder
```

#### Result

The new folder appears on the Desktop.

![Folder](https://i.imgur.com/KqJ4h9b.png)


---

## 4. Creating a Text File

### Objective

Create a new text document on the Desktop.

#### Steps

1. Navigate to the **Desktop**.
2. Right-click an empty area.
3. Select **New**.
4. Select **Text Document**.
5. Enter the file name.
6. Press **Enter**.

Example:

```text
Ervanur's Text Document.txt
```

#### Result

The new text document appears on the Desktop.

![File](https://i.imgur.com/AohhJaO.png)


---

## 5. Copying a Folder

### Objective

Copy the `Images` folder into the `Pictures` folder.

The original lab uses the following location:

```text
C:\Users
```

Inside this location are:

```text
Images
Pictures
```


![Folder HERE](https://i.imgur.com/vSuWXDF.png)


---

#### Step 2 — Copy the folder

Right-click:

```text
Images
```

Select:

```text
Copy
```

![Copy](https://i.imgur.com/mOjlJmg.png)

---

#### Step 3 — Open the destination

Open the:

```text
Pictures
```

folder.

---

#### Step 4 — Paste the folder

Right-click an empty area inside the `Pictures` folder and select:

```text
Paste
```

![Paste](https://i.imgur.com/ZeoqYD5.png)

---

#### Result

The `Images` folder is now located inside:

```text
C:\Users\Pictures
```

![Paste](https://i.imgur.com/SEOlcku.png)


---

## 6. Renaming Files and Folders

Files and folders can be renamed directly through File Explorer.

A typical process is:

1. Select the file or folder.
2. Right-click it.
3. Select **Rename**.
4. Enter the new name.
5. Press **Enter**.

For example:

```text
Ervanur's New Folder
   ↓
Rename
   ↓
My Super Folder
```

Renaming changes the name of the item without creating a separate copy.

![Rename](https://i.imgur.com/xuLjvaH.png)
![Rename](https://i.imgur.com/0wNI1uY.png)


---

## 7. Deleting a Folder

### Objective

Delete a folder using File Explorer.

Example:

```text
FolderToBeDeleted
```

#### Steps

1. Navigate to the folder containing the item.
2. Right-click the folder.
3. Select **Delete**.

![Delete](https://i.imgur.com/z5itIcv.png)


#### Result

The folder is removed from the directory.

---

## 8. Deleting a File

Files can be deleted in the same way as folders.

Example:

```text
FileToBeDeleted
```

#### Steps

1. Navigate to the file's location.
2. Right-click the file.
3. Select **Delete**.

![Delete](https://i.imgur.com/bcDYhYC.png)


### Result

The file is removed from the directory.

![Delete](https://i.imgur.com/RKDYt0S.png)


---

## 9. Searching File Contents

File Explorer can also be configured to search **inside files**, rather than only searching file and folder names.

This is useful when you know some text contained inside a file but don't know exactly which file contains it.

---

### Step 1 — Open File Explorer Options

Open File Explorer and select:

```text
View
```

Then select:

```text
Options
```

and choose:

```text
Change Folder and Search Options
```

---

## 10. Open the Search Settings

In the **Folder Options** window:

1. Select the **Search** tab.
2. Find the option:

```text
Always search file names and contents
```

3. Enable the option.
4. Click **OK**.

![Search](https://i.imgur.com/DeG65oh.png)

**Always search file names and contents** enabled.


---

## 11. Search Within File Contents

After enabling content searching, use the File Explorer search field to enter your search term.

File Explorer can then return files whose:

* File name matches the search
* File contents match the search

![Search](https://i.imgur.com/flnK8tr.png)

---

## 12. Skills Demonstrated

This lab demonstrated the following Windows IT support skills:

#### File Management

* Creating folders
* Creating text files
* Renaming files and folders
* Copying folders
* Moving files/folders
* Deleting files and folders

#### File System Navigation

* Navigating the Windows directory structure
* Working with the `C:\` drive
* Navigating between directories
* Using File Explorer's search functionality

#### Windows Troubleshooting Skills

Understanding how to locate, organize, copy, move, delete, and search for files is an important part of Windows technical support.

---

## 13. IT Support Relevance

These skills are commonly used by IT support specialists when helping users with issues such as:

* Missing files
* Incorrectly organized files
* Moving user data
* Creating folders for applications or projects
* Cleaning up unnecessary files
* Locating files containing specific information
* Troubleshooting file access problems

For example, if a user says:

> "I know the document contains the word 'invoice,' but I don't remember the file name."

An IT support specialist can use File Explorer's content-search functionality to help locate it.

---

## 14. Troubleshooting Scenario

#### Scenario

A user tells you:

> "I can't find an important document. I remember that the document contains the word 'security,' but I don't remember its filename."

#### Troubleshooting approach

1. Open **File Explorer**.
2. Navigate to the appropriate directory.
3. Enable:

```text
Always search file names and contents
```

4. Enter:

```text
security
```

5. Review the search results.
6. Identify the file containing the required information.

This demonstrates how File Explorer can be used as a basic troubleshooting and file-recovery tool.

---

## 15. Lab Summary

In this lab, I practiced managing files and folders in a Windows environment using File Explorer.

I learned how to:

* Navigate the Windows file system
* Create folders
* Create text files
* Rename files and folders
* Copy folders
* Move files and folders
* Delete files and folders
* Search file contents

These skills provide a foundation for Windows administration and IT support troubleshooting.

---

## 16. Cybersecurity Relevance

Although this lab focused on basic Windows file management, these skills are also relevant to cybersecurity.

Security analysts and IT professionals frequently need to:

* Navigate Windows directories
* Locate suspicious files
* Identify unfamiliar files and folders
* Review files during troubleshooting
* Organize investigation artifacts
* Search for specific information
* Understand where files are stored on Windows systems

Understanding normal Windows file organization is especially useful when investigating abnormal or suspicious activity.

---

