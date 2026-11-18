AI Hunter 3D - playable copy
============================

This is a standalone Windows copy you can unzip and run. It does not need the Godot editor.

Requirements
------------
- Windows 10 or 11, 64-bit

How to play
-----------
1. Put this whole folder anywhere you like (keep the .exe, .pck, and .dll files together).
2. Double-click "AI Hunter 3D.exe".
3. If Windows SmartScreen appears, choose More info, then Run anyway. The game is unsigned, so that warning is normal.

You can play solo from the main menu. You can also play with a friend over the same network, or over the internet with a direct IP (or a tool like Tailscale):

- One person chooses Host Game and the Direct / ENet option (not Epic).
- The other chooses Join and enters the host's IP address, for example 192.168.1.20:24680.
- The default port is UDP 24680. Allow the game through the Windows firewall if asked. If you are not on the same home network, the host may need to forward that port or use Tailscale.

Epic Online (optional)
----------------------
This copy does not include Epic Online Services keys, so Host/Join with Epic will not work out of the box. Solo, LAN, and direct IP still work.

If the person who gave you this game later sends a file named eos_keys.cfg, put it here and restart the game:

    %APPDATA%\AIHunter3D-Share\eos_keys.cfg

Do not post that file publicly; it contains a secret. You can paste the path above into File Explorer's address bar to open the folder (it is created the first time you run the game).

Settings and saved data
-----------------------
Your settings and any learning data stay on your computer in:

    %APPDATA%\AIHunter3D-Share\

They are not shared with anyone else's copy, and they will not overwrite the original project's data if you also have the game open in the Godot editor.

F11 toggles fullscreen. Volume, V-Sync, and other options are in Settings.
