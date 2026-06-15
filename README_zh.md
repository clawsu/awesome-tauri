<!--lint disable awesome-heading awesome-toc awesome-github double-link -->

<div align="center">
<h1>Awesome Tauri（精选 Tauri 资源）</h1>

Tauri 生态系统与社区精选资源合集。

<br />

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

</div>

## 目录

- [入门](#入门)
  - [指南与教程](#指南与教程)
  - [模板](#模板)
- [开发](#开发)
  - [插件](#插件)
  - [集成](#集成)
  - [文章](#文章)
- [应用程序](#应用程序)
  - [音频与视频](#音频与视频)
  - [ChatGPT 客户端](#chatgpt-客户端)
  - [数据](#数据)
  - [开发工具](#开发工具)
  - [电子书阅读器](#电子书阅读器)
  - [邮件与订阅](#邮件与订阅)
  - [文件管理](#文件管理)
  - [金融](#金融)
  - [游戏](#游戏)
  - [信息查询](#信息查询)
  - [学习](#学习)
  - [网络](#网络)
  - [办公与写作](#办公与写作)
  - [生产力](#生产力)
  - [搜索](#搜索)
  - [安全](#安全)
  - [社交媒体](#社交媒体)
  - [实用工具](#实用工具)

## 入门

### 指南与教程

- [Introduction](https://v2.tauri.app/start/) ![officially maintained] - Tauri 官方介绍。
- [Getting Started](https://v2.tauri.app/start/prerequisites/) ![officially maintained] - Tauri 官方入门文档。
- [create-tauri-app](https://github.com/tauri-apps/create-tauri-app) ![officially maintained] - 快速搭建 Tauri 应用脚手架。
- [Auto-Updates with Tauri v2](https://docs.crabnebula.dev/guides/auto-updates-tauri) - 使用 Tauri 与 CrabNebula Cloud 配置自动更新。
- [Create Tauri App with React](https://www.youtube.com/watch?v=zawhqLA7N9Y&ab_channel=chrisbiscardi) ![youtube] - Chris Biscardi 演示如何轻松地将 Rust crate 与 JS 模块连接并相互通信。
- [Publish to Apple's App Store](https://thinkgo.io/post/2023/02/publish_tauri_to_apples_app_store/) - 详细介绍将 Mac 应用发布到 App Store 所需的全部步骤。包含示例 bash 脚本。
- [Tauri & ReactJS - Creating Modern Desktop Apps](https://youtube.com/playlist?list=PLmWYh0f8jKSjt9VC5sq2T3mFETasG2p2L) ![youtube] - 使用 Tauri 创建现代桌面应用程序。

### 模板

- [angular-tauri](https://github.com/maximegris/angular-tauri) - Angular + TypeScript + SASS，支持热重载。
- [create-tauri-react](https://github.com/MrLightful/create-tauri-react) - 架构良好的 Vite + React + Tailwind CSS 模板。
- [nuxtor](https://github.com/NicolaSpadari/nuxtor) - Nuxt 4 + Tauri 2 + TailwindCSS v4，用于构建桌面应用的入门模板。
- [rust-full-stack-with-authentication-template](https://github.com/sollambert/rust-full-stack-with-auth-template) - Yew + Tailwind CSS + Tauri + Axum + Sqlx，内置身份验证的全栈应用入门模板。
- [tauri-angular-template](https://github.com/charlesxsh/tauri-angular-boilerplate) - Angular 模板。
- [tauri-astro-template](https://github.com/HuakunShen/tauri-astro-template) - Astro 模板。
- [tauri-bishop-template](https://github.com/RoseBlume/Bishop-Tauri-Template) - 为高中生设计的极简原生模板。
- [tauri-clojurescript-template](https://github.com/rome-user/tauri-clojurescript-template) - 基于 Shadow CLJS 和 React 的极简 ClojureScript 模板。
- [tauri-deno-starter](https://github.com/marc2332/tauri-deno-starter) - 使用 esbuild + Deno 的 React 模板。
- [tauri-fastapi-full-stack-template](https://github.com/fudanglp/tauri-fastapi-full-stack-template) ![v2] - 全栈模板：FastAPI（Python）后端、React + TypeScript 前端、SQLite/SQLModel、TanStack Router、Tailwind CSS、shadcn/ui。Sidecar 架构，配合 PyInstaller 打包。
- [tauri-leptos-template](https://gitlab.com/cristofa/tauri-leptos-template) - Leptos 模板。
- [tauri-leptos-ssr](https://github.com/codeitlikemiley/tauri-leptos-ssr) - Leptos SSR 模板，体积更小、启动更快、桌面端用户体验更好。
- [tauri-nextjs-template](https://github.com/kvnxiao/tauri-nextjs-template) - Next.js（SSG）模板，预配置 TailwindCSS、自定义 lint 规则和 GitHub Actions。
- [tauri-nuxt-template](https://github.com/HuakunShen/tauri-nuxt-template) - Nuxt 3 模板。
- [tauri-preact-rsbuild-template](https://github.com/Alfredoes234/tauri-preact-rsbuild-template) - 使用 rsbuild 而非 vite 的 Preact 模板。
- [tauri-react-mantine-vite-template](https://github.com/elibroftw/modern-desktop-app-template) - React + Mantine 模板，自带 Windows 自定义标题栏、自动发布与自动更新等功能。
- [tauri-react-parcel-template](https://github.com/henrhie/tauri-react-parcel-template) - 以 Parcel 为构建工具的 React 模板，支持 TypeScript 和热模块替换。
- [tauri-rescript-template](https://github.com/JonasKruckenberg/tauri-rescript-template) - Tauri + ReScript + React 模板。
- [tauri-solid-ts-tailwind-vite-template](https://github.com/AR10Dev/tauri-solid-ts-tailwind-vite) - 预配置 Vite、TypeScript、Tailwind CSS、ESLint 和 Prettier 的 SolidJS 模板。
- [tauri-svelte-template](https://github.com/probablykasper/tauri-svelte-template) - Svelte 模板，支持跨平台 GitHub Action 构建，集成 Vite、TypeScript、Svelte Preprocess、热模块替换、ESLint 和 Prettier。
- [tauri-sveltekit-template](https://github.com/deid84/tauri-sveltekit-admin-template) - SvelteKit Admin 模板，支持跨平台 GitHub Action 构建，集成 Vite、TypeScript、Svelte Preprocess、热模块替换、ESLint 和 Prettier。
- [tauri-sycamore-template](https://github.com/JonasKruckenberg/tauri-sycamore-template) - Tauri + Sycamore 模板。
- [tauri-tanstack-start-react-template](https://github.com/kvnxiao/tauri-tanstack-start-react-template) ![v2] - React + TanStack Start + Vite 模板，预配置 TailwindCSS、自定义 lint 规则和 GitHub Actions。
- [tauri-template](https://github.com/dannysmith/tauri-template) - 生产就绪模板，包含 React、TypeScript、shadcn/ui、Tailwind、TanStack Query、Zustand 和 UI 样板。对 Claude Code 友好。
- [tauri-vue-template](https://github.com/Uninen/tauri-vue-template) - Vue 模板，集成 TypeScript、Vite + HMR、Vitest、Tailwind CSS、ESLint 和 GitHub Actions。
- [tauri-vue-template-2](https://github.com/skymen/tauri-vue-template) - 另一个 Vue 模板，使用 JavaScript、Vite、Pinia、Vue Router 和 GitHub Actions。
- [tauri-yew-example](https://bitbucket.org/ftegtmeyer/tauri-yew-stopwatch/) - 使用 Yew + Tauri 命令与事件实现的简单秒表。
- [taurics](https://github.com/exphert/TauriCS) - 带有 C# 后端的 Tauri V2 模板。
- [tauronic](https://github.com/rgilsimoes/Tauronic/) - 使用 React 风格 Ionic 组件的 Tauri 混合应用模板。

## 开发

### 插件

- [Official Plugins](https://github.com/tauri-apps/plugins-workspace) ![officially maintained] - 包含 Tauri 团队维护的所有插件，例如 NFC、日志、通知等。
- [window-vibrancy](https://github.com/tauri-apps/window-vibrancy) ![officially maintained] - 让你的窗口呈现生动视觉效果（仅 v1，v2 已集成到 Tauri 核心）。
- [window-shadows](https://github.com/tauri-apps/window-shadows) ![officially maintained] - 在 Tauri 窗口中添加原生阴影（仅 v1，v2 已集成到 Tauri 核心）。
- [sentry-tauri](https://github.com/timfish/sentry-tauri) - 捕获 JavaScript 错误、Rust panic 以及原生崩溃 minidump 并上报到 Sentry。
- [tauri-awesome-rpc](https://github.com/ahkohd/tauri-awesome-rpc) - 基于 WebSocket 的自定义 invoke 系统。
- [tauri-nspanel](https://github.com/ahkohd/tauri-nspanel) - 将窗口转换为面板。
- [tauri-nspopover-plugin](https://github.com/freethinkel/tauri-nspopover-plugin) - 用于 macOS 状态栏的原生 NSPopover 视图。
- [tauri-plugin-android-battery-optimization](https://github.com/NeoHuncho/tauri-plugin-android-battery-optimization) - 在 Android 上检查并请求电池优化豁免。
- [tauri-plugin-android-fs](https://github.com/aiueo13/tauri-plugin-android-fs) ![v2] - 在 Android 上访问文件系统。
- [tauri-plugin-aptabase](https://github.com/aptabase/tauri-plugin-aptabase) - 面向桌面和移动应用的隐私优先、轻量级分析。
- [tauri-plugin-auth](https://github.com/inKibra/tauri-plugins/tree/main/packages/tauri-plugin-auth) - iOS 端鉴权插件，使用 ASWebAuthenticationSession 进行身份验证，并可访问钥匙串。
- [tauri-plugin-blec](https://github.com/MnlPhlp/tauri-plugin-blec) - 基于 `btleplug` 的跨平台低功耗蓝牙客户端。
- [tauri-plugin-cache](https://github.com/Taiizor/tauri-plugin-cache) - 高级磁盘缓存方案，支持内存层、TTL 管理、压缩，跨桌面与移动平台兼容。
- [tauri-plugin-clipboard](https://github.com/CrossCopy/tauri-plugin-clipboard) - 用于读写剪贴板文本/图片/HTML/RTF/文件以及监听剪贴板更新的剪贴板插件。
- [tauri-plugin-context-menu](https://github.com/c2r0b/tauri-plugin-context-menu) - 原生右键菜单。
- [tauri-plugin-desktop-underlay](https://github.com/Charlie-XIAO/tauri-plugin-desktop-underlay) - 将窗口附加到桌面，位于图标下方、壁纸上方的层级。
- [tauri-plugin-device-info](https://github.com/edisdev/tauri-plugin-device-info) ![v2] - 跨桌面与移动平台访问电池、网络、存储、显示器、操作系统等全面的设备信息。
- [tauri-plugin-dragout](https://github.com/alexqqqqqq777/tauri-plugin-dragout) - macOS 原生拖出（file promise）支持。
- [tauri-plugin-drpc](https://github.com/smokingplaya/tauri-plugin-drpc) - Discord RPC 支持。
- [tauri-plugin-fs-pro](https://github.com/ayangweb/tauri-plugin-fs-pro) - 扩展了更多文件和目录操作方法。
- [tauri-plugin-graphql](https://github.com/JonasKruckenberg/tauri-plugin-graphql) - 使用 GraphQL 实现类型安全的 Tauri IPC。
- [tauri-plugin-iap](https://github.com/Choochmeque/tauri-plugin-iap) - 在 Android、macOS、iOS 和 Windows 上启用完整应用内购流程的插件。
- [tauri-plugin-iap](https://github.com/inKibra/tauri-plugins/tree/main/packages/tauri-plugin-iap) - iOS 端应用内购插件，支持产品获取、购买和恢复。
- [tauri-plugin-in-app-review](https://github.com/Gbyte-Group/tauri-plugin-in-app-review) ![v2] - 使用各平台原生 API 弹出应用内评分提示。
- [tauri-plugin-ios-photos](https://github.com/Gbyte-Group/tauri-plugin-ios-photos) ![v2] - 通过原生 API 管理 iOS 照片相册和资源。
- [tauri-plugin-js](https://github.com/HuakunShen/tauri-plugin-js) ![v2] - 为你的应用提供类似 Electron 的 JS 后端，由 `kkrpc` 提供类型安全 RPC，支持 Bun、Node.js 和 Deno。
- [tauri-plugin-keep-screen-on](https://gitlab.com/cristofa/tauri-plugin-keep-screen-on) - 在 Android 和 iOS 上禁用屏幕休眠。
- [tauri-plugin-macos-permissions](https://github.com/ayangweb/tauri-plugin-macos-permissions) - 支持 macOS 系统权限的检查与申请。
- [tauri-plugin-mobile-sharetarget](https://github.com/IT-ess/tauri-plugin-mobile-sharetarget) ![v2] - 使用 FIFO 队列处理移动端的 Share Intent。
- [tauri-plugin-mqtt](https://github.com/kuyoonjo/tauri-plugin-mqtt) - MQTT 客户端支持。
- [tauri-plugin-network](https://github.com/HuakunShen/tauri-plugin-network) - 用于读取网络信息、扫描网络的工具。
- [tauri-plugin-nosleep](https://github.com/pevers/tauri-plugin-nosleep/) - 阻止操作系统的节能功能。
- [tauri-plugin-ota](https://github.com/inKibra/tauri-plugins/tree/main/packages/tauri-plugin-ota) - 面向应用的 OTA 插件，仅需通过清单文件持续下发新的 JavaScript 代码。
- [tauri-plugin-pinia](https://github.com/ferreira-tb/tauri-store/tree/main/packages/plugin-pinia) - 为 Vue 提供持久化的 Pinia 存储。
- [tauri-plugin-prevent-default](https://github.com/ferreira-tb/tauri-plugin-prevent-default) - 禁用默认的浏览器快捷键。
- [tauri-plugin-python](https://github.com/marcomq/tauri-plugin-python/) - 在后端使用 Python。
- [tauri-plugin-screenshots](https://github.com/ayangweb/tauri-plugin-screenshots) - 获取窗口和显示器的截图。
- [tauri-plugin-serialport](https://github.com/deid84/tauri-plugin-serialport) - 跨平台串口通信工具。
- [tauri-plugin-serialplugin](https://github.com/s00d/tauri-plugin-serialplugin) - 面向 Tauri 2 的跨平台串口通信工具。
- [tauri-plugin-sharesheet](https://github.com/buildyourwebapp/tauri-plugin-sharesheet) - 通过 Android Sharesheet 或 iOS Share Pane 将内容分享到其他应用。
- [tauri-plugin-svelte](https://github.com/ferreira-tb/tauri-store/tree/main/packages/plugin-svelte) - 提供持久化的 Svelte stores。
- [tauri-plugin-system-info](https://github.com/HuakunShen/tauri-plugin-system-info) - 详细的系统信息。
- [tauri-plugin-tcp](https://github.com/kuyoonjo/tauri-plugin-tcp) - TCP 套接字支持。
- [tauri-plugin-theme](https://github.com/wyhaya/tauri-plugin-theme) - 动态切换 Tauri 应用主题。
- [tauri-plugin-thermal-printer](https://github.com/luis3132/tauri-plugin-thermal-printer) ![v2] - 增加对热敏打印机的支持。
- [tauri-plugin-tracing](https://github.com/fltsci/tauri-plugin-tracing) - 使用 tracing crate 的结构化日志，支持 JS → Rust 日志桥接、文件滚动和火焰图分析。
- [tauri-plugin-udp](https://github.com/kuyoonjo/tauri-plugin-udp) - UDP 套接字支持。
- [tauri-plugin-velesdb](https://github.com/cyberlife-coder/VelesDB) - 原生向量数据库插件。70µs 语义检索，召回率 ≥95%，BM25 + 向量混合检索，离线优先，完整生态集成等。
- [tauri-plugin-view](https://github.com/ecmel/tauri-plugin-view) - 在移动端查看和分享文件。
- [tauri-remote-ui](https://github.com/DraviaVemal/tauri-remote-ui) - 将 Web 应用包作为网页提供，便于测试和开发。
- [taurpc](https://github.com/MatsDK/TauRPC) - 针对 Tauri 命令和事件的类型安全 IPC 包装器。

### 集成

- [Astrodon](https://github.com/astrodon/astrodon) - 使用 Deno 构建 Tauri 桌面应用。
- [axios-tauri-adapter](https://git.kaki87.net/KaKi87/axios-tauri-adapter) - 面向 `@tauri-apps/api/http` 模块的 `axios` 适配器。
- [axios-tauri-api-adapter](https://github.com/persiliao/axios-tauri-api-adapter) - 简化在 Tauri 中使用 Axios 的方式，`axios` 适配器适用于 `@tauri-apps/api/http` 模块。
- [Deno in Tauri](https://github.com/typed-sigterm/deno-in-tauri) - 在 Tauri 应用中使用 Deno Core 引擎运行 JS/TS 代码。
- [faynosync-update-server](https://github.com/ku9nov/faynoSync) - 自托管的动态更新服务器，提供统计功能，支持 Tauri 等平台。特性灵活，可实现无缝的应用更新与洞察。
- [kkrpc](https://github.com/kunkunsh/kkrpc) - 在 Tauri 应用与 node/deno/bun 进程之间进行无缝的 RPC 通信，体验类似 Electron。
- [ngx-tauri](https://codeberg.org/crapsilon/ngx-tauri) - 围绕 Tauri 模块函数封装的轻量库，便于与 Angular 集成。
- [svelte-tauri-filedrop](https://github.com/probablykasper/svelte-tauri-filedrop) - 面向 Svelte 的文件拖放处理组件。
- [Tauri Specta](https://github.com/oscartbeaumont/tauri-specta) - 完全类型安全的 Tauri 命令。
- [tauri-htmx-extension](https://github.com/ChristianPavilonis/tauri-htmx-extension) - 在 Tauri 中使用 htmx 的扩展。
- [tauri-macos-menubar-app-example](https://github.com/ahkohd/tauri-macos-menubar-app-example) - macOS 菜单栏应用项目示例。
- [tauri-macos-spotlight-example](https://github.com/ahkohd/tauri-macos-spotlight-example) - macOS Spotlight 应用项目示例。
- [tauri-mcp-server](https://github.com/hypothesi/mcp-server-tauri) ![v2] - 用于快速开发和调试的 MCP 服务器和插件。
- [tauri-update-cloudflare](https://github.com/KilleenCode/tauri-update-cloudflare) - 一键将 Tauri 更新服务器部署到 Cloudflare。
- [tauri-update-server](https://git.kaki87.net/KaKi87/tauri-update-server) - 自动将 Tauri 更新器与 Git 仓库发布对接。
- [vite-plugin-tauri](https://github.com/amrbashir/vite-plugin-tauri) - 在 Vite 项目中集成 Tauri，构建跨平台应用。

### 文章

- [Getting Started Using Tauri Mobile](https://medium.com/p/6f90de5b098) ![paid] - Ed Rutherford 阐述如何使用 Tauri 创建移动应用。
- [How to use local SQLite database with Tauri and Rust](https://blog.moonguard.dev/how-to-use-local-sqlite-database-with-tauri) - 介绍如何在 Tauri 和 Rust 中配置与使用 SQLite 数据库。
- [Managing State in Desktop Applications with Rust and Tauri](https://blog.moonguard.dev/manage-state-with-tauri) - 介绍如何在 Tauri 应用中全局共享和管理任意类型的状态。
- [Setting up Actix Web in a Tauri App](https://blog.moonguard.dev/setting-up-actix-in-tauri) - 介绍如何在 Tauri 中使用 Actix Web 设置 HTTP 服务器。
- [Tauri's async process](https://rfdonnelly.github.io/posts/tauri-async-rust-process/) - Rob Donnelly 深入探讨 Tauri 的异步机制。

## 应用程序

### 音频与视频

- [Ascapes Mixer](https://github.com/ilyaly/ascapes-mixer) - 面向 TTRPG 跑团场景的混音器，包含音乐、环境音和音效三个独立播放器。
- [Cap](https://github.com/CapSoftware/cap) - 开源的 Loom 替代品，美观且易于分享的屏幕录制工具。
- [Cardo](https://github.com/n0vella/cardo) - 集成订阅搜索与管理的播客播放器。
- [Compresso](https://github.com/codeforreal1/compressO) - 基于 FFmpeg 的跨平台视频压缩应用。
- [Cosmos](https://meetcosmos.com/) ![closed source] - 通过描述场景搜索你的媒体库。使用自然语言在本地浏览 TB 级素材，支持反向图片搜索和音频转写。
- [Curses](https://github.com/mmpneo/curses) - 适用于 OBS、VRChat、Twitch 聊天等场景的语音转文字与文字转语音字幕工具。
- [Douyin Downloader](https://github.com/lzdyes/douyin-downloader) - 跨平台抖音视频下载器。
- [Feiyu Player](https://github.com/idootop/feiyu-player) - 美观且功能强大的跨平台在线视频播放器。
- [Global Hotkey Spotify](https://github.com/Sid-V/global_hotkey_spotify) ![v2] - 通过自定义全局快捷键控制 Spotify 播放，无需媒体键。
- [Hopp](https://github.com/gethopp/hopp) ![v2] - 开源远程结对编程应用。
- [Hypetrigger](https://hypetrigger.io/) ![closed source] - 使用 FFMPEG + Tensorflow 在 GPU 上检测视频高光片段。
- [Char](https://github.com/fastrepl/char) - 面向会议的 AI 记事本，灵活的 AI 技术栈与本地化存储。
- [Jellyfin Vue](https://github.com/jellyfin/jellyfin-vue) - 基于 Vue.js 和 Tauri 的 Jellyfin 服务器 GUI 客户端。
- [Lofi Engine](https://github.com/meel-hd/lofi-engine) - 在本地随时生成 Lo-Fi 音乐。
- [mediarepo](https://github.com/Trivernis/mediarepo) - 基于标签的媒体管理应用。
- [Mr Tagger](https://github.com/probablykasper/mr-tagger) - 音乐文件标签编辑应用。
- [Musicat](https://github.com/basharovV/musicat) - 简洁优雅的离线桌面音乐播放器与标签编辑器。
- [NeoDLP](https://github.com/neosubhamoy/neodlp) ![v2] - 基于 `yt-dlp` 的现代音视频下载器，支持浏览器集成。
- [PunyTunes](https://github.com/mjoblin/punytunes) ![v1] - 通过系统托盘控制 StreamMagic 音乐流媒体播放器。
- [Screenpipe](https://github.com/screenpipe/screenpipe) - 7×24 小时本地化 AI 屏幕与麦克风录制。可基于完整上下文构建 AI 应用，兼容 Ollama。
- [SilentKeys](https://github.com/gptguy/silentkeys) ![v2] - 隐私优先的实时听写应用，基于 Tauri 构建，由 `Parakeet ASR`、`Silero-VAD` 和本地推理（ORT）驱动。
- [ToneTempo](https://tonetempo.com) ![closed source] ![paid] - 配合自动混音音乐和 AI 健身教练进行锻炼与跑步。
- [Voxly](https://github.com/ibrahimshadev/dikt) ![v2] - 具备 AI 模式的语音听写应用，可在粘贴到任意应用前先优化口述文本。
- [yt-dlp GUI](https://github.com/gaeljacquin/yt-dlp-gui) - 跨平台 GUI 客户端，封装 `yt-dlp` 命令行音视频下载器。

### ChatGPT 客户端

- [ChatGPT](https://github.com/lencx/ChatGPT) - 跨平台 ChatGPT 桌面应用。
- [ChatGPT-Desktop](https://github.com/Synaptrix/ChatGPT-Desktop) - 跨平台生产力 ChatGPT 助手启动器。
- [Jan](https://github.com/menloresearch/jan) ![v2] - 开源 ChatGPT 替代方案，100% 在你的电脑上离线运行。
- [Kaas](https://github.com/0xfrankz/Kaas) - 跨平台桌面 LLM 客户端，兼容 OpenAI ChatGPT、Anthropic Claude、Microsoft Azure 等，注重隐私与安全。
- [Nexo](https://github.com/Nexo-Agent/nexo) - 一体化工作空间 AI。
- [Orion](https://github.com/taecontrol/orion) - 跨平台应用，可使用 ChatGPT 创建多个具备特定目标的 AI 助手。
- [Oxide-Lab](https://github.com/FerrisMind/oxide-lab) ![v2] - 本地化 LLM 聊天应用，使用 `candle` 与 Rust 后端实现注重隐私的 AI 推理。
- [QuickGPT](https://github.com/dubisdev/quickgpt) - 轻量级 Windows AI 助手。
- [Yack](https://github.com/rajatkulkarni95/yack) - 类似 Spotlight 的应用，用于对接 GPT API。

### 数据

- [Annimate](https://github.com/matthias-stemmler/annimate) - 便捷导出 ANNIS 语言学语料库的查询结果。
- [BS Redis Desktop Client](https://github.com/fuyoo/bs-redis-desktop-client) - 最令人惊喜的 Redis 桌面客户端。
- [Dataflare](https://dataflare.app) ![closed source] ![paid] - 简洁优雅的数据库管理工具。
- [DocKit](https://github.com/geek-fun/dockit) - 面向 Elasticsearch、OpenSearch 等 NoSQL 数据库的 GUI 客户端。
- [Duckling](https://github.com/l1xnan/duckling) - 轻量快速的 csv/parquet 文件和数据库查看器，支持 DuckDB、SQLite、PostgreSQL、MySQL、Clickhouse 等。
- [Elasticvue](https://elasticvue.com/) - 免费开源的 Elasticsearch GUI。
- [Noir](https://noirdb.dev) - 键盘驱动的数据库管理客户端。
- [pgMagic🪄](https://pgmagic.app/?ref=awesometauri) ![closed source] ![paid] - 通过 SQL 或自然语言与 Postgres 对话的 GUI 客户端。
- [qsv pro](https://qsvpro.dathere.com) ![closed source] ![paid] - 在交互式数据表中浏览 CSV 等表格数据，自动生成元数据，并提供基于 `qsv` CLI 的节点编辑器。
- [Rclone UI](https://rcloneui.com) - 面向 **`rclone`** 与 S3 的跨平台桌面 GUI。
- [RedisME](https://github.com/hepengju/redis-me) ![v2] - 基于 Tauri 的 Redis 桌面管理工具。
- [Seaquel](https://seaquel.app/) ![v2] - 带有交互式可视化查询构建器的 SQL GUI。
- [SmoothCSV](https://smoothcsv.com/) ![closed source] - 强大且直观的 CSV 编辑工具，提供类电子表格界面。

### 开发工具

- [AHQ Store](https://github.com/ahqsoftwares/tauri-ahq-store) - 在 Windows 专有的 AHQ Store 中发布、更新和安装应用。
- [AppCenter Companion](https://github.com/zenoxs/tauri-appcenter-companion) - 重新组织、构建并跟踪你的 `VS App Center` 应用。
- [AppHub](https://github.com/francesco-gaglione/AppHub) - 通过直观的 Linux 桌面界面简化 .appImage 包的安装、管理和卸载。
- [Aptakube](https://aptakube.com/) ![closed source] - 多集群 Kubernetes UI。
- [Beadbox](https://beadbox.app) ![closed source] - 实时可视化仪表盘，用于监控 AI 智能体的任务协作、依赖与交接。
- [Brew Services Manage](https://github.com/persiliao/brew-services-manage)![closed source] - 用于管理 Homebrew 服务的 macOS 菜单栏应用。
- [claws](https://clawsapp.com/) ![closed source] - AWS CLI 的可视化界面。
- [CrabNebula DevTools](https://crabnebula.dev/devtools) - 帮助你理解应用的可视化工具，通过便捷的调试与剖析优化开发流程。
- [CrabNebula DevTools Premium](https://crabnebula.dev/devtools) ![closed source] ![paid] - 通过便捷的调试与剖析优化开发流程，让你像调试 JavaScript 一样调试应用的 Rust 部分。
- [DevBox](https://www.dev-box.app/) ![closed source] - 集成多种实用开发者工具：生成器、查看器、转换器等。
- [DevClean](https://github.com/HuakunShen/devclean) - 轻松清理开发环境。
- [DevTools-X](https://github.com/fosslife/devtools-x) - 30+ 跨平台开发工具合集。
- [Docker DB Manager](https://github.com/AbianS/docker-db-manager) ![v2] - 用于管理 Docker 数据库容器的桌面应用，提供可视化界面、数据持久化和一键连接串。
- [Dropcode](https://github.com/egoist/dropcode) - 简洁轻量的代码片段管理工具。
- [Echoo](https://github.com/zsmatrix62/echoo-app) - 适用于 macOS 与 Windows 开发者的在线/离线实用工具。
- [GitButler](https://gitbutler.com) - 一种全新的源代码管理系统。
- [Github Security Alerts](https://github.com/stephanebouget/github-security-alerts) ![v2] - 实时监控 GitHub 仓库的安全漏洞。
- [GitLight](https://github.com/colinlienard/gitlight) - 在桌面端接收 GitHub 和 GitLab 通知。
- [JET Pilot](https://www.jet-pilot.app) - 专注简洁、高速与美观的 Kubernetes 桌面客户端。
- [Hoppscotch](https://hoppscotch.com/download) ![closed source] - 数百万开发者信赖的 API 构建、测试与分享工具。
- [Keadex Mina](https://github.com/keadex/keadex) - 开源无服务器 IDE，用于轻松编写与组织大规模 C4 模型图。
- [Keyring Demo](https://github.com/open-source-cooperative/keyring-rs/wiki/Keyring) ![v2] - 面向 Rust `keyring` 生态的 GUI。
- [KFtray](https://github.com/hcavarsan/kftray) - 在托盘运行的 Kubernetes 端口转发管理应用。
- [Kunobi](https://kunobi.ninja) ![closed source] - 在桌面端进行 Rust Kubernetes 管理，内置 MCP 服务器。
- [Kubeli](https://github.com/atilladeniz/Kubeli) ![v2] - Kubernetes 管理工具，具备资源可视化、多集群支持、AI 聊天与 MCP 服务器。
- [PraccJS](https://github.com/alyalin/PraccJS) - 通过实时代码执行练习 JavaScript。
- [PromptLab](https://github.com/haideralsh/prompt-lab) ![v2] - 开源、跨平台桌面应用，用于为大语言模型构建并提供代码相关上下文。
- [nda](https://github.com/kuyoonjo/nda) - 网络调试助手，支持 UDP、TCP、Websocket、SocketIO、MQTT。
- [Ngroker](https://ngroker.com) ![closed source] ![paid] - 🆖ngrok 的 GUI 客户端。
- [Soda](https://github.com/Web3-Builders-Alliance/soda) - 通过 IDL 生成源代码。
- [Pake](https://github.com/tw93/Pake) - 使用 Rust 一键将任意网页打包为桌面应用。
- [Rivet](https://github.com/Ironclad/rivet) - 用于创建 AI 功能和智能体的可视化编程环境。
- [TableX](https://tablex-tan.vercel.app/) - 面向现代开发者的表格查看器。
- [TangleGuard](https://tangleguard.com) ![closed source] - 软件架构监控工具。
- [Tauri Mobile Test](https://github.com/dedSyn4ps3/tauri-mobile-test) - 创建并构建跨平台移动应用。
- [Testfully](https://testfully.io/) ![closed source] ![paid] - 离线 API 客户端与测试工具。
- [verbcode](https://github.com/Verbcode/verbcode-release) ![closed source] - 简化你的本地化工作流。
- [Worktree Status](https://github.com/sandercox/worktree-status/) - 在 macOS 菜单栏或 Windows 通知区域显示 Git 仓库状态。
- [Yaak](https://yaak.app) - 组织并执行 REST、GraphQL 与 gRPC 请求。
- [Yume](https://github.com/aofp/yume) ![v2] - Claude Code 的原生桌面 GUI，支持多标签会话、后台智能体、上下文压缩与插件系统。

### 电子书阅读器

- [Alexandria](https://github.com/btpf/Alexandria) - 极简跨平台电子书阅读器。
- [Jane Reader](https://janereader.com) ![closed source] - 现代、无干扰的 epub 阅读器。
- [Readest](https://github.com/chrox/readest) - 专为深度阅读者设计的现代功能丰富电子书阅读器。
- [Cloak](https://github.com/Xav1erSue/cloak) - 用于上班摸鱼的透明迷你阅读器。

### 邮件与订阅

- [Alduin](https://alduin.stouder.io/) - Alduin 是一款免费开源的 RSS、Atom 与 JSON 订阅阅读器，助你追踪喜爱的网站。
- [Aleph](https://github.com/chezhe/aleph) - Aleph 是一款 RSS 阅读器与播客客户端。
- [BULKUS](https://github.com/KM8Oz/BULKUS) - 邮件批量验证软件。
- [Lettura](https://github.com/zhanglun/lettura) - 面向 macOS 的开源订阅阅读器。
- [mdsilo Desktop](https://github.com/mdSilo/mdSilo-app) - 订阅阅读器与知识库。
- [Saga Reader](https://github.com/sopaco/saga-reader) - AI 驱动的互联网阅读器，支持抓取搜索引擎信息与 RSS。

### 文件管理

- [CzkawkaTauri](https://github.com/shixinhuang99/czkawka-tauri) - 多功能应用，可查找重复文件、空文件夹、相似图片等。
- [enassi](https://github.com/enassi/enassi) - 加密助手，可加密并存储你的笔记和文件。
- [EzUp](https://github.com/HuakunShen/ezup) - 文件与图片上传工具，专为博客写作和笔记记录设计。
- [MangoFinder](https://github.com/moyangzhan/mango-finder) ![v2] - 使用自然语言搜索文件。
- [Orange](https://github.com/naaive/orange) - 跨平台文件搜索引擎，可基于关键词快速定位文件或文件夹。
- [Payload](https://payload.app/) ![closed source] - 通过本地网络或在线进行拖放式文件传输。
- [Spacedrive](https://github.com/spacedriveapp/spacedrive) - 来自未来的文件资源管理器。
- [SquirrelDisk](https://github.com/adileo/squirreldisk) - 美观的跨平台磁盘空间分析工具。
- [Time Machine Inspector](https://github.com/probablykasper/time-machine-inspector) - 查看 Time Machine 备份占用的空间情况。
- [Xplorer](https://github.com/kimlimjustin/xplorer) - 可定制的现代化跨平台文件资源管理器。

### 金融

- [Compotes](https://github.com/Orbitale/Compotes) - 本地化的银行账户操作存储，可通过规则与标签自定义生成图表以实现更好的筛选。
- [CryptoBal](https://github.com/Rabbit-Company/CryptoBal-Desktop) - 用于监控加密资产的桌面应用。
- [Fincept Terminal](https://github.com/Fincept-Corporation/FinceptTerminal) ![v2] - 高级金融情报终端，集成 CFA 级分析、AI 智能体与 100+ 数据连接器。
- [Ghorbu Wallet](https://github.com/matthias-wright/ghorbu-wallet) - 跨平台 Bitcoin 桌面 HD 钱包。
- [Mahalli](https://github.com/AbdelilahOu/Mahalli-tauri) - Local first 库存与发票管理应用。
- [nym-wallet](https://github.com/nymtech/nym/tree/develop/nym-wallet) - Nym 桌面钱包，可使用 Nym 网络并利用其核心能力。
- [Spent](https://github.com/FrogSnot/Spent) ![v2] - 极简的跨平台个人理财跟踪器。
- [Upcount](https://www.upcount.app/) ![v2] - 面向自由职业者与小微企业的免费开票与时间跟踪应用。
- [UsTaxes](https://github.com/ustaxes/ustaxes) - 免费、私密、开源的美国报税工具。
- [Wealthfolio](https://wealthfolio.app) - 简洁、开源的桌面投资组合跟踪器，让你的财务数据安全保存在本机。

### 游戏

- [9Launcher](https://github.com/wearrrrr/9Launcher) - 现代化的东方 Project 游戏跨平台启动器。
- [BestCraft](https://github.com/Tnze/ffxiv-best-craft) - 面向《最终幻想 XIV》(FF14) 的制作模拟器，附带求解算法。
- [BetterFleet](https://github.com/zelytra/BetterFleet) - 帮助《盗贼之海》玩家组建联盟服务器。
- [Chessifier](https://github.com/Chessifier/chessifier) ![v2] - 终极国际象棋工具集。
- [clear](https://clear.adithya.zip) - 简洁、极简的电子游戏库管理与启动器。
- [CubeShuffle](https://github.com/philipborg/CubeShuffle) - 扑克牌洗牌工具。
- [Deadlock Mod Manager](https://github.com/deadlock-mod-manager/deadlock-mod-manager) ![v2] - V 社游戏《Deadlock》的模组管理器。
- [En Croissant](https://github.com/franciscoBSalgueiro/en-croissant) - 国际象棋数据库与对局分析应用。
- [FishLauncher](https://github.com/fishfight/FishLauncher) - 跨平台的 `Fish Fight` 启动器。
- [Gale](https://github.com/Kesomannen/gale) - 适用于 `Thunderstore` 上众多游戏的模组管理器。
- [HQ Launcher](https://github.com/p-asta/hq-launcher) - `lethal company` 高额度启动器。
- [Modrinth App](https://github.com/modrinth/code/blob/main/apps/app) - `Minecraft` 跨平台启动器，集成模组管理。
- [OpenGOAL](https://github.com/open-goal/launcher) - `OpenGOAL`（Jak and Daxter 系列逆向 PC 移植版）的跨平台安装器、模组管理器与启动器。
- [Outer Wilds Mod Manager](https://github.com/ow-mods/ow-mod-man) - 跨平台 `Outer Wilds` 模组管理器。
- [OyasumiVR](https://github.com/Raphiiko/OyasumiVR) - 帮助你在 VR 中入睡的软件，可与 SteamVR、VRChat 等配合使用。
- [Rai Pal](https://github.com/raicuparta/rai-pal) - 通用模组管理器，支持 `UEVR`、`UUVR` 等。
- [Resolute](https://github.com/Gawdl3y/Resolute) - 面向游戏 Resonite 的用户友好型跨平台模组管理器。
- [Retrom](https://github.com/JMBeresford/retrom) - 私有云游戏库分发服务器 + 前端/启动器。
- [Samira](https://github.com/jsnli/Samira) - Linux 上的 Steam 成就管理器。
- [Sarge Launcher](https://github.com/endless-r0ad/sarge-launcher) ![v2] - 《Quake 3 Arena》及 Q3A 模组的跨平台启动器，包含服务器、演示与关卡浏览。
- [Shard Launcher](https://github.com/Th0rgal/shard) ![v2] - 开源 Minecraft 启动器，支持声明式配置、内容寻址存储，并集成 Modrinth/CurseForge。
- [SJMC Launcher](https://github.com/UNIkeEN/SJMCL) ![v2] - 面向 `Minecraft` 的启动器，具备实例管理与多账号支持。
- [Steam Art Manager](https://github.com/Tormak9970/Steam-Art-Manager) - 自定义 Steam 游戏封面与配图的工具。
- [Tauri Chess](https://github.com/jamessizeland/tauri-chess) - 国际象棋实现：逻辑部分使用 Rust，可视化部分使用 React。
- [Teyvat Guide](https://github.com/BTMuli/TeyvatGuide) - 面向《原神》玩家的游戏工具。
- [Quadrant](https://github.com/mrquantumoff/quadrant/) - Minecraft 模组与整合包管理工具，可对接 Modrinth 与 CurseForge。

### 信息查询

- [Cores](https://github.com/Levminer/cores) ![paid] - 支持远程监控的现代化硬件监控工具。
- [HardwareVisualizer](https://github.com/shm11C3/HardwareVisualizer) ![v2] - 硬件监控工具，支持持久化历史数据、可定制仪表板和灵活的主题。
- [Seismic](https://github.com/breadthe/seismic) - 用于追踪 USGS 地震信息的任务栏应用。
- [Stockman](https://github.com/awkj/stockman) - 在 macOS 菜单栏显示股票信息。
- [Watchcoin](https://github.com/lifecoder1988/tauri-watch-coin) - 在操作系统菜单栏显示加密货币价格，无需打开窗口。

### 学习

- [Japanese](https://github.com/meel-hd/japanese) - 学习日语平假名与片假名，支持记忆、书写、发音与测验。
- [Manjaro Starter](https://github.com/oguzkaganeren/manjaro-starter) - 面向 Manjaro 新用户的文档与支持应用。
- [Piano Trainer](https://github.com/ZaneH/piano-trainer) - 使用 MIDI 键盘练习钢琴和弦、音阶等。
- [Solars](https://github.com/hiltontj/solars) - 可视化太阳系行星。
- [Syre](https://github.com/syre-data/syre) - 科学数据助手。
- [Rosary](https://github.com/Roseblume/Rosary) - 基督教学习工具。

### 网络

- [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) - Clash Verge 的延续之作，一款基于规则的代理工具。
- [CyberAPI](https://github.com/vicanso/cyberapi) - 面向开发者的 API 工具客户端。
- [EasyTier](https://github.com/EasyTier/EasyTier) ![v2] - 简单、安全、去中心化的虚拟专用网络方案。
- [Jexpe](https://github.com/jexpe-apps/jexpe) - 跨平台开源 SSH 与 SFTP 客户端，让远程服务器连接更轻松。
- [Mail-Dev](https://github.com/samirdjelal/mail-dev) - 跨平台本地 SMTP 服务器，用于邮件测试与调试。
- [mDNS-Browser](https://github.com/hrzlgnm/mdns-browser) - 跨平台 mDNS 浏览器应用，可使用 mDNS 发现网络服务。
- [NetDia](https://github.com/shellrow/netdia) ![v2] - 跨平台网络诊断工具，用于检查、监控和分析你的网络。
- [Nhex](https://github.com/nhexirc/nhex) - 受 HexChat 启发的下一代 IRC 客户端。
- [RustDesk](https://github.com/rustdesk/rustdesk-server) - RustDesk 的自托管服务器，是一款开源远程桌面工具。
- [RustDuck](https://github.com/thewh1teagle/RustDuck) - 跨平台 duckdns.org 动态 DNS 更新器。
- [r-shell](https://github.com/GOODBOY008/r-shell) ![v2] - 现代化 SSH 客户端，具备多会话管理、集成文件浏览器、系统监控等功能。
- [T-Shell](https://github.com/TheBlindM/T-Shell) - 开源 SSH、SFTP 智能命令行终端应用。
- [TunnlTo](https://github.com/TunnlTo/desktop-app) - 面向 Windows 的 WireGuard VPN 客户端，专为分隧道设计。
- [UpVPN](https://github.com/upvpn/upvpn-app) - 面向 Linux、macOS 和 Windows 的 WireGuard VPN 客户端。
- [Watcher](https://github.com/windht/watcher) - API 管理器，提供更易用的管理与协作方式。
- [Wirefish](https://github.com/stefanodevenuto/wirefish) - 跨平台抓包与分析工具。

### 办公与写作

- [Astro Editor](https://github.com/dannysmith/astro-editor) - 简洁的 Markdown 编辑器，面向 Astro 内容集合，支持 frontmatter 编辑、组件插入与专注写作的界面。
- [fylepad](https://github.com/imrofayel/fylepad/) - 基于 Vue & Tauri 构建的强大富文本记事本。
- [Bidirectional](https://github.com/samirdjelal/bidirectional) - 在不支持双向文本的应用中输入阿拉伯文。
- [Blank](https://github.com/FPurchess/blank) - 极简、专注写作的 Markdown 编辑器。
- [Blinko](https://github.com/blinkospace/blinko) ![v2] - 自托管的个人 AI 笔记工具，优先保护隐私。
- [Ensō](https://enso.sonnet.io) ![closed source] - 先写后改，Ensō 是一款帮助你进入心流状态的写作工具。
- [Fluster](https://flusterapp.com) ![v2] - 一站式、开源免费的笔记应用，满足现代学术或 STEM 从业者的全部需求。
- [Handwriting keyboard](https://github.com/BigIskander/Handwriting-keyboard-for-Linux-tesseract) - 适用于 Linux X11 桌面环境的手写键盘。
- [Inkwell](https://github.com/4worlds4w-svg/inkwell) - 便携、离线优先的 Markdown 编辑器。单一可执行文件，免安装，零遥测。
- [JournalV](https://github.com/ahmedkapro/journalv) - 用于记录日常与梦想的日记应用。
- [MarkFlowy](https://github.com/drl990114/MarkFlowy) - 现代化 Markdown 编辑器应用，内置 ChatGPT 扩展。
- [MD Viewer](https://github.com/kuyoonjo/md-viewer) - 跨平台 Markdown 查看器。
- [MDX Notes](https://github.com/maqi1520/mdx-notes/tree/tauri-app) - 多功能微信公众号排版编辑器与跨平台 Markdown 笔记软件。
- [Noor](https://noor.to/) ![closed source] - 面向高性能团队的聊天应用，专为不被打断的深度工作和快速协作而设计。
- [Notpad](https://github.com/Muhammed-Rahif/Notpad) - 跨平台富文本编辑器，保留记事本界面，并增强了超越标准记事本的高级功能。
- [Parchment](https://github.com/tywil04/parchment) - 简洁的纯本地跨平台文本编辑器，支持基础 Markdown。
- [Semanmeter](https://yibiao.fun/) ![closed source] - OCR 与文档转换软件。
- [Ubiquity](https://github.com/opensourcecheemsburgers/ubiquity) - 跨平台 Markdown 编辑器；基于 Yew、Tailwind 和 DaisyUI 构建。
- [HuLa](https://github.com/HuLaSpark/HuLa) - 基于 Tauri + Vue3 构建的桌面即时通讯应用（不只用于即时通讯）。
- [Gramax](https://github.com/Gram-ax/gramax) - 免费开源的 Git 驱动文档站创建、编辑与发布应用，基于 Markdown 和可视化编辑器。

### 生产力

- [Banban](https://github.com/HubertK05/banban) - 支持标签、分类和 Markdown 的看板。
- [Blink Eye](https://github.com/nomandhoni-cs/blink-eye) - 极简的护眼提醒应用，可减少眼睛疲劳，支持自定义计时器、全屏弹窗和屏幕使用时长统计。
- [BuildLog](https://github.com/rajatkulkarni95/buildlog) - 用于跟踪 Vercel 部署的菜单栏工具。
- [Clippy](https://github.com/0-don/clippy) - 支持同步与加密的剪贴板管理器。
- [Dalgona](https://github.com/GHGHGHKO/dalgona) - 适用于 Windows 和 macOS 的 GIF 表情包搜索应用。
- [EcoPaste](https://github.com/ayangweb/EcoPaste/tree/master) - 适用于 macOS、Windows 和 Linux(x11) 的强大开源剪贴板管理器。
- [Fairies](https://fairies.ai) ![closed source] ![paid] - 面向 macOS、Windows、移动端与 Web 的强大通用 AI 智能体。
- [Floweb](https://floweb.cn/en) ![closed source] ![paid] - 超轻量级悬浮桌面吊件，可将网页转化为支持置顶、透明、多账号、自动刷新等特性的 Web 应用。
- [Focust](https://github.com/pilgrimlyieu/Focust) ![v2] - 跨平台休息与专注提醒应用，支持自定义计划、主题、建议、应用排除与高级配置。
- [GitBar](https://github.com/mikaelkristiansson/gitbar) - 用于 GitHub 代码评审的系统托盘应用。
- [Gitification](https://github.com/Gitification-App/gitification) - 用于管理 GitHub 通知的菜单栏应用。
- [Google Task Desktop Client](https://github.com/codad5/google-task-tauri) - Google Task 桌面客户端。
- [HackDesk](https://github.com/EastSun5566/hackdesk) - 可定制的 HackMD 桌面应用。
- [iDO](https://github.com/UbiquantAI/IDO) ![v2] - AI 驱动的桌面生产力工具，帮你管理任务、想法与技术知识。
- [jasnoo](https://jasnoo.com) ![closed source] ![paid] - 帮助你解决问题、规划每日行动并保持专注的桌面软件。
- [Kanri](https://github.com/trobonox/kanri) - 跨平台、离线优先的看板应用，注重简洁与用户体验。
- [Kianalol](https://github.com/zxh3/kianalol) - 类 Spotlight 的效率工具，用于快速访问网站。
- [Kunkun](https://kunkun.sh/) - 跨平台、可扩展的应用启动器，Alfred 和 Raycast 的替代品。
- [Link Saas](https://github.com/linksaas/desktop) - 面向软件开发团队的高效工具。
- [MacroGraph](https://github.com/Brendonovich/macrograph) - 面向内容创作者的可视化编程工具。
- [MeadTools](https://github.com/ljreaux/meadtools-desktop) - 一体化蜂蜜酒、葡萄酒和苹果酒酿造计算器。
- [Mind Elixir Desktop](https://desktop.mind-elixir.com) ![closed source] ![paid] - AI 驱动的思维导图工具，让你的灵感井井有条。
- [mynd](https://github.com/Gnarus-G/mynd) - 面向开发者的快速极简待办清单管理应用，适配终端党。
- [Obliqoro](https://github.com/mrjackwills/obliqoro) - Oblique Strategies 与番茄工作法的结合。
- [PasteBar](https://github.com/PasteBar/PasteBarApp) - 适用于 Mac 与 Windows 的无限、免费剪贴板管理器。轻松管理所有复制粘贴内容。
- [PicSharp](https://github.com/AkiraBit/PicSharp) ![v2] - 具备强大且可高度配置的压缩功能，帮助你轻松优化图片，提供出色的性能与便捷的体验。
- [Pomodoro](https://github.com/g07cha/pomodoro) - 基于番茄工作法的时间管理工具。
- [Progressive](https://github.com/h8moss/progressive)![v2] - 带进度跟踪的待办应用。支持任务权重、百分比进度与父子任务。
- [Qopy](https://github.com/0PandaDEV/Qopy) - 面向 Windows 与 Mac 的固定式剪贴板管理器。
- [Remind Me Again](https://github.com/probablykasper/remind-me-again) - 可切换开关的提醒应用，支持 Mac、Linux 与 Windows。
- [Runtime](https://github.com/runtime-org/runtime) ![v2] - 面向 Web 与办公工具的 AI 任务伙伴。
- [Shell360](https://github.com/nashaofu/shell360) ![v2] - 跨平台开源 SSH 与 SFTP 客户端，支持端口转发与加密存储，面向开发者与系统管理员。
- [Stik](https://github.com/0xMassi/stik_app) ![v2] - 面向 macOS 的即时灵感捕捉工具，支持本地 AI 语义搜索。热键 → 输入 → 完成。8MB 二进制体积，纯 Markdown 文件，MIT 许可。
- [Takma](https://github.com/jam53/Takma) - 看板风格待办应用，完全离线，支持 Markdown、标签、截止日期、清单与深度链接。
- [Tencent Yuanbao](https://yuanbao.tencent.com/) ![closed source] - 腾讯元宝是基于腾讯混元大模型的 AI 应用，是写作、绘画、文案、翻译、编程、搜索、阅读和总结的全能助手。
- [TimeChunks](https://danielulrich.com/en/timechunks/) ![closed source] - 面向自由职业者的时间跟踪，无需定时器与 HH:MM:SS 输入。
- [Tranzit](https://github.com/kr5hn4/tranzit) ![v2] - 跨平台应用，可通过本地网络在附近设备间安全共享文件。
- [UniMe](https://github.com/impierce/identity-wallet) ![v2] - 身份钱包，帮助用户管理去中心化身份与可验证凭证。
- [WindowPet](https://github.com/SeakMengs/WindowPet) - 浮窗应用，让可爱的伙伴（宠物或动漫角色）出现在你的屏幕上。
- [Zawee](https://zawee.net) ![closed source] - 看板、笔记、文件共享等多种功能的无缝整合，体验高效协同。
- [Zenith](https://github.com/dewy01/Zenith) ![v1] - 无论是组织任务、协作项目还是记录重要日期，Zenith 都能满足你的需求。
- [ZeroLaunch-rs](https://github.com/ghost-him/ZeroLaunch-rs) - 专注应用启动，支持全拼/拼音/缩写搜索并提供纠错，可自定义界面与键盘快捷键。

### 搜索

- [Coco AI](http://coco.rs/) - 🥥 Coco AI 将你企业中的所有应用与数据——Google Workspace、Dropbox、GitHub 等——统一到强大的搜索与 Gen-AI 聊天平台中。
- [Harana](https://github.com/harana/search) - 即时搜索你的桌面与 300+ 云端应用。
- [Spyglass](https://github.com/a5huynh/spyglass) - 个人搜索引擎，可索引你的文件/文件夹、云账号以及你感兴趣的网络内容。

### 安全

- [Authme](https://github.com/Levminer/authme) - 桌面端双因素（2FA）身份验证应用。
- [Calciumdibromid](https://codeberg.org/Calciumdibromid/CaBr2) - 按欧洲法规生成"实验安全说明书"。
- [chiffrage](https://github.com/thrzl/chiffrage) ![v2] - 使用 age 加密格式加密文件和文本的跨平台 UI。
- [Defguard](https://github.com/defguard/client) - WireGuard VPN 桌面客户端，集成双因素（2FA）身份验证。
- [Gluhny](https://github.com/angeldollface/gluhny) - 校验 IMEI 号码的图形界面。
- [JumpServer](https://github.com/jumpserver/client/) ![v2] - 开源 PAM 客户端，现代化、优雅、跨平台一致。
- [OneKeePass](https://github.com/OneKeePass/desktop) - 安全、现代、跨平台、兼容 KeePass 的密码管理器。
- [Padloc](https://github.com/padloc/padloc) - 现代化开源密码管理器，适用于个人与团队。
- [Secops](https://github.com/kunalsin9h/secops) - 让 Ubuntu 操作系统安全防护变得简单。
- [Tauthy](https://github.com/pwltr/tauthy) - 跨平台 TOTP 身份验证客户端。
- [Vault-0](https://github.com/0-Vault/Vault-0) - 加密的秘密保险库、实时智能体监控以及面向 OpenClaw AI 智能体的 x402 支付钱包。
- [Truthy](https://github.com/fosslife/truthy/) - 现代化跨平台 2FA 管理器，功能丰富、UI 精美。

### 社交媒体

- [Dorion](https://github.com/SpikeHD/Dorion) - 轻量级第三方 Discord 客户端，支持插件和主题。
- [Identia](https://github.com/iohzrd/identia) - 基于 IPFS 的去中心化社交媒体。
- [Kadium](https://github.com/probablykasper/kadium) - 用于追踪 YouTube 频道更新的应用。
- [Poll-arize](https://poll-arize.com/?ref=awesome-tauri) ![closed source] - 专注于投票与用户意见聚合的社交媒体平台。
- [Scraper Instagram GUI Desktop](https://git.kaki87.net/KaKi87/scraper-instagram-gui-desktop) - 桌面端 Instagram 替代前端。
- [Vector](https://github.com/VectorPrivacy/Vector) ![v2] - 私有、去中心化的即时通讯工具，自带游戏和应用（E2EE）。

### 实用工具

- [AgeTimer](https://github.com/dhextras/age-timer-tauri) - 实时显示你年龄的桌面工具。
- [Auto Wallpaper](https://github.com/auto-wallpaper/auto-wallpaper) - 根据用户位置、天气、时段或自定义提示自动生成 4K 壁纸。
- [bewCloud Desktop Sync](https://github.com/bewcloud/bewcloud-desktop) - bewCloud 的桌面同步应用，Nextcloud 与 ownCloud 的更简洁替代品。
- [Basset](https://github.com/mohammadmansour200/basset) ![v2] - 一体化离线媒体工具箱：剪切、转换、压缩以及音视频和图片的人声/伴奏分离。
- [TypeView - KeyStroke Visualizer](https://github.com/dunkbing/typeview) - 在屏幕上可视化按键，并模拟机械键盘音效。
- [Browsernaut](https://github.com/billyjacoby/browsernaut) - macOS 上的浏览器选择器。
- [Clipboard Record](https://github.com/lesterhnu/clipboard) - 记录剪贴板内容。
- [CrabCamera](https://github.com/Michael-A-Kuykendall/crabcamera) - 面向 Tauri 应用的专业桌面相机插件，支持 WebRTC 流式传输与高级硬件控制。
- [DecentPaste](https://github.com/decentpaste/decentpaste) ![v2] - 基于 P2P 加密的跨平台剪贴板本地网络共享。
- [Dwall](https://github.com/dwall-rs/dwall) - 像 macOS 一样，根据太阳方位角和高度角自动更换 Windows 桌面与锁屏壁纸。
- [Fancy Screen Recorder](https://fancyapps.com/freebies/) ![closed source] - 录制全屏或选定区域，裁剪后保存为 GIF 或视频。
- [FanslySync](https://github.com/SticksDev/FanslySync) - 安全地将你的 Fansly 数据与第三方应用同步！
- [Flying Carpet](https://github.com/spieglt/flyingcarpet) - 通过自动配置热点在 Android、iOS、Linux、macOS 和 Windows 间传输文件。
- [Get Unique ID](https://github.com/hiql/get-unique-id-app) - 生成用于调试、开发或其他任何场景的唯一 ID。
- [Happy](https://github.com/thewh1teagle/happy) - 轻松控制 HappyLight 兼容的 LED 灯带。
- [Imagenie](https://github.com/zhongweili/imagenie) - AI 驱动的桌面应用，提供惊艳的图片变换效果。
- [KoS - Key on Screen](https://github.com/dubisdev/key-on-screen) - 在屏幕上显示你正在按下的按键。
- [Lanaya](https://github.com/ChurchTao/Lanaya) - 简单易用、跨平台的剪贴板管理工具。
- [Lingo](https://github.com/thewh1teagle/lingo) - 跨平台离线翻译，支持所有语言。
- [Linka!](https://github.com/linka-app/linka) - AI 驱动、简单易用的跨平台书签管理工具。
- [Locus](https://github.com/Sushants-Git/locus) - 智能活动追踪器，帮助你理解并改善专注习惯。
- [MagicMirror](https://github.com/idootop/MagicMirror) - 一键 AI 换脸、换发型、换装，焕然一新！
- [MBTiles Viewer](https://github.com/Akylas/mbview-rs) - MBTiles 查看器与检视工具。
- [Metronome](https://github.com/ZaneH/metronome) - 适用于 Windows、Linux 与 macOS 的可视化节拍器。
- [Mobslide](https://github.com/thewh1teagle/mobslide) - 将你的智能手机变为演示文稿遥控器。
- [NeoHtop](https://github.com/Abdenasser/neohtop) - 外观和体验类似 macOS 活动监视器的跨平台系统监控工具。
- [Overlayed](https://overlayed.dev) - Discord 语音聊天悬浮窗。
- [Pachtop](https://pachtop.com/) - 现代化跨平台系统监控器 🚀。
- [Passwords](https://github.com/hiql/passwords-app) - 随机密码生成器。
- [Pavo](https://github.com/zhanglun/pavo) - 跨平台桌面壁纸应用。
- [Peekaboo](https://github.com/angeldollface/peekaboo) - 用于显示图片的图形界面。
- [Pointless](https://github.com/kkoomen/pointless) - 永无止境的绘图画布。
- [Pot](https://github.com/pot-app/pot-desktop) - 跨平台翻译软件。
- [RapidRAW](https://github.com/CyberTimon/RapidRAW) ![v2] - RAW 图像编辑器，为 Windows、macOS 和 Linux 提供轻量级高性能体验。
- [RMBG](https://github.com/zhbhun/rmbg) - 跨平台图片背景移除工具。
- [Recordscript](https://github.com/Recordscript/recordscript) - 录制并转写你的在线会议，或为视频添加字幕。跨平台纯本地屏幕录制与字幕生成器。
- [Rounded Corners](https://github.com/RoundedCorners/Application) - 适用于 Windows 的圆角窗口应用。
- [RunMath](https://github.com/dubisdev/runmath) - 面向 Windows 的键盘优先计算器。
- [SensiMouse](https://github.com/Nicify/sensi-mouse) - 轻松调整 macOS 全系统鼠标灵敏度和加速度设置。
- [SlimeVR Server](https://github.com/SlimeVR/SlimeVR-Server) - SlimeVR 服务器应用，为 VR 中的全身追踪提供支持。
- [Sofast](https://sofast.fun) ![closed source] - 跨平台类 Raycast 应用。
- [SoulFire](https://github.com/AlexProgrammerDE/SoulFireClient) - 高级 Minecraft 服务器压力测试工具，可对你的服务器发起机器人攻击以评估性能。
- [Stable Diffusion Buddy](https://github.com/breadthe/sd-buddy) - 面向 Mac 版自托管 Stable Diffusion 的桌面 UI 伴侣。
- [Stacks](https://github.com/cablehead/stacks) - 现代化、功能强大的 macOS 剪贴板管理器。欢迎贡献 Linux 和 Windows 版本。
- [SwitchShuttle](https://github.com/s00d/switchshuttle) - 跨平台系统托盘应用，允许用户在各种终端应用中运行预定义命令。
- [Tauview](https://github.com/sprout2000/tauview) - 基于 Leaflet.js 的 macOS 与 Linux 极简图片查看器。
- [Tmus](https://github.com/saicem/tmus) ![v2] - 监控你在桌面应用上的时间，并通过各种图表进行可视化。
- [ToeRings](https://github.com/acarl005/toerings) - 灵感来自 Conky Seamod 的系统监控应用。
- [Toolcat](https://toolcat.app) ![closed source] - 面向开发者与创作者的一体化工具箱。
- [TrayFier](https://github.com/dubisdev/trayfier) - 通过链接、文件、可执行文件等强化你的 Windows 托盘。
- [TrguiNG](https://github.com/openscopeproject/TrguiNG) - Transmission 守护进程的远程 GUI。
- [Verve](https://github.com/ParthJadhav/verve) - 用于访问和打开应用、文件、文档的启动器。
- [Vibe](https://thewh1teagle.github.io/vibe) - 跨平台转写任意语言的音频或视频。
- [Wallpaper changer](https://github.com/zeet2020/wallpaper-changer-tauri) - 简洁的壁纸更换应用。
- [WSL UI](https://github.com/octasoft-ltd/wsl-ui) ![v2] - 用于管理 Windows 上 WSL 发行版的轻量级桌面应用。
- [Zap](https://usezap.sh/?ref=awesometauri) ![closed source] - 类 macOS Spotlight 的 Dock，让应用导航更便捷。
- [Zapicon](https://zapicon.once.work/en) ![closed source] ![paid] ![v2] - 跨平台图标生成器，支持可视化编辑、iOS 圆角方形、主题预设、设计规范与一键多平台导出。

[officially maintained]: https://img.shields.io/badge/official-FFC131?&logo=tauri&logoColor=black
[closed source]: https://img.shields.io/badge/closed%20source-FFC131?&logoColor=black
[paid]: https://img.shields.io/badge/paid-FFC131?&logoColor=black
[youtube]: https://img.shields.io/badge/YouTube-FF0000
[v1]: https://img.shields.io/badge/v1-white
[v2]: https://img.shields.io/badge/v2-white
