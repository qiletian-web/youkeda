echo "# youkeda" >> README.md
git init 将一个文件夹初始化为一个git仓库
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:qiletian-web/youkeda.git
git push -u origin main
git remote -v 查看当前git仓库绑定的远程仓库