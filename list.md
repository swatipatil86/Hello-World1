									Welcome to Unix

UNIX Commands:

1.ls: List 

Use this command to list the contents of the current directory. This will display all files and directories within the current directory.

2.mkdir:  make directory

Use this command to create a new directory.

3.cd: change directory

Use cd command to switch from one directory to another.

Using cd without a directory name following it will always return you to your home directory.

To "back up" a level in the directory structure from a subdirectory to its parent directory, you can use cd ..  

4.history:

history command is used to view the previously executed command.

5.clear: 

This command is used to clear the command prompt.

6.date:

Displays system date and time

7.rm :

rm filename --- removes a file

8.wc :

wc filename --- tells you how many lines, words, and characters there are in a file.



Steps followed in git bash to push changes made in local file to git hub repository:


	kdeep@DeepakThinkpad MINGW64 ~/explore/Hello-World1 (main)
	$ git add list.md
	warning: in the working copy of 'list.md', LF will be replaced by CRLF the next time Git touches it

	kdeep@DeepakThinkpad MINGW64 ~/explore/Hello-World1 (main)
	$ git commit -m "Unix Commands added to the file"
	[main c96c9c2] Unix Commands added to the file
	 1 file changed, 39 insertions(+), 1 deletion(-)

	kdeep@DeepakThinkpad MINGW64 ~/explore/Hello-World1 (main)
	$ git push -u origin main
	Enumerating objects: 5, done.
	Counting objects: 100% (5/5), done.
	Delta compression using up to 8 threads
	Compressing objects: 100% (3/3), done.
	Writing objects: 100% (3/3), 699 bytes | 699.00 KiB/s, done.
	Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
	remote: Resolving deltas: 100% (1/1), completed with 1 local object.
	To https://github.com/swatipatil86/Hello-World1.git
   	f645438..c96c9c2  main -> main
	branch 'main' set up to track 'origin/main'.


