[中文](README.md) | **English**

<div align=center>
<img src="icon.png" style="width:100px;" width="100"/>
<h2>BeePlayer</h2>
</div>

### 1. Feature Overview
- A free, open-source **media player** and **multimedia engine** that aims to play everything and run everywhere.
- Reads most multimedia files, discs, network streams and capture devices, and can transcode, record and stream media.
- Ships with the embeddable engine **libVLC**, providing bindings for C, C++, Python, C# and more.
- Supports Windows, macOS, GNU/Linux, BSD, Android, iOS and other mainstream platforms.

### 2. Deployment
1. Install the matching distribution package on a supported platform (Windows, macOS, Linux, Android, iOS).
2. Developers can integrate libVLC into their own applications to gain playback, transcoding and streaming capabilities.

### 3. Usage
1. Open BeePlayer and use the "Media" menu to open files, discs, network streams or capture devices.
2. Use the built-in playlist, subtitles, audio/video equalizer, skins and visualizations.
3. Command line: `vlc [options] <file or stream URL>`.
4. Remote control is available through the HTTP interface or the telnet CLI interface.

### 4. API Documentation
1. libVLC public API
   - C headers are located in `include/vlc`.
   - The engine source is located in `lib/` and `src/`.
2. Language bindings
   - Bindings for C, C++, Python, C# and more are located in `bindings/`.
3. Plugins and modules
   - `modules/` contains the plugin system for codecs, demuxers, audio/video outputs, access modules and more.

### 5. Focus
- Full format coverage and stable playback.
- One engine that runs across platforms.
- An embeddable engine that lets third-party applications keep their own licenses.
- A free software ecosystem where all source code can be reviewed and modified.

### 6. Development Progress
- [X] Media file playback
- [X] Disc and network stream support
- [X] Transcoding, recording and streaming
- [X] Cross-platform GUI (desktop, mobile, web console)
- [X] libVLC embeddable engine
- [X] Plugin-based codec and access architecture

### 7. License
- BeePlayer itself is licensed under GPLv2 (or later).
- The libVLC engine is licensed under LGPLv2 (or later) and can be embedded in third-party applications.

### 8. Contribution and Community
- Contributions via Merge Request are welcome; please resolve CI and discussion issues before participating.
- The community includes developers, packagers, documentation writers, designers and support staff.
- Resources: [BeePlayer Support](https://www.videolan.org/support/), [Forum](https://forum.videolan.org/), [Wiki](https://wiki.videolan.org/), [Bug Tracker](https://code.videolan.org/videolan/vlc/-/issues).

### 9. Build from Source

Build steps, dependencies and configuration options for each platform are documented in the [INSTALL](INSTALL) file. When building from source, prepare the toolchain for the target platform as described there before running the build.

---

## 致谢

本项目是 [videolan/vlc](https://github.com/videolan/vlc) 的 Fork，感谢原仓库及其作者的优秀开源工作，本仓库在其基础上继续维护与改进。
