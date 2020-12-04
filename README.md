# test-git

1. 本地基于production新建分支
> git checkout -b f_20201204 origin/production

2. 本地新分支发布到远程
> git push origin f_20201204

3. 提取部分提交内容
> git cherry-pick head1^...head2