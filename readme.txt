学习git推送
版本迭代1
git 常见指令
git init                        创建版本库 .git
git add readme.txt              工作区文件添加到缓存区
git commit -m '说明'            缓存区文件更新到master分支并附加说明
git log                         查看修改历史版本
git log --pretty=oneline        查看修改历史版本(单行展示)
git reset --hard HEAD^          回到前一个历史版本
git reset --hard HEAD~99        回到前99个历史版本
git reset --hard ***            回到指定版本号的历史版本
git reflog                      查看所有历史版本
