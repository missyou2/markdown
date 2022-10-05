## Git (Week 6)

👋 Welcome to Git!

*Start command*
```
$ git config --list
```  
Show you all config list

```
$ git config --global user.name "(Your name)"
$ git config --global user.email "(Your e-mail address [aaa@example.com])"
```
Type the commands above. What has been changed compare to first?

```
$ git init
```  
initialize your .git directory, but you can't see this folder the normal way. So type ```$ ls -lha``` to see your .git files.


```
$ git status
```  
you can see untracked files by git. If you add your file in stage, enter ```$ git add (file name)```.  
if you changed your file contents with ```$ nano```, git will not be able to staged.  
So, use ```$ git add (file name)``` once more.

```
$ git add .
```
Add your whole file which in current dirctory to stage area.

```
$ git rm --chaced (file name)
```
unstaged your file. **Be careful! if you use** ```rm``` **command mistake, your file will removed entirely!**

```
$ nano .gitignore
```  
make your file and list which you want to ignore.  

```
$ git commit -m (commit message)
```  
Snap your current file version.

```
$ git log
```  
Check your list which you snapshoted.

```
$ git branch
```  
Check your branch name, and you can change it by using ```$ git branch -m (current name) (new name)```command.
