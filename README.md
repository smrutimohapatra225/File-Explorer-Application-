Project Overview
The Linux File Explorer is a console-based application developed in C++ that interacts directly with the Linux operating system to perform essential file and directory management operations.It replicates the basic functionality of a file manager, but in a command-line interface (CLI), offering an efficient and lightweight way to manage files using simple commands.This project demonstrates the use of C++17 filesystem libraries, object-oriented programming principles, and Linux file permission management — showcasing both system-level programming and structured logic design.


Objective
The primary objective of this project is to build a command-line file explorer that allows users to:
-View directory contents
-Navigate through directories
-Create, delete, copy, and move files or folders
-Search for files within the system
-Manage file permissions
The project helps in understanding how C++ interacts with the Linux filesystem, and provides hands-on experience with low-level file operations and permission handling.


Day-wise Implementation
Day   	              Task	                                           Description
Day 1	              List Files	                          Designed the structure and implemented directory listing using <filesystem>
Day 2	              Navigation	                          Added directory traversal commands such as cd and ls
Day 3	              File Manipulation	                    Enabled file operations like cp, mv, rm, mkdir, and touch
Day 4	              Search                               	Implemented recursive search functionality using file iteration
Day 5             	Permissions                         	Integrated permission view and modification features (viewperm, chmod)


Features Implemented

✅ List all files and folders within a directory
✅ Navigate through directories easily
✅ Copy, move, rename, delete, and create files/folders
✅ Recursively search files by name
✅ View and modify file permissions
✅ User-friendly CLI interface with error handling


Commands Used
Command	                   Description
ls	                    List directory contents
cd <dir>	              Change current directory
cp <src> <dest>	        Copy file
mv <src> <dest>	        Move or rename file
rm <file>	              Delete file
mkdir <folder>	        Create a directory
touch <file>	          Create an empty file
search <filename>      	Search for a file recursively
viewperm <file>	        View file permissions
chmod <octal> <file>	  Change file permissions (e.g., chmod 755 file)
exit	                  Exit the explorer


Project Architecture

1.main.cpp — Core logic of the application
2.Functions Implemented:
           -Directory Listing
           -File Operations
           -Navigation
           -Recursive Search
           -Permission Management
3.Input/Output Flow:
           -User inputs commands through the terminal
           -Application processes commands
           -Outputs are displayed on the console in formatted text



Conclusion

The Linux File Explorer project successfully demonstrates the ability to develop a system-level application in C++ that interacts directly with the Linux operating system.
It includes all essential file management functionalities — from listing and navigation to file manipulation and permission control — packaged into an intuitive and user-friendly console interface.

This project enhanced understanding of:
-File handling and directory traversal in C++
-Recursive algorithms and exception handling
-Linux file permission concepts
-Command-line user interaction and automation
