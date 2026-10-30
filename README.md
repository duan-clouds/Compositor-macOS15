# Compositor macOS 15 适配版

这是 [Robbie Tilton 的 Compositor](https://github.com/robbietilton/Compositor) 的非官方 macOS 15 适配版本。Compositor 是一款免费、开源的 Mac 图像编辑器，操作思路接近 Photoshop。

## 为什么制作这个版本？

原项目当前版本要求 Apple Silicon Mac 和 macOS 26 或更高版本。本项目在原作者开源工作的基础上进行兼容性修改，让使用 macOS 15 的 Apple Silicon（M 系列）Mac 也有机会体验 Compositor，无需升级到 macOS 26。

目前仅在 macOS 15.0.1 的 Apple Silicon Mac 上验证了启动、新建画布和图层；其他功能尚未全面测试，macOS 15 以下系统也尚未验证。RAW 高光恢复功能暂不可用。

## 下载与安装

- [下载拖拽安装包](Compositor-macOS15-AppleSilicon.dmg)：打开后将 Compositor 拖入 Applications 文件夹。
- [下载源码压缩包](Compositor-macOS15-source.zip)：解压后可在 Xcode 中查看源码，详细构建方法见其中的 README-macOS15.md。

安装包为本地编译和临时签名，未经 Apple 公证，其他 Mac 可能提示无法验证。原项目自动更新可能提供不兼容 macOS 15 的版本，请勿使用它覆盖本适配版。

## 致谢与许可

感谢原作者 Robbie Tilton 及所有贡献者开源 Compositor。本项目是独立的兼容性适配，不是原作者官方发布或维护的版本。原项目采用 MIT 许可证，原始版权和许可文件保留在源码压缩包中。
