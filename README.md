# Debug Tool Opensource

**Mobile Legends: Bang Bang External Debug Tool** (ImGui Overlay)

A native Android external tool built with JNI, ImGui, and Vulkan/OpenGL support for debugging and learning purposes.

## About This Project

This project has existed since **2023** and received its last major update in **2024**.

It was created during the period when many global apps (especially games) used unusual package name tags such as **"huawei"** for Unity Engine builds targeting Huawei devices. This version was part of an experimental effort that ultimately failed to gain adoption from Google and Huawei, leading to the discontinuation of the official Huawei-tagged version.

However, the tool remains useful for **educational purposes** and as a reference for developers who want to understand:
- Memory reading/writing on Android
- ImGui integration with native Android (Vulkan & OpenGL)
- Debug Layer Info with Draw in Front Display
- Touch simulation
- Reverse engineering game structures (especially Mobile Legends)

> **Note**: This is an **opensource debug/learning tool**. Use it responsibly for educational and personal learning purposes only.

## Features

- **Debug Layer Info with Draw in Front Display**
  - Real-time hero information overlay
  - Monster information with distance & health
  - Line drawing
  - Minimap information layer

- **Estimated Logic Tool for Automation of Health Monster Response with Specific Spell Trigger**
  - Intelligent automation for monster health response
  - Specific spell trigger logic (Lord, Turtle, Buffs, etc.)

- **ImGui Interface**
  - Clean tabbed UI (Debug Layer, Automation Logic, Minimap, Settings)
  - Theme switcher
  - Adjustable settings

- **Technical**
  - Native C++ with JNI
  - Memory tools & pattern scanner
  - Vulkan + OpenGL support
  - Touch injection

## Building

Run the compile script (requires Android NDK):

```bash
./compile.sh
```

## Disclaimer

This project is provided **for educational and learning purposes only**. The author is not responsible for any misuse.

---

**Last Updated**: 2024  
**Created**: 2023