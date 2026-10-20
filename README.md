# flow-launcher

使用 Kotlin 与 Jetpack Compose 的 Android 应用项目。

## 开发配置

`app/build.gradle.kts` 配置了 Android、Kotlin、Compose、Room 和 KSP，最低 Android SDK 为 24，编译 SDK 为 35。

## 项目结构

- `app/`：应用模块。
- `build.gradle.kts`、`settings.gradle.kts`：项目级构建配置。
- `gradle/`、`gradlew`、`gradlew.bat`：Gradle Wrapper。

## 本地开发

使用 Android Studio 打开仓库目录，并依据项目的 Gradle 配置安装对应 SDK、同步依赖。完成同步后可选择设备检查应用模块的构建与运行。

构建和运行尚未在本说明中验证；具体交互功能、截图与使用步骤仍需补充。此项目的技术结构为 Android 应用，不应与同名 Windows 项目混淆。
