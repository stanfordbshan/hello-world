## GitHub协作流程
这是一个简单的GitHub协作流程，如果需要了解更多，可以查询相关资料([link](http://rogerdudler.github.io/git-guide/index.zh.html) )。下面的流程默认代码贡献者被添加为Collaborator，否则需要先fork项目。

## 客户端(GitHub Desktop)
1. 点击 Clone a repository
<img src="https://raw.githubusercontent.com/mhhfut/imgsrc/master/raw/github_1.png"></img>
2. 粘贴项目的url然后clone
3. 新建自己的分支
<img src="https://raw.githubusercontent.com/mhhfut/imgsrc/master/raw/github_5.png"></img>
4. 改动代码后提交代码，然后推送到远端仓库
<img src="https://raw.githubusercontent.com/mhhfut/imgsrc/master/raw/github_3.png"></img>
5. 打开GitHub网页，发起pull request
<img src="https://raw.githubusercontent.com/mhhfut/imgsrc/master/raw/github_4.png"></img>

## 命令行
1. Clone仓库到本地：```git clone <repository url>```
2. 建立新的分支并切换到该分支：```git checkout -b <branch name>```
3. 提交代码：```git add * ``` ```git commit -m <commit message>```
4. 推送到远程分支：```git push origin <branch name>```
5. 与客户端一样，发起pull request