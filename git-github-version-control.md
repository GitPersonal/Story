# **`Git`**

## `Initialize Git`

In terminal type `git init` in the directory you are currently working on.

a `.git` file will be created in the working directory and you won't be able to see it. You can see it by typing `-a` to see all the hidden files.

## `Track files`

To start tracking file changes you need to add the file to the `stagging area`

## `Git status`

To view what is in the `stagging area` type `git status`.

You will see all the untracked files in red. The file is still in the `working directory` and is not yet in the stagging area. 

## `Git add`

To start tracking files you need to type `git add {filename}` 

After doing `git add {filename}` type `git status` to see the change. 

The file added is now green.

## Git commit

Type `git commit -m "initial commit message"`

You will now see the Author or person who made the commit and the time of the commit.

Adding new files to the stagging area. Type `git status` and you'll see the untracked files in red.

add these files by typing `git add {file name}` and add the next file by adding the `git add {filename}` of the next file. Or you can just type `git add .`
This will add all the files.
 
