创建git：建一个文件夹，打开gitbash 输入 git init



打开记录：git log 或 git-log 或git log --。。。。

查看该文件夹里git的状态：git status

添加入缓存：git add file1.txt 或 git add .

添加入仓库：git commit  -m 'add file1'

回退：git reset --hard p10101（滚轮能直接复制）

回退的回退：git reflog

不让某文件让git管理：touch .gitignore         vi .gitignore      *.a

mv 改名

rm 删除

i 插入模式

esc 退出插入模式

:w 保存

:q 退出

:wq 保存并退出



创建分支：git branch dev01

切换分支：git checkout dev01

创建并切换到分支：git checkout -b dev01

合并分支：git merge dev01

删除分支： git branch -d dev02



生成公钥： ssh-keygen -t rsa

获取公钥：cat ~/.ssh/id_rsa.pub



连接方式：生成公钥，获取公钥，上传公钥，在bash输入 ssh -T git@gitee.com 来连接

创建：git remote add origin(远端名称) git@gitee.com:hou-kaiyao/git_test.git(仓库路径)

查看是否创建成功：git remote

上传：git push f --set-upstream origin(远端名称) master(本地分支名称+远端分支名称) 或

git push origin(远端名称) master(本地分支名称) : master(远端分支名称) 

f :强制覆盖 一般不用

--set-upstream 建立起关联关系，以后直接 git push即可

显示分远端分支 git branch -vv

克隆git： git clone 路径  新名字

克隆只需要执行一次

抓取：git fetch

合并 git merge ...

抓取加合并 git pull

!!push之前要来个pull



java-git:

连接仓库  vcs creat new respository

上传   commit push

解决冲突  merge

拉项目： file->new -> from version control

创建分支  ：下方git ->右键分支图的节点



切换分支前先提交本地代码



















