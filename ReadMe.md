今天觉得自己在github上建立的仓库太多，仓库里的东西也太乱。
太乱的仓库，让自己的思绪也乱七八糟，所以，问了一下度娘，如何把仓库删除！


So Easy !
> 在github上，打开自己的仓库，仓库右上方有个“Settings”,点开之后，在最下面有个红色Button"Delete this repository";输入要删除的仓库名，然后确认！

删除成功

我在电脑的F盘，又重新建了一个文件夹“New_Repository”

在此文件夹下，打开VSC ，克隆了一下新建的仓库。

git clone https://github.com/guofucheng1229/New_Repository_for_Python.git

warning: You appear to have cloned an empty repository.

警示：说我貌似克隆了一个空仓库。
* **

如何把上文再次发送到github上呢? 貌似前几天学习的东西都全忘记了。

温故而知新吧！

git add -A  将文件提交到暂存区

git commit -m "删旧建新，再温习"

git push origin master  今天重温，又有新发现：https://www.cnblogs.com/qianqiannian/p/6008140.html


fatal: not a git repository (or any of the parent directories): .git
致命:不是git存储库(或任何父目录):.git

遇到问题，可能是需要git init 