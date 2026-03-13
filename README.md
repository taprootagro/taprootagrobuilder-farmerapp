# ============================================================================
# TaprootAgro Android Builder — 一键打包工作流
# ============================================================================
#
# 使用方法：
#   1. 创建一个新的 GitHub 仓库（或 Fork 包含此文件的仓库）
#   2. 把这个文件放到 .github/workflows/build-android.yml
#   3. Actions → Run workflow → 填写 3 个字段 → 点击运行
#   4. 约 8-12 分钟后下载 APK
#
# 输入说明：
#   app_name  → App 显示名称（如 "丰收助手"）
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
