```
1. 创建项目和远程仓库
- 在本地用PyCharm创建一个Python项目
- 在GitHub上新建一个同名仓库(例如：qqmusic-review-av)

2. 在PyCharm终端中初始化并推送，在项目目录下依次执行以下命令：
git init                         # 初始化Git仓库
git add .                        # 添加所有文件到暂存区
git commit -m "first commit"     # 提交第一次代码
git branch -M main               # 将默认分支改为main
git remote add origin https://github.com/XYff06/qqmusic-review-av.git  # 关联远程仓库
git push -u origin main          # 推送到GitHub
# 注意：如果网络受限或443端口被阻止，可在网络通畅时，再执行git push

3. 后续提交与推送，每次更新代码后，只需执行：
git add .
git commit -m "commit message"
git push

```