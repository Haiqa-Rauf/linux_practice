. Identifying the Current Directory
Task 1.1: Using pwd Command
Concept : The pwd command stands for "print working directory". It displays the full path to the current directory.
pwd
Explanation : Running the pwd command will print the absolute path of your current directory on the terminal. This helps in confirming where you are within the filesystem structure.
2. Exploring Directories
Task 2.1: Listing Files with ls Command
Concept : The ls command is used to list the contents of a directory.

Code Snippet :

ls
Explanation :
The basic ls command will list the files and directories in the current directory.
Task 2.2: Listing with Options
Concept : Options can modify the behavior of the ls command. Common options include:

-l for long format listing.

-a to include hidden files (files starting with a dot).

Code Snippet :

ls -la
Explanation : This command combines the -l and -a options to list all files, including hidden ones, in a detailed format.
3. Changing Directories
Task 3.1: Navigating with cd Command
Concept : The cd command is used to change the current directory.

Code Snippet :

cd [directory_path]
Example: To change to a directory named Documents:

cd Documents
Explanation :
If the directory path is relative (like Documents), it's based on your current location.
For an absolute path, provide the full directory path starting from root (e.g., /home/user/Documents).
Task 3.2: Navigating to Parent Directory
Concept : Use cd .. to move up to the parent directory.

Code Snippet :

cd ..
Explanation : This command will take you one level up the directory hierarchy.
Conclusion
By completing this lab, you should be able to confidently navigate and manage your filesystem using basic commands. Understanding these commands is fundamental for efficiently interacting with any Unix-like operating system.
