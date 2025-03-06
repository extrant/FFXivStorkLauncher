# FFXivStorkLauncher

这是一个用于管理 Final Fantasy XIV 国服账号的启动器工具，目前仅支持 WeGame 游戏端登录。

## 功能特点

- 支持多账号管理
- 自动注入 Dalamud
- 可配置 Dalamud 注入延迟
- 支持账号重命名和删除
- 实时显示启动器输出
- 错误提示和状态反馈

## 系统要求

- Windows 10 或更高版本
- 已安装 Final Fantasy XIV 国服（WeGame版本）
- 已安装 Dalamud（可选）

## 安装步骤

1. 下载并解压本程序到任意目录
2. 确保 `ArgLauncher` 文件夹中包含 `FfxivArgLauncher.exe`

## Dalamud 安装（可选）

1. 在程序目录下创建 `Dalamud.Injector` 文件夹
2. 从獭或猫公司的 Dalamud 最新构建中下载 `Dalamud.Injector.exe`
3. 将 `Dalamud.Injector.exe` 放入 `Dalamud.Injector` 文件夹中

## 使用说明

1. 运行 `FFXivStorkLauncher.exe`
2. 点击"添加账号"按钮添加新的游戏账号
   - 需要先启动游戏并登录
   - 选择对应的游戏进程
   - 输入账号名称
3. 使用"启动"按钮启动游戏
4. 使用"重命名"或"删除"按钮管理账号
5. 使用延迟滑块调整 Dalamud 注入延迟（0-10000ms）

## 注意事项

- 本程序仅支持 WeGame 版本的 Final Fantasy XIV 国服
- 添加账号前需要先启动游戏并登录
- 确保游戏路径正确
- 如果使用 Dalamud，请确保正确安装 Dalamud

## 常见问题

1. 找不到 FFXIV 进程
   - 请确保游戏已经启动并登录
   - 检查游戏是否正常运行

2. 找不到 Dalamud.Injector.exe
   - 检查是否已创建 Dalamud.Injector 文件夹
   - 确认 Dalamud.Injector.exe 是否已正确放置
   - 确保使用的是最新版本的 Dalamud

3. 启动失败
   - 检查游戏路径是否正确
   - 确认账号参数是否完整
   - 查看启动器输出获取详细错误信息

## 免责声明

本程序仅供学习和研究使用，请勿用于商业用途。使用本程序产生的任何问题由使用者自行承担。 