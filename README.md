<div align="center">

# RunPilot

**说一句需求，AI 帮你写安卓自动化脚本**

免 root · 免电脑 · 数据只存本机

[![version](https://img.shields.io/github/v/release/runpilot-app/runpilot-app.github.io?label=version&color=09090B)](https://github.com/runpilot-app/runpilot-app.github.io/releases)
![platform](https://img.shields.io/badge/Android-8.0%2B-3DDC84)
![root](https://img.shields.io/badge/root-免root-blue)

[官网](https://runpilot.cn/) · [下载](https://runpilot.cn/) · [更新日志](https://github.com/runpilot-app/runpilot-app.github.io/releases) · [问题反馈](https://github.com/runpilot-app/runpilot-app.github.io/issues)

</div>

---

## 这是什么

RunPilot 是一款**免 root 的安卓自动化脚本工具**。

你不需要学编程：用一句话描述要做的事，它会调用手机上已安装的 AI（DeepSeek / Kimi / 豆包 / 千问 / 元宝 / ChatGPT）生成脚本，粘回 App 就能运行。

适合这些场景：

- 每天手动签到、打卡的 App
- 需要反复执行的固定操作流程
- 界面自动化测试
- 任何"点几十下才能做完"的重复劳动

## 界面

<p align="center">
  <img src="https://runpilot.cn/assets/shot-scripts.png" width="170" alt="脚本列表">
  <img src="https://runpilot.cn/assets/shot-editor.png" width="170" alt="脚本编辑器">
  <img src="https://runpilot.cn/assets/shot-codegen.png" width="170" alt="快捷生成代码">
  <img src="https://runpilot.cn/assets/shot-log-detail.png" width="170" alt="运行日志">
</p>

## 主要能力

| 能力 | 说明 |
|---|---|
| **用 AI 写脚本** | 说一句需求，自动打开已装的 AI 应用并带入提示词，生成后粘回即用 |
| **JavaScript 脚本** | 直接写 JS，不用学新语言 |
| **无障碍自动化** | 自动点击滑动，免 root 即装即用 |
| **定时任务** | 按天按周定间隔，重启不丢 |
| **找图找色 + OCR** | 认图认色认字，界面改版也能点中 |
| **录屏与截图** | 运行全程可录可截，复盘有据 |
| **HTTP 网络请求** | 调接口、传数据、下载文件 |
| **执行 Shell 命令** | 跑系统命令（pm、getprop 等） |
| **编辑器与手册** | 高亮补全 + 内置 API 手册，边写边查 |

## 下载

| 渠道 | 地址 |
|---|---|
| **官网（推荐）** | [https://runpilot.cn/](https://runpilot.cn/) |
| GitHub Releases | [前往 Releases 下载](https://github.com/runpilot-app/runpilot-app.github.io/releases) |

**系统要求**：Android 8.0 及以上，ARM 架构（arm64-v8a / armeabi-v7a）

**完整性校验**：官网首页公布了每个版本的 SHA-256，下载后可自行比对

## 快速上手

1. 安装 APK，在系统设置里授予「无障碍」权限
2. 打开任意脚本，点右上角菜单 → **用 AI 写脚本**
3. 描述需求，例如：`打开微信，点「我」→ 每日签到 → 领取积分`
4. 点「发送给 AI」，自动打开手机上已安装的 AI 应用
5. 在 AI 应用里按发送，生成后把代码粘回编辑器，点运行

**全程不需要写代码。** 生成的结果不对，改一句描述再试即可。

## 常见问题

**需要 root 吗？**
不需要。基于系统无障碍服务运行，不刷机、不改系统，卸载后不残留。

**会上传我的数据吗？**
不会。脚本、日志、截图都保存在本机。使用 AI 生成功能时，内容会发送到你自己选择的第三方 AI 应用，受其隐私政策约束。

**会不会被封号？**
取决于目标平台的规则。脚本模拟的是人工点击，但部分平台对自动化有明确限制。建议降低执行频率、错开时间段，使用前先阅读平台用户协议。

**脚本失效了怎么办？**
App 改版会导致查找条件失效，通常修改一下文字或图片特征即可修复。

**能跑 adb 命令吗？**
不能。`adb` 是电脑端工具，手机里没有这个可执行文件。App 内的 Shell 支持 `pm`、`getprop` 等系统命令。

## 隐私

- 不收集用户数据，不使用 Cookie
- 脚本、运行日志、截图仅存于本机
- 无需注册账号即可使用基础功能

## 免责声明

请在遵守所在地区法律法规与平台规则的前提下使用本工具，**因违规使用产生的后果由使用者自行承担**。

本项目不提供游戏辅助、批量注册、爬取隐私数据等违规用途。

## 反馈

- 邮箱：[svipl688@foxmail.com](mailto:svipl688@foxmail.com)
- 问题与建议：[提交 Issue](https://github.com/runpilot-app/runpilot-app.github.io/issues)

---

<div align="center">
<sub>RunPilot · 让重复操作自动完成</sub>
</div>
