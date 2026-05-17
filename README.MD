## NetHack-Windows 汉化

> NetHack 5.X 系列已正式发布  
> 在上游汉化得到更新前，本仓库将停止工作

基于 [NetHack-3.6.7](https://github.com/NetHack/NetHack/tree/NetHack-3.6) git 最新提交编译，
汉化文本和程序来自于 [NetHack-cn](https://github.com/SunnyYuer/NetHack-cn),
GuideBook 汉化文本基于 [NetHack_GuideBook_CN](https://github.com/w4ngzhen/NetHack_GuideBook_CN) 完善。

编译时使用 x64 编译，并添加 PDCurses 支持，此外设置配置文件路径为游戏根目录。

目前进度：
- [X] 合并 [NetHack-cn](https://github.com/SunnyYuer/NetHack-cn) 汉化文件
- ~~合并与完善 GuideBook 汉化~~
- [X] 同步至官方上游最新提交 [23d331a](https://github.com/NetHack/NetHack/commit/23d331ac64d7351d27e77ed4b95f7cdab19a3d21)
- ~~自动化编译脚本~~
- ~~其它未汉化内容完善~~

## 如何编译

首先确保设置好了 `mingw` 和 `git` 环境

克隆本仓库，运行 `.\sys\winnt\nhsetup.bat`

在 `src` 目录下执行 `mingw32-make -f Makefile-Windows.gcc`
