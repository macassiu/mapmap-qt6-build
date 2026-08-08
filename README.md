# MapMap AppImage – Qt6 Build for Linux

![MapMap](https://raw.githubusercontent.com/mapmapteam/mapmap/master/resources/images/logo/mapmap-logo.png)

> **Unofficial build** — Self-contained AppImage of MapMap v0.6.3 compiled with **Qt6** for modern Linux distributions.

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/macassiu/mapmap-qt6-build)](https://github.com/macassiu/mapmap-qt6-build/releases/latest)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

---

## 📦 Download

Get the latest version here:  
👉 **[MapMap-v0.6.3-qt6-x86_64.AppImage](https://github.com/macassiu/mapmap-qt6-build/releases/latest)**

---
## 🚀 How to use

1. **Download** the `.AppImage` file
2. **Make it executable**:

   ```bash
   chmod +x MapMap-*.AppImage
3. **Run it:**
  ```bash
  ./MapMap-*.AppImage
  ```

**No installation required — works on all recent Linux distributions (Ubuntu 24.04+, Debian, Fedora, Arch, etc.)**

**✨ Features**

 ✅ Real-time video mapping

 ✅ Multiple sources support (camera, files, streaming)

 ✅ Advanced calibration and warping

 ✅ Intuitive user interface

 ✅ OSC support for external control

 ✅ Multi-display and projector compatibility
 
 

**🖥️ System Requirements**

   Linux distribution (x86_64)

   GPU with OpenGL support

   GStreamer (bundled in AppImage)
   

**Tested on:**

   ✅ Ubuntu 24.04 LTS

   ✅ Ubuntu Studio 24.04

   ✅ Other modern distributions
   

**⚠️ Important notes**

   This is an unofficial build and is not maintained by the original MapMap team.

   Compiled with Qt6 to fix compatibility issues on Ubuntu 24.04 and newer systems.

   The original project is no longer actively maintained — this AppImage aims to keep it usable on modern Linux.

   Report issues on this repository (not the official one).

**🔧 Build from source**

To compile MapMap yourself with Qt6:
```bash
git clone https://github.com/mapmapteam/mapmap.git
cd mapmap
# Edit src/src.pri — uncomment QT += openglwidgets
qmake6 mapmap.pro
make -j$(nproc)
```

**📝 Changelog**
v0.6.3-qt6 (2026-08-08)

 Compiled with Qt6 instead of Qt5

  Fixed openglwidgets compatibility issue

  Bundled all required libraries

   GStreamer plugins included

   Works on Ubuntu 24.04+ without additional dependencies

 **🙏 Credits**

 Original [MapMap team](https://github.com/mapmapteam/mapmap) for their work

 Open-source community for build and packaging tools

 **🤝 Contributing**

This is a community build. If you find issues or have suggestions, please open an Issue on this repository.


**📜 License**

MapMap is released under the GPLv3 license. This AppImage is distributed under the same terms.
💬 Support

For questions or issues, please open an Issue on this repository.

🔗 Original repository: [mapmapteam/mapmap](https://github.com/mapmapteam/mapmap)

📢 Found this useful? Share it with the community on:

    r/projection_mapping

    LinuxMAO forums

    Ubuntu forums
