# iMessage Exporter | iMessage 导出工具

[切换语言 | Language Switch](#english-edition)

# 中文版

一个用于在 macOS 上导出 iMessage 对话的图形界面应用程序。这个目录包含了 iMessage 导出工具的主要代码和发布文件。

## 目录结构

- `dist/` - 包含已编译的应用程序
- `README.md` - 项目说明文档
- `RELEASE_NOTES.md` - 版本发布说明
- `.gitignore` - Git 忽略配置文件

## 下载和安装

1. 从 [releases 页面](https://github.com/cheercheung/export-message/releases) 下载最新版本
2. 解压下载的文件
3. 将整个 "iMessage Exporter" 文件夹复制到你想要的位置（建议放在 Applications 文件夹）
4. 请确保不要移动或删除文件夹内的任何文件，这些都是程序运行所必需的

## 首次运行

1. 双击 "iMessage Exporter" 程序图标
2. 如果看到安全提示，请按以下步骤操作：
   - 打开 系统设置 > 隐私与安全性
   - 在页面底部找到关于 "iMessage Exporter" 的提示
   - 点击 "仍要打开"
3. 程序会请求访问消息数据库的权限：
   - 点击 "好" 或 "允许"
   - 如果没有看到权限请求，请检查 系统设置 > 隐私与安全性 > 完全磁盘访问权限
   - 确保 "iMessage Exporter" 已被允许

## 使用方法

1. 选择导出格式（CSV 或 JSON）
2. 选择要导出的对话
3. 点击 "导出" 并选择保存位置
4. 等待导出完成

## 系统要求

- macOS 系统（在 macOS Sonoma 上测试通过）
- 需要完全磁盘访问权限（用于访问 Messages 数据库）

## 常见问题

- 如果程序无法打开：确保已在安全设置中允许运行
- 如果无法访问消息：检查完全磁盘访问权限设置
- 如果导出按钮不可用：确保已选择对话和导出格式

## 隐私和安全

本应用程序：
- 完全在本地运行
- 不会通过网络传输任何数据
- 仅需要访问 Messages 数据库的权限
- 开源代码，可供审查

## 技术支持

如有问题，请访问 [GitHub Issues](https://github.com/cheercheung/export-message/issues)

---

# English Edition

A GUI application for exporting iMessage conversations on macOS. This directory contains the main code and release files for the iMessage export tool.

[切换语言 | Switch to Chinese](#中文版)

## Directory Structure

- `dist/` - Contains the compiled application
- `README.md` - Project documentation
- `RELEASE_NOTES.md` - Version release notes
- `.gitignore` - Git ignore configuration file

## Download and Installation

1. Download the latest release from the [releases page](https://github.com/cheercheung/export-message/releases)
2. Extract the downloaded file
3. Copy the entire "iMessage Exporter" folder to your preferred location (Applications folder recommended)
4. Do not move or delete any files within the folder as they are essential for the program to run

## First Launch

1. Double-click the "iMessage Exporter" program icon
2. If you see a security warning, follow these steps:
   - Open System Settings > Privacy & Security
   - Find the message about "iMessage Exporter" at the bottom
   - Click "Open Anyway"
3. The program will request access to your messages database:
   - Click "OK" or "Allow"
   - If you don't see the permission request, check System Settings > Privacy & Security > Full Disk Access
   - Make sure "iMessage Exporter" is allowed

## How to Use

1. Select export format (CSV or JSON)
2. Choose conversations to export
3. Click "Export" and select save location
4. Wait for the export to complete

## System Requirements

- macOS (tested on macOS Sonoma)
- Full disk access permission (for accessing the Messages database)

## Troubleshooting

- If the program won't open: Ensure it's allowed in Security settings
- If messages are inaccessible: Check Full Disk Access permissions
- If export button is disabled: Make sure you've selected both conversation and format

## Privacy & Security

This application:
- Runs entirely locally on your machine
- Does not transmit any data over the internet
- Only requires permissions to access your Messages database
- Is open source and can be audited

## Technical Support

For support, please visit [GitHub Issues](https://github.com/cheercheung/export-message/issues) 