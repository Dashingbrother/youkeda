绑定本地仓库到githud
1、先在githud建一个同名的空仓库（一般不勾选Readme.md,这样可以看到配置的提示，并且可以避免代码冲突）
2、用cd命令进入同名文件夹，用git init命令将一个文件夹初始化为一个git仓库（如果初始化错误，删除刚创建的git文件（隐藏文件），然后进入正确文件夹进行初始化）
3、绑定远程仓库：git remote add origin 仓库地址（可以用git remote -v查看当前绑定的仓库，如果错误，可用git remote remove origin来移除绑定）