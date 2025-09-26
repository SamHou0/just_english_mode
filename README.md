# JUST English Mode!
防止微软拼音输入法启动切换到中文模式

和AutoHotkey脚本的区别是这个程序监听focus事件而不是一直循环，运行在后台几乎不消耗资源，用户完全无感知。

![Screenshot](assets/screenshot.png)

# 安装
下载以后直接运行exe即可。需要开机启动可以执行 `copy_to_startup.bat`，这个脚本会把exe复制到startup目录。
在运行的时候托盘会有一个图标，在图标上点击右键可以退出程序。

# 编译
代码用Rust编写，安装Rust环境以后执行下面的命令
`cargo build [--release]`
