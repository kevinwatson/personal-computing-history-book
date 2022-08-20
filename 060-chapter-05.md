### Chapter 5 - Apple Silicon

Apple has sold computers that have run on a variety of hardware architectures. PowerPC, Intel x86 and now Apple Silicon. Apple has always tightly-coupled their hardware and operating system, stating that this provides the best user experience.

Since the iPhone was introduced in 2007, Apple has been designing and selling both the hardware and software for their consumer devices. When a company like Apple keeps control of both the hardware and software, their teams can coordinate their efforts to create a device that is low power/battery efficient and also performant when needed.

In 2020 Apple introduced Apple Silicon. Apple computers had been running on Intel CPUs since 2006. The introduction of Apple Silicon was met with praise, even more so after consumers got their hands on them and benchmarked them against their older Intel counterparts.

To the everyday Mac user, Apple Silicon brings low power consumption (longer life fot laptops and less fan noise for desktops), faster processing, quicker response times when opening and using apps. The M1 chip was initially available in the lowest-end laptop and desktop models. For power users, video rendering, machine learning and other high-memory, CPU and GPU tasks could now be accomplished in nearly half the time on cheaper hardware.

The performance gains in Apple Silicon are because of an architecture design where the components have been combined on a single chip, known as system on a chip (SoC). In contrast, most computers have separate CPU, memory and hard drive, housed on a motherboard or logicboard. The upside of SoC is that data has less distance to travel between the memory and CPU which translates into faster speeds. The downside is that none of the components can be upgraded on a SoC.

Device makers have been making SoC devices for many years. Personal computing devices like smart phones and tablets have pushed the design of SoCs for more performance and better efficiency. Apple's approach with Apple Silicon is to provide speciailized chips for common tasks, combine them on a single chip and the result is both speed and efficiency.

Apple has taken its mobile device SoC architecture and in 2020 released a ramped-up version for macOS, its desktop operating system. Based on their mobile hardware designs, the M1 and M2 chip designs are based on the Apple A14 Bionic SoC, which powers the iPhone 12 smart phone.

The M lines detailed below are Apple's SoC strategy for devices that run both macOS and iPadOS.

## M1

The [M1 chip](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/) is available in the iPad Pro and a number of MacBooks and Mac desktops. The introductory Apple SoC platform, it combines all of the components below into a single chip.

Table 5-1

