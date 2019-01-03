# List of Commonly used Terminal Commands

#### Here is a list of commands which are useful for the making the day to day life of a programmer easier. Moreover, performing tasks using the terminal gives an extra edge over in terms of efficiency since they're common across all UNIX systems i.e., no hassle of navigating through file explorers and menus of different operating systems and what not.



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

```sh
$ git pull
```
- Used to fetch and download content from a remote repository and immediately update the local repository to match that content. It is a good practice to use `git pull` when working in teams since the changes are brought about to the remote repository and it'd be very efficient to keep out local repository updated as much as possible.

```sh
$ git merge master
```
- This command is used to merge the contents of `master` branch to the `feature_branch` which you're currently on. Like the previous command, this helps in keeping your local repo and yout branch up-to-date with latest `master`.

```sh
$ [command1] && [command2] && ... [commandN]
```
- When we need to execute a set of commands on after the other wherein you need to wait in between individual commands, we can chain them together using `&&`, sit back and wait for all of them to be executed in sequence. Again, this helps in being more efficient if used properly.

```sh
$ git commit -m "Type in your commit message here"
```
- Probably the most frequently utilized command wherein you commit your local changes to the repo. It is highly recommended to create alias for this command as well as any other frequently used git commands

```sh
$ git commit --amend -m "Make changes to previous commit"
```
- Used to make changes to previous commit and also change the commit message at the same time. This works only if the commit has not been pushed to remote repo, otherwise local & remote repos will have diverged.

```sh
$ git commit --amend --no-edit
```
- This command is similar to the previous one but can be used when you don't to change the commit message.

```sh
$ take [dir_name]
```
- Must have Oh My Zsh installed. This command will create a new directory and change to it.
