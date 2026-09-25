[中文](README.md) | **English**

<div align="center">
<img src="icon.png" style="width:100px;" width="100"/>
<h2>BeePlayer</h2>
</div>

### 1. Product Overview

- A free, open-source **media player** and **multimedia engine** that aims to play everything and run everywhere.
- Reads most multimedia files, discs, network streams and capture devices, and can transcode, record and stream media.
- Ships with the embeddable engine **libVLC**, providing bindings for C, C++, Python, C# and more.
- Supports Windows, macOS, GNU/Linux, BSD, Android, iOS and other mainstream platforms.
- Full format coverage with stable playback; one engine across platforms; all source code reviewable and modifiable.
- **Publisher** Mutantcat Working Group (mutantcat.org) · GitHub: https://github.com/Mutantcat-Working-Group

Core value: if the player can open it, BeePlayer opens it, and the engine can do the work inside your own application.

### 2. Interface Overview

- The main window opens files, discs, network streams or capture devices from the "Media" menu.
- Built-in playlist, subtitle loading, audio/video equalizer, skins and visualizations.
- Command line and remote control interfaces (HTTP / telnet CLI) for scripted and unattended scenarios.

### 3. Features

#### Playback

- Full support for multimedia files, discs, network streams and capture devices.
- Transcoding, recording and streaming in one place.
- Plugin-based codec and access architecture, with codecs, demuxers, audio/video outputs and more under `modules/`.

#### libVLC Embeddable Engine

- The engine is separate from the application, letting third-party applications keep their own licenses.
- GUI implementations across desktop, mobile and the web console.

#### Development Progress

- [X] Media file playback
- [X] Disc and network stream support
- [X] Transcoding, recording and streaming
- [X] Cross-platform GUI (desktop, mobile, web console)
- [X] libVLC embeddable engine
- [X] Plugin-based codec and access architecture

### 4. Install and Download

1. For desktop and mobile use: install the matching distribution package on Windows, macOS, GNU/Linux, BSD, Android, iOS, etc. (VideoLAN official channels provide packages for each platform).
2. For integration: bring libVLC into your own application (see section 6) to gain playback, transcoding and streaming capabilities without rewriting the stack.
3. To build yourself: prepare the toolchain as described in section 7 and build from source.

### 5. Quick Start

1. Open BeePlayer and use the "Media" menu to open files, discs, network streams or capture devices.
2. Use the built-in playlist, subtitles, audio/video equalizer, skins and visualizations.
3. Command line: `vlc [options] <file or stream URL>`.
4. Remote control is available through the HTTP interface or the telnet CLI interface.

### 6. API Reference

#### libVLC Public API

- C headers are located in `include/vlc`.
- The engine source is located in `lib/` and `src/`.

#### Language Bindings

- Bindings for C, C++, Python, C# and more are located in `bindings/`.

#### Plugins and Modules

- `modules/` contains the plugin system for codecs, demuxers, audio/video outputs, access modules and more.

### 7. Build from Source

- Build steps, dependencies and configuration options for each platform are documented in the [INSTALL](INSTALL) file.
- When building from source, prepare the toolchain for the target platform as described there before running the build.

### 8. License

- BeePlayer itself is licensed under GPLv2 (or later).
- The libVLC engine is licensed under LGPLv2 (or later) and can be embedded in third-party applications.
