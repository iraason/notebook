git config --global user.email "yungxeon@gmail.com"
git config --global user.name "yungxeon"

##### 创建一个空目录
> mkdir learngit

##### 把这个目录变成Git可以管理的仓库
> git init

##### 把文件添加到仓库
> git add readme.txt
> git add .

##### 把文件提交到仓库
> git commit -m "wrote a file"

##### Unix通用的diff格式
> git diff

##### 查看commit历史记录
> git log --pretty=oneline

##### 通过commit id回退到某一个版本
> git reset --hard 《commitId》

##### 退到上两个版本
> git reset --hard HEAD^^

##### 查看历史git命令
> git reflog

##### 文件管理器中把没用的文件删了
> git status
> git rm test.txt
> git commit -m "remove test.txt"

##### 创建SSH keys 并把公钥放入github的ssh设置中
> ssh-keygen -t rsa -C "iraason@gmail.com"

##### clone到本地
 git clone git@github.com:iraason/japanese.git
 
 
 #####  常用命令
git pull> git add ->git commit -> git push

