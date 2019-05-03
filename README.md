# 说明
个人i3配置分享，详细安装配置见[i3窗口管理器总结](https://note.yuchaoshui.com/blog/post/yuziyue/i3-window-manager)


# 安装
```
~$ git clone https://github.com/yuchaoshui/i3-config.git ~/.config/i3
or
~$ git clone https://github.com/yuchaoshui/i3-config.git ~/.i3
```

## 1、配置profile
编辑`/etc/profile`添加如下配置
```
# set i3 config dir
export i3config=/home/yzy/.config/i3
export PATH=$PATH:$i3config/scripts
export PATH=$PATH:$i3config/scripts/bin
```

## 2、安装i3所需包
```
~$ sudo apt-get install i3 i3status rofi
```
详细安装配置见[i3窗口管理器总结](https://note.yuchaoshui.com/blog/post/yuziyue/i3-window-manager)

## 3、配置预览

<div align=center>
![desktop][https://raw.githubusercontent.com/yuchaoshui/static/master/i3-config/wallpaper.png]
</div>

