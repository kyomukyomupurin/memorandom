# Git

## Reset local repository branch to be just like remote repository HEAD

[Link](https://stackoverflow.com/questions/1628088/reset-local-repository-branch-to-be-just-like-remote-repository-head)  
```git fetch origin```  
```git reset --hard origin/master```

## Git push without entering URL & password

[Link](https://help.github.com/en/articles/connecting-to-github-with-ssh)  
```git remote set-url origin git@github.com:user_name/repository_name.git```  
copy and paste ~/.ssh/id_rsa.pub to https://github.com/setting/ssh/new  
...Now you can push directly!
