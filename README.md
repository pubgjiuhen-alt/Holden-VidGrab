# Holden VidGrab

Holden VidGrab 是面向 macOS 的视频下载桌面应用，基于 [Videdown](https://github.com/cshuangyy/videdown) 改造。保留原有解析、下载、历史和设置功能，采用新的深色界面与应用图标。

## 下载

从 [Releases](https://github.com/pubgjiuhen-alt/Holden-VidGrab/releases) 下载最新的 `macOS-universal.dmg`。安装包包含 Intel 和 Apple Silicon 两种架构。

当前版本尚未使用 Apple Developer ID 签名或公证；首次在其他 Mac 上打开时，macOS 可能显示安全提示。

## 更新检查

应用的“检测更新”会读取本仓库最新的 GitHub Release，并比较版本号。发布新版本时，创建非草稿、非预发布的 Release，标签使用 `v主版本.次版本.修订版本`（例如 `v1.1.1`），再上传对应的 DMG。“前往下载”会打开该 Release 页面。

## 问题反馈

在应用的“问题反馈”中打开本仓库的 [新建 Issue](https://github.com/pubgjiuhen-alt/Holden-VidGrab/issues/new/choose) 页面，提交使用建议或故障报告。现有反馈可在 [Issues](https://github.com/pubgjiuhen-alt/Holden-VidGrab/issues) 查看。

## 默认下载位置

新安装默认使用 `~/Downloads/VidGrab`。已有版本若仍使用原默认目录 `~/Downloads/Videdown`，应用会把保存位置改为新目录；用户自行选择的目录保持不变。旧目录中的已有文件不会被搬动或删除。

## 来源与许可

原项目 Videdown 采用 MIT License，原始版权和许可条款见 [LICENSE](LICENSE)。Holden VidGrab 保留该声明。
