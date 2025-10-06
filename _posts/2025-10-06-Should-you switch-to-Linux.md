---
layout: post
title: Should you switch to Linux?
subtitle: 
tags: []
author: Sean
---

Windows 10 support is ending, your old machine is dying, and everything feels sluggish. I was facing this exact dilemma, this is my journey to Linux.

Ask yourself about your computer use:
-  Do you mostly just use the web browser?
-  Do you want to revive aging hardware?
- Do you dislike the strings that come with Windows?
- Do you like an occasional challenge and importantly don't mind doing some troubleshooting?

## My Mum's laptop was dying.

My parents were about to spend around $2000 on a PC. She mostly uses a web browser, word processor, solitaire and it's variations. Luckily I'd been reading about the end of support for Windows 10 coming up for older machines. So it was on my mind that I could repurpose an old laptop I had my parents to use instead. I thought it would be worth installing a different OS (operating system) and seeing if she could get used to it. I did a little Googling, many people recommended Linux Mint for Windows users due to its similar look.

I changed a setting for the laptop to look the USB drive for an OS when powered on. 
Without this it would automatically get the installed Windows OS from the hard drive.
I put Linux Mint on a USB and started it up. I made sure the track pad, Wi-Fi, sound and USB ports all worked. Everything was in order.

Then I went ahead with the full install that would overwrite the Windows installation on the hard drive. In less that 15 minutes it was ready to go. I set it to update automatically in the background, Firefox, libre office and a card game (with 200+ variations) on the desktop and had a try. Compared to its former sluggish state it was like a new machine for these tasks. 

From my calculations the computer would have been from the later Windows 7 (July 22, 2009 release date for hardware manufacturers) or Windows 8 (August 1, 2012) era so it wasn't designed with Windows 10 in mind. Then a week later I handed it over to my Mum.

## My gaming PC and the Windows apocalypse.

This success pushed me to try Linux on my gaming PC. I bought the components before COVID 19 was considered a pandemic. One of the components didn't have a feature required to get the upgrade. I probably could have gotten Windows 11 to work on it, but there was a chance it would become unstable.

But I'd read about advances that had been made in the last few years running games in Linux. Going in I was worried about issues around the hardware of my computer. But being slightly older hardware meant people had made drivers for it.
### Problems   
In my initial searches two OSs came up. Next night I had free I made live USBs of both of them. **Ubuntu**, one of the most widely used by consumer versions of Linux. I'd used it before, running it in tandem with Windows on a different laptop. It didn't work properly with my graphics card straight away. I didn't like the way the desktop looked either. 

![GNOME desktop](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Ubuntu_20.04_GNOME_desktop.jpg/330px-Ubuntu_20.04_GNOME_desktop.jpg)

Both things that I probably could have fixed, but I moved on just to check out the other options. With Nobara, still there were driver issues with my graphics card. I just didn't like the feel of it after using Mint's "Cinnamon" desktop environment.

![Nobara desktop](https://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/Desktop_Nobara.png/330px-Desktop_Nobara.png)

And I'd have to get used to slightly different set of BASH commands. By that time, it was getting a little late for a work night. I left it without changing anything, hoping a better solution would appear. 

### The solution
A bit more Googling gave me my answer. POP!\_OS, an operating system that is maintained by system76.

![Nobara's Desktop](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5f/Apps_Pop%21_OS_21.10.png/960px-Apps_Pop%21_OS_21.10.png)

They sell specialised computer hardware but also make the OS available for free. 

I liked it because it is built on Ubuntu which has a large userbase. Uses a dock at the bottom of the screen. I'm already used to Ubuntu flavour of BASH commands. I decided I was onto a winner, it worked straight away with my graphics card. Other hardware checked out too. Very responsive at the start up because of all of the Windows related junk I've been used to. Proton ran my Steam games library, Lutris handled non-Steam titles.
### Input issues

The road block came when my XBOX controller didn't register as an input device for the computer. Instead of Googling it straight away I improperly used Chat-GPT exclusively to try and fix the issue. Not my smartest idea. For 45 dumbfoundingly frustrating minutes it lead me willingly down the garden path. I'd run BASH commands that would attempt to install drivers that were already installed. If I pointed out a flaw in it's logic, I was lavishly praised and we'd take a different course of action.

I know large language models aren't made for this type of process, but because they can talk I still offer my problems up to them like some sort of oracle or shrine. As usual it was very convincing but ultimately wrong, digging it's heels in with it's original conclusion and doubling down at every step.

I had to do it the old fashioned way and search for the answer myself on Reddit. I restarted the computer and it started working. After this, to my surprise it just worked. No issues all my games are compatible and my saves are backed up with Steam

## Should you switch?

### The verdict.
Yes, Linux has matured to a point where it's a viable option for most users. You should switch if you:

- Need to **revive old hardware** (like my Mum’s "new" laptop).
- Have a PC that **can’t run Windows 11** but is still good.
- Mostly use a web browser and office software.
- Don't mind a _small_ amount of troubleshooting.

**But if you rely on specialized tools,** consider sticking with Windows or exploring Apple products.
### Wrap up for my story
Linux revived a 2009 Alienware for my mum and made my gaming PC better than ever with Pop!\_OS. In hindsight, it was actually satisfying to solve the controller problem. 

My PC now runs better with faster boot times, no bloat, even the LEDs stay off unless I enable them. To my surprise It has been about a month since I gave my mother the laptop, she is actually getting used to using it.
## Appendix:

### Useful links
Sites:
ProtonDB, A database of games that work with Proton along with information about hardware compatibility.

Subreddits:
In my opinion, best to search via Google for these.

r/linux_gaming, r/linux_for_noobs and r/pop_os .

### PC Parts for those interested:

- CPU (Central Processing Unit) - **AMD Ryzen 5 3600:** 6-Core / 12-Thread, 3.6 GHz (Boost up to 4.2 GHz)
- GPU (Graphics Processing Unit) - **Gigabyte Radeon RX 590:** 8GB GDDR5 VRAM
- Motherboard - **ASUS TUF Gaming X570-Plus (Wi-Fi):** AMD X570 Chipset, PCIe 4.0, Wi-Fi 5 (802.11ac)
- RAM (Random Access Memory) - G.Skill Trident Z RGB:** 16GB (2x8GB) DDR4-3600

### Helpful BASH commands

If you are reading this and are having issues with XBOX controllers and Steam on POP_OS!, this is what I used.

Make sure everything's up to date first.

`sudo apt update && sudo apt upgrade`

Install steam on the command line rather than the app store.

 `sudo apt install steam`
 
Ensure steam has its drivers for hardware.

`sudo apt-get install steam-devices`

And making sure that in the Steam settings to turn on support for the type of controller you are using.

Rebooting the computer.

Failing this

-------------------
The following commands that Chat GPT gave me get some details on my situation and may help you if you have a different problem.

To list the USB devices.

`lsusb`

To see what is happening when you plug in your device.

`dmesg`

Then possible solutions may be to install

`xpad`

Or 

`xpadneo`

drivers.

### Last remarks
After all of this, my used 2016 ThinkPad I bought from my employer seems to be angling for a hard drive and OS upgrade.