| Component/Feature | Description | New to Mac? |
|---|---|---|
| [Thunderbolt controller](https://support.apple.com/guide/mac-help/about-the-thunderbolt-ports-mh35952/mac) | Interface between external devices like a display or external hard drive | No |
| [T2 security chip](https://support.apple.com/guide/security/hardware-security-overview-secf020d1074/1/web/1) | Securely stores fingerprint data and secure boot options | No |
| Unified memory architecture (UMA) | High bandwidth and low latency translates to a faster device | Yes |
| [5 nanometer](https://www.forbes.com/sites/linleygwennap/2020/10/12/apple-moores-law-is-running-out/?sh=7ed55676529a) | The latest process for creating faster CPUs that use less electricity | Yes |
| 16 billion transistors in the CPU | | Yes |
| The CPU is split into 2 types of cores | 4 high-performance and 4 high-efficiency. The high-performance cores are used for CPU-intensive tasks and use more power (and drain a laptop battery faster), while the high-efficiency cores are used for less intensive tasks like browsing the web and use less power (and less battery) | Yes |
| 8-core GPU | Used for video playback and encoding | No |
| [Advanced power management](https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/) | Allocates tasks between the performance and efficiency CPU cores | Yes |
| High-bandwidth caches | Faster caches for the CPU, GPU, RAM and solid state drive | Yes |
| Cryptography acceleration | Speeds up security related tasks | No |
| [High-performance unified memory](https://www.macobserver.com/analysis/understanding-apples-unified-memory-architecture/) | Unified means shared memory, so instead of data being transferred from a CPU's memory bank to a GPU's memory bank and then back again, when both the CPU and GPU share the same memory banks, less time and bandwidth is required to process the task | Yes |
| Machine learning accelerators | Speeds up tasks like voice recognition and image processing | Yes |
| [Advanced display engine](https://www.notebookcheck.net/12-9-inch-iPad-Pro-mini-LED-display-is-as-custom-as-its-M1-SoC-but-early-issues-have-emerged.540770.0.html) | High-performance display management | Yes |
| [HDR video processor](https://support.apple.com/en-us/HT210980) | Dedicated chip for high dynamic range (HDR) video support | No |
| [Always-on processor (AOP)](https://machinelearning.apple.com/research/hey-siri) | Allows for background processing while in a near-suspended state, for example to allow Siri voice recognition to listen and wake the computer | Yes |
| High-quality image signal processor | Dedicated processor for real-time video capture | No |
| Low-power design | Designed for lower power consumption, beneficial for both battery powered and non-battery powered systems | Yes |
| [Secure Enclave](https://support.apple.com/guide/security/secure-enclave-sec59b0b31ff/web) | Used to store and process sensitive user data | No |
| High-performance NVMe storage | Nonvolatile memory express (NVMe) is a protocol that doesn't require a separate hardware controller to communicate with the CPU like other storage devices | No |
| Low-power video playback | Dedicated video decoding chips are used for video playback to use less power | Yes |
| High-performance GPU | | Yes |
| High-performance video editing | | Yes |
| Thunderbolt/USB 4 controller | | No |
| High-efficiency audio processor | | Yes |
| 16-core Neural Engine - 11 trillion operations per second | | Yes |
| HDR imaging | | No |
| Gen 4 PCI Express | | No |
| Performance controller | | Yes |
| Advanced silicon packaging | | Yes |


* Available in the MacBook Air
* Available in the iMac
* Available in the Mac mini

### M1 Pro

* 200GB/s memory bandwidth
* 32GB unified memory
* Dedicated ProRes accelerator
* 33.7 billion transistors
* 10 core CPU
* 8 high-performance cores
* 2 high-efficiency cores
* 70% faster than M1
* 16 core GPU
* 16 core Neural Engine
* Available in the 2021 14 and 16-inch MacBook Pros

### M1 Max

* 400GB/s memory bandwidth
* 64GB unified memory
* Dedicated ProRes accelerator
* 57 billion transistors
* 10 core CPU
* 32 core GPU
* 16 core Neural Engine
* Available in the Mac Studio

### M1 Ultra

* 114 billion transistors
* 128 GB unified memory
* 20 core CPU
* 64 core GPU
* 32 core Neural Engine
* Composed of 2 M1 Max boards that appears to be one chip by the operating system
* 800GB/s memory bandwidth
* Available in the Mac Studio

## M2

* Maxmimizing performance while minimizing power consumption
* Second generation 5 nm technology
* 20 billion transistors
* 100GB/s Unified Memory Bandwidth
* Up to 24GB unified memory
* 8 Core CPU
* 4 High performance cores
* 4 High efficiency cores
* 18% better performance over M1
* Up to 10 core GPU
* Up to 25% better graphics performance than the M1
* Secure Enclave
* Neural Engine - 15.8 trillion operations/sec
* Media engine
* 18% faster CPU
* 35% faster GPU
* 40% faster neural engine
* Up to 24 B LPDDR5 memory
* ProRes encode and decode
* 6k external display support
* 50% more memory bandwidth
* Available in the 2022 MacBook Air
* Available in the 2022 MacBook Pro 13-inch

## Resources

* https://en.wikipedia.org/wiki/System_on_a_chip
* https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/
* https://youtu.be/5AwdkGKmZ0I
* https://www.youtube.com/watch?v=q5D55G7Ejs8
* https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/
* https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/

[Next >>](070-chapter-06.md)
