# **Command-line "cheat" sheet**
**hello hope you enjoy!!!**

## Abbreviation

pwd( print working directory)

cd (Change directrory)

cp (copy)

ls (lists)

gst: git status

mv: move

m: message

f: force

r: recursive

mkdir: make directory

## Change directory

pwd(print working directory) :shows path of current working directory

  * *Example:/Users/yourname* 

cd: goes to home directory

cd <name of folder> : changes directory to that named folder

cd .. : go to parent directory

cd - : goes back to previous or last folder browsed

ls :lists of folders and folders

ls -a :lists of all directory contents, this includes owner and date last modified 

ls -la : list of all directory contents, including any hidden files.

## Folders & Files

mkdir <BNTA>: create new folder or directory named BNTA

touch <lab>: creates new file named <lab> without extension

touch <lab>.extension: creates new file name <lab> with an extension.



cp <file> <directory>: copy file into desginated location

* *Example : cp file ..* 

rm <file> : to delete file

*rm -r <directory> : to delete directory (be VERY CAREFUL when do doing this command)

*rm -rf <directory> : to force delete the directory (be VERY CAREFUL when do doing this command)

*rm -rf ~ :delete all folders (WARNING DONT USE THIS!!)

open . : opens directory

mv : used to move or rename folder or files

* _Example 1:  mv name_1 name_2 renames name_1 to name_2_

* _Example 2 : mv name_1 .. moves the directory up_

## Git command line

git init: intialise a git repository for an existing directory

git add: add a file as it looks now to your next commit 

git commit -m "with your message": commit your staged content as a new commit snapshot

gst : show modified files in working directory

git log: show all commits in the current branch's history
