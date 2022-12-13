- 设置'用户名' <br/>> git config global --user.name 
- 设置'邮箱' <br/>> git config global --user.email
- 查看以上设置' <br/>> git config global --list  
- 状态。查看的改动文件||显示红色为改动，添加后变绿色<br/>> git status
- 所有提交的日志信息<br/>> git log 
-- git log 提交后无法退出git，输入法切换英文按Qt<br/>
- 删除文件<br/>>rm <文件名> -r --cached <br/> 删除缓存区里的文件<br/>>和 git add <文件名> 一起使用
- 重命名文件<br/>> git mv <原文件名> <新文件名> <br/> >和git add<文件名>一起使用
- 移动文件到文件夹<br/>> git mv <原文件名> <文件夹路径>
- 移动文件到文件夹并且重命名<br/>> git mv <原文件名> <文件夹路径/新文件名>
- 查看文件修改信息<br/>> git log --pretty=oneline <文件名> , 获取到id，获取具体信息  git show \<id\><br/>> git log -p <文件名> 获取文件具体修改信息
- 操作失误，回到最后一次提交的状态<br/>> git checkout -- <文件名>
- 1.操作失误，回到最后一次提交的状态 2.文件加入暂存区当中<br/>> 用git reset HEAD <文件名>取消 <br/>> git add <文件名> | git reset HEAD <文件名> | git checkout -p <文件名>
- 回到到上个或者之前的版本<br/>> git reset --hard HEAD^<br/> ^回到上个版本(一个^表示一个版本)<br/> git log --hard 版本ID (git log 获取版本id，在通过id获取到需要的版本)
- 将<strong>指定文件</strong>回退到某个版本<br/>> git checkout <版本id> -- <文件名><br/>> git log 获取版本id
- 创建最近一次提交的标签<br/>> git tag v1.0 
- 创建指定版本的标签<br/> > git log 获取版本id， git tag  版本标签  \<id\>
- 删除标签<br/>> git tag -d 
- 远程推送标签<br/>> git push origin v1.0
- 远程删除标签<br/>> git push -d origin <标签版本>
- 创建分支<br/>> git branch <分支名称>
- 创建分支并进入<br/>> git checkout -b <分支名称>
- 查看所有分支<br/>> git branch
- 切换分支<br/>> git checkout <分支名称>
- 删除分支<br/>> git branch -d <分支名称>
- 强制删除分支<br/>> git branch -D <分支名称><br/>> 该分支处于git commit -m '提交状态'
- 合并分支<br/>> git merge <分支名称>
- 解决代码冲突<br/>> 手动排除. git add . -> git commit 
- 解决代码冲突2，保留主线代码<br/>>git merge --abort 
- 查看版本路线<br/>> git log --online --graph
- 远程拉取所有分支<br/> git fetch

- 谷歌访问github插件<br/> > Octotree<br/> > Enhanced GitHub<br/> > GitZip for GitHub