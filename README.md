# 随机数生成器 Android App

这是一个原生 Android 工程，使用 Android WebView 加载本地 HTML，因此核心功能无需网络权限、可离线运行。

## 功能
- 自定义最小值、最大值和数量（1–500）
- 允许重复 / 不重复
- 结果排序
- 复制、清空结果
- 手机适配与系统深色模式

## 云端生成 APK
仓库包含 `.github/workflows/build-apk.yml`。将整个工程上传到 GitHub 仓库后，进入仓库的 **Actions** 页面，选择 **Build Android APK**，点击 **Run workflow**。构建完成后，在对应运行记录页面的 **Artifacts** 区域下载 `random-number-generator-apk`，解压得到 `app-debug.apk`。

此项目还未在当前环境实际运行 Android SDK 构建；APK 只有在 GitHub Actions 构建成功后才算生成。
