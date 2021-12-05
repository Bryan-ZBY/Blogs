>- 官方网站
https://ohmyz.sh/#install
>- 主题美化
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

## 安装 zsh
```bash
# 安装
$ sudo apt-get install zsh

# 应用
$ chsh -s /bin/zsh
```

## 安装方式 - Install oh-my-zsh now
```bash
# curl
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

# wget
$ sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```


## 更换主题
```bash
$ vim ~/.zshrc
# --------- 
## xiong-chiamiov-plus

# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:/usr/local/bin:$PATH

# Path to your oh-my-zsh installation.
export ZSH="/home/yuanbao/.oh-my-zsh"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/ohmyzsh/ohmyzsh/wiki/Themes

#ZSH_THEME="robbyrussell"
ZSH_THEME="xiong-chiamiov-plus"
```

## 实用技巧
```bash
# 增强 tab 键自动补全
-  >cd c/k/k/t/c ---->>>>  >cd code/ktsg_new/ktsg_new/trunk/config

# 历史记录
┌─[yuanbao@WIN-7QEOL1RIOU2] - [/mnt/f/JobWork/decorationservice/Release] - [Fri Dec 03, 14:30]
└─[$] <git:(jira/KF-20298*)> d
0       /mnt/f/JobWork/decorationservice/Release
1       /mnt/f/JobWork
2       /mnt/g/Tools/vrdecorationeditor
3       /mnt/g/Tools
┌─[yuanbao@WIN-7QEOL1RIOU2] - [/mnt/f/JobWork/decorationservice/Release] - [Fri Dec 03, 14:32]
└─[$] <git:(jira/KF-20298*)> 2
/mnt/g/Tools/vrdecorationeditor
┌─[yuanbao@WIN-7QEOL1RIOU2] - [/mnt/g/Tools/vrdecorationeditor] - [Fri Dec 03, 14:33]
└─[$] <git:(DecoViewer3D*)>

# 通配符搜索增强
┌─[yuanbao@WIN-7QEOL1RIOU2] - [/mnt/f/JobWork/decorationservice/Release] - [Fri Dec 03, 14:36]
└─[$] <git:(jira/KF-20298*)> ll *.json
-rwxrwxrwx 1 yuanbao yuanbao 191K Nov 30 15:15 NewChinese_374.json
-rwxrwxrwx 1 yuanbao yuanbao 182K Nov 30 15:55 NorthEurope_370.json
-rwxrwxrwx 1 yuanbao yuanbao  88K Nov 30 15:53 SimpleModern_360.json
```
