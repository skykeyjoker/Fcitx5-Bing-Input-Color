# Bing-Input-Color

该Fcitx5主题设计思路源自Win10 2004更新后的自带的输入法，旨在模仿其UI。



## 使用方式

### 安装

#### For Arch Users: AUR安装

使用AUR助手下载安装：

```
yay -S fcitx5-bing-input-color
```

修改配置文件`~/.config/fcitx5/conf/classicui.conf`

```
# 垂直候选列表
Vertical Candidate List=False

# 按屏幕 DPI 使用
PerScreenDPI=True

# Font (设置成你喜欢的字体)
Font="思源黑体 CN Medium 13"

# 主题
Theme=Fcitx5-Bing-Input-Color
```

**重启输入法后生效**



#### 手动安装

创建文件夹：

```
mkdir -p ~/.local/share/fcitx5/themes/Bing-Input-Color
```

克隆到本地：

```
git clone git@github.com:skykeyjoker/Fcitx5-Bing-Input-Color.git ~/.local/share/fcitx5/themes/Fcitx5-Bing-Input-Color
```

修改配置文件：`~/.config/fcitx5/conf/classicui.conf`

```
# 垂直候选列表
Vertical Candidate List=False

# 按屏幕 DPI 使用
PerScreenDPI=True

# Font (设置成你喜欢的字体)
Font="思源黑体 CN Medium 13"

# 主题
Theme=Fcitx5-Bing-Input-Color
```

**重启输入法后生效**



### 配置

#### 使用单行模式

要使用单行模式(inline_preedit),
对于fcitx5自带pinyin 请修改 `~/.config/fcitx5/conf/pinyin.conf`, 
加入/修改以下内容: 

```
#可用时在应用程序中显示预编辑文本
PreeditInApplication=True
```

**重启输入法后生效**



## 截图

该皮肤效果：

![](./Screenshot.png)