# OnePiece VPN

Shadowsocks VPN for **Android, Windows and Mac**. Add your `ss://` link, press Connect.

**[⬇ Download the latest version](../../releases/latest)**

| Device | File |
|---|---|
| Android phone | `OnePieceVPN-1.0.0-android.apk` |
| Windows PC | `OnePieceVPN-1.0.0-windows-x64.msi` |
| Windows on ARM (Snapdragon / Surface Pro X) | `OnePieceVPN-1.0.0-windows-arm64.msi` |
| Mac (Apple Silicon: M1, M2, M3, M4…) | `OnePieceVPN-1.0.0-macos-arm64.dmg` |

The app has no servers built in: you need an `ss://` link (or a subscription URL) from whoever runs your server.

## Install

### Android
1. Download the `.apk` on your phone and open it.
2. If asked, allow installing apps from your browser / file manager.
3. Open OnePiece VPN → **Servers → Import** → paste your `ss://` link (or scan its QR code).
4. Tap the big button on **Home** and accept the VPN request.

### Windows
1. Run the `.msi`. Windows may say "Windows protected your PC": click **More info → Run anyway**.
2. Open OnePiece VPN → **Servers → Import** → paste your `ss://` link.
3. Click **Connect**. The first time, choose **Restart as administrator** and click **Yes** (Windows only lets administrators create the VPN adapter).

### Mac
1. Open the `.dmg` and drag **OnePieceVPN** into **Applications**.
2. Open it. If macOS blocks it, go to **System Settings → Privacy & Security → Open Anyway**.
3. **Servers → Import** → paste your `ss://` link.
4. Click **Connect** and enter your Mac password (macOS requires it to create the VPN).
5. If macOS asks whether OnePiece VPN may use your Keychain, click **Always Allow**.

## Good to know

- **Rule mode** (default): Chinese sites go direct, everything else through your server. **Global**: everything through your server.
- Server passwords are stored encrypted on your device and are never sent anywhere else.
- The apps aren't signed by Apple or Microsoft, which is why the warnings above appear.
- Built on [sing-box](https://github.com/SagerNet/sing-box) (GPL-3.0).

---

# OnePiece VPN（中文）

适用于 **Android、Windows 和 Mac** 的 Shadowsocks VPN。添加你的 `ss://` 链接，点击连接即可。

**[⬇ 下载最新版本](../../releases/latest)**

| 设备 | 文件 |
|---|---|
| Android 手机 | `OnePieceVPN-1.0.0-android.apk` |
| Windows 电脑 | `OnePieceVPN-1.0.0-windows-x64.msi` |
| ARM 版 Windows（骁龙 / Surface Pro X） | `OnePieceVPN-1.0.0-windows-arm64.msi` |
| Mac（Apple 芯片：M1、M2、M3、M4…） | `OnePieceVPN-1.0.0-macos-arm64.dmg` |

应用内不含服务器：你需要服务器提供者给你的 `ss://` 链接（或订阅 URL）。

## 安装

### Android
1. 在手机上下载 `.apk` 并打开。
2. 如有提示，允许从浏览器或文件管理器安装应用。
3. 打开 OnePiece VPN →「服务器」→「导入」→ 粘贴 `ss://` 链接（或扫描二维码）。
4. 在「首页」点击大按钮，并允许 VPN 请求。

### Windows
1. 运行 `.msi`。如出现“Windows 已保护你的电脑”，点击「更多信息」→「仍要运行」。
2. 打开 OnePiece VPN →「服务器」→「导入」→ 粘贴 `ss://` 链接。
3. 点击「连接」。首次使用时选择「以管理员身份重新启动」并点击「是」（Windows 只允许管理员创建 VPN 网络适配器）。

### Mac
1. 打开 `.dmg`，将 **OnePieceVPN** 拖入「应用程序」。
2. 打开应用。如被 macOS 阻止，前往「系统设置 → 隐私与安全性 → 仍要打开」。
3. 「服务器」→「导入」→ 粘贴 `ss://` 链接。
4. 点击「连接」并输入 Mac 密码（macOS 创建 VPN 需要密码）。
5. 如 macOS 询问是否允许使用钥匙串，点击「始终允许」。

## 说明

- **规则模式**（默认）：国内网站直连，其他走你的服务器。**全局模式**：全部走你的服务器。
- 服务器密码加密保存在你的设备上，不会发送到其他地方。
- 应用未经 Apple 或 Microsoft 签名，所以会出现上述提示。
- 基于 [sing-box](https://github.com/SagerNet/sing-box)（GPL-3.0）。
