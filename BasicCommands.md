## Basic commands :

### Profile setup

```
git config --global user.name ajay                                                                        
git config --global user.email ajay.kumar.awscloud@gmail.com    
git init

```


`git status`  ==> status of untracked files.

![image](https://user-images.githubusercontent.com/31384241/59270826-12bb4780-8c70-11e9-9bb6-a4f09ac0ad2b.png)


`git add <file_name>`  ==> to add file

`git add -A`           ==> to add all files

`git commit -m "file added"`  ==> to commit files we have added. `-m` means message.

`git checkout file_name` . ==> match the values from last commit.

`git checkout -f`         ==> match the values from last commit for all files.

`git log`      ==> which person commited what ...

`git log -p -1` .  ==> last 1 log

`git log -p 10`     ==> last 10 logs.

`git diff ` . ==> to see changes before commiting.
