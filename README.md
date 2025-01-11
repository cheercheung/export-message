# iMessage Exporter | iMessage 导出工具

[切换语言 | Language Switch](#english-edition)

# 中文版

一个用于在 macOS 上导出 iMessage 对话的图形界面应用程序。

## 下载

1. 从 [releases 页面](https://github.com/cheercheung/export-message/releases) 下载最新版本
2. 解压下载的文件
3. 按照应用程序文件夹中的 README.txt 说明操作

## 功能特点

- 支持导出 iMessage 对话为 CSV 或 JSON 格式
- 友好的用户界面
- 支持个人和群组对话
- 保留消息时间戳和发送者信息
- 完全本地运行，保护隐私

## 系统要求

- macOS 系统（在 macOS Sonoma 上测试通过）
- 需要完全磁盘访问权限（用于访问 Messages 数据库）

## 安装和使用

下载后请查看应用程序文件夹中的 README.txt 文件，其中包含详细的安装和使用说明。

主要步骤：
1. 将程序文件夹复制到合适的位置（建议放在 Applications 文件夹）
2. 首次运行时授予必要的系统权限
3. 选择要导出的对话和导出格式
4. 点击导出并选择保存位置

## 隐私和安全

本应用程序：
- 完全在本地运行
- 不会通过网络传输任何数据
- 仅需要访问 Messages 数据库的权限
- 开源代码，可供审查

## 从源代码构建

如果你想从源代码构建应用程序：
1. 克隆仓库
2. 安装依赖：`pip install -r requirements.txt`
3. 运行 PyInstaller：`pyinstaller --windowed --name="iMessage Exporter" imessage_gui.py`

## 许可证

MIT License

## 贡献

欢迎提交问题报告或代码贡献！

---

# English Edition

A simple GUI application for exporting iMessage conversations on macOS.

[切换语言 | Switch to Chinese](#中文版)

## Download

1. Download the latest release from the [releases page](https://github.com/cheercheung/export-message/releases)
2. Extract the downloaded file
3. Follow the instructions in the README.txt file inside the application folder

## Features

- Export iMessage conversations to CSV or JSON format
- User-friendly interface
- Support for individual and group chats
- Maintains message timestamps and sender information
- Runs locally for privacy protection

## System Requirements

- macOS (tested on macOS Sonoma)
- Full disk access permission (for accessing the Messages database)

## Installation & Usage

Please refer to the README.txt file in the application folder for detailed installation and usage instructions.

Key steps:
1. Copy the program folder to a suitable location (Applications folder recommended)
2. Grant necessary system permissions on first run
3. Select conversations and export format
4. Click export and choose save location

## Privacy & Security

This application:
- Runs entirely locally on your machine
- Does not transmit any data over the internet
- Only requires permissions to access your Messages database
- Is open source and can be audited

## Building from Source

If you want to build the application from source:
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run PyInstaller: `pyinstaller --windowed --name="iMessage Exporter" imessage_gui.py`

## License

MIT License

## Contributing

Feel free to open issues or submit pull requests! 