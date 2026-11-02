# OnePiece VPN

**[⬇ Download](../../releases/latest)**

| Device | File |
|---|---|
| Android | `…-android.apk` |
| Windows | `…-windows-x64.msi` |
| Windows on ARM | `…-windows-arm64.msi` |
| Mac (Apple Silicon) | `…-macos-arm64.dmg` |

## Connect in 3 steps

You need a **QR code** or a **link** from the person who runs the server (it starts with `vless://` or `ss://`). Keep it private — it's your personal access.

### 1. Install the app
Download the file for your device from **[Releases](../../releases/latest)** and install it (see *Install* below for each device).

### 2. Add your server — choose one way

**A. Scan the QR code (phone)**
1. Open OnePiece VPN → **Servers → Import → Scan QR code**.
2. Allow camera access and point it at the QR code.
   *Got the QR as a picture?* Tap **Import → QR code from image** and pick it from your photos.

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
1. Open the `.apk` and allow installing apps if asked.
2. **Servers → Import** → **Scan QR code**, **QR code from image**, or **Paste from clipboard**. You can also just tap the link on your phone.
3. Tap the button on **Home** and accept the VPN request.

### Windows
1. Run the `.msi`. If Windows warns you: **More info → Run anyway**.
2. **Servers → Import** → paste your link.
3. **Connect** → **Restart as administrator** → **Yes** (first time only).

### Mac
1. Open the `.dmg` and drag **OnePieceVPN** into **Applications**.
2. Open it. If macOS blocks it: **Done** → **System Settings → Privacy & Security** → **Open Anyway**.
   If it says the app is damaged, run this in **Terminal**:
   ```
   xattr -dr com.apple.quarantine /Applications/OnePieceVPN.app
   ```
3. **Servers → Import** → paste your link.
4. **Connect** and enter your Mac password.

---

# 安装

**[⬇ 下载](../../releases/latest)**

## 三步连接

你需要服务器提供者发给你的 **二维码** 或 **链接**（以 `vless://` 或 `ss://` 开头）。请勿分享给他人。

### 1. 安装应用
在 **[Releases](../../releases/latest)** 下载适合你设备的文件并安装（各设备安装方法见下方）。

### 2. 添加服务器（任选一种）

**A. 扫描二维码（手机）**
1. 打开 OnePiece VPN →「服务器」→「导入」→「扫描二维码」。
2. 允许使用相机，对准二维码。
   *二维码是图片？* 点「导入」→「从图片识别二维码」，在相册中选择。

**B. 粘贴链接（手机或电脑）**
1. 复制收到的完整链接（微信、邮件等）。
2. 打开 OnePiece VPN →「服务器」→「导入」→「从剪贴板粘贴」。电脑上粘贴到输入框后点「导入」。

服务器会出现在「服务器」列表（例如 *OnePiece*），点击选中。

### 3. 连接
1. 回到「首页」，点击大按钮「连接」。
2. 手机上允许 VPN 请求；电脑上输入密码或允许管理员权限。
3. 打开 google.com 或 youtube.com 检查是否成功。

**连不上？** 确认复制了*完整*链接，试试切换到移动数据，或向提供者索取新的二维码。试用码用完 1 GB 后会停止。

### Android
1. 打开 `.apk`，如有提示允许安装。
2. 「服务器」→「导入」→「扫描二维码」、「从图片识别二维码」或「从剪贴板粘贴」。也可以在手机上直接点击链接。
3. 在「首页」点击按钮，并允许 VPN 请求。

### Windows
1. 运行 `.msi`。如有警告：「更多信息」→「仍要运行」。
2. 「服务器」→「导入」→ 粘贴链接。
3. 「连接」→「以管理员身份重新启动」→「是」（仅首次）。

### Mac
1. 打开 `.dmg`，将 **OnePieceVPN** 拖入「应用程序」。
2. 打开应用。如被阻止：「完成」→「系统设置 → 隐私与安全性」→「仍要打开」。
   如提示应用已损坏，在「终端」运行：
   ```
   xattr -dr com.apple.quarantine /Applications/OnePieceVPN.app
   ```
3. 「服务器」→「导入」→ 粘贴链接。
4. 「连接」并输入 Mac 密码。
