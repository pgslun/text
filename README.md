# 前端效果操作：

**步骤一**：登录到Github上，新建一个repo，命名为test，勾选 initialize this repository with a README，点击create repository。

 

 ![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305134947346-1921005167.png)

![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305135528627-97762586.png)

**步骤二**：打开settings，有一个Github Pages 的设置，点击 source 中的本来的 None ，使其变成 master 分支，也就是作为部署github pages 的分支，然后点击 save(没有就自动保存)。

![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305140204096-424861698.png)

![img](https://images2015.cnblogs.com/blog/903320/201701/903320-20170115212404385-1979000093.png)

 

**步骤三**：页面刷新之后，再看 github pages 设置框处，多了一行网址，就是你的 github pages 的网址了。

![img](https://images2015.cnblogs.com/blog/903320/201701/903320-20170115213630338-44375750.png)

 

点击这个链接

![img](https://images2015.cnblogs.com/blog/903320/201701/903320-20170115213708181-1344935302.png)

**步骤四** ：打开此电脑，选择一个盘，比如 f 盘，右键空白处点击 git bash here。

![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305143603580-1181123251.png)

**步骤五**：输入如下命令，用来在 f 盘创建 test 文件放你的github上的test repository，克隆test repository到 test 文件中。

这个时候你的 f 盘，就会多一个 test 文件，打开它，

mkdir test

cd test

git clone http://github.com/pgslun/test.git

git add .

git commit -m ""

git pull

git push

![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305144226284-240519711.png)

![img](https://images2015.cnblogs.com/blog/903320/201603/903320-20160305144422830-1748939517.png)

 

会看到一个 README.md 的文件，这个文件是从哪来的呢？追溯到gihub上，你会发现 README 文件是来自 master 分支。