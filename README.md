# AI Hunter 3D

A playable Windows build of **AI Hunter 3D**, a 3D survivor-vs-monster game. This repository is for sharing a standalone copy you can download and run. It does not include the Godot project or source.

## Download and run

1. Go to **[Releases](https://github.com/Smile638/AI-Hunter-3D/releases)** and download `AI Hunter 3D - Share.zip` from the latest release (v0.1). If you are browsing the repo files and see the zip there instead, download that.
2. Unzip the folder anywhere you like. Keep the `.exe`, `.pck`, and `.dll` files together.
3. Double-click **AI Hunter 3D.exe**.
4. If Windows SmartScreen appears, choose **More info**, then **Run anyway**. The build is unsigned, so that warning is normal.

**Requirements:** Windows 10 or 11, 64-bit.

## Play with a friend

You can play solo from the main menu. To play together:

- One person chooses **Host Game** and the **Direct / ENet** option (not Epic).
- The other chooses **Join** and enters the host's IP address, for example `192.168.1.20:24680`.
- The default port is **UDP 24680**. Allow the game through the Windows firewall if asked. On the same home network this is usually enough. Over the internet, the host may need to forward that port or use something like Tailscale.

## Epic Online

This copy does **not** include Epic Online Services keys, so Host/Join with Epic will not work out of the box. Solo, LAN, and direct IP still work. More detail is in `README_FRIEND.txt`.

## About this repo

The original project and any editor work stay separate. Settings and learning data from this build are stored only on your computer.
