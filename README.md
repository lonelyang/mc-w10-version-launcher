## Language
- [中文](#中文)
- [English](#english)
---

### 中文
# MCLauncher

此工具允许您并行安装多个版本的 Minecraft: Windows 10 Edition (Bedrock)。
如果您想并排测试测试版、版本或其他任何内容，而无需卸载并重新安装游戏，这将非常有用。

## 免责声明
这个工具不会帮助你盗版游戏;它要求您拥有一个可用于从商店下载Minecraft的Microsoft帐户。

## 必要条件
- 登录了**拥有 Minecraft for Windows 10** 的 Microsoft Store 的 Microsoft 帐户
- **管理员权限** 您的用户帐户（或对具有的帐户的访问权限）
- 在 Windows 10 设置中为应用安装启用了**开发人员模式**
- 如果您希望能够使用 Beta 版，您还需要使用 Xbox Insider Hub 订阅 Minecraft Beta 计划。
- 已安装 [Microsoft Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe)

## 设置
- 从 [Releases](https://github.com/lonelyang/mc-w10-version-launcher/releases) 部分下载最新版本。在某个地方解压缩它。
- 运行“MCLauncher.exe”以启动启动器。

## 自己编译启动器
需要安装了 Windows 10 SDK 版本 10.0.17763 和 .NET Framework 4.6.1 SDK 的 Visual Studio。如果没有现成的，可以在 Visual Studio 安装程序中找到它们。
只要你没有做任何奇怪的事情，这个项目就应该用VS开箱即用地构建。

## 常见问题解答
**这是否允许同时运行多个 Minecraft: Bedrock 实例？**

在撰写本文时，没有。它允许您_安装_多个版本，但一次只能运行一个版本。

---

### English
# MCLauncher

This tool allows you to install several versions of Minecraft: Windows 10 Edition (Bedrock) side-by-side.
This is useful if you want to test beta versions, releases or anything else side-by-side without needing to uninstall and reinstall the game.

## Disclaimer
This tool will **not** help you to pirate the game; it requires that you have a Microsoft account which can be used to download Minecraft from the Store.

## Prerequisites
- A Microsoft account connected to Microsoft Store which **owns Minecraft for Windows 10**
- **Administrator permissions** on your user account (or access to an account that has)
- **Developer mode** enabled for app installation in Windows 10 Settings
- If you want to be able to use beta versions, you'll additionally need to **subscribe to the Minecraft Beta program using Xbox Insider Hub**.
- [Microsoft Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) installed.

## Setup
- Download the latest release from the [Releases](https://github.com/lonelyang/mc-w10-version-launcher/releases) section. Unzip it somewhere.
- Run `MCLauncher.exe` to start the launcher.

## Compiling the launcher yourself
You'll need Visual Studio with Windows 10 SDK version 10.0.17763 and .NET Framework 4.6.1 SDK installed. You can find these in the Visual Studio Installer if you don't have them out of the box.
The project should build out of the box with VS as long as you haven't done anything bizarre.

## Frequently Asked Questions
**Does this allow running multiple instances of Minecraft: Bedrock at the same time?**

At the time of writing, no. It allows you to _install_ multiple versions, but only one version can run at a time.
