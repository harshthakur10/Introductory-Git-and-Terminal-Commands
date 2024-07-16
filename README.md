#  *Git and Uses of Basic Commands* 

![1_Vbbgb1GWEFgbuO4vbaqcxg](https://github.com/user-attachments/assets/4d8fe99b-bbcf-4976-b7a9-ccab938ee8f3)


This repository contains sample code snippets demonstrating basic file manipulation and Git commands.

# Contents

new_directory: A directory created to demonstrate basic file manipulation commands.

new_text.txt: A text file created within new_directory as part of the demonstration.

README.md: This README file explaining the contents and purpose of the repository.


## Code with Annotations:
**Create a new directory named "new_directory"**
		
          $ mkdir new_directory

**List the contents of the directory "Geekster"**
               
          $ ls Geekster
            Eda/  excel/  python/  sql/

**Change directory to "new_directory"**
               
          $ cd new_directory

**Create a new file named "file.txt"**
        
          $ touch file.txt

**Open the file "file.txt" in the nano text editor**

          $ nano file.txt

**Display the contents of the file "file.txt"**
          
          $ cat file.txt
          Hello! I hope you are doing Great.

**Print the present working directory (PWD) followed by "file.txt"**
          
          $ pwd file.txt
          /c/Users/Asus/new_directory

**Move the file "file.txt" to "new_text.txt" in the same directory**
          
          $ mv /c/Users/Asus/new_directory/file.txt /c/Users/Asus/new_directory/new_text.txt

**Attempt to list the contents of "new_directory" (which no longer exists)**
          
          $ ls new_directory
          ls: cannot access 'new_directory': No such file or directory

**Move up one directory level**
          
          $ cd ..

**List the contents of "new_directory" (to verify the presence of "new_text.txt")**

          $ ls new_directory
          new_text.txt

**Attempt to remove "new_directory" (which is a directory)**

          $ rm new_directory
          rm: cannot remove 'new_directory': Is a directory

**Remove the directory "new_directory" recursively (including all its contents)**

          $ rm -r new_directory

**Initialize an empty Git repository in the current directory**

          $ git init
          Initialized empty Git repository in C:/Users/Asus/.git/




### Functions and Keywords:
* mkdir: Creates a new directory.
* touch: Creates a new file.
* cd: Changes the current directory.
* nano: Text editor for creating or editing files.
* cat: Displays the contents of a file.
* pwd: Prints the present working directory.
* mv: Moves or renames files or directories.
* ls: Lists the contents of a directory.
* rm: Removes files or directories.
* git clone: Clones a repository from a remote URL.
* git init: Initializes a new Git repository.
* git add: Adds files or changes to the staging area.
* git commit: Records changes to the repository.
* git push: Uploads local changes to a remote repository.

