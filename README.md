# Gear Kernel for Poco F1 (beryllium)

## Device specifications

Basic   | Specification
-------:|:-------------------------
SoC     | Qualcomm SDM845 Snapdragon 845
CPU     | Octa-core (4x2.8 GHz Kryo 385 Gold & 4x1.8 GHz Kryo 385 Silver)
GPU     | Adreno 630
Memory  | 6/8 GB RAM
Storage | 64/128/256 GB
Battery | Non-removable Li-Po 4000 mAh battery
Display | 1080 x 2246 pixels, 18:9 ratio, 6.18 inches, IPS LCD (~403 ppi density)
Camera  | 12 MP + 5MP, dual pixel PDAF, dual-LED (dual tone) flash
Release Date | August 2018

## Features
- Always updates with latest caf & linux tag.
- Compiled with proton clang.
- Slew of TCP Congestion Algorithms.
- Added devfreq boost.
- Default TCP is BBR.
- Disabled a lot of debug drivers that are not required in production builds.
- Drivedroid Support.
- Proper fast charging support according to temps.
- Sultan's perf critical IRQ framework to affine fast CPUs.
- Sultan's simple low memory killer.
- Check commit on git for more.



