- 设置'用户名' <br/>> git config global --user.name 
- 设置'邮箱' <br/>> git config global --user.email
- 查看以上设置' <br/>> git config global --list  
- 状态。查看的改动文件||显示红色为改动，添加后变绿色<br/>>git status
- 所有提交的日志信息<br/>>git log 
-- git log 提交后无法退出git，输入法切换英文按Qt<br/>
- 删除文件<br/>>rm <文件名> -r --cached <br/> 删除缓存区里的文件<br/>>和 git add <文件名> 一起使用
- 重命名文件<br/>>git mv <原文件名> <新文件名> <br/> >和git add<文件名>一起使用
- 移动文件到文件夹<br/>>git mv <原文件名> <文件夹路径>
- 移动文件到文件夹并且重命名<br/>>git mv <原文件名> <文件夹路径><新文件名>
- 查看文件修改信息<br/>>git log --pretty=oneline <文件名> , 获取到id，获取具体信息  git show \<id\><br/>>git log -p <文件名> 获取文件具体修改信息
- 操作失误，回到最后一次提交的状态<br/>> git checkout -- <文件名>
- 1.操作失误，回到最后一次提交的状态 2.文件加入暂存区当中<br/>> 用git reset HEAD <文件名>取消
> git add <文件名> | git reset HEAD <文件名> | git checkout -p <文件名>
- 回到到上个或者之前的版本<br/>
> git reset --hard HEAD^<br/> ^回到上个版本(一个^表示一个版本)
> git log --hard 版本ID (git log 获取版本id，在通过id获取到需要的版本)