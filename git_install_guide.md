# Windows系统Git安装指南

## 第一步：下载Git安装包
1. 访问Git官方网站下载页面：https://git-scm.com/download/win
2. 点击"Download for Windows"按钮下载最新版安装程序
3. 下载完成后会得到一个名为"Git-x.x.x-64-bit.exe"的文件（x.x.x为版本号）

## 第二步：运行安装程序
1. 双击下载的安装程序文件
2. 在用户账户控制提示中点击"是"允许安装
3. 阅读许可协议后点击"Next"

## 第三步：选择安装组件
1. 保持默认勾选的组件
2. 建议勾选"Windows Explorer integration"中的"Git Bash Here"和"Git GUI Here"
3. 点击"Next"继续

## 第四步：选择默认编辑器
1. 推荐选择"Use Visual Studio Code as Git's default editor"
2. 如果未安装VS Code，可选择其他熟悉的编辑器如Notepad++
3. 点击"Next"继续

## 第五步：调整PATH环境
1. 选择"Git from the command line and also from 3rd-party software"
2. 这样可以在任何命令行中使用Git命令
3. 点击"Next"继续

## 第六步：选择HTTPS传输后端
1. 保持默认选择"Use the OpenSSL library"
2. 点击"Next"继续

## 第七步：配置行尾转换
1. 选择"Checkout Windows-style, commit Unix-style line endings"
2. 这是Windows系统下的推荐设置
3. 点击"Next"继续

## 第八步：配置终端模拟器
1. 选择"Use MinTTY (the default terminal of MSYS2)"
2. 点击"Next"继续

## 第九步：完成安装
1. 点击"Install"开始安装
2. 等待安装进度完成
3. 取消勾选"View Release Notes"
4. 点击"Finish"完成安装

## 验证安装
1. 打开命令提示符或Git Bash
2. 输入命令：`git --version`
3. 如果显示Git版本号则表示安装成功

## 基本配置
1. 设置用户名：`git config --global user.name "Your Name"`
2. 设置邮箱：`git config --global user.email "your.email@example.com"`
3. 查看配置：`git config --list`
