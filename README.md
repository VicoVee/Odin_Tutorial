# CLI List
A list of commands when using the command terminal
1. `ls [directory name]`: Prints all files/directories from the specified directory
2. `pwd`: Prints the current working directory
3. `cd [directory-name/directory-name2/dir...]`: Go forward to different directories
   - `cd ../`: Go backwards one directory
   - `cd ~`: Go to root directory
5. `mkdir [directory-name]`: Create a new directory in the current working directory
6. `rm [file-name]`: Removes a file
   - `rm -r [directory-name]`: When you want to remove a whole directory w/its files
8. `mv [directory/file] [directory/file]`: Moves the specified file to a new location. If both locations are the same, it would rename the current file to the new one.
9. `cp [directory/file] [directory/file]`: Copies a file/directory to a new location. The old file still exists.
10. `nano [file-name]`: Edits a file. After you finish, writeout (ctrl+O), return, and then exit (ctrl+X)
11. `[command] [file1] > [file2]`: Overwrites the file contents to another file
12. `[command] [file1] >> [file2]`: Appends the file contents to another file
13. `[command1] | [command2] | ...`: You can pipe commands together in one line using `|`
    - NOTE: Order matters! The previous command can impact the next command

### NOTE
- All file and directory names MUST BE UNIQUE
- Deleting files/directories are PERMANENT. You CANNOT recover them
- WILDCARDS: When searching for a more general files/directory, you can use `*` for any characters/words AND `?` for a single character
  - `*.txt` shows all text files
  - `?at.txt` shows all text files that ends in `-at.txt`
