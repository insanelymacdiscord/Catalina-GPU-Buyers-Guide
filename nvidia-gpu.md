# Nvidia GPUs

## Native nVidia GPUs

**Kepler Series \(GTX 6xx, 7xx\) Highest Supported OS: Current/Catalina**

Currently the only 100% native Nvidia architecture that works with Catalina. Users have reported issues with the GTX 650Ti, 660, 660ti but this is caused by a driver issue on Apple’s end by not supporting the GK106 core\(or quite poorly as the issue seems to be memory leakage which also affects real Macs\). Another issue with this generation is lower end products marketed as first generation Kepler are actually using a Fermi core but have identical counterparts running Kepler cores as well\(GF 116 vs GK 107 found in the GT 640\). **AND PLEASE NOTICE THAT GTX 745, 750 and ti VARIANTS ARE NOT INCLUDED, THEY'RE NOT KEPLER**

Supported cards:

Kepler Gen 2:

* GTX Titan \(GK 110 Maxwell core\)
* GTX Titan Black\(GK 110 Maxwell core\)
* GTX Titan Z \(One of the few dual GPU cards supported in MacOs\)
* GTX 780 Ti
* GTX 780
* GTX 770
* GTX 760 Ti
* GTX 760
* GT 740
* GT 730\(GK208 variant\)
* GT 720
* GT 710

Kepler Gen 1:

* GTX Titan \(GK 110 Maxwell core\)
* GTX Titan Black\(GK 110 Maxwell core\)
* GTX Titan Z \(One of the few dual GPU cards supported in MacOs, unfortunately was never truly utilized\)
* GTX 690\(Another dual GPU card compatible with macOS\)
* GTX 680
* GTX 670
* GTX 660 Ti
* GTX 660\(MUST BE RUNNING A GK 104 core, NOT GK 106\)
* GTX 650\(GK 107 core\)
* GT 640\(Kepler edition, GK 107/208 core\)
* GT 630\(Kepler edition, GK 107/208 core\)

Quadro:

* Quadro K6000
* Quadro K5200
* Quadro K5000
* Quadro K4200
* Quadro K2000D
* Quadro K2000
* Quadro K600
* Quadro K420
* Quadro 410

Needed kexts:

* [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
* [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)

## Unsupported nVidia GPUs

**Turing Series \(RTX 20xx, GTX 16xx\) Highest Supported OS:NONE**

Unfortunately, no support in any version of macOS as no drivers were ever written even for High Sierra. Not much else to add.

These cards include:

* Titan RTX
* RTX 2080 Ti
* RTX 2080 Super
* RTX 2080
* RTX 2070 Super
* RTX 2070
* RTX 2060 Super
* RTX 2060
* GTX 1660 Ti
* GTX 1660
* GTX 1650

Quadro:

* Quadro RTX 8000
* Quadro RTX 6000
* Quadro RTX 5000
* Quadro RTX 4000

**Volta Series Highest Supported OS:NONE**

The same idea as Turing, no drivers were ever written

These cards include:

* Titan V
* Titan V CEO Edition

Quadro:

* Quadro GV100

**Kepler Series\(GK 106 Variants\)**

GPUs running the GK 106 core have the unfortunate concequene of having a serious issue regarding VRAM leakage. This means that there's a high chance of disotrion and overall instabilty when running these GPUs which unfortuanty have no real solution as even installing web drivers has no affect. A list of GPUs with this core can be found [here](https://www.techpowerup.com/gpu-specs/nvidia-gk106.g186)

Second generation Kepler:

* GT 740

First generation Kepler:

* GTX 660
* GTX 650 Ti
* GTX 650
* GTX 645

Quadro:

* K4000

**Pascal Series \(GTX 10xx\) Highest Supported OS: High Sierra 10.13.6**

Well pretty sure most users know what going on with Pascal and Maxwell but I’ll just mention it quickly here. No support for these cards in Mojave/Catalina but macOS High Sierra 10.13.6 do support these cards with the combination of Nvidia’s somewhat shotty drivers and Lilu+WhateverGreen

Supported cards:

* GTX Titan X\(GP 102-400 Pascal core\)
* GTX Titan Xp\(GP 102-450 Pascal core\)
* GTX 1080 Ti
* GTX 1080
* GTX 1070 Ti
* GTX 1070
* GTX 1060
* GTX 1050 Ti
* GTX 1050
* GT 1030

Quadro:

* Quadro GP100
* Quadro P6000
* Quadro P5000
* Quadro P4000
* Quadro P2000
* Quadro P1000
* Quadro P620
* Quadro P600
* Quadro P400

Needed kexts:

* [Nvidia’s Web drivers](https://www.nvidia.com/download/driverResults.aspx/125379/en-us)
* [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
* [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)

**Maxwell Series \(GTX 9xx, 745, 750 and ti variant\) Highest Supported OS: High Sierra 10.13.6**

Same idea as Pascal, though the naming scheme is a bit odd as the GTX 745, 750 and 750ti are all Maxwell based even though they’re being marketed with the Kepler line so be wary when buying

Supported cards:

* GTX Titan X\(GM 200 Maxwell core\)
* GTX 980 Ti
* GTX 980
* GTX 970
* GTX 960
* GTX 950
* GTX 750 Ti
* GTX 750
* GTX 745

Quadro:

* Quadro M6000
* Quadro M5000
* Quadro M4000
* Quadro M2000
* Quadro K220
* Quadro K1200
* Quadro K620
* NVS 510

Needed kexts:

* [Nvidia’s Web drivers](https://www.nvidia.com/download/driverResults.aspx/125379/en-us)
* [Lilu.kext](https://github.com/acidanthera/Lilu/releases)
* [WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen/releases)

