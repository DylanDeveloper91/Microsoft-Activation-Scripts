# 中文下载与运行说明

本文件为此 fork 新增的中文说明。原项目为 [massgravel/Microsoft-Activation-Scripts](https://github.com/massgravel/Microsoft-Activation-Scripts)，简称 MAS，**不是 Microsoft 官方项目**。

## 来源与许可证

- 核对日期：2026-11-17。
- 核对版本：原 README 标注 3.14，发布日期 2026-11-11。
- fork 时 master 提交：`6cfd6f455ffb4983ce567231d800f08c44c39f00`。
- 原始源代码、README、提交历史及 [GPL-3.0 许可证](LICENSE) 保留。本文件亦按 GPL-3.0 提供。
- 上游主页：https://massgrave.dev/
- 此仓库为公开 fork，不放个人资料、密钥或账号信息。fork 不会自动持续同步上游。

## 先理解“安装”

MAS 是 Windows 批处理/PowerShell 工具，不是需要长期安装的桌面应用。“下载到 GitHub”是保存源代码副本，不会安装到电脑，也不会自动修改或激活系统。

源代码的 GPL 许可不等于 Windows/Office 使用许可证；技术上的激活状态不代表已取得合法产品授权。应确认自己的软件授权及适用条款。不要把此工具视为 Microsoft 官方授权、购买凭证或安全保证。

## 方法一：下载仓库后运行（可先检查源代码）

1. 打开本仓库主页，点击 **Code → Download ZIP**。
2. 下载后右键 ZIP，选择 **全部解压缩**。不要直接在 ZIP 内运行。
3. 在解压目录内找到 `MAS/All-In-One-Version-KL/MAS_AIO.cmd`。
4. 先阅读文件和上游文档，确认来源、用途与授权；这类脚本可能要求管理员权限并修改系统设置。出现安全警告时先核实，不要盲目关闭防护。
5. 如果决定执行，运行 `MAS_AIO.cmd`，按系统提示确认所需权限。
6. 按当前菜单显示选择所需功能；原 README 指引选择对应的绿色选项编号。菜单会随版本变化，不应照搬旧截图中的编号。

原 README 的传统方式适用于 Windows Vista 及之后版本；具体功能各有系统要求，不表示所有功能都支持每个版本。

## 方法二：上游 PowerShell 快捷方式

原 README 针对 Windows 8.1、10、11 给出的命令是：

```powershell
irm https://get.activated.win | iex
```

在开始菜单打开 PowerShell 后输入该命令。**这不是“只下载”命令**：`irm` 下载网络脚本，`iex` 立即执行它；执行内容来自该网址当时的版本，不固定为本仓库副本。希望先审阅或保留固定版本时使用方法一。

请逐字核实网址，避免冒名网站及修改过的命令。不必把快捷命令放进开机启动或计划任务。

## Home 与 Pro 是两件事

激活当前版本，与把 Windows Home 更改为 Pro，是不同操作。运行一次激活选项不应被理解为必然完成 Home → Pro。版本变更的适用条件、系统支持、是否需要重启和许可证要求，应按实际系统与最新上游说明核实。合法 Pro 授权可通过 Windows 的“设置 → 系统 → 激活”及 Microsoft 官方升级流程使用。

在任何版本变更前备份重要文件并妥善保存 BitLocker/设备加密恢复密钥；本说明不保证版本变更成功或数据不受影响。

## 更新与排错

- 更新副本：仓库首页 **Sync fork**，先检查上游变更与本地中文说明是否冲突，不要盲目覆盖。
- 原始说明：[README.md](README.md)
- 上游排错：https://massgrave.dev/troubleshoot
- 本次仓库整理仅复制项目和添加文档，**未在任何电脑上执行脚本、安装软件或改变 Windows 激活状态**。
