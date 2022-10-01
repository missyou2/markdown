# Linux 5 Week

*Reminder*: Linux is a multi-user system.

---

You can use '>' to save result as .txt file.

*For example,*
```
$ls -lh > file_list.txt
```
Save result of ```$ls -lh``` in file_list.txt

```
$ cat (file name)
```
Show text file's contents.  
Use '>>' when append, but if there is no file exists, then they create a new file.

*for example*: ```$ ls -lh >> file_list.txt```

Using '<' when you make output.  
You can use '<' and '>' at once.

example:
```
$ sort < words.txt > sorted_result.txt
```
↑ output saved in ***sorted_result.txt***

```
|
```
This charater is neither "I" nor "L", mostly you can enter this command nearby "Enter" in your keyboard.  
example: ```$ (command 1) | (command 2)```

```
$ echo (text)
```
print (text).

```
\
```
use this command when you enter command continuously.

## Permissions
___ ___ ___  
owner / groups / others  
r w x  
r: read  
w: write  
x: execute
based on binary system.

```
$ chmod (number) (file name)
```
example: ```$ chmod 600 your_text```  
6:110  
0:000  
0:000  
So, it means rw- --- ---  
Result: Owners can read/write/execute, but others can't.

"sudo" commands meaning of superuser.

```
$ nano (file name)
```
open text editor.

```
$ history
```
Show previous history.
for example, you can use this with '>' commands.

```$ history > history.txt```
