# Vita Ports Scanner

This project uses [quark](github.com/lp1dev/quark), which is an early-stage JS/HTML framework I built to develop PS Vita (and GNU/Linux-compatible) apps.

It requires an **index.html** and **style.css** file as a starting point, all of the source code related to the project is present in those two files!

It is a TCP hosts/ports scanner for local networks, which for each scan type 3 different scan levels.

---

## Install

To install, you will need a jailbroken PS Vita. Then, use either your SD card (if you use SD2Vita) or [VitaShell](https://github.com/TheOfficialFloW/VitaShell)'s FTP server to add the .vkp file of the [latest release available](https://github.com/lp1dev/vita_ports_scanner/releases) on this GitHub repo to your console.

Then, install it using [VitaShell](https://github.com/TheOfficialFloW/VitaShell).

---

## Build

If you want to modify the project and see how it works by yourself, you will need to setup [vitasdk](https://vitasdk.org/) and [quark](github.com/lp1dev/quark) on your machine.

Then, create a **projects** folder in your quark directory and clone this repository in it.

If quark is correctly setup, you can run the **build.sh** script to build a new version of this application!
