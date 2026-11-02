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

## Connect in 3 steps

You need a **QR code** or a **link** from the person who runs the server (it starts with `vless://` or `ss://`). Keep it private — it's your personal access.

### 1. Install the app
Download the file for your device from **[Releases](../../releases/latest)** and install it (see *Install* below for each device).

### 2. Add your server — choose one way

**A. Scan the QR code (phone)**
1. Open OnePiece VPN → **Servers → Import → Scan QR code**.
2. Allow camera access and point it at the QR code.
   *Got the QR as a picture?* Tap **Import → From image** and pick it from your photos.

**B. Paste the link (phone or computer)**
1. Copy the whole link you received (from WeChat, email, etc.).
2. Open OnePiece VPN → **Servers → Import → Paste from clipboard**. On a computer, paste it into the box and click **Import**.

The server appears in **Servers** (named e.g. *OnePiece*). Tap it to select it.

### 3. Connect
1. Go to **Home** and tap the big **Connect** button.
2. Accept the VPN request (phone) or enter your password / allow admin (computer).
3. Open google.com or youtube.com to check it works.

**Not working?** Make sure you copied the *entire* link, try again on mobile data, or ask for a new QR code. Trial codes stop after 1 GB.

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
2. Open it. macOS will say Apple could not verify the app (it isn't signed by Apple). To allow it, once:
   1. Click **Done** on the warning (not *Move to Bin*).
   2. Open **System Settings → Privacy & Security** and scroll down to **Security**.
   3. Next to *"OnePieceVPN was blocked…"*, click **Open Anyway**, enter your password, then **Open Anyway** again.

   If it says the app **"is damaged and can't be opened"**, or there's no *Open Anyway* button, open **Terminal**,
   run this, then open the app again:
   ```
   xattr -dr com.apple.quarantine /Applications/OnePieceVPN.app
   ```
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

## 三步连接

你需要服务器提供者发给你的 **二维码** 或 **链接**（以 `vless://` 或 `ss://` 开头）。请勿分享给他人。

### 1. 安装应用
在 **[Releases](../../releases/latest)** 下载适合你设备的文件并安装（各设备安装方法见下方）。

### 2. 添加服务器（任选一种）

**A. 扫描二维码（手机）**
1. 打开 OnePiece VPN →「服务器」→「导入」→「扫描二维码」。
2. 允许使用相机，对准二维码。
   *二维码是图片？* 点「导入」→「从图片」，在相册中选择。

**B. 粘贴链接（手机或电脑）**
1. 复制收到的完整链接（微信、邮件等）。
2. 打开 OnePiece VPN →「服务器」→「导入」→「从剪贴板粘贴」。电脑上粘贴到输入框后点「导入」。

服务器会出现在「服务器」列表（例如 *OnePiece*），点击选中。

### 3. 连接
1. 回到「首页」，点击大按钮「连接」。
2. 手机上允许 VPN 请求；电脑上输入密码或允许管理员权限。
3. 打开 google.com 或 youtube.com 检查是否成功。

**连不上？** 确认复制了*完整*链接，试试切换到移动数据，或向提供者索取新的二维码。试用码用完 1 GB 后会停止。

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
2. 打开应用。macOS 会提示“无法验证”该应用（因为它未经 Apple 签名）。只需允许一次：
   1. 在提示框中点击「完成」（不要点「移到废纸篓」）。
   2. 打开「系统设置 → 隐私与安全性」，向下滚动到「安全性」。
   3. 在“已阻止 OnePieceVPN……”旁点击「仍要打开」，输入密码，再点一次「仍要打开」。

   如果提示应用**“已损坏，无法打开”**，或者没有「仍要打开」按钮，请打开「终端」，运行以下命令，然后重新打开应用：
   ```
   xattr -dr com.apple.quarantine /Applications/OnePieceVPN.app
   ```
3. 「服务器」→「导入」→ 粘贴 `ss://` 链接。
4. 点击「连接」并输入 Mac 密码（macOS 创建 VPN 需要密码）。
5. 如 macOS 询问是否允许使用钥匙串，点击「始终允许」。

## 说明

- **规则模式**（默认）：国内网站直连，其他走你的服务器。**全局模式**：全部走你的服务器。
- 服务器密码加密保存在你的设备上，不会发送到其他地方。
- 应用未经 Apple 或 Microsoft 签名，所以会出现上述提示。
- 基于 [sing-box](https://github.com/SagerNet/sing-box)（GPL-3.0）。
