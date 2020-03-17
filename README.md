# File Segregation Shell script

This shell script segregates files in a folder based on the extension of files. For instance all `.sh` files will be moved to a separate folder.

## How to use?
1. Go to directory where the shell script `file_seg` is stored. 
2. `chmod +rwx file_seg`, to give executable permission for the shell script.
3. `export PATH=$PATH:$PWD` to add path of the shell script to the Envionment PATH variable.
4. Run the script using command `file_seg`, if segregation to be done in present working directory
5. Run the script using command `file_seg directory_path`, if segregation to be done in another directory. (Here `directory_path` is path of the directory where segregation has to be done)

#### Files before execution of command:

![alt text](https://github.com/pprakarsh/File_segregation_bash_script/blob/master/ls_file_seg_before.png)

#### Executing the command
![alt text](https://github.com/pprakarsh/File_segregation_bash_script/blob/master/command_file_seg.png)

#### Files after execution of command:
![alt text](https://github.com/pprakarsh/File_segregation_bash_script/blob/master/ls_file_seg_after.png)

