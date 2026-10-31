# Composa 1.4.0 — Windows x64 安装包

Robbie Tilton 的 macOS 图像编辑器 **Compositor** 的第三方 Windows 移植版（.NET 实现）。

| 项目 | 说明 |
| --- | --- |
| 文件 | `composa-1.4.0-win-x64-setup.exe` |
| 大小 | 80,239,732 字节（77 MB） |
| 版本 | 1.4.0（2026-10-03 发布） |
| 平台 | Windows 10 / 11，x64 |
| 作者 | Dennis van der Stelt |
| 上游仓库 | https://github.com/dvdstelt/Composa |
| 原版（macOS） | https://github.com/robbietilton/Compositor |
| 许可 | 见上游仓库 LICENSE（非 MIT，上游为自定义许可） |

## 校验

```
sha256  e3883a6824f91ea9755bb5579e442aadc81c3fe2badd6469ebdb67997fa46160
```

与 GitHub Release 官方摘要一致。

## 安装

双击运行即可，无需管理员权限。安装包内含 ImageMagick 与三个本地 AI 模型
（U²-Net lite、MODNet 抠图，Real-ESRGAN 放大），不联网下载依赖。

## 注意

- **未数字签名**，首次运行 Windows SmartScreen 会提示"未知发布者"，
  需点"更多信息 → 仍要运行"。
- 这是第三方移植，不是原作者维护，问题请反馈到上游 Composa 仓库。
- 另一移植 `IAmTheBlurr/CompositorWindows`（C++/Qt6）仍是 0.1.4 预览版，
  且标注仅支持 Windows 11，未收录。

## 下载

直接克隆仓库后取 `resources/windows/composa-1.4.0-win-x64-setup.exe`，
或从上游 Release 下载：
https://github.com/dvdstelt/Composa/releases/tag/v1.4.0
