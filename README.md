# Anti-NSFW
----
<img src="antinsfw.png" width="100%">

<p><a href="https://ant1nsfw.github.io" class="btn" target="_blank">Official Anti-NSFW site</a></p>

----

## What is Anti-NSFW?
Anti-NSFW is a project made by T0P0ICHH and RD that blocks NSFW (Not Safe For Work) content on your browser.
- 1000+ sites are already blocked by Anti-NSFW.
----
## How to install Anti-NSFW?
### Windows:
#### With Installer:
- Download the Installer [here](https://github.com/topoichh/Anti-NSFW/releases)
#### Manually:
1. Download [hosts file](https://github.com/topoichh/Anti-NSFW/blob/main/hosts).
2. Open `cmd` as Administrator.
3. Locate the folder the hosts file is in using `cd` command.
4. Run `move /y "hosts" "C:\Windows\System32\drivers\etc"`.
5. Restart your PC if you use the Firefox browser.
### MacOS/Linux
#### Manually:
1. Download [hosts file](https://github.com/topoichh/Anti-NSFW/blob/main/hosts).
2. Locate the hosts file and move it to the /etc/ folder
----
## How does Anti-NSFW work?

Anti-NSFW blocks NSFW websites via the hosts file.

### How hosts file works:

1. Your computer checks the hosts file first when you try to visit a website.
2. If found, it uses the listed IP address, skipping the normal internet lookup (DNS).
3. The hosts file overrides DNS.
### Location:

- Windows: C:\Windows\System32\drivers\etc\hosts
- macOS/Linux: /etc/hosts

### Uses:

- Testing websites locally.
- Blocking websites. (Which is used for the Anti-NSFW project obviously.)
- Custom names for network devices.

----
Sites not blocked? Not working? Or having other issues? They can be fixed, just create a new [Issue in GitHub](https://github.com/topoichh/Anti-NSFW/issues) and you will let us know :-)
> We are also looking for Android and Linux developers to help us make the project better! Do a pull request if you can help us
----
## Contributors: 2 
- [topoichh](https://github.com/topoichh) - Anti-NSFW Project Creator, Blocks the NSFW websites, created the [OG installer script](https://github.com/topoichh/Anti-NSFW/releases/tag/preview-v1.0).
- [RD](https://github.com/RD-github31) - Re-coded the Windows Anti-NSFW Installer. (Will create Linux Installer soon.)
