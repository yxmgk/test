## gitHub操作步骤:
+ 1、下载安装git
+ 2、登录你的github账号，并创建一个仓库：new repository,并复制其https地址
+ 3、在任何你想放置项目的地方右键选择Git Bash Here
+ 4、首先clone你的远程仓库（即在github上创建的远程仓库）
```bash
git clone 刚才复制的地址
```
+ 5、下载后就可以在你的项目里进行操作了,比如新增了一个index.html
+ 6、修改完项目后，先从项目工作区添加到暂存区
```bash
git add index.html
```
+ 7、此时可通过git status查看状态
+ 8、将变动的内容添加到你的本地仓库
```bash
git commit -m "这里写一个简单的描述信息"
```
+ 9、将本地仓库内容推到远程github仓库中
```bash
git push
```
## 注意点
+ 1、一般github中账户名和邮箱，和git中账号邮箱一致。
github中：创建的用户名和邮箱。
git中：使用`git config --list`查看
+ git中配置命令
```bash
git config --global user.name "你的账户"
git config --global user.email "你的邮箱地址"
```

