# 我的 Git 学习笔记

1\. git add 的作用是：把文件的修改放进暂存区。实验里add之前git status显示红色的Untracked，add之后变成绿色的Changes to be committed，说明文件已经进入暂存区等待提交。

2\. git commit 的作用是：把暂存区里的内容正式保存为本地仓库的一次版本记录。

3\. git restore notes.md 的作用是：丢弃工作区对notes.md的修改，把它恢复成上次提交时的样子。实验里我追加的那句"准备放弃的练习文字"被restore后消失了；删掉的plan.md也用restore整个救了回来。

4\. commit 与 push 的区别是：commit只把版本记录保存在自己电脑的本地仓库里，GitHub上看不到；push才是把本地的提交上传到远程仓库，别人才能看到。

