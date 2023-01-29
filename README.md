# Dell Inspiron 3650 Hackintosh
An OpenCore EFI folder for a Dell Inspiron 3650 OEM

<img width="685" alt="HackintoshSierra" src="https://user-images.githubusercontent.com/45981228/215347447-209b3406-738e-43c8-9240-ec747d57c942.png">

## Specs for this build

**CPU:** Intel Core i7-6700 3.4 GHz Quad-Core Processor<br>
**Memory:** 16 GB (2 x 8 GB) DDR4-2133 CL15 Memory<br>
**Storage:** Samsung 860 Evo 250 GB Solid State Drive<br>
**GPU:** AMD Radeon R9 360 OEM (2GB)

## Caveats
Unfortunately, the Radeon R9 360 OEM/Radeon R7 360 (exact same GPU) do not work with the Metal API. Apple switched the entire desktop interface to Metal on macOS 10.14 (Mojave), meaning anything newer than that OS will not work with this GPU. 

Additionally, opening any app that utilizes the Metal API on macOS 10.13 (High Sierra) causes the entire desktop to freeze. Therefore, the latest stable OS for this GPU is macOS 10.12.6 (Sierra), and all apps must use OpenGL to function properly.

<hr>
Special thanks to <a href="https://github.com/corpnewt">CorpNewt</a> for the custom SSDT-GPU-SPOOF.
