
# Udacity FSND Git Lessons


## Command List

1. Use the ```git init``` command to create a new, empty repository in the current directory.

```` shell
$ git init
````
>Running this command creates a hidden **.git** directory. This .git directory is the brain/storage center for the repository. It holds all of the configuration files and directories and is where all of the commits are stored.

___

2. The ```git clone``` command is used to create an identical copy of an existing repository.
   ```` shell
   $ git clone <path-to-repository-to-clone>
   ````
>This command:
>* takes the path to an existing repository
>* by default will create a directory with the same name as the repository that's being cloned
>* can be given a second argument that will be used as the name of the directory
>* will create the new repository inside of the current working directory

___

3. The ```git status``` command will display the current status of the repository.

   ```` shell
   $ git status
   ````

>This command will:
>* tell us about new files that have been created in the Working Directory that Git hasn't started tracking, yet
>* files that Git is tracking that have been modified

____

4. The ```git log``` command is used to display all of the commits of a repository.
   
   ```` shell
   $ git log
   ````
>By default, this command displays:
>* the SHA
>* the author
>* the date
>* and the message
>...of every commit in the repository. I stress the "By default" part of what Git displays because the git log command can display a lot more information than just this.

>Git uses the command line pager, Less, to page through all of the information. The important keys for Less are:
>* to scroll down by a line, use j or ↓
>* to scroll up by a line, use k or ↑
>* to scroll down by a page, use the spacebar or the Page Down button
>* to scroll up by a page, use b or the Page Up button
>* to quit, use q
>
>We'll increase our git log-wielding abilities in the next lesson when we look at displaying more info.

____