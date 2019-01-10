---
layout: page
title: MOD下载
published: true
---
**注意：已经下载mod的选手请删除以下文件夹**  
* //rFactor/GameData/Vehicles/OFCR2019  
* //rFactor/GameData/Locations/OFCR_2019
* //rFactor/GameData/Sounds/OFCR2019  
* //rFactor/Music/OFCR2019  
* //rFactor/rFm/OFCR2019.rfm  
* //rFactor/UIData/OFCR2019  
  
### 命令行  
1. 确保你的电脑已经安装了[Git](https://git-scm.com/downloads)  
2. 在你的rFactor根目录下新建文件夹`assets_ofcr2019`，右击该文件夹，选择`Git Bash Here`  
3. 出现命令提示符窗口后，输入`git init .`进行初始化并按下回车  
4. 输入`git remote add upstream http://120.78.160.93:34166/r/assets_ofcr2019.git`进行节点设置并按下回车  
5. 输入`git pull upstream master`开始进行下载
6. 初次下载会要求输入用户名和密码，用户名为你的参赛名（全小写，空格处为下划线），密码为你的车号+166（例：3号车手的密码是`03166`, 23号车手的密码是`23166`），没有车号的车手密码默认为`00166`.  
7. 没有错误信息即代表下载完成。后期进行更新时仅需执行步骤6，并且不需要再次登录  

### GitHub Desktop  
1. 确保你的电脑已经安装了[GitHub Desktop](https://desktop.github.com/)  
2. 首次打开GitHub桌面版可能会提示注册账号，该步骤可以跳过  
3. 打开后出现如下界面，选择最右侧的`Clone a repository`  
![image](https://i.ibb.co/z4vgckn/TIM-20190107235732.png) 
4. 选择`URL`标签页，下方选择你的rFactor所在路径，上方输入`http://120.78.160.93:34166/r/assets_ofcr2019.git`，如下图所示  
![image](https://i.ibb.co/ypRzR9d/TIM-20190110234844.png)  
5. 首次下载会提示输入用户名和密码，用户名为你的参赛名，密码为你的车号+166（例：3号车手的密码是`03166`, 23号车手的密码是`23166`），没有车号的车手密码默认为`00166`.  
![image](https://i.ibb.co/LtBr0Zk/TIM-20190110235108.png)
6. 出现如下界面表示正在进行下载并等待下载完成，mod即可使用  
![image](https://i.ibb.co/jk78sX3/TIM-20190108000121.png)  

### 进行更新操作（桌面版）  
1. 打开如下界面后点击如图所示fetch  
![image](https://i.ibb.co/GHBQnJb/TIM-20190108000314.png)  
2. 右上角按钮更改为`pull origin`时代表有更新可用，此时再点击`pull origin`即可完成更新  
![image](https://i.ibb.co/cvwgF8t/TIM-20190108000432.png)  
