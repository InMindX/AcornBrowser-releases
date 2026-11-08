<p align="center">
  <!-- 按 GitHub 主题（不是系统外观）切换：#gh-dark-mode-only / #gh-light-mode-only 由 GitHub 的样式直接显示或隐藏 -->
  <img src="https://raw.githubusercontent.com/InMindX/AcornBrowser-releases/main/assets/acornbrowser-lockup-vertical-dark.svg#gh-dark-mode-only" alt="橡果浏览器 AcornBrowser" width="260">
  <img src="https://raw.githubusercontent.com/InMindX/AcornBrowser-releases/main/assets/acornbrowser-lockup-vertical-light.svg#gh-light-mode-only" alt="橡果浏览器 AcornBrowser" width="260">
</p>

<p align="center">
  一款注重效率与隐私的 macOS 浏览器<br>
  A macOS browser built for focus and privacy
</p>

<p align="center">
  <a href="https://github.com/InMindX/AcornBrowser-releases/releases/latest"><b>下载最新版本 · Download</b></a>
</p>

---

## 橡果浏览器是什么

橡果浏览器（AcornBrowser）是一款 macOS 浏览器，基于 Chromium 内核（通过 CEF 嵌入），网页兼容性与 Chrome 一致。标签竖排在左侧，充分利用宽屏的屏幕空间，我们对用户体验做了大量的优化，尝试用「空间」把工作、学习、生活分开，以及把常用的网站固定在收藏夹里。

### 主要功能

- **侧栏标签**：标签竖排，可分组、拖动排序、改名、换图标；侧栏可以收起成一条窄栏。
- **空间**：每个空间有自己的颜色、收藏夹和标签，一键切换。
- **收藏夹**：常用网站固定成格子，点一下就打开；收藏里点开的外部链接在预览浮窗里打开，不打乱当前页面。
- **分屏**：一个窗口里并排看两到四个网页。
- **新建标签对话框**：在窗口中央输入网址或搜索，联想历史记录、书签和已打开的标签。
- **下载**：下载进度、暂停与继续、下载记录，完成后可在访达中显示。
- **自动升级**：后台下载新版本，退出时自动安装；不升级内核的版本只需下载很小的增量包。

### 隐私

- **WebRTC 默认关闭**，网站无法借此获取你的真实 IP 地址；需要视频通话时可以在设置里打开。
- **代理设置**与 Firefox 相同：手动 HTTP / HTTPS / SOCKS、PAC、系统代理；PAC 加载失败时默认禁止直接连接。
- **基于 HTTPS 的 DNS**：可选 Cloudflare、NextDNS、Google 或自定义。
- **网页使用的时区**可以设成与系统不同，例如和代理所在地一致。
- 位置信息权限默认阻止；浏览记录保存在本机，可以按时间范围清除。

## 下载与安装

在 [Releases](https://github.com/InMindX/AcornBrowser-releases/releases/latest) 下载对应芯片的安装包：

| 你的 Mac | 下载 |
|---|---|
| Apple 芯片（M1、M2、M3、M4 等） | `AcornBrowser-<版本>-apple-silicon.dmg` |
| Intel 芯片 | `AcornBrowser-<版本>-intel.dmg` |

不确定是哪种芯片：左上角苹果菜单 →「关于本机」，「芯片」一栏写 Apple M… 的选 Apple 芯片版，「处理器」一栏写 Intel 的选 Intel 版。

打开 DMG，把「橡果浏览器」拖进「应用程序」文件夹即可。需要 **macOS 13 或更新的系统**。安装后浏览器会自动升级。

Release 里其余的文件（`.delta`、`appcast-*.xml`）是自动升级用的，不需要手动下载。

---

## English

**AcornBrowser** (橡果浏览器) is a macOS browser built on Chromium (via CEF), so websites work just like in Chrome. It keeps tabs in a vertical sidebar, separates work and life with Spaces, and pins your favorite sites as tiles.

- **Sidebar tabs** with groups, renaming, custom icons, and a collapsible sidebar
- **Spaces**, each with its own color, favorites and tabs
- **Favorites** that open external links in a peek window
- **Split view** with two to four pages side by side
- **Downloads** with pause / resume and history
- **Automatic updates** in the background, usually as a small delta download
- **Privacy**: WebRTC off by default, Firefox-style proxy settings, DNS over HTTPS, and a custom time zone for websites

**Download** the `apple-silicon.dmg` (Apple silicon Macs) or `intel.dmg` (Intel Macs) from [Releases](https://github.com/InMindX/AcornBrowser-releases/releases/latest), open it and drag Acorn into Applications. Requires macOS 13 or later.
