# ============================================================================
# TaprootAgro Android Builder — 一键打包工作流
# ============================================================================
#
# 使用方法：
#   app_name  → App 显示名称（如 "taprootagro"）
#   app_id    → 安卓包名（如 com.harvest.helper）
#   pwa_repo  → 你的 PWA 源码仓库地址（如 https://github.com/yourname/your-pwa）
#
# 此工作流会：
#   ✅ 拉取你的 PWA 源码并构建
#   ✅ 用 Capacitor 包装成安卓应用（本地模式，代码打包进 APK）
#   ✅ 自动处理 512px 图标 → 安卓全尺寸适配 + 自适应图标
#   ✅ 注入全套安卓权限（网络/相机/定位/存储/推送/后台/生物识别）
#   ✅ 自动生成签名 Keystore（首次）或使用已有 Keystore（后续）
#   ✅ 输出 APK + AAB + Keystore + 签名信息

# ============================================================================
# TaprootAgro Android Builder — One-Click Packaging Workflow
# ============================================================================
#
# Usage:
#   app_name  → App Display Name (e.g., "taprootagro")
#   app_id    → Android Package Name (e.g., com.harvest.helper)
#   pwa_repo  → Your PWA Source Code Repository URL (e.g., https://github.com/yourname/your-pwa)
#
# This workflow will:
#   ✅ Pull your PWA source code and build it
#   ✅ Wrap it into an Android application using Capacitor (Local Mode: code bundled directly into the APK)
#   ✅ Automatically process your 512px icon → Full Android size adaptation + Adaptive Icons
#   ✅ Inject a complete set of Android permissions (Network/Camera/Location/Storage/Push Notifications/Background Services/Biometrics)
#   ✅ Automatically generate a signing Keystore (for the first run) or use an existing Keystore (for subsequent runs)
#   ✅ Output the APK + AAB + Keystore + Signing Information
