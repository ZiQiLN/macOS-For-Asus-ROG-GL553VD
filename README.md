# GL553VD MacOS

> I've moved to MacBook Pro, and I'm no longer maintaining this configuration, still... If somebody needs a help with Hackintosh I would be open to help.

Hackintosh configuration for **ASUS GL533VD** based on **OpenCore**. For stable version which is tested and working on **Catalina 10.15.3** refer to `streamline/stable` brach. This configuration is in progress and I do not recommend using it until there will be a `v2.0` release tag.

![cover](./assets/cover.jpg)


## Configuration Specification

Information about KEXTs used to build configuration for GL553VD.

### Hardware Status

Information about supported elements and these things that doesn't work on GL553VD.

| Device        |                        Name                         | working in macOS |
| :------------ | :-------------------------------------------------: | ---------------: |
| CPU           |         Intel® Core™ i7 7700HQ or i5 7300HQ         |              YES |
| Chipset       |            Intel® HM175 Express Chipset             |              YES |
| GPU           |               INTEL HD 630 - 2GB VRAM               |              YES |
| GPU           |               NVIDIA GeForce GTX 1050               |            NEVER |
| Audio         |                     ALC233(235)                     |              YES |
| Optical Drive |                   Super-Multi DVD                   |              YES |
| Keyboard      |                      ASUS AURA                      |          10.14.x |
| Card Reader   |                 RTS5229 PCI Express                 |              YES |
| WebCam        |                    USB2.0 HD UVC                    |              YES |
| Networking    | Realtek RTL8168H/8111H PCI Express Gigabit Ethernet |              YES |
| Networking    |                    Intel AC7260                     |          Depends |
| Bluetooth     |                    Intel AC7260                     |              YES |
| Battery       |                   4 Cells Battery                   |              YES |
| USB           |                     USB 3.0 Bus                     |              YES |
| HDMI          |                  INTEL HDMI HD 630                  |              YES |
| Touchpad      |                      ELAN 1200                      |              YES |

## Resources

External informations related for building MacOS on GL553VD.

- [ASUS AuraCore](https://github.com/hieplpvip/macrogaura/)

## Credits

- [Mohammadtaghi Farkhondekarsahih](https://github.com/MohammadtaghiFarkhondekar), for building intial versions of Clover and maintaining them.
