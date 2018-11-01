# Git Learning

## 克隆仓库
git clone https://github.com/gmflowers/test.git

## 查看仓库状态
git status # 需要切换到仓库目录下去，否则会报错 fatal: not a git repository (or any of the parent directories): .git

## 添加 docs 目录

## 添加 git-learning.md 文件，并且编辑该文件

## 查看仓库状态
git status

## 添加到本地 repo
git add docs\git-learning.md  
git status

提示需要设置 邮箱 和 姓名（首次登陆需要设置)  
git config --global user.email "gmin_yting0315@163.com"  
git config --global user.name "rm花儿朵朵"  

提交到本地 -m(注释)  
git commit -m "add git-learning file"  
git status # 疑惑: origin/master 是什么?    

提交到GitHub  
git push  

提示需要GitHub的账号及密码  

git status
