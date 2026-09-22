# 第三章课堂模拟
1. git add 的作用是：将工作区中修改、新增或删除的文件添加到暂存区，为下一步的提交（commit）做准备。

2. git commit 的作用是：将暂存区中的内容提交到本地Git仓库，生成一个新的提交记录，用于保存当前版本的修改。

3. git restore notes.md 的作用是：撤销 `notes.md` 在工作区中的未暂存修改，使其恢复为最近一次提交（HEAD）所对应的版本。如果 `notes.md` 已经通过 `git add` 加入暂存区，`git restore notes.md` 默认不会撤销暂存区中的内容。

4. commit 与 push 的区别是：
    `commit` 是将修改从暂存区保存到本地仓库，形成版本记录；
    `push` 是将本地仓库中已经提交（commit）的内容上传到远程仓库，使远程仓库同步这些提交。因此，`commit` 不等于 `push`，完成 `commit` 后还需要执行 `push` 才能将提交同步到远程仓库。
