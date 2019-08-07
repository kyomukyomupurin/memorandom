# Git

## Reset local repository branch to be just like remote repository HEAD

```git fetch origin```  
```git reset --hard origin/master```

## Git push without entering URL & password

```git remote set-url origin git@github.com:user_name/repository_name.git```  
copy ~/.ssh/id_rsa.pub to [](https://github.com/setting/ssh/new)  
...Now you can push directly!
