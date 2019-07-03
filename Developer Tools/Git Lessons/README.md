
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

___
