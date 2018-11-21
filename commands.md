# List of Commonly used Terminal Commands

### Here is a list of commands which are useful for the making the day to day life of a programmer easier. Plus it performing tasks using the terminal gives an extra edge over in terms of efficiency since they're common across all UNIX systems, i.e., no hassle of navigating through file explorers and menus of differnet operating systems and what not.

```sh
$ ls -l
```
- List directory contents in long format. Output shows most of the info about files which one would need to know.

```sh
$ which [executable]
```
- A built-in SHELL command used to identify the location of executables. This is commonly used if a specific executable is installed in the system.

```sh
$ git status
```
- Displays the state of the working directory and the staging area. This is used extensively when working on projects which involve team collaboration and VCS.

```sh
$ man [name]
```
- man command is used to display the manual pages for a executable. It can be used as a reference to utilize the complete power of a specific command. This can be used before googling the usage of a command.

```sh
$ zip -r [zipped_name.zip] [directory]
```
- `zip` is used to compress the files to reduce file size and also used as file package utility. Handy utility tool which usually ships with UNIX. The above command is used to compress and package a folder which one would perform more often than not. `-r` stands for recursive zipping of files in the folder. 

```sh
$ unzip [zipped_name.zip] -d [directory]
```
- Here unzip command is used to extract files from a `.zip` file and move them to a specific directory. This goes hand in hand with the zip folder command.