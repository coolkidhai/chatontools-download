# ChatonTools

ChatonTools 是 Windows 法语输入小工具，本仓库仅发布下载包。

## 功能
- 悬浮面板：16 个法语特殊字符 à â ä æ ç é è ê ë î ï ô œ ù û ü 及对应大写。
- 物理键盘模拟：France AZERTY / Canadian French / Canadian Multilingual Standard。
- 内置图解键盘教学。

## 下载与运行
[下载 ChatonTools（Windows x64 ZIP）](https://github.com/coolkidhai/chatontools-download/releases/latest/download/ChatonTools-win-x64.zip)

要求 Windows 10 1809+ / Windows 11 x64。解压后运行 `ChatonTools.exe`，无需安装。

程序未签名，SmartScreen 可能提示警告。确认下载来源后选择“更多信息 → 仍要运行”。更新前请先从系统托盘退出旧版，再替换文件。

## 快捷键
- Ctrl+Alt+F8：显示或隐藏面板。
- Ctrl+Alt+F9：开启或关闭物理键盘模拟（默认关闭）。
- Ctrl+Alt+F12：紧急恢复，关闭模拟并显示面板。

## 隐私
不记录按键，不上传输入内容，无需管理员权限。

## SHA256 校验
每个 Release 提供 `SHA256SUMS.txt`，请核对下载文件的 SHA256：

```powershell
Get-FileHash ./ChatonTools-win-x64.zip -Algorithm SHA256
```

官网：https://chatontcf.com
