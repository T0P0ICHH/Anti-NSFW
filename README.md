# <div align="center">Anti-NSFW</div>
<img src="antinsfw.png" width="100%">

<div align="center"><a href="https://ant1nsfw.github.io" class="btn" target="_blank">Anti-NSFW Website</a> | <a href="https://t.me/ant1nsfw" class="btn" target="_blank">Telegram</a></div>

----

## What is Anti-NSFW?
Anti-NSFW is a project made by T0P0ICHH and RD that blocks NSFW (Not Safe For Work) content on your browser.
- 1700+ sites are already blocked by Anti-NSFW.
----
## How to install Anti-NSFW?
### Windows:
#### With Installer:
- Download the Installer [here](https://github.com/topoichh/Anti-NSFW/releases)
#### Manually:
1. Download [hosts file](https://github.com/topoichh/Anti-NSFW/blob/main/hosts).
2. Open `cmd` as Administrator.
3. Locate the folder the hosts file is in using `cd` command.
4. Run
```
move /y "hosts" "C:\Windows\System32\drivers\etc"
```
> [!WARNING]
> Restart your PC after installing Anti-NSFW if you use the Firefox browser.
### Android
#### Without root:
> [!CAUTION]
> Doing this may make some services not load (for example: Roblox, GitHub and YouTube).
1. Download the Android Release files [here](https://github.com/topoichh/Anti-NSFW/releases/tag/android-release-v1.0).
2. Unzip the `android-release-v1.0.zip` file.
3. Open the `android-release-v1.0` folder. (If there is an another folder with the same name, open it.)
4. Install `Virtual Hosts.apk`
5. Open the app and click the + icon.
![Screenshot_20250514_003946_Virtual Hosts](https://github.com/user-attachments/assets/192d0a2f-720d-472f-a616-d71a9fbdc438)
6.Turn on the "On startup" option, and open app Settings.
![Screenshot_20250514_004041_Virtual Hosts](https://github.com/user-attachments/assets/8c3e7639-f1c1-4a7c-b3e5-c53688fcb5c1)
7. Turn on "use net hosts" and then click the "remote hosts url" option.
![Screenshot_20250514_004135_Virtual Hosts](https://github.com/user-attachments/assets/692134dc-dace-4e9a-8c64-56fa42681ec4)
>[!TIP]
>You can also download the hosts file and select the hosts file you downloaded from the main screen, but using net hosts is better because it auto updates.
8. Paste this link in here:
```
https://raw.githubusercontent.com/topoichh/Anti-NSFW/refs/heads/main/hosts
```
![Screenshot_20250514_004145_Virtual Hosts](https://github.com/user-attachments/assets/7aae3c97-a592-4c92-8a0d-fd733b6b09a7)
9. Go back to the main screen and enable the very big switch.
![Screenshot_20250514_004235_Virtual Hosts](https://github.com/user-attachments/assets/61b084a5-145e-40ea-829b-128535cfede8)
> [!NOTE]
> I am NOT sure if you need to reboot after doing this but it didn't work for me (RD) after enabling the big switch in the app, but after a reboot it worked.
#### With Root:
Download the hosts file and move it to `/system/etc/` folder.
More info [here](https://xdaforums.com/t/editing-host-file.4345167/#post-87204127)
>[!TIP]
>Using the Without Root method is better because of auto updating.
### MacOS/Linux
#### Manually:
1. Download [hosts file](https://github.com/topoichh/Anti-NSFW/blob/main/hosts).
2. Locate the hosts file and move it to the /etc/ folder
> [!NOTE]
> Linux and MacOS Anti-NSFW installers are coming soon.
----
## How does Anti-NSFW work?

Anti-NSFW blocks NSFW websites via the hosts file.

### How hosts file works:

1. Your computer checks the hosts file first when you try to visit a website.
2. If found, it uses the listed IP address, skipping the normal internet lookup (DNS).
3. The hosts file overrides DNS.
### Location:

- Windows:
```
C:\Windows\System32\drivers\etc\hosts
```
- macOS/Linux:
```
/etc/hosts
```
### Uses:

- Testing websites locally.
- Blocking websites. (Which is used for the Anti-NSFW project obviously.)
- Custom names for network devices.

----
Sites not blocked? Not working? Or having other issues? They can be fixed, just create a new [Issue in GitHub](https://github.com/topoichh/Anti-NSFW/issues) and you will let us know :-)
> We are also looking for Android and Linux developers to help us make the project better! Do a pull request if you can help us
----
## Contributors: 2 
- [topoichh](https://github.com/topoichh) - Anti-NSFW Project Creator, Blocks the NSFW websites, created the [OG installer script](https://github.com/topoichh/Anti-NSFW/releases/tag/preview-v1.0), Website Developer.
- [RD](https://github.com/RD-github31) - Re-coded the Windows Anti-NSFW Installer. Explained what is Anti-NSFW and how does it work. Made a tutorial on how to install Anti-NSFW on different OSes (Operating systems). (Will create Linux Installer soon.), Website Developer
