---
title: NetEase-MusicBox
layout: post
guid: urn:uuid:2ef3550f-8cf3-400b-a55b-c512c9af8b2d
tags:
  - music
  - 高品质
---

[![bridge to wonderland](/media/files/2014/09/05/NetEase-MusicBox.gif)](http://7vikpt.com1.z0.glb.clouddn.com/NetEase-MusicBox.gif)

高品质网易云音乐命令行版本，简洁优雅，丝般顺滑，基于Python编写。

### [](https://github.com/darknessomi/musicbox#%E5%8A%9F%E8%83%BD%E7%89%B9%E6%80%A7)功能特性

  1. 320kps的高品质音乐
  2. 歌曲，艺术家，专辑检索
  3. 网易热门歌曲排行榜
  4. 网易新碟推荐
  5. 网易精选歌单
  6. 网易DJ节目
  7. 私人歌单
  8. 随心打碟
  9. 本地收藏（不提供下载）
  10. Vimer式快捷键让操作丝般顺滑
  11. 可使用数字快捷键

### [](https://github.com/darknessomi/musicbox#%E9%94%AE%E7%9B%98%E5%BF%AB%E6%8D%B7%E9%94%AE)键盘快捷键

J
Down
下移

K
Up
上移

H
Back
后退

L
Forword
前进

U
Prev page
上一页

D
Next page
下一页

F
Search
快速搜索

[
Prev song
上一曲

]
Next song
下一曲

=
Volume +
音量增加

-
Volume -
音量减少

Space
Play/Pause
播放/暂停

?
Shuffle
手气不错

M
Menu
主菜单

P
Present
当前播放列表

A
Add
添加曲目到打碟

Z
DJ list
打碟列表

S
Star
添加到收藏

C
Collection
收藏列表

R
Remove
删除当前条目

Q
Quit
退出

W
Quit&Clear
退出并清除用户信息

### [](https://github.com/darknessomi/musicbox#mac%E5%AE%89%E8%A3%85)Mac安装
    
    $ git clone https://github.com/darknessomi/musicbox.git  
    
    $ cd musicbox
    
    $ sudo python setup.py install
    
    $ brew install mpg123
    

### [](https://github.com/darknessomi/musicbox#linux%E5%AE%89%E8%A3%85)Linux安装
    
    $ git clone https://github.com/darknessomi/musicbox.git  
    
    $ cd musicbox
    
    $ sudo python setup.py install
    
    $ sudo apt-get install mpg123
    

#### [](https://github.com/darknessomi/musicbox#%E9%94%99%E8%AF%AF%E5%A4%84%E7%90%86)错误处理

  1. pkg_resources.DistributionNotFound: requests

$ sudo pip install requests

如果是运行 $ musicbox 出错

$ sudo pip install --upgrade setuptools

  2. pip: Command not found

$ sudo apt-get install python-pip

  3. ImportError: No module named setuptools

$ sudo easy_install pip

$ sudo apt-get install python-setuptools

### [](https://github.com/darknessomi/musicbox#%E4%BD%BF%E7%94%A8)使用
    
    $ musicbox
    

Enjoy it !

>项目地址：* [darknessomi/musicbox](https://github.com/darknessomi/musicbox)

Thanks： darknessomi，vellow,hbprotoss,Catofes,尘埃
