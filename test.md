# 查看 git 版本

- git version

**配置用户和邮箱(只用于显示是谁提交的,不校验邮箱的真实性),可以使用`git config -l`查看**

- git config --global user.name "用户名"
- git config --global user.email "邮箱"

- git init:初始化,创建`.git`隐藏文件夹
- git add .:添加所有文件到暂存区
- git commit -m "提交说明":提交
- git log:查看提交信息
- git reset --hard 版本 id:版本强制回退(还有 soft 和 mixed 模式)
- git branch 分支名:创建分支
- git checkout 分支名:切换分支
- git merge 分支名:把分支名合并到当前分支
- git tag 标签名:创建标签
- git tag:查询已创建的标签名
- git show 标签名:显示该标签名
- git tag -d 标签名:删除标签名
