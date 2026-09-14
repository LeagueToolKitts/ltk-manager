# LTK Manager

The next-generation mod manager for **League of Legends**, successor to cslol-manager.

## 📥 Download

Go to the [Releases](https://github.com/LeagueToolKitts/ltk-manager/releases) page and download the latest version:

| File | Description |
|------|-------------|
| `LTK.Manager_1.7.1_x64-setup.exe` | Windows installer (recommended) |
| `LTK.Manager_1.7.1_x64_en-US.msi` | Windows MSI package |

## 🚀 Features

- Modern and redesigned user interface
- Improved mod compatibility and performance
- Automatic update checking
- Advanced profile management
- Full backward compatibility with cslol-manager mods

## 🛠️ Build from Source

```bash
cmake -B build -S .
cmake --build build --config Release
```

**Requirements:** Qt 6, CMake 3.16+

## 📂 Project Structure

```
src/        — C++ & QML source files
dist/       — Distribution scripts and tools
docs/       — Documentation and screenshots
```

## 🔄 Migration from cslol-manager

LTK Manager is fully compatible with your existing mods from cslol-manager.
Simply install LTK Manager and point it to your existing mod folder.

## 📄 License

This project is open source. See source files for details.
