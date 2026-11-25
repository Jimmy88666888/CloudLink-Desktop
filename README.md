# CloudLink Desktop

国际网盘 **电脑端** 直链助手（油猴脚本）

## 支持网盘

- Google Drive
- OneDrive / SharePoint
- Dropbox

## 下载方式

| 按钮 | 作用 |
|------|------|
| 复制全部直链 | 纯 URL，一行一个 |
| **导出 IDM (.ef2)** | 生成 `cloudlink-idm.ef2`，IDM → 任务 → 导入 → EF2 |
| **导出 MDM 批量** | `url \| 文件名 \| referer`，并复制到剪贴板 |
| **推送 Aria2** | JSON-RPC（默认 `http://127.0.0.1:6800/jsonrpc`） |
| 复制 aria2c / curl | 命令行 |

## 安装

https://raw.githubusercontent.com/Jimmy88666888/CloudLink-Desktop/main/CloudLink-Desktop.user.js

## 使用

1. 打开网盘文件或分享页  
2. 点击右下角 **CloudLink**  
3. 选择 IDM / MDM / Aria2 等导出方式  

## 相关

- 手机版：[CloudLink-Mobile](https://github.com/Jimmy88666888/CloudLink-Mobile)
- 国内网盘手机版：[LinkSwift-Mobile](https://github.com/Jimmy88666888/LinkSwift-Mobile)
