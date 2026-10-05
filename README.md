# Linux distribution Order of Business
> [!NOTE]
> Windows is abysmal to the point where I'm writing this in case I ever need to migrate to GNU/Linux once and for all.

- [Windows 11](#windows-11)
- [GNU/Linux](#gnulinux)

---
## [Windows 11](https://github.com/nhantrichuyenanh/win-11-ofb "nhantrichuyenanh")
It's for everyone, from the casual home user to the office user to the competitive gamer to an IT admin. So everyone's experience using Windows 11 is relatively the same. In addition, many corporations use it, so it has to be backward compatible with old software. Because Windows 11 has to accommodate many needs, it's often unstable and buggy.

So it's no surprise Windows is known for having its fair share of downsides:
- **Major**:
  - bloatware and ads everywhere
  - telemetry and spyware kicks in as soon as you connect to the internet  
  - resource hungry even at idle state  
  - limited UI customization
  - [UI inconsistencies](https://ntdotdev.wordpress.com/2023/01/01/state-of-the-windows-how-many-layers-of-ui-inconsistencies-are-in-windows-11/ "NTDEV")
  - dark mode inconsistency <sup>after a decade, it's finally happening in build 26200.5751 (Dev) / 26120.5751 (Beta)</sup>
  - not completely free, requiring product key  
- **Minor**:
  - unnecessary preinstalled system/administrative tools only technical users use  
  - legacy components like *Phone and Modem (from Windows 95/98)*, and *Windows Problem Reporting* for example
  - half-baked Settings, frequently redirecting to Control Panel dialogs for advanced configurations <sup>though Microsoft is making strides in migrating them to Settings</sup>
  - feature duplications such as *Disk Cleanup* - *Storage Sense*, *Run dialog* - *Windows Search*, *[MSRT](https://www.youtube.com/watch?v=PXTsuda6cvI&t=30s "ThioJoe")* - *Windows Defender*, etc...  

All of these drawbacks can be fixed with third-party tools.

---
## GNU/Linux
Meanwhile, some distros are for newly migrated users from Windows, some for competitive gamers, and some for power users, each with different desktop environments. So everyone's experience using GNU/Linux is vastly different. In addition, many corporations use it for their servers, so it has to be lightweight.

- Because GNU/Linux (Unix-like) is extremely diverse and fundamentally different from Windows (MS-DOS), it can be challenging to fully embrace it, such as:
  - navigating desktop environments
  - understanding concepts like *package managers* and *[FHS](https://wikipedia.org/wiki/Filesystem_Hierarchy_Standard "Wikipedia")*
  - doing common activities like installing/uninstalling apps and updating system via the terminal emulator
  - learning system and admin tools that comes preinstalled or needed to be installed

- I still use Windows 11 on my PC because:
  - I have to research which distro/DE to pick and which alternative to download should software isn't available on Linux
  - installing configuring, setting up, and learning to use the tech (distro, DE, software) takes up so much time, effort, patience and willpower
  - all the hotkeys, directory structure, system applications, OS security, and GUI on GNU/Linux are radically different to Windows <sup>aka the learning curve</sup>
  - it is fixable, so why bother switching to GNU/Linux in the first place?

Here're some websites to get started: (I personally peruse them so they're pretty trustworthy)
- [Linux for Beginners](https://christitus.com/linux-for-beginners "Chris Titus Tech")
- [Windows to Linux for Powerusers](https://christitus.com/windows-to-linux "Chris Titus Tech")
- [Linux explained](https://www.youtube.com/watch?v=vpdnMPDEBrg "Awesome")
- [Linux Journey](https://labex.io/linuxjourney "labex.io")
- [Ultimate Beginners Linux Ricing Guide](https://www.youtube.com/watch?v=CRLEfo_4X0M "Xigo")
- [DistroSea](https://distrosea.com "basilky")
---

P.S. I successfully installed **Arch Linux (Cinnamon)** on an old 2007 DELL laptop, but didn't on a 2013 SONY one. So for the latter, I installed **Linux Mint**, which was successful but it ran painfully slow, so I ultimately installed **EndeavourOS (KDE Plasma)**.

---
# Windows <=> Linux
| Windows | Linux |
|---|---|
| `C:\` | `/` |
| `C:\Users\Name` | `/home/name` |
| Explorer | File manager |
| Task Manager | Process viewers such as `top`/`htop` |
| Device Manager | Kernel/device subsystems + tools |
| Windows Services | systemd services |
| Registry | No direct equivalent |
| `.exe` | No single universal equivalent |
| `.msi` | No direct universal equivalent |
| Microsoft Store | Repositories/package managers |
| Control Panel/Settings | Multiple configuration interfaces |
| Administrator | root / `sudo` |
| `%APPDATA%` | Various config directories, commonly under `~/.config` |
| `C:\Windows\System32` | No direct equivalent; `/usr`, `/etc`, `/var`, etc. have different purposes |
| Windows Update | Distribution/package updates |
