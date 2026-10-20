Objectives:

Understand the basic operations for managing directories in a filesystem.
Learn how to create, remove, move, and rename directories using command-line tools.
Prerequisites:

Basic understanding of using a terminal or command line interface.
Access to a Unix-like operating system (Linux, macOS).
Introduction
In this lab, we will explore fundamental directory operations using the command line. Managing directories efficiently is a critical skill for organizing files and maintaining a streamlined workflow in a Unix-like environment.

Tasks
Task 1: Create a Directory Using mkdir
Objective: Learn how to create a new directory.

Explanation:

The mkdir command is short for "make directory." It creates a new, empty directory at the specified path.
Steps:

Open your terminal.

To create a directory named my_new_directory, use the following command:

mkdir my_new_directory
Verify the directory was created by listing the contents of the current directory:

ls
Example: If you want to create a subdirectory inside an existing directory, use:

mkdir existing_directory/sub_directory
Task 2: Remove a Directory with rmdir
Objective: Learn how to remove an empty directory.

Explanation:

The rmdir command removes empty directories. If the directory contains files or subdirectories, rmdir will not work.
Steps:

Ensure my_new_directory is empty.

To remove the directory, use:

rmdir my_new_directory
Confirm it was removed by listing the directory contents:

ls
Important: For removing directories with content, use rm -r cautiously, as it will recursively remove all content:

rm -r directory_with_contents
Task 3: Move or Rename a Directory with mv
Objective: Learn how to move or rename directories.

Explanation:

The mv command is used for both moving and renaming files and directories.
Steps:

Renaming a Directory:
Make sure you have a directory named old_directory.

Rename it to new_directory using:

mv old_directory new_directory
Verify the rename by listing:

ls
Moving a Directory:
To move new_directory into another directory called parent_directory, use:

mv new_directory parent_directory/
Confirm the move:

ls parent_directory/

Key Concepts:

mkdir: Create new directories.
rmdir: Remove empty directories.
mv: Move or rename directories.
