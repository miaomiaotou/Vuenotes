#首先找到本地文件所在的文件夹里  git bash
  同时在页面建好服务器仓库

1.创建本地仓库
  git init
2.把工程加到本地仓库暂存区里
  git add .
3.把本地仓库和远程仓库连接起来
  git remote add origin +URL
4.把本地暂存区里的提交到本地库里
  git commit -m"（字符串就写写吧）"
5.把本地库里的提交到服务器库
  git push origin master
 6.查看服务器库
   git remote -v
 7.把服务器库的拉下来
  git pull origin master
8.把服务器库拉单本地(本地没有这个工程)
git clone