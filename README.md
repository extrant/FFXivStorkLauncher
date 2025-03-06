# 🎮 FFXivStorkLauncher

<div align="center">

![FFXIV](https://img.shields.io/badge/FFXIV-国服-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Version](https://img.shields.io/badge/Version-1.0.0-green)

</div>

## 📝 简介

这是一个用于管理 Final Fantasy XIV 国服账号的启动器工具，目前仅支持 WeGame 游戏端登录。通过简单的界面，你可以轻松管理多个游戏账号，并支持 Dalamud 自动注入功能。

## ✨ 功能特点

- 🎯 多账号管理：轻松添加、删除和重命名游戏账号
- 🔄 自动注入：支持 Dalamud 自动注入功能
- ⏱️ 延迟控制：可配置 Dalamud 注入延迟（0-10000ms）
- 📊 实时反馈：显示详细的启动器输出和错误信息
- 🔒 安全存储：账号信息经过加密存储
- 🎨 简洁界面：使用 ImGui 构建的现代化界面

## 🛠️ 系统要求

- Windows 10 或更高版本
- 已安装 Final Fantasy XIV 国服（WeGame版本）
- 已安装 Dalamud（可选）

## 📦 安装步骤

1. 下载并解压本程序到任意目录
2. 确保 `ArgLauncher` 文件夹中包含 `FfxivArgLauncher.exe`

## 🔧 Dalamud 安装（可选）

1. 在程序目录下创建 `Dalamud.Injector` 文件夹
2. 从獭或猫公司的 Dalamud 最新构建中下载 `Dalamud.Injector.exe`
3. 将 `Dalamud.Injector.exe` 放入 `Dalamud.Injector` 文件夹中

## 📖 使用说明

### 基本操作

1. 运行 `FFXivStorkLauncher.exe`
2. 点击"添加账号"按钮添加新的游戏账号
   - 需要先启动游戏并登录
   - 选择对应的游戏进程
   - 输入账号名称
3. 使用"启动"按钮启动游戏
4. 使用"重命名"或"删除"按钮管理账号
5. 使用延迟滑块调整 Dalamud 注入延迟（0-10000ms）

### 详细步骤

#### 添加账号
1. 启动 FFXIV 并登录
2. 点击"添加账号"按钮
3. 在弹出的窗口中选择对应的游戏进程
4. 输入一个便于识别的账号名称
5. 等待添加完成

#### 启动游戏
1. 在账号列表中找到要启动的账号
2. 点击"启动"按钮
3. 等待游戏启动
4. 如果配置了 Dalamud，将自动注入

#### 管理账号
- 重命名：点击"重命名"按钮修改账号备注
- 删除：点击"删除"按钮删除账号
- 刷新：点击"刷新列表"更新账号列表

## ⚠️ 注意事项

- 本程序仅支持 WeGame 版本的 Final Fantasy XIV 国服
- 添加账号前需要先启动游戏并登录
- 确保游戏路径正确
- 如果使用 Dalamud，请确保正确安装 Dalamud
- 建议定期备份账号数据

## ❓ 常见问题

### 1. 找不到 FFXIV 进程
- 请确保游戏已经启动并登录
- 检查游戏是否正常运行
- 确认是否使用 WeGame 版本

### 2. 找不到 Dalamud.Injector.exe
- 检查是否已创建 Dalamud.Injector 文件夹
- 确认 Dalamud.Injector.exe 是否已正确放置
- 确保使用的是最新版本的 Dalamud
- 检查文件权限是否正确

### 3. 启动失败
- 检查游戏路径是否正确
- 确认账号参数是否完整
- 查看启动器输出获取详细错误信息
- 检查是否有足够的系统权限

## 📝 更新日志

### v1.0.0
- 初始版本发布
- 支持多账号管理
- 支持 Dalamud 自动注入
- 添加延迟控制功能

## 📄 免责声明

本程序仅供学习和研究使用，请勿用于商业用途。使用本程序产生的任何问题由使用者自行承担。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来帮助改进这个项目！

## 📞 联系方式

如有问题或建议，请通过以下方式联系：
- 提交 Issue
- 发送邮件至：[your-email@example.com]

---

<div align="center">
Made with ❤️ for FFXIV players
</div> 