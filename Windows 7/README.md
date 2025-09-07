# Windows 7 Retro Gaming Build

This machine is part of my personal retro PC project, tailored for running Windows 7-era titles at native performance on real hardware. It’s built with performance and compatibility in mind for late 2000s gaming.

## History

I [found out that Batman Arkham Asylum seems to have PhysX issues on any GPU after the Tesla architecture](www.resetera.com/threads/rtx-50-series-gpus-have-dropped-support-for-32-bit-physx-many-older-pc-games-are-impacted-mirrors-edge-borderlands-etc.1111698/page-9#post-136180425) and decided that I wanted to start having PC builds to support specific eras of gaming.

---

## Mission Statement

To create a PC that runs Batman Arkham Asylum, with PhysX, at 1920x1080 (or Full HD) resolution.

## Build Specs


| Component            | Model                                         | Release Date     | Status              |
|---------------------|-----------------------------------------------|------------------|---------------------|
| **CPU**             | Intel Core i7-4770K                           | Jun 2013         | ✔️ Found             |
| **Motherboard**     | Gigabyte GA-Z87X-UD3H                         | Aug 2013         | ✔️ Found             |
| **RAM**             | 2× 8GB DDR3                                   | N/A              | ✔️ Found             |
| **GPU (SLI)**       | NVIDIA GTX 295                                | Jan 2009         | ✔️ Arrived (£73)     |
| **GPU (SLI)**       | NVIDIA GTX 295                                | Jan 2009         | ✔️ Arrived (£21)     |
| **GPU (Alt./PhysX)**| NVIDIA GTX 285                                | Jan 2009         | ✔️ Arrived (£15)     |
| **Sound Card**      | Motherboard Realtek HD Audio                  | N/A              | ✔️ Arrived (£20)     |
| **Storage**         | 256GB SSD                                     | N/A              | ✔️ Arrived (w/ Mobo) |
| **Optical Drive**   | ZuluIDE (IDE bridge for legacy CD/DVD drives) | N/A              | 🕓 Planned (£100)    |
| **CPU Cooler**      | Cooler Master X Dream i117                    | N/A              | ✔️ Arrived (£9)      |
| **Power Supply**    | EVGA Supernova 1000W G3                       | 2016             | ✔️ Found             |

---

## Reasoning

- The NVIDIA GTX 295 is the most powerful card using the Tesla architecture but it is a single card SLI.  Having two makes it into a Quad SLI system.  This brings it's own issues but I always fantasised about having a Quad SLI setup in the late 2000s and the second GTX 295 was very reasonably priced.
- I'd already purchased a very cheap GTX 285 before buying the first GTX 295.  It's actually faster than a GTX 295 in single card mode so I thought it'd be good to keep it in as a PhysX GPU but also available as a rendering GPU.

---

## Why Not Windows 10?

While Windows 10 would have been fine for this build I decided to go with Windows 7 to be more era appropriate.  It also means that if there are any games with Windows 10 quirks I can use this build for those.

---

## Ideal Games for This Build

- Batman Arkham Asylum

---

## Issues Encountered

- The ASRock N7AD-SLI nForce 740i, that I already had from my PC in the late 2000s, worked fine with the single GTX 295.  But as soon as I added a second GTX 295 performance tanked.  I believe this is because the cards were being starved off bandwidth.
- Unfortunately after buying the nForce 790i I was still getting very similar results in the Batman Arkham Asylum Scarecrow level with PhysX on high (drops to single digit FPS).  The frame rate would drop to around 18fps.  I tried multiple driver versions, PhysX versions, combinations of SLI, Quad SLI and single GPU rendering.  I even added the GTX 285 in to use as a dedicated PhysX card. All had the same result.  This means it's pointing at the Intel Core 2 Extreme QX9650 being the problem.  So will have to look into going more modern with the CPU/Motherboard.
- In the end I had to swap out the CPU & Motherboard.  It's definitely a CPU limitiation with the number of PhysX objects on the Scarecrow level.  Moving to a Intel Core i7 4770K eased this but did not completely solve it, I now get drops to 18fps.  There is no feature loss in moving from a QX9650 to 4770K, but there is feature gain (SSE4.2 & HyperThreading).  So will need to check for any quirks that are not period accurate.
- Also of interest is that the DDR3 RAM from the XFX nForce 790i ULTRA motherboard did not work in the Z87X motherboard.
- The Thermalright Peerless Assassin 120 MINI can not be forced to fit a Socket 775.
- I removed the Creative X-Fi Elite as the GTX 285 was covering the only PCI slot on the board.  Currently just using the onboard Realtek HD Audio, which is fine and supports 7.1 out.  Doesn't seem like any PCI-e Sound Blaster's support 7.1 so will likely stick with the onboard.

  
---

## Setup Tips

- For Steam I use this [Steam (Mar 6th 2024)](https://archive.org/details/Steam_Windows_7) and then create a [custom Steam.CFG file](https://blog.lightwo.net/steam-client-downgrades-survival-kit.html#editing-steamcfg).
- Use [Legacy Update](https://legacyupdate.net/).  Install this first and make sure Windows 7 is up to date.

---

## Screenshots

*(Optional section — include gameplay or desktop shots if desired)*

---

## License

All content in this repository is provided for personal archival and preservation purposes. See [LICENSE](../LICENSE) for details.
