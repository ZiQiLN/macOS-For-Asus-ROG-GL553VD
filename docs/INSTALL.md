# Installation Notes on MacOS

This installation guide covers MacOS installation from another MacOS, installation from Windows is also possible but will be not covered in this document. I'm lazy bitch tbh, and personally I would like to do ICC in World of Warcraft instead writting this so I'll try to keep it short.

### Reqiurements

- Mackintosh
- 8GB+ Pendrive

## Table of Contents

### Theory

#### Why not tonymacx86?

> TL;DR Tonymacx86 love to steal open-source code from programmers without credits to creator, personally I don't have trust to them and I do not recommend their tools additonally it's hard to debug problems when using tonymacx86's tools. Guides are fine.

Few people are aware of bad fame of tonymacx86, it's still a good resource for finding information because it's probably most popular forum for hackintoshers.

tonyxmacx86 got fame from using open-source projects in their software and releasing their tools as closed-source. As a example we can take conflict with Conti (creator of MyHack, tool that was used in times of 10.6-10.9) first version of MultiBeast was just copied version of Conti's MyHack, whole situation resulted in closing access to MyHack's code.

That was not one-time action, In 2011 tonymacx86 stole source code of legacy kernel developed by qoopz, nawcom, AnV and other developers, which was allowing users to run OSX on machines with AMD processors and older Intel processors.

https://prasys.info/2011/01/tonymac-seriously/

There was laso problem with Lnx2Mac driver for Realtec network cards (promoted by tonymacx86), which was breaking GPL license (source code of drivers was never released), at the same time containing in code ported linux drivers released on GPL. IIRC Mieze, developer who written a lot of networking drivers for MacOS (all of them was linux driver ports as well, but their code was released) got banned on tonyxmacx86 forum, because he was critic to Lnx2Mac for not releasing source code (which is required in GPL License).

In middle of 2012 and 2013 there was another uncomfortable situation associated with RampageDev (author of multiple guides on tonymacx86 forum), which leaved community because conflict with admins, which have favourized Gigabyte motherboards. RampageDev decided to delete his files, guides published on tonymacx86 and publish them on his own site. tonymacx86 send DCMA to RampageDev.

On tonymacx86 forum everybody can find a lot of good guides (ex. RehabMan's guides), but tools developed by tonymacx86 (UniBeast, MultiBeast) which are useless (Unibeast copies installator and installs Clover, MultiBeast installs unsigned KEXTs to /System/Library/Extensions and requires disabled SIP - additionaly installs AppleHDA, which usually is not from same system version, instead using better solutions for patching on the fly like AppleALC). By this reason and pass of time discussion about UniBeast and Mulitbeast on InsanelyMac is bannable.

That's not all about tmac, Admin of `/r/hackintosh` added few fundamentall words on this topic.

> Beast tools have been created to facilitate the installation process. By doing this they hide the entire creation process from the end user. If (better to use when here) something goes wrong - our end user has no idea what has been installed, where, which way and how to fix it. He doesn't know what a bootloader is, how to configure it, he doesn't know what kexts are and much more.
>
> Of course, manual macOS installation requires more effort - but we don't use the original poppies here. Installing macOS on unsupported hardware requires effort. In addition, for something as specific as putting Hackintosh - choosing all-in-one tools is not the best solution.
>
> These are my personal reasons for not using or recommending these tools to others.
>
> [Orginal Post](https://www.reddit.com/r/hackintosh/comments/6enbsf/differences_between_tonymac_insanelymac_others/dibm4pu)

According to this answer, we can say that tmac tools are same as iAtkos, Hackintosh.Zone an so on. These tools usually hide installation process which doesn't allow us to find source of our error, uses old drivers which can ruin our installation, stability or system functionality. Tools like that additionally doesn't provide source of drivers which is confusing for creators of these drivers.

Personally I agree with InsanelyMac and simillar forums, and I do not use tools "developed" by tmac.

#### Reporting problems

> TBC

### Preparing to Installation

> TBC

#### Getting Specification

> TBC

```
Motherboard (or Laptop Model):
CPU:
GPU:
---
RAM:
Network (Ethernet):
WiFi:
Audio:
```

##### Specification on Windows

AIDA64, and here we go.

##### Specification on GNU/Linux

`lshw -short`, essa.

### Downloading MacOS

### Preparing Pendrive

### Installing System

#### Clover installation

#### Configuration of Clover

#### Kexts

#### Installation

### Post-Installation

---

### **Credits**

Guide was build with informations contained in polish blogs such as [`hackintosh-polska.pl`]() and [`hackintosh.com.pl`](), and worldwide resources contained at [`/r/hackintosh`](), [`tonymacx86`](), [`olarila`]().
