# RealityScan 2.2 简体中文替换包

**下载即用**：点 GitHub 右上 `Code -> Download ZIP`，得到一个压缩包，解压后按下面覆盖即可。
不需要 Python、不需要跑任何脚本、不需要重新构建。

适用版本：**RealityScan 2.2.x（Windows）**。

## 这个包里是什么

| 文件 | 作用 |
|---|---|
| `languages/zh-CN/ui.xml` | 界面语言包成品。官方 `zh-CN` 只翻了约 57.5%，本文件补到 99.2%（2,653 条替换） |
| `help/en-US/*.htm`（157 个） | 内置帮助文档全文汉化，157 / 157 页，126,613 字 |

未改动的资源（CSS / JS / 图片等 251 个文件）**不在包里**，继续用你本机原有的即可。

## 怎么替换

1. 关闭 RealityScan。
2. 打开 `%ProgramData%\Epic\RealityScan\LanguagePack\`
   （程序读的是这个目录，**不是**安装目录下的 `LanguagePack`）。
3. **先备份**你自己的 `languages\zh-CN\ui.xml` 和 `help\en-US\` 目录，方便回滚。
4. 把本包 `languages\zh-CN\ui.xml` 覆盖到同位置。
5. 把本包 `help\en-US\` 下的 157 个 `.htm` 覆盖到同位置（保持原有子目录结构）。
6. 重新打开 RealityScan；若界面仍是英文，在设置里把界面语言切到「简体中文」。
7. 打开内置帮助，应全部为中文。

**回滚**：把第 3 步的备份覆盖回去即可。

## 翻译约定

- 命令名、函数名、参数名、API 方法名、枚举值、进程 ID、CLI 示例 **保留英文**，
  这样查文档时能和实际调用一一对上。
- 界面按钮名（Workflow / Alignment / Start 等）保留英文，与软件界面显示一致。
- 表头统一：命令名称 / 必需参数 / 可选参数 / 说明；名称 / 说明 / 是否必需。
- 帮助文档里仍有极少量英文（约 10 处），都是命令行示例、进程 ID 常量、畸变模型名、
  文件名模式，按上述约定保留。

## 版权与免责声明

> 本项目为**非官方**社区翻译，与 Epic Games, Inc. 没有任何关联、授权或背书关系。
>
> 本仓库中的帮助页面是 Epic 官方内置帮助文档的**修改版本**，界面语言包也是在其官方
> `zh-CN/ui.xml` 基础上补全的；RealityScan、Epic Games 及相关商标、原始文档内容
> 均归 Epic Games, Inc. 所有。本仓库只提供中文译文部分的补充。
>
> 使用者需自行持有合法安装并授权使用的 RealityScan，本包仅用于在你自己的安装副本上
> 改善中文阅读体验。请勿用于商业分发。
>
> 如权利人认为本仓库不当，请联系维护者，我们将立即下架或转为私有。

## English Summary

Unofficial Simplified Chinese **ready-to-replace** pack for RealityScan 2.2.x (Windows):
a completed UI language file plus all 157 translated built-in help pages.
Download the ZIP, back up your own files, then copy them over
`%ProgramData%\Epic\RealityScan\LanguagePack\`. No build step, no scripts required.
Not affiliated with or endorsed by Epic Games, Inc. Original documentation remains
the property of Epic Games, Inc.
