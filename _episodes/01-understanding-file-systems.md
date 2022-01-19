---
title: "Understanding your file system"
teaching: 5
exercises: 40
questions:
- 
objectives:
- "Explain the hierarchical structure of a file system"
- "Understand the structure of the file system on their on machine"
- "Create, move and delete folders and files on their machine"
- "Understand what working directories, paths and relative paths are"

keypoints:
-
---
## What is a file system?

A file system is exactly what it sounds like - a way for your computer to store your data in an organised way using **files**.

You will definitely have come across **files** before. All the data stored on your computer is split into separate files, making it much easier to keep track of than if it was all in one big blob. 

There are lots of different file types; we can often find out something about what kind of data a file contains by looking at its **filename extension**. For example:
- **.txt** tells us that the file contains text
- **.exe** tells us that the file contains a program to be run
- **.html** tells us that the file contains a webpage, and should be run inside a web browser

We will come across various different file types during this course, some of which you may not have seen before. Do not worry. We will introduce them to you and explain how to use them when necessary.

In a file system, files are often organised into **directories**, which can also be called **folders**. Hopefully you will have used folders to organise your files before! Folders can contain sub-folders, which contain their own sub-folders, and so on. 

It is easiest to picture your file system as a tree, starting with the **root** (or **home**) directory and branching out from there. This is called a **hierarchical structure**. Here is an example of a hierarchical file structure:

![A file hierarchy containing 4 levels of folders and files](../fig/file-system-hierarchy-graphic.png){:height="500px"}

> ## Exercise
> Think about your own computer and how your files and directories are organised. Sketch a tree diagram like the one above for your file system.
>
> Hint: remind yourself of your file system's layout using a file manager application such as:
>
> - <img src="../fig/icon-file-explorer-windows.png" width="20px" align="left">  **File Explorer** in Windows.  
> - <img src="../fig/icon-finder-mac.png" width="20px" align="left">  **Finder** on Mac.
>
> You probably use these applications regularly to find and organise files.
{: .challenge}

## File Paths

It is not practical to draw out a tree diagram every time we want to refer to a file's location with a system. Instead, we can represent the information as a **file path**.

In a **file path**, each directory is represented as a separate component separated by a character such as `\` or `/`. It is like writing an address or set of instructions for someone to follow if they want to find a specific file.

For example, the path for the file called *doc3.txt* in the file system above looks like this:
`root/docs/data/doc3.txt`.


## Create a folder for the course

To keep things tidy and easily accessible, we will create a folder (directory) to keep everything related to this course: the key you will need to log in, your notes, data etc. 

In theory you can make this file anywhere in your file system but we recommend making it inside your Desktop folder, to make it easy to access.

1. **Create the folder** *cloudspan* in your *Desktop*.

   Minimise all windows until you can see your desktop background. Right click and select *New*, then *Folder*. Name the folder *cloudspan*.

   You should see a folder icon appear on your desktop with the label *cloudspan*.

   Additionally, if you enter your file explorer application you should be able to click on the *Desktop* directory at the side and see the *cloudspan* folder.

****

We will then download your login key file to that folder and change its access permissions for the reasons given below. Finally we will login into your instance with ssh.



2. **Download your login key file** to the folder you just created.

   Click on the link embedded in the email you received from the Cloud-SPAN team.
   
   **Mac users** may need to Click on 'download' when the file says it can't be opened.

   If your browser asks you "where do you want to download the file?", choose the directory for the course you just created.

   Otherwise, drag and drop your login key file from wherever it was downloaded to the folder for the course you created.
