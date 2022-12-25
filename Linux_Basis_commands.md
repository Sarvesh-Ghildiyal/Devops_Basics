## Basics Linux commands
Here we will be discussing about basic linux commands to get u started on, how to work in CLI

### For Directories
cd-> change directory  

ls-> list files and directory in your present location  

pwd-> shows your present location "present working directory"

mkdir-> make directory in the given location

mkdir -p -> helps in making directory tree all at once

rm-> remove flie/directory

rm -r-> remove directory with all of its contents


### For Files
touch file_name-> to create an empty file

cat > file_name-> to create a file and enter its content, when u are done entering its content , press CTRL+D, to save it
>cat > hello.txt  
>hello how are you doin buddy?  
>CTRl+D

cat hello.txt-> to view content of hello file

> touch hi.txt
cp hello.txt hi.txt-> this commands copies content of hello file ot hi file in the same directory


```
cd /temp
mkdir -p /temp/new/h
cd /temp/new/h
touch hello.txt

```

mv /temp/new/h/hello.txt /temp/new-> this will move hello.txt file form h folder to new folder :::::So now the contents of temp folder are "new" and "hello.txt"




> Now to edit a created file various text editors in linux can be used, like nano, vim, and vi

So hello.txt can be edited again using:

nano hello.txt
