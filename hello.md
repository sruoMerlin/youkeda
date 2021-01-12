## git操作
```
mkdir youkeda
cd youkeda
git init // 初始化仓库
git remote -v // 查看是否有关联
git remote add origin https://github.com/sruoMerlin/youkeda.git // 关联远程仓库
git remote -v // 查看是否关联成功
touch hello.md
git add -A // 添加到暂存区
git commit -m "docs: 创建编辑hello.md" // 提交信息
git push --set-upstream origin master // 在远程仓库创建master分支并提交到master分支
```