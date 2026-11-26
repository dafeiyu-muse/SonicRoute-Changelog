# SonicRoute-Changelog

[![上游仓库](https://img.shields.io/badge/%E4%B8%8A%E6%B8%B8%E4%BB%93%E5%BA%93-kunkunkunQoQ%2FSonicRoute-181717?style=flat-square&logo=github)](https://github.com/kunkunkunQoQ/SonicRoute) ![收录版本](https://img.shields.io/badge/%E6%94%B6%E5%BD%95%E7%89%88%E6%9C%AC-39%20%E4%B8%AA-007EC6?style=flat-square) ![总下载量](https://img.shields.io/badge/%E6%80%BB%E4%B8%8B%E8%BD%BD%E9%87%8F-1669%20%E6%AC%A1-4CAF50?style=flat-square) ![最新版本](https://img.shields.io/badge/%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC-v1.36-FF9800?style=flat-square) ![许可证](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81-GPL--3.0--only-9E9E9E?style=flat-square)

> 📜 收录 SonicRoute 每个版本的官方变化，内容来自上游 release 说明原文；源仓库：[kunkunkunQoQ/SonicRoute](https://github.com/kunkunkunQoQ/SonicRoute)，上游发布页：[Releases](https://github.com/kunkunkunQoQ/SonicRoute/releases)。

---

## 📥 下载量

**总下载量：1669 次**（39 个版本合计）。数据为 GitHub release 附件下载量快照，统计时间 2026-11-26 15:21；数字会随时间增长。

| 排名 | 版本 | 发布日期 | 下载量 | 占比 | 可视化 |
| --- | --- | --- | ---: | ---: | --- |
| 🥇 | [v1.35](#v135) | 2026-11-21 | 199 | 11.9% | ████████████████████ |
| 🥈 | [v1.32](#v132) | 2026-11-14 | 155 | 9.3% | ████████████████░░░░ |
| 🥉 | [v1.29](#v129) | 2026-10-27 | 107 | 6.4% | ███████████░░░░░░░░░ |

前三名合计 **461 次**，占总下载量的 **27.6%**。

## 🧭 快速导航

- **2026 年 11 月**：[v1.36](#v136) · [v1.35](#v135) · [v1.34](#v134) · [v1.33](#v133) · [v1.32](#v132) · [v1.31](#v131) · [v1.30](#v130)
- **2026 年 10 月**：[v1.29](#v129) · [v1.28](#v128) · [v1.27](#v127) · [v1.26](#v126) · [v1.25](#v125) · [v1.24](#v124) · [v1.23](#v123) · [v1.22](#v122) · [v1.21](#v121) · [v1.20](#v120)
- **2026 年 9 月**：[v1.12r](#v112r) · [v1.19](#v119) · [v1.18](#v118) · [v1.17](#v117) · [v1.16](#v116) · [v1.15](#v115) · [v1.14](#v114) · [v1.13](#v113) · [v1.12](#v112) · [v1.11](#v111) · [v1.10](#v110)
- **2026 年 8 月**：[v1.0.9](#v109) · [v1.0.8](#v108) · [v1.0.7r2](#v107r2) · [v1.0.7](#v107) · [v1.0.6](#v106) · [v1.0.5r4](#v105r4) · [v1.0.5r3](#v105r3) · [v1.0.4](#v104) · [v1.0.3](#v103) · [v1.0.2](#v102) · [v1.0.5r2](#v105r2)

## 🗂️ 版本总览

| 版本 | 发布日期 | 主题 |
| --- | --- | --- |
| [v1.36](#v136) | 2026-11-24 | AirPlay 多设备同时输出、Android 未压缩 PCM 与 3 档延迟、捕获兼容 Android 11、多输出键位重映射与主窗口侧栏折叠 |
| [v1.35](#v135) | 2026-11-21 | 快捷面板统一即时切换、防闪烁设备切换 OSD、显式多输出保留与剪贴板并发修复 |
| [v1.34](#v134) | 2026-11-21 | 应用多设备播放、Android 双面板重连与文件传输、触屏与托盘操作 |
| [v1.33](#v133) | 2026-11-18 | 自研 C# AirPlay 音画投屏、H.265 与声画解码器选择、统一配对与无线重连、独立麦克风 OSD 与全端轻量/稳定性优化 |
| [v1.32](#v132) | 2026-11-14 | Full 纯 C# 自研 Android 后端瘦身、虚拟屏游戏手柄支持、系统输出自动跟随默认播放设备、手机面板间距调整与全端闲时资源优化 |
| [v1.31](#v131) | 2026-11-08 | 友好编码器名称与九语本地化、120 fps 与 24/32/50 Mbps 预设、整机主屏镜像恢复与多设备剪贴板同步 |
| [v1.30](#v130) | 2026-11-04 | Full 增加可选 Android 手机音频集成与独立虚拟屏幕、桌面端面板布局与自动化体验升级 |
| [v1.29](#v129) | 2026-10-27 | 全部输出设备音量面板、按需加载与 Shift 滚轮系统音量 |
| [v1.28](#v128) | 2026-10-26 | 应用卡片、清晰的状态标记与托盘设备切换 |
| [v1.27](#v127) | 2026-10-24 | 音频会话事件通知、快速面板统一与设置体验改进 |
| [v1.26](#v126) | 2026-10-23 | 高权限应用图标修复、按需音频读取与底层状态可靠性 |
| [v1.25](#v125) | 2026-10-22 | 拥抱 .NET 10、便携版一键安全更新与 37 种自动化连招 |
| [v1.24](#v124) | 2026-10-20 | 场景起步模板与个性化应用图标 |
| [v1.23](#v123) | 2026-10-15 | 托盘右键音频控制与盲调分离 |
| [v1.22](#v122) | 2026-10-11 | 开机自启隔离与轻量化加载 |
| [v1.21](#v121) | 2026-10-09 | 事件驱动架构与 18 种自动化编排 |
| [v1.20](#v120) | 2026-10-01 | 自动化编排初登场与极客命令行联动 |
| [v1.12r](#v112r) | 2026-09-27 | OSD 架构全面重构零闪烁、多屏 DPI 抖动修复与深浅托盘适配 |
| [v1.19](#v119) | 2026-09-21 | Legacy .NET Framework 4.8 兼容版首发、ARM64 原生实验支持与自动化启动增强 |
| [v1.18](#v118) | 2026-09-18 | 简洁面板固定高度重构、自动化退出与定时触发、规则启用停用状态 |
| [v1.17](#v117) | 2026-09-17 | 自动化可视化积木化、拖拽重排动画、OSD 初始化与平滑过渡 |
| [v1.16](#v116) | 2026-09-14 | 极简可视化自动化规则引擎上线、快速面板滑入动效 |
| [v1.15](#v115) | 2026-09-13 | 9 语言架构重构与外置语言扩展、屏幕定位与启动选项 |
| [v1.14](#v114) | 2026-09-12 | 任务栏与托盘滚轮盲调、音量步进统一、配置清理与备份 |
| [v1.13](#v113) | 2026-09-11 | 麦克风静音常驻横幅、幽灵音频会话智能过滤、输入设备全量感知 |
| [v1.12](#v112) | 2026-09-09 | 全新 Win11 飞出式简洁快速面板、状态强调色与多语言 |
| [v1.11](#v111) | 2026-09-05 | 全局快捷键矩阵升级、多维设备切换与一键还原 |
| [v1.10](#v110) | 2026-09-04 | 折叠 UI 优化、8 语言翻译补齐、内存换出优化 |
| [v1.0.9](#v109) | 2026-08-31 | 实验设置一键还原、关闭 UI 内存回收多层修复 |
| [v1.0.8](#v108) | 2026-08-28 | 1080p 高清图标、商店版图标与开机自启修复 |
| [v1.0.7r2](#v107r2) | 2026-08-28 | 关闭 UI 内存释放子选项与发布说明乱码修复 |
| [v1.0.7](#v107) | 2026-08-28 | 实验模式彩蛋解锁、麦克风选项、OSD 自定义位置与折叠开关 |
| [v1.0.6](#v106) | 2026-08-26 | 禁用自动切换、快捷键与任务栏解析一致、粉色主题修正 |
| [v1.0.5r4](#v105r4) | 2026-08-26 | 修复快捷键识别错误应用缺陷 |
| [v1.0.5r3](#v105r3) | 2026-08-26 | 设置页全选按钮交互优化 |
| [v1.0.4](#v104) | 2026-08-26 | 应用改名输入即保存、多语言按需加载、主题色彩优化 |
| [v1.0.3](#v103) | 2026-08-26 | 应用自定义名称、最近使用模式、应用排序功能 |
| [v1.0.2](#v102) | 2026-08-26 | 多语言初版上线、全局麦克风总闸静音、快捷键改键优化 |
| [v1.0.5r2](#v105r2) | 2026-08-26 | 修复全选按钮打勾符号在部分字体的显示 |

---

## 📜 完整版变化记录

以下为 39 个版本的完整发布说明原文，按发布日期倒序排列；每章末尾可返回[版本总览](#-版本总览)。

## v1.36

发布日期：2026-11-24 · 上游 release：[v1.36](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.36)

下载量：**77 次**

# 🎧 SonicRoute v1.36 正式版

> **发布日期** 2026-11-24 · **主题** AirPlay 多设备同时输出、Android 未压缩 PCM / 3 档延迟与自适应码率、多输出键位重映射与主窗口侧栏折叠 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.36) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🎛️ **多输出选区重映射与主窗口同步**。Full、Lite 和 Legacy 的快速面板将 `Shift + 单击` 改为保留现有选择并追加连续范围，`Ctrl + Shift + 单击` 切换 Windows 原生路由主设备，并以不同主题样式区分原生路由与镜像分发；「应用」页补齐多输出操作，主窗口左侧主导航栏支持折叠与状态记忆。
- 🍎 **AirPlay 多设备同时输出（仅 Full）**。AirPlay 音频会话支持在快速面板和「应用」页中同时选择多个输出目标（电脑或 Android 设备），统一遵循多输出选区与样式规则。
- 🔊 **Android 未压缩 PCM、3 档延迟与更高兼容性（仅 Full）**。每台手机新增未压缩 `Raw PCM` 音频传输及「超低延迟 / 平衡 / 稳定」三档延迟模式；扩展多 ROM 音频捕获兼容，应用捕获最低要求下探至 Android 11。
- 🎬 **Android 视频自适应码率与全端性能/商店优化**。无线连接支持事件驱动自适应视频码率与样本池解码优化；全版本合并设备通知中心、批量音量写入与空闲资源回收；Store 版保持任务栏分组标识并声明 AirPlay 防火墙规则。

---

## 🛠️ 详细更新

### 1. 全版本（Full / Lite / Legacy）· 多输出交互、主窗口与底层重构

- **多输出键位重映射与样式区分**。`Shift + 单击` 现保留当前已有选择（含已选隐藏设备）并追加连续范围，`Ctrl + Shift + 单击` 用于选择或切换 Windows 原生路由设备（支持系统默认镜像并在默认输出变化时按事件重新绑定）。主设备（`DevButtonActive`）与采集分发镜像（`DevButtonMirror`）采用区分样式并自适应浅色/深色主题；同步更新九种语言的 `Qp.PlaybackMultiSelect` 提示。
- **主窗口侧栏折叠与「应用」页对齐**。主窗口左侧主导航栏支持平滑折叠/展开并持久化状态，收窄「应用」页二级设备栏宽度并收紧间距。「应用」页补齐与快速面板一致的多输出选区、即点即亮（Optimistic UI）与原生/镜像样式，并与快速面板保持跨窗口同步。
- **设备通知、空闲回收与配置安全**。引入 `AudioDeviceNotificationHub` 合并 CoreAudio 设备通知，保护内部镜像会话并复用轻量镜像播放；统一设备筛选、音量批量写入（`CoalescedVolumeWriter`）与异步启动项编辑器；改进主窗口空闲 UI 回收与 `AtomicFile` 原子配置写入，清理 13 项经审计的未用符号与资源。
- **Microsoft Store 任务栏标识**。Store 打包版启动时显式绑定应用用户模型 ID（AUMID），保持任务栏图标与固定标识一致。

### 2. Full 版 · AirPlay 多输出、Android 音视频与防火墙规则

- **AirPlay 多设备同时输出**。AirPlay 音频会话接入 `IMultiOutputAudioSession`，可在快速面板和「应用」页同时选择多个电脑或已连接 Android 输出设备，并同步头部增益、音量与静音状态。
- **Android Raw PCM 与 3 档音频延迟**。设备流媒体设置新增未压缩 `Raw PCM` 传输选项与「超低延迟 / 平衡（默认）/ 稳定」三档延迟模式，配合 Concentus Opus 延迟配置与自适应 PCM 缓冲；九种界面语言同步本地化设置项与生效说明。
- **Android 音频捕获兼容性扩展**。改进跨 ROM 播放音频捕获兼容，将应用音频捕获门槛下探至 Android 11 及以上，新增不支持音频格式与无效音频流错误提示。
- **Android 视频自适应码率与解码优化**。无线连接增加事件驱动的视频自适应码率控制器（`AdaptiveBitrateController`，平滑下调码率并支持关键帧同步请求）；桌面端引入引用计数安全的 MediaFoundation 输入样本池、`ComLease`、双 span 解码与同步帧恢复，限制编码器 FPS/能力边界并优化低延迟回退；跨 ADB 服务缓存 helper JAR、共享 USB 监听并保护活动 USB 流，改进虚拟屏触控/输入处理。
- **Store Full 版 AirPlay 防火墙规则**。Store Full 清单声明 AirPlay mDNS、PTP 时钟及传输端口范围（UDP `5353`、`319–320`，TCP/UDP `47120–47183`）的入站防火墙规则，并在商店运行时绑定该端口范围。

<details>
<summary>English release notes</summary>

## What’s new

### Full, Lite, and Legacy

- **Remapped multi-output modifiers and route styling**. In Quick Panel, `Shift-click` now preserves existing selections (including hidden selected outputs) while adding a contiguous range, and `Ctrl+Shift-click` selects or switches the Windows native routing endpoint (including System Default mirrors with event-driven rebinding). Native routes (`DevButtonActive`) and capture-distributed mirrors (`DevButtonMirror`) use distinct adaptive light/dark button styles, with updated `Qp.PlaybackMultiSelect` guidance in all nine languages.
- **Collapsible main sidebar and Apps page parity**. The main window’s primary sidebar can now collapse and expand with persisted state, and the Apps page secondary sidebar is narrower with tighter spacing. The Apps page now matches Quick Panel’s multi-output selection, optimistic UI, native vs. mirror styling, and cross-window state synchronization.
- **Consolidated audio notifications, idle reclaim, and cleanup**. Added `AudioDeviceNotificationHub` to consolidate CoreAudio device notifications, protect internal mirror sessions, and reuse lightweight mirror playback. Unified device filtering, batched volume writes (`CoalescedVolumeWriter`), async launch-item editing, atomic file backups, and idle main-window UI reclamation, while removing 13 audited unused symbols and resources.
- **Microsoft Store taskbar identity**. Packaged Store builds explicitly apply their AppUserModelID on startup so taskbar icons and pinned entries stay grouped consistently.

### Full

- **AirPlay simultaneous multi-device output**. AirPlay audio sessions now implement `IMultiOutputAudioSession`, letting you play AirPlay audio across multiple PC or connected Android outputs at the same time from Quick Panel or the Apps page with synchronized volume, mute, and gain.
- **Android Raw PCM and three audio latency modes**. Per-phone streaming settings add uncompressed `Raw PCM` audio transport alongside Concentus Opus and introduce three audio latency modes — Ultra-low latency, Balanced (default), and Stable — backed by adaptive PCM buffering and localized across all nine languages.
- **Broader Android audio capture compatibility**. Improved app playback capture compatibility across Android ROMs, lowering the minimum requirement notice to Android 11 and adding clear error messages for unsupported audio formats or invalid audio streams.
- **Adaptive video bitrate and decoding pipeline improvements**. Wireless virtual displays add an event-driven `AdaptiveBitrateController` with smoothed downshifts and keyframe sync requests. Desktop decoding adds a refcount-safe MediaFoundation input sample pool, `ComLease`, two-span decoding, and sync frame recovery with encoder FPS/capability clamping. Helper JAR transfers are cached across ADB services with shared USB hook handling and live USB stream protection, alongside refined virtual display input handling.
- **AirPlay firewall rules in Store Full**. `AppxManifest.xml` declares inbound domain/private firewall rules for AirPlay discovery, PTP timing, and listener ports (UDP `5353`, `319–320`, TCP/UDP `47120–47183`), matched by `AirPlayListenerPorts` when packaged.

</details>

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
| --- | --- | --- |
| ⭐ **Full**（全功能版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-v1.36-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-v1.36-arm64.exe) | Windows 音频、Android 互联与 AirPlay。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-v1.36-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-v1.36-Lite-arm64.exe) | Windows 本机音频。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🛡️ **Legacy x64**（兼容版） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-v1.36-Legacy-x64.zip) | Windows 本机音频，需 .NET Framework 4.8，完整解压后运行 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 在架版本以各自的商店页面为准 |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SonicRoute-update.json) | 客户端自动更新检测清单 |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.36/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

便携版升级时先退出对应版本，再替换程序。Legacy 请完整解压新版 ZIP。原有设置保存在用户数据目录。Microsoft Store 版本以商店页面显示为准。

To upgrade a portable edition, close that edition before replacing its executable. For Legacy, extract the entire new ZIP. Your settings remain in the user data directory. See the Microsoft Store listings for the versions available there.

---

## 📜 许可证说明（GPL-3.0-only）

本版采用 GPL-3.0-only。第三方组件沿用各自的许可证。 [许可证全文](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.36/LICENSE) · [第三方声明](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.36/packaging/AndroidLab/THIRD-PARTY-NOTICES.md) · [完整源码比较](https://github.com/kunkunkunQoQ/SonicRoute/compare/v1.35...v1.36)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.35

发布日期：2026-11-21 · 上游 release：[v1.35](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.35)

下载量：**199 次**

# 🎧 SonicRoute v1.35 正式版

> **发布日期** 2026-11-21 · **主题** 快捷面板统一即时切换、防闪烁设备切换 OSD、显式多输出保留与剪贴板并发修复 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.35) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🎛️ **快捷面板统一即时切换**。Full、Lite 和 Legacy 的电脑应用麦克风输入与外部音频行均支持点击后即时高亮并排队生效，不再禁用按钮；应用行标题即时同步所选输出设备名称，失败时自动回退并提示。
- ⚡ **设备切换快捷键与防闪烁 OSD**。全局设备切换与路由还原快捷键改为无阻塞排队执行。45 ms 内完成的快速切换直接显示结果，耗时更久时再展示本地化“切换中”提示并至少保留 500 ms 可见。
- 🔊 **显式多输出镜像稳定保留**。移除按系统默认端点或原生活动会话自动剔除镜像的逻辑，原生音频会话在已选输出之间移动时继续保持用户的多路播放组合。
- 📋 **Android 音频与剪贴板并发修复（仅 Full）**。在模式切换期间保持输出切换能力并维持虚拟屏响应；修复停用手机来源后在途桌面剪贴板写入与清空剪贴板前的标记内存管理。

---

## 🛠️ 详细更新

### 1. 全版本（Full / Lite / Legacy）· 快捷面板交互、快捷键 OSD 与多输出

- **快捷面板统一即时切换**。电脑应用的麦克风输入行支持独立单选即时切换（与多选播放输出互不干扰），AirPlay 与单输出外部音源行同样改为点击后即时高亮并按顺序排队应用，切换期间保持按钮可点击。快速面板中电脑、Android 与 AirPlay 应用行标题均即时同步显示目标输出名称（电脑系统默认输出保留默认设备后缀样式）。顶部系统设备下拉框增强默认设备回退与并发保护；目标不可用或切换失败时回退到实际状态并弹出提示。
- **设备切换快捷键与 OSD 阈值**。切换当前或全局应用输出/输入、切换系统默认输出/输入及还原全部应用路由改为无阻塞排队处理。45 ms 内完成的快速切换直接展示最终 OSD，避免瞬时闪烁；超过该阈值后展示本地化的“正在切换输出设备”或“{应用} · 切换中”提示并至少保持 500 ms 可见，失败时立即提示，不额外等待。九种界面语言同步新增对应切换提示文案。
- **显式多输出镜像保留**。移除按系统默认端点或原生活动会话自动剔除已选本机镜像的逻辑。当原生音频会话在多个已选输出之间移动时，继续保留用户显式选择的多路镜像，并防止同一端点被重复添加。

### 2. Full 版 · Android 音频、虚拟屏响应与剪贴板同步

- **Android 输出切换与虚拟屏响应**。在模式切换经过重新启动阶段时保持活动输出切换能力；在音频输出打开与连接阶段记录分段耗时，保持虚拟屏点击与操作响应，并补充异常清理。
- **剪贴板同步并发与资源安全**。多手机启用双向剪贴板同步时，停用其中一台来源设备会立即取消其尚未写入电脑的在途桌面剪贴板写入，同时不影响其余已启用设备；清空系统剪贴板前先预分配并托管本地标记格式（`Remote` / `Cloud`）内存句柄，避免写入失败时泄露或产生未标记状态；释放剪贴板同步器时先取消在途任务再关闭桌面监听。

<details>
<summary>English release notes</summary>

## What’s new

### Full, Lite, and Legacy

- **Unified optimistic switching in Quick Panel**. Microphone input selections for PC apps (independent of multi-output playback) and single-output external sources (including AirPlay) now highlight immediately and apply through a serialized queue without disabling buttons. PC, Android, and AirPlay row titles update optimistically to reflect the selected output name (keeping the default-device suffix on PC system-default rows). The top system device selector hardens default rollback and concurrency handling, and failed or unavailable switches roll back cleanly with an on-screen notice.
- **Non-blocking device hotkeys and flicker-free OSD**. Global device-switching and route-reset hotkeys execute via a non-blocking queue with two-stage OSD feedback. Switches finishing within 45 ms jump straight to the final result without flashing a pending banner; slower switches show localized switching status and keep it visible for at least 500 ms before updating (failures display immediately without waiting). All nine interface languages include the new switching and failure strings.
- **Explicit multi-output mirror retention**. Removed logic that dropped mirrors based on the system default endpoint or native session moves. When a native audio session moves between selected outputs, explicitly chosen mirrors remain active and duplicate endpoints are prevented.

### Full

- **Android output switching and virtual display responsiveness**. Keeps active output switching enabled across capture mode transitions, instruments output startup phases while preserving virtual display input responsiveness, and strengthens error cleanup.
- **Clipboard sync concurrency and handle safety**. When multiple phones are enabled, disabling a source phone now cancels its in-flight desktop clipboard write while keeping other devices active. Local clipboard marker flags (`Remote` and `Cloud`) are pre-allocated before `EmptyClipboard()` with unified ownership transfer and cleanup on failure, and disposal cancels pending clipboard tasks before tearing down the desktop listener.

</details>

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
| --- | --- | --- |
| ⭐ **Full**（全功能版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-v1.35-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-v1.35-arm64.exe) | Windows 音频、Android 互联与 AirPlay。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-v1.35-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-v1.35-Lite-arm64.exe) | Windows 本机音频。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🛡️ **Legacy x64**（兼容版） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-v1.35-Legacy-x64.zip) | Windows 本机音频，需 .NET Framework 4.8，完整解压后运行 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 在架版本以各自的商店页面为准 |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SonicRoute-update.json) | 客户端自动更新检测清单 |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.35/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

便携版升级时先退出对应版本，再替换程序。Legacy 请完整解压新版 ZIP。原有设置保存在用户数据目录。Microsoft Store 版本以商店页面显示为准。

To upgrade a portable edition, close that edition before replacing its executable. For Legacy, extract the entire new ZIP. Your settings remain in the user data directory. See the Microsoft Store listings for the versions available there.

---

## 📜 许可证说明（GPL-3.0-only）

本版采用 GPL-3.0-only。第三方组件沿用各自的许可证。 [许可证全文](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.35/LICENSE) · [第三方声明](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.35/packaging/AndroidLab/THIRD-PARTY-NOTICES.md) · [完整源码比较](https://github.com/kunkunkunQoQ/SonicRoute/compare/v1.34...v1.35)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.34

发布日期：2026-11-21 · 上游 release：[v1.34](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.34)

下载量：**77 次**

# 🎧 SonicRoute v1.34 正式版

> **发布日期** 2026-11-21 · **主题** 应用多设备播放、Android 双面板重连与文件传输、触屏与托盘操作 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.34) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🎛️ **应用多设备播放与恢复**。Full、Lite 和 Legacy 均可为同一个应用选择多个电脑输出，保存成功的组合，在应用重新播放时尝试恢复。
- 📱 **Android 双面板与重连（仅 Full）**。同步 USB 和 Wi-Fi 状态，快捷手机面板的「刷新」也可重新连接所选设备。Android 应用的输出选单会显示已保存的手机输出别名。
- 📂 **Android 文件传输（仅 Full）**。可从设备详情发送、浏览和接收文件，分别设置手机与电脑的接收目录。
- 🖱️ **桌面操作与语言更新**。托盘滚轮与鼠标快捷键共用一个监听，触屏可长按拖动，自动化编辑器可保留草稿并切换语言。

---

## 🛠️ 详细更新

### 1. 全版本（Full / Lite / Legacy）· 桌面功能与界面语言

- **应用多设备播放与恢复**。在快捷面板中按住 Ctrl 可增减播放设备，按住 Shift 可选择连续范围。各版可组合多个电脑输出，Full 还可加入可用的手机输出。成功的多输出组合按应用保存，应用再次播放或输出设备恢复可用时会尝试恢复。切回单输出会清除保存的组合。
- **鼠标和托盘操作**。托盘滚轮调节音量和鼠标快捷键共用一个系统鼠标监听。关闭托盘滚轮后，已启用的鼠标快捷键仍可使用。匹配的快捷键只执行一次，普通滚动继续传给原窗口。
- **触屏操作**。短距离滑动仍可滚动列表。长按后移动可拖动应用图标，也可用拖动手柄排列自动化规则和步骤。
- **界面语言和文档**。切换语言时，已经打开的自动化编辑器也会刷新，并保留未保存的规则内容和正在输入的延迟值。设备选择器、窗口按钮、设置提示和无障碍标签补充了本地化。九种语言的 README 同步更新，并提供日文自动化编辑器预览。

### 2. Lite / Legacy · 本机音频与按需启动

- **按需启动**。仅在托盘运行时推迟加载窗口资源和触控处理。首次显示界面时再加载。
- **本机多输出**。为同一个应用选择多个本机设备时，多个输出共用同一路应用音频采集，输出设备暂时来不及接收时按需缓冲。
- **Legacy 打包**。本机播放使用的 NAudio 程序集内嵌到 EXE，继续通过完整 ZIP 分发。

### 3. Full 版 · Android 互联与 AirPlay

- **Android 连接管理**。打开的主界面与快捷手机面板会随 USB 插拔和 Wi-Fi 断线更新状态。同一手机在两种连接方式之间切换时可保留原设备 ID、名称和设置。快捷手机面板右下角的「刷新」和设备详情页的「重新连接」共用恢复流程。USB 无法打开时，设备详情会显示原因，并继续显示仍有效的 Wi-Fi 连接。
- **手机音频输出**。「手机当前输出」跟随手机的媒体路由，可作为 Windows 应用、Android 来源及 AirPlay 的播放目标。Android 应用的输出选单会使用为该输出设置的自定义名称。设备音频与单个 Android 应用可选择多个播放目标，保存的路由可在来源和目标重新可用后尝试恢复。
- **仅手机播放**。把电脑应用声音只送到手机时，先尝试可用的备用电脑输出进行隔离。没有可用备用输出时，在满足条件的情况下才暂时静音来源扬声器，并在退出该路由后恢复。
- **Android 文件浏览和传输**。可从设备详情拖入或选择多个文件发送，浏览受支持的手机目录并选择文件接收到电脑。手机和电脑的接收目录可分别设置，传输可取消。
- **剪贴板和串流**。改进双向文字剪贴板在 USB 或 Wi-Fi 连接变化后的恢复，并补充权限问题提示。编码器查询绑定当前连接。从后台或托盘启动后，视频窗口会正确显示首帧。
- **AirPlay 界面与连接状态**。主界面和快捷面板同步显示接收的启动、等待、连接和停止状态，接收状态也显示在快捷面板底部。切换接收状态期间防止重复操作。

<details>
<summary>English release notes</summary>

## What’s new

### Full, Lite, and Legacy

- **Multi-device playback per app**. In Quick Panel, hold Ctrl to add or remove playback devices, or hold Shift to select a range. Every edition can combine multiple PC outputs. Full can also include an available phone output. SonicRoute saves successful selections per app and tries to restore them when the app plays again or an output becomes available. Switching to a single output clears the saved group.
- **Mouse and tray controls**. Tray-wheel volume control and mouse shortcuts share a system mouse hook. Enabled mouse shortcuts keep working when tray-wheel volume control is turned off. A matching shortcut fires once, and ordinary scrolling still reaches the original window.
- **Touch controls**. Short swipes still scroll lists. Press and hold, then move to drag an app icon or use a drag handle to reorder automation rules and steps.
- **Interface languages and documentation**. Changing the language refreshes an open automation editor while preserving unsaved rule changes and partially entered delay values. Device pickers, window controls, settings hints, and accessibility labels have broader localization coverage. The READMEs were updated in all nine languages, and a Japanese automation editor preview is available.

### Lite and Legacy

- **On-demand startup**. Tray-only startup defers loading window resources and touch handling until the first interface opens.
- **Local multi-output playback**. When an app plays through multiple local devices, the outputs share one capture of the app’s audio. An output buffers data only when the device cannot accept it immediately.
- **Legacy packaging**. The NAudio assemblies used for local playback are embedded in the executable. Legacy is still distributed as a complete ZIP.

### Full

- **Android connection management**. The main window and quick phone panel update when a USB cable is connected or removed or when Wi-Fi disconnects. A phone can keep its saved device ID, name, and settings when switching between USB and Wi-Fi. Refresh in the quick phone panel and Reconnect in device settings use the same recovery flow. If the USB interface cannot be opened, the device page explains the problem and still shows a working Wi-Fi connection.
- **Phone audio output**. The phone’s current output follows its active media route and can be selected for Windows apps, Android audio sources, and AirPlay. The Android app output menu displays the custom name assigned to that output. Device-wide Android audio and individual apps can use multiple playback targets. SonicRoute can try to restore saved routes when the source and targets become available again.
- **Phone-only playback**. When sending a PC app’s audio only to the phone, SonicRoute first tries to isolate playback with an available spare PC output. If none can be used, it temporarily mutes the source speaker only when the conditions allow it and restores it when the route ends.
- **Android file browsing and transfers**. From the device page, drag in or select multiple files to send. Browse supported folders on the phone and select files to receive on the PC. You can set separate receive folders on the phone and PC and cancel a transfer.
- **Clipboard and streaming**. Bidirectional text clipboard sync can recover after USB or Wi-Fi changes and now indicates permission problems. Encoder queries are tied to the current connection. The video window now appears on the first frame when SonicRoute was started in the background or from the tray.
- **AirPlay interface and status**. Starting, waiting, connected, and stopping states are synchronized across the main window and quick panel, with receiving status in the quick panel footer. The receive switch is disabled during transitions to prevent duplicate actions.

</details>

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
| --- | --- | --- |
| ⭐ **Full**（全功能版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-v1.34-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-v1.34-arm64.exe) | Windows 音频、Android 互联与 AirPlay。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-v1.34-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-v1.34-Lite-arm64.exe) | Windows 本机音频。单文件 EXE，需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| 🛡️ **Legacy x64**（兼容版） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-v1.34-Legacy-x64.zip) | Windows 本机音频，需 .NET Framework 4.8，完整解压后运行 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 在架版本以各自的商店页面为准 |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SonicRoute-update.json) | 客户端自动更新检测清单 |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.34/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

便携版升级时先退出对应版本，再替换程序。Legacy 请完整解压新版 ZIP。原有设置保存在用户数据目录。Microsoft Store 版本以商店页面显示为准。

To upgrade a portable edition, close that edition before replacing its executable. For Legacy, extract the entire new ZIP. Your settings remain in the user data directory. See the Microsoft Store listings for the versions available there.

---

## 📜 许可证说明（GPL-3.0-only）

本版采用 GPL-3.0-only。第三方组件沿用各自的许可证。 [许可证全文](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.34/LICENSE) · [第三方声明](https://github.com/kunkunkunQoQ/SonicRoute/blob/v1.34/packaging/AndroidLab/THIRD-PARTY-NOTICES.md) · [完整源码比较](https://github.com/kunkunkunQoQ/SonicRoute/compare/v1.33...v1.34)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.33

发布日期：2026-11-18 · 上游 release：[v1.33](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.33)

下载量：**96 次**

# 🎧 SonicRoute v1.33 正式版

> **发布日期**：2026-11-18 · **主题**：自研 C# AirPlay 音画投屏、H.265 与声画解码器选择、统一配对与无线重连、独立麦克风 OSD 与全端轻量/稳定性优化 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.33) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🍎 **自研 C# AirPlay 音频与屏幕镜像接收（仅 Full）**：无需额外运行库或外部软件，支持 PCM / ALAC / AAC-LC 与 C# 双声道 AAC-ELD 音频，支持等比投屏窗口（置顶 / `F11` 全屏）、可选 4 位投屏码、媒体曲名/歌手/封面展示，以及在快速面板中拖拽或一键转发至电脑设备或已连接的 Android 扬声器/蓝牙设备。
- 🎞️ **H.265（HEVC）与声画解码器选择（仅 Full）**：Android 与 AirPlay 新增 H.265 支持（Android 编码启动失败在同一连接自动回退 H.264，含独立关键帧恢复与损坏帧防护）；Android 设备设置新增声音/画面解码器选择器与可见设备页按需编码器查询（按机缓存最多 4 台），并将游戏手柄严格门控至获焦前台视频窗口。
- 📱 **统一手机配对卡片、无线重连刷新与配置恢复（仅 Full）**：将二维码（2 分钟自动换码、点击主动刷新）与配对码整合进同一张卡片且互不阻塞；设备设置重连、快捷设备面板刷新、应用页侧栏刷新统一验证当前设备连接，筛掉过期端口并按已保存身份找回新 IP/端口（无可用候选或失败时切回手动输入并保留草稿）；支持移除重加按稳定身份自动恢复设置与 USB 显式恢复，并加固配对身份与期限控制。
- 🎛️ **独立麦克风 OSD 开关、配置卡片与轻量性能优化（全版本）**：主题页独立显示并保存「所有麦克风静音时 OSD 常驻」与「默认录音设备静音时 OSD 常驻」；实验设置整合单行「配置文件管理」卡片（导出/导入/清理）；超过 20 个应用行启用虚拟化容器，合并 OSD 过渡并释放已解码 PNG 原始字节与闲置视频纹理，Full 取消关窗显式主动 GC 请求（交由运行时自然回收）。
- 🛡️ **可靠性加固、Store Lite 独立包与 GPL-3.0-only 迁移**：新增 `config.json.bak` 原子备份与损坏保护、单实例重启交接、鼠标多键仲裁与按需错误诊断日志；支持独立 Microsoft Store **Lite** MSIX 打包（`9N37LQ8SMLF6`），并于 2026-11-17 起迁移至 `GPL-3.0-only`（全版本设置页内置离线查看）。

---

## 🛠️ 详细更新

### 1. Full 版：自研 AirPlay 音画投屏、H.265 与手机互联体验升级
- **自研 C# AirPlay 接收与输出转发**：从「添加设备 → AirPlay」或手机面板底部开启接收，广播电脑名称并加入可用 IPv4 接口；支持媒体标题/歌手/按需封面解码、可选 4 位投屏码、投屏窗口置顶与 `F11` / `Esc` 等比全屏；AirPlay 音量行共用电脑设备顺序与别名规则，可将声音切至电脑输出或已连接的 Android 扬声器/蓝牙（目标失效自动回退 Windows 系统输出），并支持图标拖拽切换或断开当前串流。
- **H.265（HEVC）、解码器选择与串流稳定性**：Android 设备页「声音」「画面」行新增解码器选择（默认自动，可选 C# `Concentus Opus` 与 `Windows D3D11 优先 / Windows 软件解码`），仅在当前设备设置页可见时后台查询编码器并缓存；H.265 切换编码配置时保留上一帧并等待独立帧再提交画面、跳过损坏帧；游戏手柄仅在当前前台未最小化窗口生效，手机 PCM16 转换启用 SIMD 加速（保留标量回退）。
- **合并配对卡片、无线端口验证重连与身份加固**：连接页左侧二维码自动开启并到期刷新，右侧保留手动配对与直接连接；打开安卓连接页或点击「搜索」发起一次性 `_adb-tls-connect._tcp.local` 局域网发现并验证候选端口，无可用候选或失败时切回手动地址并保留用户输入草稿；设备设置重连、快捷设备面板刷新、应用页侧栏刷新统一验证当前设备连接，先确认现存 ADB 身份响应，失效时以一次性 mDNS 查找与短 TCP 探测筛掉过期端口、按已保存身份找回新地址并在连接核对身份后才覆盖保存；移除设备保留配置档案，无线显式重连或 USB 显式恢复时按稳定身份还原，不再被同 IP 旧记录覆盖；统一 `20s` 自动连接 / `30s` 手动配对期限并将取消配对绑定当前真实认证身份。

### 2. 全版本（Full / Lite / Legacy）：桌面功能、性能优化与可靠性加固
- **桌面交互与配置整理**：两项麦克风静音 OSD 常驻开关独立保存、共享同一次事件驱动录音读取（无新增轮询）；实验设置将导出、导入（保留拖入）与清理合并至单行「配置文件管理」卡片。
- **按需渲染与轻量资源管理**：应用列表超过 20 行时切换 WPF 可回收容器并延后创建控件（20 行内维持预建路径）；OSD 合并同目标连续输入并按硬件/软件渲染限帧；通过 `ImageDataStream` 释放解码后不再持有的原始 PNG 字节，Full 切换软硬解码时即时释放退役 GPU 纹理并取消关窗显式主动 GC 请求（交由运行时自然回收，Lite / Legacy 保持关窗后单次限频工作集收缩）。
- **配置安全、稳定性与发行规范**：写入/导入/重置前原子保留 `config.json.bak` 并在损坏时保护原件；单实例重启等待新进程资源就绪后再退出旧实例；精确仲裁鼠标组合键冲突、隔离坏图标，并在异常时按需写入 `Logs/diagnostics.log`；新增独立 Microsoft Store **Lite** MSIX 清单支持与设置页内置离线 `GPL-3.0` 查看器。完整逐项改动与验证边界请参阅 [Wiki 版本历史（09-版本历史）](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2)。

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
|---|---|---|
| ⭐ **Full**（全功能全量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-v1.33-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-v1.33-arm64.exe) | 完整版（纯 C# Android 互联、自研 AirPlay 音画与电脑音频路由），单文件 EXE（需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0)） |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-v1.33-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-v1.33-Lite-arm64.exe) | 轻量版（仅保留 Windows 本地音频路由），单文件 EXE（需匹配架构的 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/zh-cn/download/dotnet/10.0)） |
| 🛡️ **Legacy x64**（免装运行库） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-v1.33-Legacy-x64.zip) | 兼容版（.NET Framework 4.8），多文件绿色免安装包 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 商店版（提供独立 Full / Lite；在架版本以商店页面为准，需 x64 .NET 10 Desktop Runtime） |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SonicRoute-update.json) | 客户端自动更新检测清单 |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.33/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

---

## 📜 许可证说明（GPL-3.0-only）

- **当前发行协议（GPL-3.0-only）**：自 **2026 年 11 月 17 日**起（提交 `46cf001`），完整 SonicRoute 源码与 `v1.33` 及后续发行物（在版权所有者有权授权的范围内）采用 GNU 通用公共许可证第 3 版，仅限该版本（`GPL-3.0-only`），允许商用、销售与收费分发，须遵守 GPL 条款；分发所涵盖的修改作品或二进制文件时，须继续使用 GPL 第 3 版并按 GPL 第 6 条提供完整对应源码与必要声明，详见仓库 [LICENSE](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/LICENSE) 与 [LICENSING.md](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/docs/LICENSING.md)（新版本设置页亦可点击 `GPL-3.0` 离线查看）。
- **既有发行物与第三方许可保留**：此前已授予的 MIT 权限（含原始 `v1.32` 标签 `4e3138f` 及其既有下载资产）及 2026-11-14 期间的旧自定义许可权限继续有效；本次仓库协议迁移不撤销先前授予的权限，亦不改写既有标签或已发布的旧二进制资产，第三方组件保留各自原有许可（见 [THIRD-PARTY-NOTICES.md](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/packaging/AndroidLab/THIRD-PARTY-NOTICES.md) 与 [AirPlay 兼容声明](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/SonicRoute.AndroidAudio/AirPlay/Compatibility/NOTICE.md)）。

> [⬆ 返回版本总览](#-版本总览)

---

## v1.32

发布日期：2026-11-14 · 上游 release：[v1.32](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.32)

下载量：**155 次**

# 🎧 SonicRoute v1.32 正式版

> **发布日期**：2026-11-14 · **主题**：Full 纯 C# 自研 Android 后端瘦身、虚拟屏游戏手柄支持、系统输出自动跟随默认播放设备、手机面板间距调整与全端闲时资源优化 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.32) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🧩 **Full 纯 C# 自研后端与单文件显著瘦身**：彻底移除随包内嵌的 `adb.exe`、`scrcpy`、FFmpeg 与 SDL2 等外部二进制（ARM64 同步移除外置 x64 辅助进程），改用纯 C# 传输与 Windows 原生解码/渲染，单文件大幅缩减。
- 🎮 **虚拟屏游戏手柄透传支持（仅 Full）**：独立虚拟屏与主屏镜像窗口支持 Windows 手柄直通（最多 4 路 XInput 及 RawInput HID 手柄），仅窗口获焦且未最小化时生效，失焦或断连自动释放按键防卡键。
- 📐 **调整手机面板距离（仅 Full）**：将速控面板旁并排弹出的手机面板间距由 `12` DIP 收窄至 `6` DIP，与音量浮窗保持统一紧凑间距。
- 🔊 **手机系统输出自动跟随默认播放设备（仅 Full）**：手机音频输出设为「系统输出」时，切换 Windows 默认播放设备后自动重建本地播放并保留当前捕获与音量状态。
- 🛠️ **全版本交互修复与按需闲时资源优化**：修复托盘「系统默认播放」长名称子菜单重叠问题，图标按需解码、闲置 OSD 定时释放、按窗体加载样式字典并优化闲时内存回收。

---

## 🛠️ 详细更新

### 1. Full 版：纯 C# 自研 Android 后端与体验增强
- 移除 `adb.exe`、`scrcpy`、SDL2 与 FFmpeg DLL 外部依赖，保留轻量化自研 Android 服务与图标资源。
- 新增基于窗口焦点门控的游戏手柄透传支持，收窄手机附窗面板间距（`12 → 6` DIP），支持「系统输出」自动跟随 Windows 默认播放设备切换。
- 修复连接并发竞态、TLS 1.3 上下文、USB 失败槽位重试、取消建窗句柄泄漏、最大化不回写自定义尺寸及退出整机镜像恢复单应用音频等问题，并正式合入 SmartVolume 增益曲线调参。

### 2. 全版本（Full / Lite / Legacy）：桌面交互与资源管理
- 修复异步读取长设备名称时托盘「系统默认播放」二级子菜单重叠遮挡问题。
- 实施图标按目标尺寸解码、8 秒无提示释放闲置 OSD、主窗口按需加载样式与取色器资源，以及闲时缓存/连接/LOH 优化（Full 继续保护活动手机音视频与虚拟屏）。

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
|---|---|---|
| ⭐ **Full**（全功能全量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-v1.32-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-v1.32-arm64.exe) | 完整版（纯 C# 自研后端，含手机音画、虚拟屏与手柄透传），单文件 EXE |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-v1.32-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-v1.32-Lite-arm64.exe) | 轻量版（仅保留 Windows 本地音频路由），单文件 EXE |
| 🛡️ **Legacy x64**（免装运行库） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-v1.32-Legacy-x64.zip) | 兼容版（.NET Framework 4.8），多文件绿色免安装包 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 商店版（提供 Full / Lite；在架版本以商店页面为准） |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SonicRoute-update.json) | 客户端自动更新检测清单 |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.32/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

---

## 📜 许可证说明（已于 2026-11-17 迁移至 GPL-3.0-only）

- **当前主分支协议（GPL-3.0-only）**：自 **2026 年 11 月 17 日**起（提交 `46cf001`），主分支完整 SonicRoute 源码（在版权所有者有权授权的范围内）采用 GNU 通用公共许可证第 3 版，仅限该版本（`GPL-3.0-only`），允许商用、销售与收费分发，须遵守 GPL 条款；分发所涵盖的修改作品或二进制文件时，须继续使用 GPL 第 3 版并按 GPL 第 6 条提供完整对应源码与必要声明，详见仓库 [LICENSE](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/LICENSE) 与 [LICENSING.md](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/docs/LICENSING.md)。
- **既有发行物与历史许可保留**：此前已授予的 MIT 权限（含原始 `v1.32` 标签 `4e3138f` 及其既有下载资产）及 2026-11-14 期间的旧自定义许可权限继续有效；本次仓库协议迁移不撤销先前授予的权限，亦不改写既有标签或已发布的旧二进制资产，第三方组件保留各自原有许可（见 [THIRD-PARTY-NOTICES.md](https://github.com/kunkunkunQoQ/SonicRoute/blob/master/packaging/AndroidLab/THIRD-PARTY-NOTICES.md)）。

> [⬆ 返回版本总览](#-版本总览)

---

## v1.31

发布日期：2026-11-08 · 上游 release：[v1.31](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.31)

下载量：**91 次**

# 🎧 SonicRoute v1.31 正式版

> **发布日期**：2026-11-08 · **主题**：友好编码器名称与九语本地化、120 fps 与 24/32/50 Mbps 预设、整机主屏镜像恢复与多设备剪贴板同步 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.31) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 🏷️ **多语言友好编码器名称与九语本地化**：手机详情页 Opus 与 H.264 编码器选择器升级为可读友好说明（厂商 + 软/硬件编码并保留原 Codec ID），支持 Android 29+ 编解码器能力实时查询与离线厂商兜底，硬件优先排序与长文本悬停提示，九语即时刷新。
- ⚡ **更高画质码率与高帧率选项**：画面 H.264 码率预设扩展为 `[1, 4, 6, 8, 12, 16, 24, 32, 50] Mbps`（移除 2 Mbps）；画面帧率预设扩展支持 `120 fps`（`[15, 24, 30, 60, 120] fps`）。520 DIP 窄布局优化，确保选项完整无截断。
- 🖥️ **整机主屏镜像恢复与等比缩放**：整机卡片拖出使用 display0 等比缩放镜像手机主屏，接管整机音频，复用 GPU D3D11 渲染，标题栏显示手机名称与统一轮廓图标。
- 📋 **多设备剪贴板同步**：支持电脑与已连接 Android 手机之间的文本剪贴板按需同步，并提供快速面板与完整界面的即时开关控制。
- 🌐 **设置页稳定性与数据绑定优化**：九种内置语言补齐至 838 键，修复数据绑定单向写回问题以消除特定语言下进入设置页异常。

---

## 🛠️ 详细更新

### 1. 友好编码器名称、高码率与 120 fps 支持
- 将手机详情页直接暴露的原始 Android 编解码器 ID 替换为可读友好说明（例如中文 `高通 · 硬件编码 (c2.qti.avc.encoder)`、`Android · 软件编码 (c2.android.avc.encoder)`），并在括号中保留原始 ID 以保持配置持久化与底层命令参数兼容。
- 实时通过 `EncoderCatalog` 查询 Android 29+ 的真实软硬件编解码能力，未上报或离线展示时基于高通、联发科、三星 Exynos、海思、紫光展锐等厂商前缀表安全兜底；编码器列表按硬件优先排序，下拉框文本过长时使用省略号并在悬停时实时展示完整说明。
- 码率预设新增 `24/32/50 Mbps`，帧率新增 `120 fps`；整机主屏镜像与单应用虚拟屏均支持全码率与高帧率透传。

### 2. 整机主屏镜像恢复与多设备剪贴板同步
- 手机整机卡片拖出恢复为镜像当前手机主屏（display0），保持画面等比缩放并接管整机声音。
- Scrcpy 原生客户端程序图标及窗口/任务栏图标统一复用手机轮廓资源，标题栏仅显示手机设备名称。
- 支持 PC 与 Android 手机双向剪贴板同步，在快速面板与完整界面中按设备独立开启或关闭。

### 3. 本地化完善与设置页稳定性修复
- 全面补充九种内置语言（简中、繁中、英文、日文、韩文、法文、德文、西班牙文、俄文）至 838 键。
- 修复设置页特定控件默认的双向绑定写回错误，彻底解决部分系统下打开设置界面闪退的问题。

---

## 📦 资产下载与校验

| 版本 | 下载 | 说明 |
|---|---|---|
| ⭐ **Full (x64)** | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.31/SonicRoute-v1.31-x64.exe) (27.2 MB) | 完整版（含手机音频流转、主屏镜像与剪贴板同步），单文件 EXE |
| 🪶 **Lite (x64)** | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.31/SonicRoute-v1.31-Lite-x64.exe) (6.0 MB) | 轻量版（仅保留 Windows 本地音频路由），单文件 EXE |
| 🛡️ **Legacy (x64)** | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.31/SonicRoute-v1.31-Legacy-x64.zip) (978 KB) | 兼容版（.NET Framework 4.8），多文件绿色免安装 ZIP |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 商店版（提供 Full / Lite；在架版本以商店页面为准） |
| 📋 **更新清单** | [`SonicRoute-update.json`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.31/SonicRoute-update.json) | 客户端自动更新检测清单（Protocol 2） |
| 🔒 **校验散列** | [`SHA256SUMS.txt`](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.31/SHA256SUMS.txt) | SHA-256 完整性校验文件 |

> [⬆ 返回版本总览](#-版本总览)

---

## v1.30

发布日期：2026-11-04 · 上游 release：[v1.30](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.30)

下载量：**67 次**

# 🎧 SonicRoute v1.30 正式版

> **发布日期**：2026-11-04 · **主题**：Full 增加可选 Android 手机音频集成与独立虚拟屏幕、桌面端面板布局与自动化体验升级 · [📥 发布页](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.30) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 更新亮点

- 📱 **Full 加入可选手机集成**：连接 Android 手机后，可把手机应用声音接入电脑，按应用调节音量、静音和播放设备，也可将电脑应用声音送到手机。手机功能只包含在 Full；Lite 与 Legacy 保持纯 PC 音频功能，不带任何手机集成或依赖。
- 🖥️ **手机应用独立虚拟屏幕**：可将手机应用画面显示在电脑独立窗口中，并按「手机 + 应用」保存窗口对应的虚拟分辨率；调整电脑窗口尺寸会同步调整虚拟显示尺寸。
- 🔊 **手机音频输出明确受控与源手机设备直显**：流转到电脑的手机应用在播放设备列表中直接显示源手机扬声器与已连接蓝牙设备；切换到源手机扬声器或蓝牙时仅改变输出目标，主面板继续保留音量、静音、智能音量与虚拟屏幕控制，点击「退出」或拖回左侧手机面板才交还手机。电脑或入站手机音频送往手机端时，均严格核对实际目标物理设备，避免把“请求成功”误当成路由已切换。
- 📊 **快速面板手机应用峰值电平与智能音量（SmartVolume）**：可见的手机应用行复用实时电平条（关闭面板或禁用电平表即停止采样订阅）；手机设备页固定应用直接显示在快速手机面板，并默认开启「智能音量」自动平衡感知响度范围，支持按应用独立切换。
- 🎛️ **快速面板布局选项、39 项自动化动作与桌面端体验升级**：主题页新增快速面板简洁/完整应用行布局与设备名显示设置；自动化新增「设置/切换当前应用麦克风静音状态」动作（共 6 类触发 × 39 项动作）；新增配置导入预览确认、应用绝对音量合并写入与无外阴影窗口风格。

---

## 🛠️ 详细更新

### 1. Full 手机集成与独立虚拟屏幕

- 在 Full 中加入 Android 设备连接（USB 调试及无线调试二维码/配对码与 mDNS 发现）、手机应用目录缓存、按应用音频流转、手机输出选择及独立虚拟显示；手机侧原生运行组件按需释放使用。
- 手机应用沿用 SonicRoute 的音量、静音、智能音量和播放设备操作；切换到源手机扬声器或已连接蓝牙设备时，会话仍由电脑侧接管控制（通过低延迟轨道在手机端渲染），仅在点击快速面板「退出」或将应用图标拖回左侧手机面板时才退出流转并交还手机自身播放。
- 手机应用和电脑应用的音频路径相互隔离。手机流使用独立外部源标识，不会伪装成 Windows 进程或录音会话；没有可用的 Windows 输入会话时，输入操作保持不可用。
- 完整界面「设置 → 关于」作者主页同行末尾提供「开源许可」链接，按需查看内嵌第三方声明。Lite 与 Legacy 不包含手机 UI、手机音频实现、手机运行依赖或手机许可入口。Microsoft Store 的安装包以 Full 为构建来源，但商店当前在架版本及上架时间以 [Store 页面](https://apps.microsoft.com/detail/9NQZGRTPM1NT)为准。

### 2. 手机路由、快速面板峰值电平与智能音量

- 手机应用行显示实时峰值电平条：分配独立负目标 ID，与 Windows 正数 PID 的 COM 会话枚举隔离；手机流的 PCM 写入只在采样器处于等待状态且写入非静音样本时触发单次合并唤醒，这项机制不等同于整版 CPU 或内存降幅。
- 设备页固定应用直接显示在快速手机面板（取消固定即移除）。「智能音量」（`SmartVolume`）默认开启，可逐应用实时切换；手机输出列表只提供该源手机可用的扬声器（使用已保存手机名称）和已连接蓝牙输出。
- 全部音频路由、输出切换与退出操作保持按应用隔离。电脑送往手机或手机流切回源手机输出时，均建立会话范围渲染策略并验证实际物理设备路由（避免被手机其它应用的蓝牙深缓冲输出合并）；未确认路由前保持静音，不会把成功提交设置当作声音已切换的证据。

### 3. 桌面端界面、音频控制与自动化维护（Full / Lite / Legacy）

- **快速面板应用行布局与滑块交互**：
  - 在「主题」页集中提供快速面板应用行显示设置：支持切换「使用简洁应用行布局」（默认开启）及其子选项「显示播放设备名称」，或完整布局下的「应用行显示播放设备名称」。
  - 扩大应用音量滑块拖拽响应区域，并修复快速面板滚动条出现时的应用行宽度跳动问题。
- **概览页、应用卡片与窗口风格统一**：
  - 概览页与「应用」页音量卡片布局对齐，将静音按钮移至音量滑块旁并支持整卡点击，移除概览页设备选择器旁冗余的“当前”文字标签。
  - 移除完整主窗口与快速面板主表面的外层阴影，保留主题背景、边框与圆角；九种语言界面统一将面向用户的“输出/输入”规范为“播放/录音”。
- **自动化引擎扩充（6 类触发 × 39 项动作）**：
  - 新增动作 37「设置当前应用麦克风静音状态」（`SetCurrentAppInputMute`）与动作 38「切换当前应用麦克风静音状态」（`ToggleCurrentAppInputMute`），运行时按当前应用规则解析录音会话并校验回读（全局快捷键集合保持与 v1.29 一致）。
  - 新增动作分组显示模型，最近执行历史详情新增目标确认计数（`已确认 X / Y 个目标`）及一次性定时规则停用说明。
- **配置导入预览、合并写入与更新器优化**：
  - 实验设置「导入配置」新增预览确认弹窗，导入前展示快捷键数、设备/应用别名数及当前未连接设备与未运行应用数量。
  - 新增应用绝对音量合并写入与回读确认，设置保存改为快照异步串行落盘；优化快速面板初始重叠读取与额外播放设备音量面板的通知合并刷新。
  - 软件更新下载与校验过程支持取消，细化校验失败与网络失败提示。
- **分版本内存回收策略**：
  - Lite 与 Legacy 延续 v1.29 的轻量工作集回收策略（窗口关闭 1.5 秒延迟后单次工作集收缩，带可见窗口门控与 30 秒冷却，不叠加显式全代 GC）；Full 保护后台活动手机连接、音频与虚拟屏，不执行全进程工作集裁剪。本版没有量化整版 CPU、内存或窗口响应提升，不据此推断长时间使用或不同设备上的性能变化。

---

## 📋 验证范围与限制

- 开发阶段记录了桌面端多套定向检查及手机端 118 项定向检查，其中小米 13 真机检查覆盖入站与 PC 出站路径的扬声器与蓝牙切换、非静音 Opus/PCM 数据和受控退出。这是开发阶段证据，不表示这些检查均在本次正式候选包上重跑，也不代表所有 Android 机型、系统版本或音频设备均已验证。
- 真机验证覆盖了指定的手机应用和测试路径；人工听感、长时间 CPU/内存测量、原生 ARM64 设备及其他 Android 设备仍未验收。微软商店安装后的行为取决于当前商店在架版本，不能由便携版测试替代。
- 定向读取或通知合并检查只证明对应路径行为，不构成整版性能提升数据。自动化 39 项动作数量来自当前源码枚举。

## 📦 下载矩阵

| 版本 | 下载 | 说明 |
|---|---|---|
| ⭐ **Full**（全功能旗舰版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.30/SonicRoute-v1.30-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.30/SonicRoute-v1.30-arm64.exe) | .NET 10 单个 EXE；包含可选 Android 集成（ARM64 原生未实测，ADB/辅助为 x64） |
| 🪶 **Lite**（纯 PC 轻量版） | [x64](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.30/SonicRoute-v1.30-Lite-x64.exe) / [ARM64（实验）](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.30/SonicRoute-v1.30-Lite-arm64.exe) | .NET 10 单个 EXE；纯 PC 音频，不含手机集成 |
| 🛡️ **Legacy x64**（免装运行库） | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.30/SonicRoute-v1.30-Legacy-x64.zip) | 系统 .NET Framework 4.8；13 文件 ZIP 归档，完整解压后运行 |
| 🔄 **Microsoft Store** | [Full](https://apps.microsoft.com/detail/9NQZGRTPM1NT) / [Lite](https://apps.microsoft.com/detail/9N37LQ8SMLF6) | 由 Full / Lite 构建；商店在架版本以 Store 页面为准 |

Full 与 Lite 按单 EXE 提供，不做额外程序压缩；Legacy 是 13 文件 ZIP 归档。便携版为框架依赖部署，需要匹配架构的 .NET 10 Desktop Runtime；Legacy 使用 Windows 内置 .NET Framework 4.8。发布附件另含校验文件和更新元数据。NET8 下载链接继续指向 v1.29 历史版本；该兼容版已停止提供新版本。ARM64 资产为实验性，未在原生 ARM64 设备验证；Full 的 ADB 与视频辅助工具仍是独立 x64 进程。

## 🔄 升级与数据保留

升级前请从托盘正常退出 SonicRoute。替换单 EXE 或完整解压 Legacy ZIP 时，选择对应发行形态与架构；升级器不会跨发行形态或运行时迁移。设置、自动化规则、主题和自定义图标保存在数据目录中，手动升级前可按需备份 `%LocalAppData%\SonicRoute\`。Store 版继续通过 Microsoft Store 更新。

> [⬆ 返回版本总览](#-版本总览)

---

## v1.29

发布日期：2026-10-27 · 上游 release：[v1.29](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.29)

下载量：**107 次**

# 🎧 SonicRoute v1.29 正式版

> **发布时间**：2026-10-27 · **核心主题**：全部输出设备音量面板、按需加载与 Shift 滚轮系统音量 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.29) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🎚️ **展开控制全部输出设备**：快速面板顶部新增展开按钮，在额外面板中分别调整输出设备的主音量与静音，显示设备名称、默认标记和音量百分比。
- 📐 **自动选择展开位置与高度**：保留主面板原位置；额外面板优先向上展开，顶部空间不足时选择合适侧边。高度随设备数量变化，最高与主面板一致，空间不足时滚动。
- 💤 **按需加载和事件刷新**：收起时释放额外控件与监听；展开先显示已有设备列表，再异步确认状态。连续音量通知合并，只读取变化设备，快速收展与筛选不会被旧结果覆盖。
- 🖱️ **Shift＋滚轮调系统音量**：在原托盘响应区域按住 Shift 滚动，直接调节系统默认播放设备音量，并复用已有 OSD 反馈。

---

## 🛠️ 详细更新

### 1. 全部输出设备音量面板

- 点击快速面板设备选择器右侧的箭头展开或收起，记住用户选择，下次打开沿用；默认保持收起。
- 每个真实输出设备有独立的音量、静音、百分比和音量档位菜单；滚轮沿用现有音量步长。主面板原有应用音量列表保持原用法。
- 额外面板自动选择可用空间：通常向上；主面板位于左上角时放右侧、右上角时放左侧。展开和收起不改变主面板保存的位置与基础高度。
- 高度按实际显示设备数量计算，上限为当前主面板高度，同时受屏幕工作区限制；设备较少时缩短，较多时滚动，没有设备时显示紧凑提示。
- 展开箭头使用随明暗主题切换的背景。额外面板由该箭头统一收起，不增加重复关闭按钮。
- 在“快速面板更改系统默认设备”下方新增独立开关 **“额外面板只显示保留设备”**。开启后仅显示原“保留的设备”中保留的输出设备，默认关闭；该筛选不禁用主面板自己的设备音量控制。
- “快速面板更改系统默认设备”继续默认开启，保留用户明确保存的关闭选择。

### 2. 加载、同步与释放

- 额外设备行在展开时才创建，先复用主面板设备快照完成初始显示，再异步确认最新设备和音量，减少先显示空白小面板再扩高的过程。
- 输出端点分别监听变化；健康状态下，连续通知合并后只读取发生变化的设备。通知回调不执行音频读取或释放工作。
- 收起和关窗取消额外面板排队的刷新及读取等待，释放控件、端点与设备通知；重新展开使用新的加载范围，旧结果不能覆盖新界面。
- 修复读取过程中快速切换设备筛选后，新行可能缺少初始状态的问题；新建行主动补读，保留旧读回的版本保护。
- 拓扑变化与失败恢复继续核对完整状态。只有额外面板可见且通知注册或读取失败时才启用原恢复检查，成功或收起后停止；健康状态不新增后台轮询。
- 保留原音量合并写入队列和关窗 1.5 秒工作集缩减。

### 3. 托盘滚轮

| 操作 | 行为 |
|---|---|
| 普通滚轮 | 调节当前应用播放音量 |
| Shift＋滚轮 | 调节系统默认播放设备音量 |
| Alt＋滚轮 | 切换当前应用输出设备 |
| Alt＋Shift＋滚轮 | 切换系统默认播放设备 |

- 四种操作共用原托盘命中范围、暂停开关、步长、合并派发和快捷键优先级。Shift 系统音量复用现有快捷键音量处理与 OSD，不新增设置或轮询。
- 托盘命中复用已解析的反射元数据，修正原生返回值声明，删除不安全的 Toolbar 回退；保留 30 秒失败恢复并限定为同一图标身份，减少错误命中风险。

### 4. JSON、语言与电平路径

- NET10 执行历史写入采用紧凑的生成序列化合同；语言读写集中复用已有模块和写入选项，保持现有文件格式与按需初始化。
- 合并电平工作状态并减少字典查找，保留原采样节奏、平滑、量化、回零和通知恢复机制。
- 未保留缺少稳定收益的锁替换与读取试验。本版不宣称整版 CPU、内存或窗口打开耗时下降百分比。

---

## 📋 升级与验证说明

- 额外面板的最终定向检查覆盖 NET10、NET8 和 Framework x64：各 14 项观察器/恢复检查与 41 项真实产品私有桌面检查，验证加载取消、快速收展、筛选反转、订阅释放、尺寸上限和主音量可用性。之前的九语、深浅主题及托盘检查记录继续保留。
- 模拟 8 台设备时，同一台 100 次通知合并后只读取该台设备；这是定向读取次数检查，不等于整版 CPU 降幅。
- 真实音频检查仅执行读取，没有写入用户音量、静音或默认设备。物理鼠标、真实热插拔/驱动重启、混合 DPI 跨屏、Windows 10 真机、原生 ARM64 和 Store 安装后行为仍需对应环境实测。
- 支持独立更新器的便携版可在“设置 → 软件更新”检查、下载、校验并确认重启升级；自动检查仍默认关闭。更新匹配发行形态、运行时和架构，不自动跨运行时迁移。

---

## 🚀 资产下载矩阵

| 发行形态 | 下载 | 运行环境要求 |
|---|---|---|
| ⭐ **Lite x64**（默认主版本） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-v1.29-Lite-x64.exe) | x64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ⚡ **Lite ARM64**（实验性） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-v1.29-Lite-arm64.exe) | ARM64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ☕ **Lite NET8 x64**（兼容版） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-v1.29-Lite-NET8-x64.exe) | x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ☕ **Lite NET8 ARM64**（兼容版） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-v1.29-Lite-NET8-arm64.exe) | ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64** | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-v1.29-Legacy-x64.zip) | 系统 .NET Framework 4.8；完整解压后运行 |
| 🔄 **Microsoft Store** | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | x64 .NET 10 Desktop Runtime；在架版本以商店页面为准 |

> [!NOTE]
> - 支持 Windows 10 2004+（Build 19041+）与 Windows 11。
> - Lite 与 Store MSIX 为框架依赖部署，不内置 .NET Desktop Runtime。
> - 2026 年 11 月之后停止提供和维护 NET8 版。此后 x64 用户可手动选择 NET10 或 Legacy，ARM64 用户选择 NET10。
> - 七项 Release 附件还包含 [SHA256SUMS.txt](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SHA256SUMS.txt) 与 [SonicRoute-update.json](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.29/SonicRoute-update.json)（Protocol 2）。SHA-256 校验完整性，不等于独立发布者签名。MSIX 单独构建，不包含在七项附件中；商店在架版本独立维护。

---

## 🔄 升级与数据保留

1. 使用软件内更新，或下载当前发行形态、运行时与架构对应的文件。v1.24 及更早版本请手动更新。
2. 手动升级前从托盘正常退出 SonicRoute，再替换 EXE 或完整解压 Legacy ZIP；不同发行形态的文件分别存放。
3. 更新器不替换原数据目录中的设置、自动化规则、主题及自定义图标。手动升级前可备份 `%LocalAppData%\SonicRoute\`；Store 版继续使用商店更新机制。

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [快捷键](https://github.com/kunkunkunQoQ/SonicRoute/wiki/03-%E5%BF%AB%E6%8D%B7%E9%94%AE) · [自动化规则](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99)
- [完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [反馈问题](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [支持作者](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.28

发布日期：2026-10-26 · 上游 release：[v1.28](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.28)

下载量：**52 次**

# 🎧 SonicRoute v1.28 正式版

> **发布时间**：2026-10-26 · **核心主题**：应用卡片、清晰的状态标记与托盘设备切换 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.28) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🪟 **应用页面重新整理**：应用信息、音频路由、音量和快捷控制分组展示；名称旁点击铅笔即可原位改名，导入图标与恢复默认放在右上角。
- 🎯 **状态标记各有含义**：列表右侧反色点表示播放静音，正常点表示音频会话活动；不在快速面板显示的应用，在图标左上角单独标记。
- 🖱️ **托盘滚轮切设备**：Alt＋滚轮切换当前应用的输出设备；Alt＋Shift＋滚轮切换系统默认播放设备。普通滚轮继续调节当前应用播放音量，已有设备切换快捷键保留。
- 📦 **发布与升级流程完善**：正式说明优先使用人工核对的 UTF-8 文本；加强候选文件、运行时隔离、下载回验与更新助手恢复检查。

---

## 🛠️ 详细更新

### 1. 应用卡片与操作

- **原位编辑应用名称**：名称旁的铅笔会在原位置展开输入框，自动选中当前名称。输入沿用原有自动保存；回车或移开焦点后收起，留空恢复默认名称。仅打开编辑器不会把默认名称额外保存成自定义名称。
- **输入与输出共用路由卡片**：“音频路由”标题、输出设备和输入设备放在同一张卡片内。关闭麦克风选项后隐藏输入区，输出选择器铺满整行。
- **快捷控制更紧凑**：静音、禁用自动切换、在快速面板显示各自保留开关，开关靠右居中；“在快速面板显示”采用开启即显示的正向含义，旧配置保持兼容。
- **减少重复说明**：去掉路由、音量和快捷控制卡片的冗余辅助文字。名称编辑的留空与保存提示保留在悬停提示中；失败反馈复用原有提示方式。
- **避免旧结果串到新应用**：切换选中应用或关闭窗口后，延迟返回的音量、路由及静音结果不会更新错误的目标；未选中应用时清空并禁用对应操作。

### 2. 列表状态标记

- **右侧反色点：播放静音**。静音与活动状态同时存在时，静音标记优先。
- **右侧正常点：音频会话活动**。未静音且存在 Active 会话时显示；它表示会话状态，不等同于实时电平、实际可听声音或没有其他静音因素。
- **图标左上角反色点：不在快速面板显示**。这个标记独立于播放静音，可以同时显示。
- 静音读取复用现有会话缓存，在进入应用页、手动刷新和原有操作读回时更新；无需先逐一选中应用。不增加为这些标记服务的定时轮询，外部音量合成器改动按原有刷新时机读回。

### 3. 托盘与默认设置

- **普通滚轮**调节当前应用播放音量；**Alt＋滚轮**在当前应用的可用输出设备间切换；**Alt＋Shift＋滚轮**切换系统默认播放设备。上滚选择上一个，下滚选择下一个。
- 这些操作共用原有托盘命中区域、设备筛选与切换实现。暂停托盘滚轮时一并暂停；已匹配全局滚轮快捷键时，保留快捷键优先级。
- **新配置默认仅在 SonicRoute 托盘图标上响应滚轮**。“托盘区域滚轮”开启后扩展到托盘通知区域，说明文字同步简化。
- **新配置默认开启快速面板更改系统默认设备**。这两个默认值均保留用户已经保存的选择，不强制覆盖旧偏好。
- 已撤回上一／下一设备独立快捷键的试验，现有设备切换动作及绑定继续使用原来的方式；NET10 Lite 继续采用单文件 EXE。

### 4. 发布维护

- 修正稳定版日志基线选择，排除草稿与预发布，不因 GitHub 列表顺序或前几条结果漏掉更新记录；历史读取失败会明确停止。
- 改进发布后 Latest 指针延迟的重试与审计时间记录；发布前继续核对源码收据、五个程序包、更新清单与哈希，并从远端下载回验。
- 更新 README、AI 代码索引与 BenchmarkLab 测量工具。测试工具改进不作为应用本身的性能收益承诺；本版不宣称整版 CPU／内存加速。

---

## 📋 升级与验证说明

- 支持独立更新器的便携版可在“设置 → 软件更新”检查、下载、校验并确认重启升级；自动检查仍默认关闭。更新严格匹配 Lite／Legacy、NET10／NET8／NET48 及 x64／ARM64，不自动跨运行时迁移。
- v1.24 及更早版本请正常退出后手动替换。Legacy 必须完整解压；设置、自动化规则、主题及自定义图标继续使用原有数据目录。
- 应用页定向验证覆盖九种语言、浅深主题、不同窗口宽度、改名保存、标记优先级、只读缓存回读与关闭清理。发行流程另行校验五包七资产、运行时隔离及更新助手失败恢复。
- 离屏界面与隔离夹具检查不等于真实音频写入、物理输入或完整性能基准。原生 ARM64、Windows 10 真机、多显示器 DPI、真实中文输入法及 Store 安装后行为仍需对应环境实测。

---

## 🚀 资产下载矩阵

| 发行形态 | 下载 | 运行环境要求 |
|---|---|---|
| ⭐ **Lite x64**（默认主版本） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-v1.28-Lite-x64.exe) | x64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ⚡ **Lite ARM64**（实验性） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-v1.28-Lite-arm64.exe) | ARM64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ☕ **Lite NET8 x64**（兼容版） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-v1.28-Lite-NET8-x64.exe) | x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ☕ **Lite NET8 ARM64**（兼容版） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-v1.28-Lite-NET8-arm64.exe) | ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64** | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-v1.28-Legacy-x64.zip) | 系统 .NET Framework 4.8；完整解压后运行 |
| 🔄 **Microsoft Store** | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | x64 .NET 10 Desktop Runtime；在架版本以商店页面为准 |

> [!NOTE]
> - 支持 Windows 10 2004+（Build 19041+）与 Windows 11。
> - Lite 单文件和 Store MSIX 均为框架依赖部署，不内置 .NET Desktop Runtime；Microsoft Store 安装不代表系统一定已具备运行时。
> - 2026 年 11 月之后停止提供和维护 NET8 版。x64 用户可手动选择 NET10 或 Legacy，ARM64 用户请选择 NET10。
> - 七项 Release 附件还包含 [SHA256SUMS.txt](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SHA256SUMS.txt) 与 [SonicRoute-update.json](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.28/SonicRoute-update.json)（Protocol 2）。SHA-256 验证完整性，不等同于独立发布者签名。

---

## 🔄 升级与数据保留

1. 使用软件内更新，或从上表下载当前运行时与架构对应的文件。
2. 手动升级时先从托盘正常退出 SonicRoute，再替换 EXE 或完整解压 Legacy ZIP。不要将多个发行形态的程序文件混放。
3. 更新器不替换 `%LocalAppData%\SonicRoute\` 中的设置、规则、主题和自定义图标；手动更新前仍可自行备份该目录。Store 版继续由商店更新。

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [快捷键](https://github.com/kunkunkunQoQ/SonicRoute/wiki/03-%E5%BF%AB%E6%8D%B7%E9%94%AE) · [自动化规则](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99)
- [完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [反馈问题](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [支持作者](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.27

发布日期：2026-10-24 · 上游 release：[v1.27](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.27)

下载量：**53 次**

# 🎧 SonicRoute v1.27 正式版

> **发布时间**：2026-10-24 · **核心主题**：音频会话事件通知、快速面板统一与设置体验改进 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.27) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🎧 **音频会话事件驱动与智能采样**：由会话创建/状态变化与设备通知驱动电平发现与恢复，替代正常状态下每 2 秒完整重建会话；非活动会话零电平即刻休眠等待通知唤醒，活动会话即使瞬时为零仍保持采样，兼顾低功耗与不漏音。
- 🪟 **全面统一快速面板（Modern）**：彻底移除冗余的历史独立经典面板与切换分支，精简 600+ 行代码；统一支持 350~850px 自由高度、坐标记忆与流畅实时电平，老旧配置无损平滑过渡。
- 🎯 **快捷键精准靶向与消除重复 OSD**：修正快速面板呼出时「当前应用静音」快捷键的目标解析，杜绝误静音顶部系统物理设备；复用全局通知服务，彻底消灭麦克风快捷键的重复 OSD 弹窗。
- 🏷️ **设备卡片优先呈现自定义名称**：设置页设备卡片优先展示用户设置的个性化别名，底层设备说明与真实标识如实保留；改名即时全局同步，一目了然。
- 🎨 **全界面现代细滑块滚动条**：全新引入主题色圆角悬停滚动条，支持深色、浅色与高对比度无感切换；复用 WPF 原生虚拟化与滚动性能，零额外后台开销。
- ⚡ **设置行按 ID 复用与全选合并保存**：全选/取消全选操作合并为单次原子持久化写入，刷新时按设备 ID 智能复用控件，大幅减少重复 I/O 与界面抖动。

---

## 📋 详细演进说明

### 1. 音频监听与恢复

- **实时电平按会话通知发现和恢复**：监听会话创建、状态变化及设备通知，替代正常状态下每 2 秒完整重建会话列表。非活动会话电平归零后等待通知；活动会话即使瞬时为零仍保持采样，避免漏掉恢复的声音。通知注册或读取失败时保留必要的恢复检查。
- **复用短时缺失结果**：只有完整成功的扫描才缓存“目标应用没有会话”的结果，缓存有效期 200ms；状态变化会使缓存失效。失败或不完整扫描不会被当作可靠的无会话状态。极端时序下，新会话的发现可能增加约 200ms 等待。
- **麦克风故障恢复减少重复创建**：注册失败时只补齐缺失的通知，复用有效音频对象；真正读取或设备故障仍走原有恢复流程。
- **自动化保留 1 秒兜底**：进程通知异步初始化，订阅失败按 2、4、8 秒递增、最多 30 秒重试；这只调整订阅恢复，不放慢应用启动/退出的 1 秒快照检查。旧监听源及时清理，无相关规则时不保留专用监听。

### 2. 快速面板与快捷键

- **统一为快速面板**：彻底移除旧的独立应用面板窗口、模式选择和专用代码；主窗口的“应用”页面继续保留。面板支持 350–850px 高度、位置保存和实时电平，旧配置可继续加载。
- **修复静音快捷键目标**：快速面板打开时，“当前应用静音”仍作用于应用播放会话，不再误静音顶部选中的系统输出设备；顶部设备静音按钮保持原有作用范围。
- **消除麦克风快捷键重复提示**：复用全局服务与面板读回，只显示一次 OSD。快速面板顶部直接调节设备音量不再弹出 OSD，快捷键等入口仍正常提示。
- **减少面板重复工作**：复用设备名称列表、行和既有刷新机制，清理旧双面板判断与重复初始化路径。全局快捷键动作跳过无关的当前应用探测，并修正右 Win 键配合鼠标的识别。

### 3. 设置与外观

- **设备卡片优先显示自定义名称**：未命名时保留原来的标题，下方原始设备说明、提示和真实设备标识不变；改名沿用原有保存流程并同步现有标题。
- **接入统一滚动条**：使用圆角细滑块，悬停/拖动反馈与主题强调色；复用 WPF 原生滚动、拖动、分页及滚轮交互，支持浅色、深色与系统高对比度资源，不新增后台轮询或持续动画。
- **设备设置行按需复用**：全选/取消全选合并为一次保存，重复刷新按设备 ID 复用现有行，跳过已经完成的同状态展开/收起操作，保留离线设备和编辑状态。
- **麦克风选项保持默认开启**：新配置及缺省字段为开启，用户已经明确关闭的设置继续保留；这不强制开启“在快速面板中显示麦克风”。
- **多语言体验统一**：九种语言同步清理过时面板文案，中文统一使用“快速面板”，高度提示与实际 850px 上限一致。

---

## 📋 升级与验证说明

- **便携版在软件内一键极速升级**：v1.25 / v1.26 便携版可在“设置 → 软件更新”检查、下载并确认升级；自动检查仍默认关闭，只匹配当前发行类型、运行时与架构。Microsoft Store 版继续由商店更新。
- **手动升级与数据保留**：v1.24 及更早版本请退出旧程序后手动更新；Legacy 必须完整解压 ZIP。用户设置、规则、主题及自定义图标仍使用原有数据目录，不随程序替换。
- **性能与验证边界**：本轮已对 NET10、NET8、Legacy 进行音频通知、自动化/快捷键、持久化与面板定向检查。设置行的局部 A/B 显示重复同步和保存减少，但首次创建约增加 1–2ms；这不是整版 CPU/内存基准，不承诺零 CPU 或所有场景加速。
- **环境要求**：原生 ARM64、Windows 10 真机、物理多 DPI/触控及 Store 安装后的运行仍需环境验收。社区反馈的部分全屏游戏快捷键问题尚未复现，不宣称全部解决。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（.NET 10 推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.27/SonicRoute-v1.27-Lite-x64.exe) | 需匹配的 x64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ⚡ **Lite ARM64**（.NET 10 实验版） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.27/SonicRoute-v1.27-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ☕ **Lite NET8 x64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.27/SonicRoute-v1.27-Lite-NET8-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ☕ **Lite NET8 ARM64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的 ARM64 机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.27/SonicRoute-v1.27-Lite-NET8-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.27/SonicRoute-v1.27-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 由商店提供更新，在架版本以商店页面为准 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | x64 .NET 10 Desktop Runtime；MSIX 不内置运行时 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - .NET 10 默认文件名无附加后缀，.NET 8 兼容版带有 `-NET8` 后缀。依照规划，**2026 年 11 月之后将停止提供 .NET 8 新构建**，x64 用户可手动选择 .NET 10 或 Legacy，ARM64 用户请选择 .NET 10，不进行跨运行时自动替换。
> - 发布附件提供 `SHA256SUMS.txt` 校验清单与升级清单 `SonicRoute-update.json`（协议版本 2）。

---

## 🔄 升级与数据保留指引

- **v1.25 / v1.26 便携版用户（推荐在软件内一键升级）**：
  打开 SonicRoute「主窗口 → 设置 → 软件更新」，点击「检查更新」，系统将自动匹配当前架构与运行时，下载并完成校验后点击「立即重启升级」，全程自动备份并平滑过渡。
- **v1.24 及更早版本用户（手动升级）**：
  请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，然后下载对应的新版 EXE（或将 Legacy ZIP 解压覆盖到原程序目录），双击启动即可。
- **保留独立存储的用户数据**：
  软件的所有用户设置、37 种自动化连招规则、全局快捷键绑定及自定义图标均独立保存在 `%LocalAppData%\SonicRoute\`，更新器不替换这些用户数据；建议在手动更新前备份该目录。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [自动化规则配置手册](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.26

发布日期：2026-10-23 · 上游 release：[v1.26](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.26)

下载量：**49 次**

# 🎧 SonicRoute v1.26 正式版

> **发布时间**：2026-10-23 · **核心主题**：高权限应用图标修复、按需音频读取与底层状态可靠性 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.26) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🖼️ **高权限与受保护应用图标智能修复**：彻底解决非管理员权限下网易 UU 远程、系统服务等高权限程序只显示文字占位符的问题；通过复用 Windows WASAPI 音频会话原生图标元数据与窗口回退机制，无感还原真实应用图标。
- 🎚️ **音频会话与策略对象深度复用**：重构底层 CoreAudio 查询流程，在单轮查询中端到端复用设备句柄与策略接口；合并音量与静音状态读取，快速面板在无活跃发声应用时立即跳过额外读取，大幅减少无效 COM 轮询与开销。
- 🎯 **默认设备角色与静音判定更精准**：严格解耦数据流向（Render / Capture）与设备角色（Console / Multimedia / Communications），彻底杜绝跨角色配置冲突；多会话应用合并静音状态更准确，操作遇阻时如实反馈，不再假定全部成功。
- ⚡ **运行时持久化定制加速（.NET 10 / Legacy）**：.NET 10 主力版引入源生成（Source Generator）预编译 JSON 上下文，彻底告别反射开销，提速配置读写；Legacy 版全面缓存元数据及程序路径，同时修复文件监视器退出时的锁等待问题。
- 🍃 **资源按需加载与无感生命周期管理**：图标元数据仅在界面实际展开可见时按需加载，面板关闭即刻暂停专用监听；继续严守克制原则，闲时保持接近 0% CPU 占用，不新增任何周期性后台轮询。
- 🔄 **便携版在软件内一键极速升级**：v1.25 便携版用户可直接在「设置 → 软件更新」中一键检测、校验并平滑重启升级至 v1.26，无需手动前往网页下载覆盖，无缝继承所有规则与配置。

---

## 📋 详细演进说明

### 1. 攻克高权限进程图标缺失，无侵入还原视觉体验
在 Windows 安全机制中，未以管理员身份运行的程序无法通过 Win32 API 读取高权限进程（如 SYSTEM 权限的网易 UU 远程服务、以管理员运行的游戏或工具）的可执行文件路径，此前往往只能回退显示首字母或通用占位图标。
- **WASAPI 会话元数据原生提取**：创新性地利用 Windows 原生音频会话接口（`IAudioSessionControl2.GetIconPath`），在无需提权、无注入的前提下直接获取应用创建音频流时声明的图标路径；
- **多层自愈与自定义优先**：建立「会话元数据 → 窗口图标（WM_GETICON）→ 进程模块」的多级回退链条；用户拖拽导入的自定义图标（PNG/JPEG/ICO）始终保持最高优先级；
- **动态就绪通知**：当后台受保护应用的音频流元数据延迟就绪时，界面对应行会自动刷新呈现，且全程异步加载，绝不阻塞 UI 渲染主线程。

### 2. 音频查询路径精简，空面板零开销
为了在频繁呼出面板或多设备切换时提供更极致的跟手感，v1.26 对核心音频服务（`AudioService`、`SessionVolumeService`）进行了系统级轻量化重构：
- **对象生命周期复用**：在单次应用扫描中，复用已获取的 `IMMDevice` 与策略接口实例，避免对系统混音器服务发起数十次重复的 COM 实例化与释放；
- **状态读取批量合并**：将原本分离的会话音量大小获取与静音状态查询合并为单次批量交互，减少一半的系统内核态切换开销；
- **空面板快速旁路**：当快速面板展开但当前没有任何应用在发声时，直接跳过全量会话遍历逻辑，实现空闲状态下的极低资源损耗。

### 3. 严格厘清设备角色，规避潜在配置串扰
Windows 底层将音频设备划分为数据流向（播放 Render / 录音 Capture）与业务角色（控制台/游戏 Console、多媒体 Multimedia、语音通讯 Communications）。
- **解耦角色枚举**：修正了策略客户端中的角色参数映射，保证设置默认播放设备或麦克风时，精确作用于用户指定的业务角色，杜绝以往在特定系统版本上可能发生的流向与角色混淆；
- **多会话复合应用静音校准**：部分复杂应用（如现代浏览器或大型游戏）会为不同音轨创建多个独立的音频播放会话。新版本能够准确聚合多个子会话的静音状态，并在部分会话操作失败时如实向上层反馈，确保自动化流水线与状态显示 100% 真实。

### 4. 平台针对性持久化调优，消灭退出锁等待
针对 SonicRoute 支持的多元化运行环境，分别量身定制优化方案：
- **.NET 10 源生成预编译**：通过 `PersistenceJsonContext` 在编译期完成 JSON 序列化契约的静态生成，彻底消除 `config.json` 与自动化规则在运行时的动态反射与泛型构造开销，规则保存与读取更加轻快；
- **Legacy 兼容版元数据复用**：在 .NET Framework 4.8 环境下全面缓存序列化元数据与可执行文件路径，保持旧机型上的流畅表现；
- **安全关停修复**：修复了配置与规则目录的 `FileSystemWatcher` 在程序退出时可能因多线程锁竞争导致短暂卡顿的问题，确保应用退出干净利落。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（.NET 10 推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.26/SonicRoute-v1.26-Lite-x64.exe) | 需匹配的 x64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ⚡ **Lite ARM64**（.NET 10 实验版） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.26/SonicRoute-v1.26-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ☕ **Lite NET8 x64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.26/SonicRoute-v1.26-Lite-NET8-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ☕ **Lite NET8 ARM64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的 ARM64 机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.26/SonicRoute-v1.26-Lite-NET8-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.26/SonicRoute-v1.26-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - .NET 10 默认文件名无附加后缀，.NET 8 兼容版带有 `-NET8` 后缀。依照规划，**2026 年 11 月之后将停止提供 .NET 8 新构建**，建议广大用户优先迁移至 .NET 10 或选用无需运行库的 Legacy 版本。
> - 所有便携版发行附件均附带 `SHA256SUMS.txt` 校验清单与升级清单 `SonicRoute-update.json`（协议版本 2）。

---

## 🔄 升级与数据保留指引

- **v1.25 便携版用户（推荐在软件内一键升级）**：
  打开 SonicRoute「主窗口 → 设置 → 软件更新」，点击「检查更新」，系统将自动匹配当前架构与运行时，下载并完成校验后点击「立即重启升级」，全程自动备份并平滑过渡。
- **v1.24 及更早版本用户（手动升级）**：
  请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，然后下载对应的新版 EXE（或将 Legacy ZIP 解压覆盖到原程序目录），双击启动即可。
- **数据与规则 100% 完整保留**：
  软件的所有用户设置、37 种自动化连招规则、全局快捷键绑定及自定义图标均独立保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [自动化规则配置手册](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.25

发布日期：2026-10-22 · 上游 release：[v1.25](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.25)

下载量：**29 次**

# 🎧 SonicRoute v1.25 正式版

> **发布时间**：2026-10-22 · **核心主题**：拥抱 .NET 10、便携版一键安全更新与 37 种自动化连招 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.25) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- ⚡ **率先跃升 .NET 10 现代运行时**：主力 Lite 版本升级至微软最新的 .NET 10 平台，带来更强的底层执行效率；同时贴心提供带 `-NET8` 后缀的兼容版及免装环境的 Legacy 版（.NET 4.8），平滑全兼容。
- 🔄 **单文件便携版实现安全一键更新**：Lite 单文件版终于支持在线更新！在设置中一键检查、下载校验、自动备份并平滑重启升级，自带失败自动回滚保障，告别以往手动下包解压覆盖。
- 🎮 **自动化引擎大扩充（37 种操作）**：动作库从 20 项扩展至 37 项！新增指定设备音量/静音、默认麦克风切换、所有会话批量静音、全应用双向路由重置及快速面板显隐等 17 项强大控制能力。
- 🖼️ **应用图标直接拖拽导入**：在应用详情页支持直接将单张 PNG、JPEG 或 ICO 文件拖入窗口，瞬间为无图标或系统通用图标的程序完成个性化装扮。
- 🎛️ **面板体验与自适应拓展**：快速面板高度上限拓宽至 850px，更适合容纳超长应用列表；应用面板按钮布局紧凑重排；实验设置新增设备全称显示开关。
- 🍃 **底层事件解耦与极致轻量**：优化自动化调度与快照机制，杜绝重复触发；整理 WPF 资源与控件生命周期，界面关闭后彻底释放无用监听，待机闲时保持近乎 0% CPU 占用。

---

## 📋 详细演进说明

### 1. 跃升 .NET 10 时代，兼顾全环境平滑过渡
为了获得更现代的系统级优化与内存调度特性，SonicRoute 主力版本率先迁移至 **.NET 10 Desktop Runtime**。
- **Lite x64 / ARM64（推荐主力）**：基于最新的 .NET 10 构建，适合绝大多数 Windows 10/11 电脑及高通骁龙 / Surface Pro 设备；
- **Lite NET8 x64 / ARM64（兼容版）**：为当前仅安装了 .NET 8 运行时的设备保留，文件名带 `-NET8` 后缀，将持续维护至 2026 年 11 月；
- **Legacy x64（零依赖版）**：依赖系统内置的 .NET Framework 4.8，解压即用，适合受限办公机；
- **Microsoft Store（商店版）**：由微软应用商店负责后台静默自动更新。

### 2. 便携版（Lite）告别繁琐，支持全自动安全更新
以往单文件版用户每次更新都需要打开网页手动下载、关闭旧进程、再替换文件。从 v1.25 开始，便携版拥有了完整的原生更新工作流：
- **渠道严格隔离**：检查更新时会严格根据当前架构（x64 / ARM64）与运行时（.NET 10 / .NET 8 / Legacy）智能匹配对应的补丁包，绝不发生跨环境错升；
- **原子替换与灾备回滚**：更新包完成 SHA-256 校验后，升级代理会自动对原 EXE 进行备份；替换过程中若发生异常或被占用，会自动将原程序完整还原，确保数据零损坏；
- **克制无感**：自动更新检查默认保持关闭，绝不会在后台静默偷跑下载或强制弹窗打扰，把掌控权完全交给用户。

> [!TIP]
> **关于从 v1.24 升级**：由于自动更新机制始于 v1.25，已有 v1.24 版本的用户请先按以往方式手动退出旧版并运行新版 EXE；自 v1.25 起即可在软件内一键无感升级。

### 3. 自动化动作扩容至 37 项，玩法自由组合
本次更新将自动化操作库扩容了整整 17 项（编号 20~36），覆盖了更多发烧友与高级玩家的日常场景：
- **精准硬件设备调控**：支持直接指定某台播放设备设定音量、增减步进或反转静音；支持动态将指定麦克风设为系统默认录音设备；
- **会话级批量静音**：一键对所有正在发声的应用执行静音或音量重置；
- **全应用双向路由一键还原**：基于 Windows 原生机制安全重置所有应用的声音分流，完全不破坏系统混音器配置；
- **快速面板程序化呼出**：支持通过快捷键或外部脚本联动将快速面板显示或关闭，完美配合 Stream Deck 等外接控制台。

### 4. 界面交互与细节体验提升
- **图标拖拽导入**：无需在文件选择对话框中反复翻找路径，直接把桌面或文件夹里的图标文件（PNG/JPEG/ICO）拖入应用页面即可应用；
- **面板自适应扩容**：快捷面板可调高度由原本的 350~800px 提升为 **350~850px**，在高分屏或后台音频软件较多时能一屏呈现更多内容；
- **实验性设备名称显示**：在实验设置中可勾选开启“现代面板显示输出设备名称”，方便直观确认各应用当前绑定的目标设备。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（.NET 10 推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.25/SonicRoute-v1.25-Lite-x64.exe) | 需匹配的 x64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ⚡ **Lite ARM64**（.NET 10 实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.25/SonicRoute-v1.25-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0) |
| ☕ **Lite NET8 x64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.25/SonicRoute-v1.25-Lite-NET8-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ☕ **Lite NET8 ARM64**（.NET 8 兼容版） | 现有仅安装了 .NET 8 的 ARM64 机型 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.25/SonicRoute-v1.25-Lite-NET8-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.25/SonicRoute-v1.25-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 10（或 .NET 8）桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与数据保留指引

- **从 v1.24 首次升级**：请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或把 Legacy ZIP 解压覆盖到原程序目录。
- **数据完全保留**：您现有的应用分流规则、全局快捷键、自动化流水线及自定义图标均保存在 `%LocalAppData%\SonicRoute\`，新版本启动后会自动无损继承。
- **后续更新**：升级至 v1.25 后，便携版用户可直接在「设置 → 软件更新」中一键获取后续新版。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [自动化规则配置手册](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.24

发布日期：2026-10-20 · 上游 release：[v1.24](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.24)

下载量：**23 次**

# 🎧 SonicRoute v1.24 正式版

> **发布时间**：2026-10-20 · **核心主题**：场景起步模板与个性化应用图标 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.24) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🤖 **自动化场景起步模板**：新建规则旁一键选择开黑独占、会议闭麦、游戏降噪等 7 套典型场景，生成未保存草稿，降低规则编写门槛。
- 📊 **最近执行详情日志**：实验设置可选开启（默认关闭、可设 1–64MB 存储上限），提供按需两段滚动与每一步状态、耗时精细排查。
- 🎨 **逐应用自定义图标与首字标识**：支持导入 PNG、JPEG、ICO 格式图标或恢复默认，缺失图标时自动提取首字生成专属强调色标识；导出配置自动打包内嵌。
- ⚡ **按需读取与性能优化**：执行历史按需加载并自动取消过时请求，配置传输与图标复用后台路径。
- 🐛 **修复高权限应用图标**：解决部分以管理员身份运行的应用图标无法在列表中显示的问题（感谢 @Billy636 的 [PR #6](https://github.com/kunkunkunQoQ/SonicRoute/pull/6)）。

---

## 📋 详细演进说明

### 1. 自动化场景起步模板
在「自动化」页面，点击「＋ 新建规则」旁边的示例菜单，即可快速选择：
- 🎮 **游戏使用耳机**：前台为游戏时，声音自动切往耳机；
- 🎙️ **会议使用指定麦克风**：打开飞书/腾讯会议时，自动指定高品质麦克风；
- ⚡ **快捷键切换声音组合**：一键在「耳机+语音」与「音箱+静音麦」之间快速轮转；
- 🎵 **进入游戏降低音乐音量**：游戏启动时背景音乐压低至 30%；
- 🌙 **每晚降低系统音量**：定时防扰民；
- 🚪 **退出游戏切回音箱**：关闭游戏后自愈还原。

> [!TIP]
> 选择示例仅会在界面中生成一份未保存的草稿，不会立刻生效。您可以按需修改应用名、设备与音量参数；所有模板创建的规则默认保持停用，确认无误后手动启用即可。

### 2. 最近执行详情与毫秒级耗时
- 在设置页点击作者头像/名称 5 次解锁「实验模式」，开启「最近执行详情」开关；
- 查看器支持存储最近 200 条执行记录（可自定义 1–64MB 存储上限，默认 4MB）；
- 展开每条记录可深入查看规则内各个步骤的执行结果、状态（成功、跳过、失败）与毫秒级耗时；
- 默认保持关闭，关闭状态下完全不占用内存与磁盘 I/O。

### 3. 应用图标管理与首字强调色
- 在「应用」页选中任意发声程序，点击顶部「导入图标…」即可自定义设定个性化头像；
- 当软件未提取到图标或为系统通用图标时，系统会自动采用应用首字生成美观的强调色标识块；
- 在实验设置导出完整配置时，自定义导入的图标会自动内嵌打包，换机导入无缝还原。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.24/SonicRoute-v1.24-Lite-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ⚡ **Lite ARM64**（实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.24/SonicRoute-v1.24-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.24/SonicRoute-v1.24-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 8 桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与迁移指引

- **覆盖升级**：升级前请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或解压覆盖 Legacy 文件夹。
- **数据保留**：已有的应用分流设置、快捷键与自动化规则（保存在 `%LocalAppData%\SonicRoute\`）会自动无损继承。
- **开机自启**：普通版与微软商店版各自使用独立自启项，互不干扰。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [自动化规则配置](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99) · [常见问题解答](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.23

发布日期：2026-10-15 · 上游 release：[v1.23](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.23)

下载量：**47 次**

# 🎧 SonicRoute v1.23 正式版

> **发布时间**：2026-10-15 · **核心主题**：托盘右键音频控制与盲调分离 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.23) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🖱️ **托盘右键音频控制中枢**：右键菜单直接选择系统默认输出设备、调节当前应用音量预设/静音、分配应用输出端点及全部麦克风静音；操作期间锁定前台焦点。
- ⏸️ **托盘滚轮调音支持暂停**：支持在托盘右键菜单随时暂停/恢复托盘区滚轮调音，状态跨重启持久化，防止误触。
- 🎚️ **应用音量与系统音量独立键位**：默认快捷键清晰划分——应用音量 `Ctrl+Alt+滚轮`，系统默认音量 `Ctrl+Alt+Shift+滚轮`。
- ⚙️ **设置交互分层收拢**：输入静音监听与麦克风选项层级优化，按需创建页面与共用菜单控件，关闭后及时停止后台界面读取。
- 🌐 **九语国际化同步**：同步更新 9 种语言界面文案与 README 结构，表述更地道流畅。

---

## 📋 详细演进说明

### 1. 托盘右键全能调度
无需打开主窗口或弹出面板，在托盘右键菜单中即可完成核心音频操作：
- **系统默认输出选择**：一键切换桌面音箱与耳机；
- **当前应用音量档位**：支持 25%、50%、75%、100% 快速赋值与一键静音；
- **前台焦点锁定**：右键菜单呼出时会瞬间固定当前发声应用，避免因鼠标移动到菜单上而误把焦点切给其他进程。

### 2. 托盘区滚轮盲调防误触
在托盘右键菜单中新增「暂停滚轮调节音量」开关。对于习惯在任务栏右下角密集操作其他软件的用户，开启后托盘区域滚轮不再调节音量，且该状态会持久化保存至配置文件中；全局音量快捷键不受影响。

### 3. 应用音量与系统音量快捷键分离
- **前台应用音量**：默认分配为 `Ctrl+Alt+滚轮上/下`；
- **系统主音量**：默认分配为 `Ctrl+Alt+Shift+滚轮上/下`；
- 已有自定义键位的用户自动保留原有设置，也可随时在「快捷键」页面自由修改。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.23/SonicRoute-v1.23-Lite-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ⚡ **Lite ARM64**（实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.23/SonicRoute-v1.23-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.23/SonicRoute-v1.23-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 8 桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与迁移指引

- **覆盖升级**：升级前请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或解压覆盖 Legacy 文件夹。
- **数据保留**：已有的应用分流设置、快捷键与自动化规则（保存在 `%LocalAppData%\SonicRoute\`）会自动无损继承。
- **开机自启**：普通版与微软商店版各自使用独立自启项，互不干扰。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [快捷键设置手册](https://github.com/kunkunkunQoQ/SonicRoute/wiki/03-%E5%BF%AB%E6%8D%B7%E9%94%AE) · [常见问题解答](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.22

发布日期：2026-10-11 · 上游 release：[v1.22](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.22)

下载量：**24 次**

# 🎧 SonicRoute v1.22 正式版

> **发布时间**：2026-10-11 · **核心主题**：开机自启隔离与轻量化加载 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.22) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🔄 **双版本自启彻底隔离**：普通版与商店版分别注册独立自启项，消除窗口激活冲突与系统状态同步差异。
- 📦 **精简依赖与体积优化**：重构商店自启动接口，Lite 单文件程序体积进一步精简缩小。
- ⚡ **自动化页面按需加载**：自动化规则界面采用延迟初始化，首次进入时构建，后续切页无缝复用。
- 🎨 **菜单视觉规范统一**：托盘、自动化与音量预设菜单采用统一样式，移除默认灰色边缘与图标留白。
- 🛠 **短命令复制健壮性提升**：修复“复制执行命令”偶发卡顿，增加后台重试机制与失败友好提示。
- 🌐 **多语言用词微调**：修正 9 种内置语言的用词、语法与标点，使跨语言表述更加自然地道。

---

## 📋 详细演进说明

### 1. 商店版与普通版自启隔离
- 微软商店版依托 Windows `StartupTask` 规范管理后台自启；
- 普通版（Lite 与 Legacy）依托注册表当前用户 Run 项进行自启管理；
- 本次更新将两套逻辑完全解耦，彻底修复此前两版本在同一机器切换时窗口激活混淆与状态判断失效的问题。

### 2. 界面加载与内存控制
- 自动化规则管理页面改用按需加载机制，在用户首次点击进入时才实例化重量级组件，降低常驻启动开销；
- 统一样式菜单，全面移除 Windows 原生 ContextMenu 遗留的多余灰色内边距与图标占位槽，界面更加精致紧凑。

### 3. 命令行交互稳定性
- 针对极端情况下剪贴板占用引发的“复制执行命令”短暂停顿，增加异步后台保护与异常回退提示，杜绝主界面线程受阻塞。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.22/SonicRoute-v1.22-Lite-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ⚡ **Lite ARM64**（实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.22/SonicRoute-v1.22-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.22/SonicRoute-v1.22-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 8 桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与迁移指引

- **覆盖升级**：升级前请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或解压覆盖 Legacy 文件夹。
- **数据保留**：已有的应用分流设置、快捷键与自动化规则（保存在 `%LocalAppData%\SonicRoute\`）会自动无损继承。
- **开机自启**：普通版与微软商店版各自使用独立自启项，互不干扰。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [命令行执行规则](https://github.com/kunkunkunQoQ/SonicRoute/wiki/05-%E5%91%BD%E4%BB%A4%E8%A1%8C%E6%89%A7%E8%A1%8C%E8%A7%84%E5%88%99) · [常见问题解答](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.21

发布日期：2026-10-09 · 上游 release：[v1.21](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.21)

下载量：**16 次**

# 🎧 SonicRoute v1.21 正式版

> **发布时间**：2026-10-09 · **核心主题**：事件驱动架构与 18 种自动化编排 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.21) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- ⚡ **零轮询事件驱动架构**：全面改用 Windows 前台应用切换与音频物理设备系统通知机制；关闭界面时彻底解绑动画与事件引用，实现极低系统闲时开销。
- 🤖 **自动化编排扩充至 18 种操作**：规则卡片直观显示触发条件与动作摘要；支持拖拽排序、搜索筛选、名称留空自动编号；新增「单步失败后停止」与「执行另一条规则」。
- 💻 **命令行 `sr` 深度联动**：支持一键复制规则执行命令并在 PowerShell / CMD 中秒级调用。
- 🎨 **全新设计语言与透明图标**：采用全新透明耳机轮廓托盘图标，随系统任务栏深浅自动适配；统一导航、卡片、Hex/RGB/HSL 色谱选色器与设备名重命名体验。
- 🛡️ **可选后台定时兜底**：实验设置中新增可选的后台定时巡检兜底开关，默认关闭，针对部分丢失 Windows 通知的老旧驱动提供可选保障。

---

## 📋 详细演进说明

### 1. 自动化规则体系全面成熟
- **可视化卡片与交互**：规则列表展示真实名称、操作动作与触发器摘要；支持按名称模糊搜索与类型筛选；拖拽即可自由调整展示排序；
- **容错与链路控制**：支持为每个步骤设置「失败后停止」，执行链路更加可控；执行结果明确标注 Success、Skipped 或 Stopped；
- **规则跨链调用**：新增「执行另一条规则」操作，支持将通用动作模块化复用。

### 2. 界面与主题美学重塑
- **统一视觉组件库**：重构导航栏、设置卡片、开关、数字输入框与下拉菜单，带来现代精细质感；
- **主题强调色系统**：内置色谱选色器，支持 Hex、RGB、HSL 自由输入与实时预览；
- **设备重命名**：支持为音频设备自定义命名，清空即可即时恢复系统默认物理名称。

### 3. 事件驱动与资源释放机制
- 界面关闭后自动解绑非必要的观察者监听，排队未处理的非关键界面刷新自动取消，并将空闲工作集移交操作系统调度；
- 状态更新完全交由系统通知触发，杜绝空闲时的无用周期轮询。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.21/SonicRoute-v1.21-Lite-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ⚡ **Lite ARM64**（实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.21/SonicRoute-v1.21-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.21/SonicRoute-v1.21-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 8 桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与迁移指引

- **覆盖升级**：升级前请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或解压覆盖 Legacy 文件夹。
- **数据保留**：已有的应用分流设置、快捷键与自动化规则（保存在 `%LocalAppData%\SonicRoute\`）会自动无损继承。
- **开机自启**：普通版与微软商店版各自使用独立自启项，互不干扰。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [自动化规则指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/04-%E8%87%AA%E5%8A%A8%E5%8C%96%E8%A7%84%E5%88%99) · [技术实现架构](https://github.com/kunkunkunQoQ/SonicRoute/wiki/07-%E6%8A%80%E6%9C%AF%E5%AE%9E%E7%8E%B0)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.20

发布日期：2026-10-01 · 上游 release：[v1.20](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.20)

下载量：**32 次**

# 🎧 SonicRoute v1.20 正式版

> **发布时间**：2026-10-02 · **核心主题**：自动化编排初登场与极客命令行联动 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.20) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🤖 **自动化编排引擎初登场**：引入可视化规则编排体系，支持 5 组 17 种操作（切换系统/应用端点、相对/绝对音量调节、明确静音、麦克风控制与外部脚本启动）。
- ⚡ **极客命令行客户端 `sr`**：引入本地命名管道 (IPC) 通信机制，在 PowerShell / CMD 中输入 `sr "规则名称"` 即可秒级触发运行实例。
- 📊 **实时电平音频活动指示**：快捷面板新增实时电平采样反馈，发声状态一目了然；主题内支持随时开启或关闭。
- 🪟 **四大多元分发形态确立**：正式形成 Lite x64 单文件、Lite ARM64 实验版、Legacy x64 (免额外运行库) 与 Microsoft Store 四大并行的分发矩阵。
- 🖥 **OSD 浮窗体验进化**：支持关闭音量条、数字左置、强调色与标题深浅适配，合并高频调音动画。

---

## 📋 详细演进说明

### 1. 自动化编排引擎与五组十七种操作
- **系统音频控制**：切换默认播放设备、切换默认录音设备、调整系统音量、相对调整系统音量、系统静音/解除静音；
- **应用定向分流**：切换指定应用播放设备、调整应用音量、相对调整应用音量、指定应用静音/解除静音；
- **麦克风控制**：全局麦克风硬件级静音、解除静音、反转静音状态；
- **外部联动**：启动指定外部程序、执行 PowerShell 脚本、延时等待；
- **编排体验**：支持规则复制、步骤复制、步骤拖动与序号预览。

### 2. 本地命名管道与短命令 `sr`
内置极简的 Windows 命名管道客户端，用户在终端只需键入：
```bash
sr "游戏开黑"
```
无需调出主窗口即可静默触发后台常驻的 SonicRoute 执行既定动作链，无缝衔接 Stream Deck、AutoHotkey 或批处理脚本。

### 3. 实时电平采样与面板改进
- 简洁面板引入非侵入式实时电平反馈，准确感知各应用是否正在推流发声；
- 适配 Windows 深色与浅色模式，自动排除被隐藏或已静音的应用；
- 优化面板滑入动画与默认高度（450px），展开/收拢更加稳固流畅。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主力） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.20/SonicRoute-v1.20-Lite-x64.exe) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| ⚡ **Lite ARM64**（实验） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.20/SonicRoute-v1.20-Lite-arm64.exe) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.20/SonicRoute-v1.20-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ / Windows 11 系统。
> - Lite 版本请确保安装了对应架构的 .NET 8 桌面运行时；Legacy 版本解压后直接运行 `SonicRoute.exe` 即可。
> - 资产完整性 SHA-256 校验和请查看发布附件 `SHA256SUMS.txt`。

---

## 🔄 升级与迁移指引

- **覆盖升级**：升级前请先在任务栏右下角托盘图标右键选择「退出」，然后运行新版 EXE 或解压覆盖 Legacy 文件夹。
- **数据保留**：已有的应用分流设置与快捷键配置会自动迁移至新版本配置目录。
- **开机自启**：普通版与微软商店版各自使用独立自启项，互不干扰。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [命令行执行规则](https://github.com/kunkunkunQoQ/SonicRoute/wiki/05-%E5%91%BD%E4%BB%A4%E8%A1%8C%E6%89%A7%E8%A1%8C%E8%A7%84%E5%88%99) · [常见问题解答](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [提交建议或 Bug 反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.12r

发布日期：2026-09-27 · 上游 release：[v1.12r](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.12r)

下载量：**4 次**

# 🎧 SonicRoute v1.12r 正式版

> **发布时间**：2026-09-27 · **核心主题**：OSD 架构全面重构零闪烁、多屏 DPI 抖动修复与深浅托盘适配 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.12r) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🚀 **OSD 架构重构与内存压降**：重构浮窗绘制管线，杜绝频繁调音时的内存上涨与多屏 DPI 抖动。
- 📐 **OSD 自由拖拽与大小自适应**：支持拖拽定位与长设备名防闪烁排版。
- 🎨 **托盘图标深浅双色自适应**：任务栏深浅切换时自动重绘托盘图标。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12r/SonicRoute-v1.12r-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12r/SonicRoute-v1.12r-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12r/SonicRoute-v1.12r.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12r/SonicRoute-v1.12r.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.19

发布日期：2026-09-21 · 上游 release：[v1.19](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.19)

下载量：**85 次**

# 🎧 SonicRoute v1.19 正式版

> **发布时间**：2026-09-21 · **核心主题**：Legacy .NET Framework 4.8 兼容版首发、ARM64 原生实验支持与自动化启动增强 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.19) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🪟 **.NET Framework 4.8 兼容版（Legacy）首发**：面向 Win10 1903+ / Win11 原生自带的 .NET Framework 4.8，免装 .NET 8 运行库，解压即用。
- 🖥 **Windows ARM64 原生架构实验支持**：推出纯原生 ARM64 实验版，针对高通骁龙 PC 与 Surface Pro 打造，无仿真开销。
- 🎲 **自动化「启动程序」支持随机启动**：启动项列表支持「全部启动」或「随机启动一个」，满足游戏或音乐随机选择场景。
- 📂 **每个启动项独立指定打开方式**：与系统文件关联深度打通，每个启动项可自由指定关联应用、默认程序或自定义路径。
- 📁 **一键直达规则脚本目录**：自动化界面新增「打开脚本文件夹」，直达 `%LocalAppData%\SonicRoute\Automation`。
- 🛠 **启动项状态与文件选择修复**：修复重新加载规则时启动方式可能丢失的问题，优化文件选择器与拖拽追加体验。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 主流 64 位 PC 绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-Lite-x64.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-Lite-x64.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 🛡️ **Legacy x64**（免装运行库） | 公司办公电脑 / 受限机型 | [完整 ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-Legacy-x64.zip) | 系统自带 .NET Framework 4.8（解压即用） |
| ⚡ **Lite ARM64**（实验版） | Surface Pro / 骁龙 PC 原生高效 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-Lite-arm64.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-Lite-arm64.zip) | 需匹配的 ARM64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置 .NET 8 运行时（免单独安装） | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-x64.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.19/SonicRoute-v1.19-x64.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.18

发布日期：2026-09-18 · 上游 release：[v1.18](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.18)

下载量：**34 次**

# 🎧 SonicRoute v1.18 正式版

> **发布时间**：2026-09-18 · **核心主题**：简洁面板固定高度重构、自动化退出与定时触发、规则启用停用状态 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.18) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🧩 **简洁快速面板固定高度重构**：面板高度支持 350~800px 恒定调节，底部操作栏始终锚定，应用列表内部独立滚动，切换应用不晃动。
- 🤖 **自动化触发源扩展**：新增「应用退出触发」与「定时计划触发」（一次/每天/每周），错过时间自动旁路跳过。
- ⏸️ **规则单项启用与禁用**：支持单条规则随时启停，状态点实时展示并跨进程持久化。
- 🔔 **设置页内置检查更新**：作者主页卡片新增手动更新检测，引导前往 Release 下载。
- 🌐 **繁体中文用语精细化**：多语言审查统一繁体中文为「儲存」。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.18/SonicRoute-v1.18-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.18/SonicRoute-v1.18-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.18/SonicRoute-v1.18.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.18/SonicRoute-v1.18.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.17

发布日期：2026-09-17 · 上游 release：[v1.17](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.17)

下载量：**16 次**

# 🎧 SonicRoute v1.17 正式版

> **发布时间**：2026-09-17 · **核心主题**：自动化可视化积木化、拖拽重排动画、OSD 初始化与平滑过渡 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.17) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🧱 **规则操作积木化重构**：操作卡片采用模块化积木设计，随系统主题深浅自适应配色，参数直接内嵌。
- 🔄 **平滑拖拽重排体系**：支持积木拖拽实时换位与滑动物理动画，放宽判定阈值至 35%，调整顺序行云流水。
- 🎚️ **积木滑块滚轮直调**：规则内的音量控制滑块支持鼠标滚轮 ±5 步进微调。
- 🎬 **全界面流体折叠动画**：更多选项与快速面板应用行折叠均加入平滑淡入滑行动画。
- 🎯 **OSD 首次弹出零闪烁**：先在内存计算坐标再执行渲染，消灭启动后首次触发时的中心闪烁。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.17/SonicRoute-v1.17-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.17/SonicRoute-v1.17-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.17/SonicRoute-v1.17.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.17/SonicRoute-v1.17.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.16

发布日期：2026-09-14 · 上游 release：[v1.16](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.16)

下载量：**24 次**

# 🎧 SonicRoute v1.16 正式版

> **发布时间**：2026-09-14 · **核心主题**：极简可视化自动化规则引擎上线、快速面板滑入动效 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.16) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🤖 **首创极简自动化规则体系**：建立「触发条件 + 动作链条」流水线，支持快捷键、应用打开、切换前台等触发模式。
- 🎛️ **跨维度动作支持**：单条规则可顺序执行系统播放/录音切换、音量/静音控制、指定应用路由及外部脚本启动。
- 📂 **外部程序与脚本拖拽追加**：启动项支持直接拖拽 EXE / PowerShell 脚本自动去重录入。
- 🎬 **面板滑入动画过渡**：经典与简洁面板呼出时增加 180ms 缓出物理动画。
- 🛠 **切换操作参数崩溃修复**：修复切换规则参数下拉框偶发的 UI 异常。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.16/SonicRoute-v1.16-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.16/SonicRoute-v1.16-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.16/SonicRoute-v1.16.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.16/SonicRoute-v1.16.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.15

发布日期：2026-09-13 · 上游 release：[v1.15](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.15)

下载量：**19 次**

# 🎧 SonicRoute v1.15 正式版

> **发布时间**：2026-09-13 · **核心主题**：9 语言架构重构与外置语言扩展、屏幕定位与启动选项 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.15) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🌐 **9 语言按需动态加载**：采用独立 JSON 国际化解耦架构，切换语言即时生效无需重启，首创繁中港澳台综合版。
- 📁 **外置自定义语言支持**：支持导出内置语言模板、本地编辑并一键导入；外置语言优先加载。
- 📐 **快速面板屏幕定位算法优化**：合并高频重复定位计算，自适应多显示器 DPI 与工作区变化，杜绝窗口跳动。
- ⚙️ **设置页启动选项独立重组**：开机自启、启动最小化与启动显示面板统一收纳在首栏。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.15/SonicRoute-v1.15-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.15/SonicRoute-v1.15-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.15/SonicRoute-v1.15.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.15/SonicRoute-v1.15.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.14

发布日期：2026-09-12 · 上游 release：[v1.14](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.14)

下载量：**35 次**

# 🎧 SonicRoute v1.14 正式版

> **发布时间**：2026-09-12 · **核心主题**：任务栏与托盘滚轮盲调、音量步进统一、配置清理与备份 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.14) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🖱️ **任务栏与托盘滚轮盲调**：鼠标停留在任务栏右侧或托盘图标直接滚动滚轮，即刻静默微调当前应用音量。
- 🎚️ **全通道音量步进统一**：音量快捷键与滚轮调节步进支持 1%~20% 自由设置。
- 🏷️ **OSD 智能设备与应用别名**：提示信息优先采用用户自定义的友好设备名称与「全部应用」标识。
- 🧹 **配置管理与备份还原**：实验设置新增配置一键备份与清理功能。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.14/SonicRoute-v1.14-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.14/SonicRoute-v1.14-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.14/SonicRoute-v1.14.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.14/SonicRoute-v1.14.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.13

发布日期：2026-09-11 · 上游 release：[v1.13](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.13)

下载量：**15 次**

# 🎧 SonicRoute v1.13 正式版

> **发布时间**：2026-09-11 · **核心主题**：麦克风静音常驻横幅、幽灵音频会话智能过滤、输入设备全量感知 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.13) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🎙️ **麦克风静音常驻 OSD 横幅**：开麦/闭麦状态始终在屏幕边缘一目了然，支持监听系统默认录音设备。
- 👻 **幽灵音频会话自动清洗**：过滤已失效或已关闭但残留在系统中的僵死音频通道。
- 🎛️ **全量物理输入端点枚举**：概览与应用页输入下拉框支持列出系统中所有可用录音硬件。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.13/SonicRoute-v1.13-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.13/SonicRoute-v1.13-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.13/SonicRoute-v1.13.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.13/SonicRoute-v1.13.zip) | Windows 10 2004+ / Windows 11 |
| 🔄 **Microsoft Store** | 商店静默后台自动更新 | [商店安装](https://apps.microsoft.com/detail/9NQZGRTPM1NT) | 适用于 64 位 Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.12

发布日期：2026-09-09 · 上游 release：[v1.12](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.12)

下载量：**14 次**

# 🎧 SonicRoute v1.12 正式版

> **发布时间**：2026-09-09 · **核心主题**：全新 Win11 飞出式简洁快速面板、状态强调色与多语言 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.12) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🪟 **首发 Win11 飞出式简洁快速面板**：极简应用卡片流，每行配备独立电平滑块、静音按钮与设备快速选择。
- 🎨 **主题强调色与自适应托盘图标**：耳机托盘图标随系统深浅色任务栏自动切换，按钮状态采用强调色高亮。
- 🌐 **繁中等 9 语言初版**：全面支持繁体中文在内的国际化体验。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12/SonicRoute-v1.12-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12/SonicRoute-v1.12-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12/SonicRoute-v1.12.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.12/SonicRoute-v1.12.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.11

发布日期：2026-09-05 · 上游 release：[v1.11](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.11)

下载量：**21 次**

# 🎧 SonicRoute v1.11 正式版

> **发布时间**：2026-09-05 · **核心主题**：全局快捷键矩阵升级、多维设备切换与一键还原 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.11) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- ⌨️ **快捷键输入矩阵全面扩充**：支持 F1~F24、单字符键、鼠标多功能侧键（XButton1/2）与滚轮组合，支持 Esc 键清除绑定。
- 🔄 **三层设备切换逻辑成型**：支持当前应用设备循环、系统默认输出/输入切换、所有发声应用一键批量路由。
- ♻️ **一键还原系统默认**：提供快捷键或菜单一键重置所有应用路由，恢复干净的系统默认分流。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.11/SonicRoute-v1.11-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.11/SonicRoute-v1.11-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.11/SonicRoute-v1.11.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.11/SonicRoute-v1.11.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.10

发布日期：2026-09-04 · 上游 release：[v1.10](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.10)

下载量：**26 次**

# 🎧 SonicRoute v1.10 正式版

> **发布时间**：2026-09-04 · **核心主题**：折叠 UI 优化、8 语言翻译补齐、内存换出优化 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.10) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🧹 **内存按需释放机制**：引入 TrimWorkingSet 内存优化策略，关闭 UI 后自动释放非必要内存。
- 🌐 **8 语言本地化补齐**：补齐多语言对照表与界面文案。
- 📑 **设置界面折叠收纳**：高级选项支持折叠与展开，界面更清爽。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.10/SonicRoute-v1.10-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.10/SonicRoute-v1.10-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.10/SonicRoute-v1.10.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.10/SonicRoute-v1.10.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.9

发布日期：2026-08-31 · 上游 release：[v1.0.9](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.9)

下载量：**15 次**

# 🎧 SonicRoute v1.0.9 正式版

> **发布时间**：2026-08-31 · **核心主题**：实验设置一键还原、关闭 UI 内存回收多层修复 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.9) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- ♻️ **实验设置一键还原**：快速将所有实验参数重置为出厂安全值。
- 🧠 **三层内存深度回收**：彻底修复窗口关闭后的未释放引用。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.9/SonicRoute-v1.0.9-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.9/SonicRoute-v1.0.9-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.9/SonicRoute-v1.0.9.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.9/SonicRoute-v1.0.9.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.8

发布日期：2026-08-28 · 上游 release：[v1.0.8](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.8)

下载量：**16 次**

# 🎧 SonicRoute v1.0.8 正式版

> **发布时间**：2026-08-28 · **核心主题**：1080p 高清图标、商店版图标与开机自启修复 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.8) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🖼️ **1080p 超清应用图标**：多分辨率资源包适配高分屏。
- 🔄 **商店版自启动修复**：优化开机自动启动注册。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.8/SonicRoute-v1.0.8-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.8/SonicRoute-v1.0.8-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.8/SonicRoute-v1.0.8.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.8/SonicRoute-v1.0.8.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.7r2

发布日期：2026-08-28 · 上游 release：[v1.0.7r2](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.7r2)

下载量：**20 次**

# 🎧 SonicRoute v1.0.7r2 正式版

> **发布时间**：2026-08-28 · **核心主题**：关闭 UI 内存释放子选项与发布说明乱码修复 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.7r2) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🧹 **快速面板内存释放细分**：提供独立的快速面板 UI 内存释放选项。
- 📝 **发布与字符集校正**：解决 Release 页面中文显示格式。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7r2/SonicRoute-v1.0.7r2-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7r2/SonicRoute-v1.0.7r2-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7r2/SonicRoute-v1.0.7r2.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7r2/SonicRoute-v1.0.7r2.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.7

发布日期：2026-08-28 · 上游 release：[v1.0.7](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.7)

下载量：**19 次**

# 🎧 SonicRoute v1.0.7 正式版

> **发布时间**：2026-08-28 · **核心主题**：实验模式彩蛋解锁、麦克风选项、OSD 自定义位置与折叠开关 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.7) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🧪 **实验模式与彩蛋入口**：连续点击版本号解锁实验设置。
- 🎙️ **独立麦克风控制开关**：按需开启录音设备管理。
- 📐 **OSD 自由拖拽定位**：支持自定义屏幕浮动位置。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7/SonicRoute-v1.0.7-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7/SonicRoute-v1.0.7-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7/SonicRoute-v1.0.7.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.7/SonicRoute-v1.0.7.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.6

发布日期：2026-08-26 · 上游 release：[v1.0.6](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.6)

下载量：**17 次**

# 🎧 SonicRoute v1.0.6 正式版

> **发布时间**：2026-08-26 · **核心主题**：禁用自动切换、快捷键与任务栏解析一致、粉色主题修正 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.6) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🚫 **应用级禁用自动切换**：支持对特定应用锁定路由，不随焦点变动。
- 🎯 **前台判定逻辑校准**：统一快捷键与任务栏的前台进程识别。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.6/SonicRoute-v1.0.6-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.6/SonicRoute-v1.0.6-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.6/SonicRoute-v1.0.6.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.6/SonicRoute-v1.0.6.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.5r4

发布日期：2026-08-26 · 上游 release：[v1.0.5r4](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r4)

下载量：**16 次**

# 🎧 SonicRoute v1.0.5r4 正式版

> **发布时间**：2026-08-26 · **核心主题**：修复快捷键识别错误应用缺陷 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r4) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🎯 **前台进程识别修复**：修复特定窗口句柄下快捷键误判目标进程的问题。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r4/SonicRoute-v1.0.5r4-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r4/SonicRoute-v1.0.5r4-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r4/SonicRoute-v1.0.5r4.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r4/SonicRoute-v1.0.5r4.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.5r3

发布日期：2026-08-26 · 上游 release：[v1.0.5r3](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r3)

下载量：**16 次**

# 🎧 SonicRoute v1.0.5r3 正式版

> **发布时间**：2026-08-26 · **核心主题**：设置页全选按钮交互优化 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r3) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🔘 **设置全选交互改进**：优化设备多选与全选按钮反馈。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r3/SonicRoute-v1.0.5r3-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r3/SonicRoute-v1.0.5r3-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r3/SonicRoute-v1.0.5r3.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r3/SonicRoute-v1.0.5r3.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.4

发布日期：2026-08-26 · 上游 release：[v1.0.4](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.4)

下载量：**16 次**

# 🎧 SonicRoute v1.0.4 正式版

> **发布时间**：2026-08-26 · **核心主题**：应用改名输入即保存、多语言按需加载、主题色彩优化 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.4) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- ✏️ **应用改名即时持久化**：应用自定义名称输入即自动保存生效。
- 🎨 **主题调色精细化**：调优粉色与深浅主题搭配。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.4/SonicRoute-v1.0.4-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.4/SonicRoute-v1.0.4-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.4/SonicRoute-v1.0.4.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.4/SonicRoute-v1.0.4.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.3

发布日期：2026-08-26 · 上游 release：[v1.0.3](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.3)

下载量：**16 次**

# 🎧 SonicRoute v1.0.3 正式版

> **发布时间**：2026-08-26 · **核心主题**：应用自定义名称、最近使用模式、应用排序功能 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.3) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🏷️ **应用自定义名称管理**：支持给任意程序设置易记别名。
- 🕒 **最近使用模式**：自动锁定最近一次发声的应用。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.3/SonicRoute-v1.0.3-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.3/SonicRoute-v1.0.3-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.3/SonicRoute-v1.0.3.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.3/SonicRoute-v1.0.3.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.2

发布日期：2026-08-26 · 上游 release：[v1.0.2](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.2)

下载量：**15 次**

# 🎧 SonicRoute v1.0.2 正式版

> **发布时间**：2026-08-26 · **核心主题**：多语言初版上线、全局麦克风总闸静音、快捷键改键优化 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.2) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🎙️ **全局麦克风总闸静音**：设备级静音所有录音端点。
- 🌐 **内置 8 语言支持**：初版多语言本地化体系落地。
- ⌨️ **录制与绑定优化**：快捷键录制即刻保存。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.2/SonicRoute-v1.0.2-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.2/SonicRoute-v1.0.2-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.2/SonicRoute-v1.0.2.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---

## v1.0.5r2

发布日期：2026-08-26 · 上游 release：[v1.0.5r2](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r2)

下载量：**16 次**

# 🎧 SonicRoute v1.0.5r2 正式版

> **发布时间**：2026-08-26 · **核心主题**：修复全选按钮打勾符号在部分字体的显示 · [📥 资产下载](https://github.com/kunkunkunQoQ/SonicRoute/releases/tag/v1.0.5r2) · [📖 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

---

## ✨ 核心更新亮点

- 🔤 **字符集与字体图标修复**：修复特殊字符在不同系统字体下的回退呈现。

---

## 🚀 资产下载矩阵

| 发行形态 | 推荐目标人群 | 下载链接 | 运行环境要求 |
|---|---|---|---|
| ⭐ **Lite x64**（推荐主流） | 极简轻量绿色单文件 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r2/SonicRoute-v1.0.5r2-Lite.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r2/SonicRoute-v1.0.5r2-Lite.zip) | 需匹配的 x64 [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) |
| 📦 **自包含完整版 x64** | 内置运行库，免额外配置 | [单个 EXE](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r2/SonicRoute-v1.0.5r2.exe) · [ZIP](https://github.com/kunkunkunQoQ/SonicRoute/releases/download/v1.0.5r2/SonicRoute-v1.0.5r2.zip) | Windows 10 2004+ / Windows 11 |

> [!NOTE]
> - 支持 Windows 10 2004+ (Build 19041+) 及 Windows 11 系统。
> - Lite 绿色版体积小巧，解压或双击即用。

---

## 🔄 升级与数据保留指引

- **手动升级**：请先在右下角系统托盘右键退出当前运行的旧版 SonicRoute，下载新版解压/覆盖启动即可。
- **数据与配置 100% 完整保留**：软件的所有用户设置、规则配置与快捷键均保存在 `%LocalAppData%\SonicRoute\`，跨版本升级绝不丢失任何数据。

---

## 📚 相关链接

- [Wiki 使用指南](https://github.com/kunkunkunQoQ/SonicRoute/wiki/01-%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97) · [常见问题排障](https://github.com/kunkunkunQoQ/SonicRoute/wiki/06-%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)
- [📚 完整版本历史](https://github.com/kunkunkunQoQ/SonicRoute/wiki/09-%E7%89%88%E6%9C%AC%E5%8E%86%E5%8F%B2) · [🐛 提交建议与问题反馈](https://github.com/kunkunkunQoQ/SonicRoute/issues/new/choose) · [💖 在爱发电支持我们](https://afdian.com/a/koukou021)

> [⬆ 返回版本总览](#-版本总览)

---
