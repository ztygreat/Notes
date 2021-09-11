### git clone远程仓库的分支
当我们想clone别人的在分支中修改的code时，我们在github中看到往往是master，并且我们clone下来的也是也是master，如下图，是一个工程的不同分支，当我点击不同的分支，其clone的https却是一样的，那么该如何clone我想要的分支呢？
####  1、
首先是把这个master分支（默认分支） clone下来

指令：git clone (your url)
#### 2、
查看当前的master有多少分支，这时你会发现你想要的分支也一定在里面

指令：git branch -a
#### 3、
指令：git checkout -b aaa origin/aaa

上面的语句作用是在本地创建新的分支，分支的名称是aaa，aaa也是我想要clone的分支的名字，这里为了便于理解将本地的分支名字和clone的分支名字设为一样，其实-b后面的aaa可以随意设置。执行完上述语句后，会发现你想clone的code已经在你的本地老老实实的待着了。