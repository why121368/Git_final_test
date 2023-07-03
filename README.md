# Git_final_test
### 时间
2023.7.3
### 地点
哈尔滨工业大学科学院2A-714
### Git常用命令总结
* 在Github账户下新建Repository
* 在本地项目仓库路径下打开Git Bash（或VSCode）
* echo "# final" >> README.md（或VSCode里新建README.md）
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/why121368/Git_final_test.git
* git push -u origin main
* git branch feature_1
* git checkout feature_1
* git push origin feature_1(* [new branch]      feature_3 -> feature_3,此时远程Repository里已经还有feature_1分支，但是还未与本地的feature_1建立联系)
* git push --set-upstream origin feature_1(branch 'feature_1' set up to track 'origin/feature_1'，此后联系正式建立)
* 合并到主分支，先切换到main，然后git merge feature_1，此时只是在本地merge了，要再git add,git commit,git push一下下
### Really final test!
<<<<<<< HEAD
=======


### FFFFFFinal!
### Merge
>>>>>>> feature_3
