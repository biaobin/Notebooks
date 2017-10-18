# summary
1. modify your file 
1. git add *
1. git commit -m "what I just have done"
1. git push origin master 



# how to use git
- install git
- make the directory you want to be git repository
```
git init
```
- edit a file then add it to git
```
git add git.notes baba1.txt balala.txt ....
```
-  
```
git commit -m "what I have done just now."
```

# using githup
1. create ssh key
cd into ~/.ssh and type:
```
ssh-keygen -t rsa -C "biaobinli@foxmail.com"
```
2. go to github/account settings/ssh keys, add ssh key, paste the file in $id_rsa.pub$, this is for connecting with the github, and commit files to it.
 - github is a remote computer
 - for each computer you have to add a key
3. Go to github add a synch repository
4. get the two repository related. go to local computer,
```
git remote add origin git@github.com:michaelliao/learngit.git

git push -u origin master
```
5. After modifying the local files, type the following line:
```
git push origin master
``` 

