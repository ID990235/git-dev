## git分支预习

- 创建dev分支：git branch dev 

- 切换分支(切换到master分支)：git checkout master

- 创建并切换到dev分支：git checkout -b dev

- 合并分支dev到master主分支，先切换到要合并的分支，再把dev分支合并到当前分支

  git checkout  master    

  git merge  --no-f  dev  -m  '合并的信息'

- 提交分支dev到远程：git push origin dev

