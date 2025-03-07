# 🎮 FFXivStorkLauncher

<div align="center">

![LOGO](https://raw.githubusercontent.com/extrant/IMGSave/main/FFXivStorkLauncher/logo.png)

![FFXIV](https://img.shields.io/badge/FFXIV-国服-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Version](https://img.shields.io/badge/Version-1.0.1-green)

</div>

## 📝 简介

这是一个用于管理 Final Fantasy XIV 国服账号的启动器工具，目前已经支持双端登录。依赖于Python & Pyimgui & FFxivArgLauncher，你可以轻松管理多个游戏账号，并支持 Dalamud 自动注入功能，亦或者仅仅使用注入功能。

- [NyLib2](https://github.com/nyaoouo/NyLib2)
- [ArgLauncher](https://github.com/ottercorp/FfxivArgLauncher)

## 📸 项目截图

<div align="center">

![界面截图](https://raw.githubusercontent.com/extrant/IMGSave/main/FFXivStorkLauncher/项目截图.png)

</div>

## ✨ 功能特点

- 🎯 多账号管理：轻松添加、删除和重命名游戏账号
- 🔄 自动/强制注入：支持 Dalamud 自动注入功能/指定PID注入，可配置 Dalamud 自动注入延迟
- ⏱️ 离线启动：没有任何强制性更新检查，即刻启动注入
- 📊 实时反馈：显示详细的启动器输出和错误信息
- 🔒 安全存储：账号信息经过加密存储
- 🎨 简洁界面：使用 ImGui 构建的现代化界面

## 📦 安装步骤

1. 下载并解压本程序到任意目录
2. 确保 `ArgLauncher` 文件夹中包含 `FfxivArgLauncher.exe`

## 🔧 Dalamud 安装（可选）
**如果你启动过一次或者正常注入过国服Dalamud，则不要看这一条**
### 手动安装
1. 在程序目录下创建 `Dalamud.Injector` 文件夹
2. 从獭或猫公司的 Dalamud 最新构建中下载 `Dalamud`
3. 将 `Dalamud` 解压放入 `Dalamud.Injector` 文件夹中 确保 `Dalamud.Injector` 文件夹中包含 `Dalamud.Injector.exe`

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
## ⚠️ 注意事项

- 请不要套娃增加账号
- 添加账号前需要先启动游戏并登录
- 如果凭证失效，请删除并重新用官方启动方式登录并添加账号
- 如果使用 Dalamud，请确保正确安装 Dalamud
- 建议定期备份账号数据
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




## 📝 更新日志

### v1.0.0
- 初始版本发布
- 支持多账号管理
- 支持 Dalamud 自动注入
- 添加延迟控制功能

### v1.0.1
- 优化注入方法
- 现在可以识别WG和SQ客户端了
- 增加了强制注入功能

## 📄 免责声明

本程序仅供学习和研究使用，请勿用于商业用途。使用本程序产生的任何问题由使用者自行承担。


---

<div align="center">
Siren
</div> 