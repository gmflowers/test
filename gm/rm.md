# 在工作区GUOMIIN下添加文件夹gm gm文件夹下添加文件rm.md文件   
## 查看仓库状态  
```
git status  
  
# 若出现  

fatal: not a git repository (or any of the parent directories): .git  

需要切换到仓库目录下去  

cd docs  
```
## 查看仓库状态  
```
git status  

# 若出现  
  
Untracked files: #未跟踪的文件：  
  (use "git add <file>..." to include in what will be committed) #（使用“git add <file> ...”包含将要提交的内容）  
   gm/  
```

## 则需要将文件gm/rm.md添加到暂存区  
```
git add gm\rm.md  
```

## 查看仓库状态  
```
git status  

# 若出现  
Changes to be committed: #要提交的更改:  
  (use "git reset HEAD <file>..." to unstage) #（使用“git reset HEAD <file> ...”取消暂存） 
```
是否要将暂存区更改的内容提交到本地；  
如果提交 
```
git commit -m "备注修改的地方"  
```

如果不提交,按提示进行  

## 查看仓库状态  
```
git status  
```

最后将本地文件提交到GitHub上  
```
git push  
```

输入GitHub账号及密码  
