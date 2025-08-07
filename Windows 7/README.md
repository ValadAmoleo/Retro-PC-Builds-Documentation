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
| **CPU**             | Intel Core 2 Quad Q9550                       | March 2008       | ✔️ Found             |
| **Motherboard**     | ASRock N7AD-SLI (nForce 740i)                 | 2008             | ✔️ Found             |
| **RAM**             | 4× 2GB DDR2                                   | N/A              | ✔️ Found             |
| **GPU (SLI)**       | NVIDIA GTX 295                                | Jan 2009         | ✔️ Arrived (£73)     |
| **GPU (SLI)**       | NVIDIA GTX 295 (second card)                  | Jan 2009         | ✔️ Ordered (£21)     |
| **GPU (Alt./PhysX)**| NVIDIA GTX 285                                | Jan 2009         | ✔️ Ordered (£15)     |
| **Sound Card**      | Creative X-Fi Elite Pro                       | Aug 2005         | ✔️ Arrived (£20)     |
| **Storage**         | 256GB SSD                                     | N/A              | ✔️ Found             |
| **Optical Drive**   | ZuluIDE (IDE bridge for legacy CD/DVD drives) | N/A              | 🕓 Planned (£100)    |
| **CPU Cooler**      | Thermalright Peerless Assassin 120 MINI       | N/A              | 🕓 Planned (test fit)|
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

  
---

## Setup Tips

- Document how to get Steam working.

---

## Screenshots

*(Optional section — include gameplay or desktop shots if desired)*

---

## License

All content in this repository is provided for personal archival and preservation purposes. See [LICENSE](../LICENSE) for details.
