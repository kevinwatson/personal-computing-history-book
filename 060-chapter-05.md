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

The [M1 chip](https://www.apple.com/newsroom/2020/11/apple-unleashes-m1/) is available in the iPad Pro and a number of MacBooks and Mac desktops. The introductory Apple SoC platform, it combines all of the components in table 5-1 below into a single chip.

Soon after the M1 chip was introduced, consumers could purchase a 2020 Macbook Air, iMac or Mac Mini with the M1. With its newer features, the M1's low price, low power consumption and fast performance for many tasks impressed critics and users alike.

Below is a table of features built into the M1 chip.

_Table 5-1_

| Component/Feature | Description | New to Mac? |
|---|---|---|
| [Thunderbolt controller](https://support.apple.com/guide/mac-help/about-the-thunderbolt-ports-mh35952/mac) | Interface between external devices like a display or external hard drive | No |
| [T2 security chip](https://support.apple.com/guide/security/hardware-security-overview-secf020d1074/1/web/1) | Securely stores fingerprint data and secure boot options | No |
| Unified memory architecture (UMA) | High bandwidth and low latency translates to a faster device | Yes |
| [5 nanometer](https://www.forbes.com/sites/linleygwennap/2020/10/12/apple-moores-law-is-running-out/?sh=7ed55676529a) | The latest process for creating faster CPUs that are more efficient | Yes |
| 16 billion transistors in the CPU | | Yes |
| 2 types of CPU cores | 4 high-performance and 4 high-efficiency. The high-performance cores are used for CPU-intensive tasks and use more power (and drain a laptop battery faster), while the high-efficiency cores are used for less intensive tasks like browsing the web and use less power (and less battery) | Yes |
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
| High-performance NVMe storage | Nonvolatile memory express (NVMe) is a protocol that doesn't require a separate hardware controller to communicate with the CPU | No |
| Low-power video playback | Dedicated video decoding chips are used for video playback to use less power | Yes |
| High-performance GPU | Used for rendering video, 3D gaming, and machine learning tasks | Yes |
| High-performance video editing | A result of shared memory, high-bandwidth caches, NVMe storage and an 8-core high-performance GPU | Yes |
| Thunderbolt/USB 4 controller | | No |
| High-efficiency audio processor | | Yes |
| 16-core Neural Engine - 11 trillion operations per second | | Yes |
| HDR imaging | | No |
| Gen 4 PCI Express | | No |
| Performance controller | | Yes |
| Advanced silicon packaging | | Yes |

### M1 Pro

The M1 Pro system on a chip was announced ??? and was made available in the 2021 14 and 16-inch MacBook Pro laptops. It provides additional memory bandwidth, twice as many transistors, more high-performance CPU cores and twice as many GPU cores as the original M1. Apple reported that the M1 Pro is up to 70% faster than the M1 for many common tasks.

_Table 5-2_

| Component/Feature | Description |
|---|---|
| 200GB/s memory bandwidth | Bigger pipes for data transfer between RAM and the CPU and GPU cores |
| 32GB unified memory | Double the amount available in the M1 (M1 x 2) |
| Dedicated ProRes accelerator | |
| 33.7 billion transistors | M1 x 2 |
| 10 core CPU | Two more high-performance cores than were available in the M1 |
| 16 core GPU | M1 x 2 |
| 16 core Neural Engine | Same as the M1 |

### M1 Max

The M1 Max SoC was announced ??? and available for purchase in the 2022 Mac Studio desktop computer.

_Table 5-3_

| Component/Feature | Description |
|---|---|
| 400GB/s memory bandwidth | Double the amount available in the M1 Pro |
| 64GB unified memory | M1 Pro x 2 |
| Dedicated ProRes accelerator | |
| 57 billion transistors | Nearly twice that of the M1 Pro |
| 10 core CPU | Same as the M1 Pro |
| 32 core GPU | M1 Pro x 2 |
| 16 core Neural Engine | Same as the M1 |


### M1 Ultra

The M1 Ultra SoC was announced ??? and also available as an upgrade in the 2022 Mac Studio desktop computer. The M1 Ultra is comprised of two M1 Max SoCs that appear to the operating system to be a single chip.

_Table 5-4_

| Component/Feature | Description |
|---|---|
| 114 billion transistors | M1 Max x 2 |
| 128 GB unified memory | M1 Max x 2 |
| 20 core CPU | DM1 Max x 2 |
| 64 core GPU | M1 Max x 2 |
| 32 core Neural Engine | Same as the M1 Max |
| 800GB/s memory bandwidth | M1 Max x 2 |

## M2

The M2 SoC was introduced on June 6, 2022. It's available for purchase in the 2022 MacBook Air and 2022 MacBook Pro 13-inch laptops. The M2 is the next generation of Apple's SoC with low power consumption, 18% faster CPU, 35% faster GPU, 40% faster neural engine, 50% more memory bandwidth, up to 25% better graphics performance, 18% better all around performance and higher resolution external display support.

_Table 5-5_

| Component/Feature | Description |
|---|---|
| Second generation 5 nanometer technology | The next vesion of the chip technology that was available in the M1 |
| 20 billion transistors | M1 x 1.25 |
| 100GB/s Unified Memory Bandwidth | M1 x 1.5 |
| Up to 24GB unified memory | Same as the M1 |
| 8 Core CPU | 4 high-performance and 4 efficiency cores |
| Up to 10 core GPU | 2 more than the M1 |
| Secure Enclave | Same as the M1 |
| Neural Engine - 15.8 trillion operations/sec | Same as the M1 |
| Media engine | Same as the M1 |
| Up to 24 GB LPDDR5 memory | New to the M2, it helps provide the 100GB/s memory bandwidth |
| ProRes encode and decode | New to the M2, provides faster faster playback and encoding of 4k and 8k video |
| 6k external display support | Same as the M1 |

### M2 Pro

The M2 Pro was introduced January 2023 in the Mac Mini and MacBook Pro 14 and 16 inch models. The M2 Pro provides specs that are in some cases double that of the M2 chip.

_Table 5-6_

| Component/Feature | Description |
|---|---|
| 40 billion transistors | Double the number of the M2 |
| 200GB/s memory bandwidth | Double the bandwidth of the M2 |
| Up to 32GB unified memory | 8GB more than the M2 |
| Up to 12 core CPU | Two more cores than are available in the M2 |
| Up to 19 core GPU | Nine more than the M2 |
| 16 core Neural Engine | Same as the M1 |

### M2 Max

The M2 Max was introduced January 2023 in the MacBook Pro 14 and 16 inch models. It provides everything the M2 Pro provides plus additional transistors, memory, and GPUs.

_Table 5-7_

| Component/Feature | Description |
|---|---|
| 67 billion transistors | More than 3x the number in the M2 |
| 200GB/s memory bandwidth | Double the bandwidth of the M2 |
| Up to 96GB unified memory | Three times more than the max available in the M2 Pro |
| 12 core CPU | Two more cores than are available in the M2 |
| Up to 38 core GPU | Double the maximum available in the M2 Pro |
| 16 core Neural Engine | Same as the M1 |

### M3

The M3 was introduced in 2023 and is an option in the 2023 iMac and MacBook Pro.

_Table 5-8_

| Component/Feature | Description |
|---|---|
| 8 core CPU | 4 performance and 4 efficiency cores |
| 8 core GPU | Features dynamic caching which optimizes memory usage per task |
| 120GB/s memory bandwith | 1.2 times faster than the M2 |
| 16 core Neural Engine | Capable of 18 trillion operations/second |
| 8 memory controllers | Each controller can access up to 4GB of memory |

### M3 Pro

The M3 Pro was introduced in 2023 at the same time as the M3 and is an option in the 2023 iMac and MacBook Pro.

_Table 5-9_

| Component/Feature | Description |
|---|---|
| 11 or 12 core CPU | 5 or 6 performance and 6 efficiency cores |
| 14 or 18 core GPU | Features dynamic caching which optimizes memory usage per task |
| 120GB/s memory bandwith | 1.2 times faster than the M2 |
| 16 core Neural Engine | Capable of 18 trillion operations/second |
| 12 memory controllers | Each controller can access up to 4GB of memory |

### M3 Max

The M3 Pro was introduced in 2023 at the same time as the M3 and is an option in the 2023 iMac and MacBook Pro.

_Table 5-10_

| Component/Feature | Description |
|---|---|
| 14 or 16 core CPU | 10 or 12 performance and 4 efficiency cores |
| 40 core GPU | Features dynamic caching which optimizes memory usage per task |
| 120GB/s memory bandwith | 1.2 times faster than the M2 |
| 16 core Neural Engine | Capable of 18 trillion operations/second |
| 32 memory controllers | Each controller can access up to 4GB of memory |

### M4

The M4 was introduced on May 7, 2024 included in the 2024 iPad Pro. The 3 nanometer process and other efficiency improvements means that the M4 can provide the same performance as the M2 but with half the power.

_Table 5-11_

| Component/Feature | Description |
|---|---|
| 3 nanometer | The latest process for creating faster CPUs that are more efficient |
| 9 or 10 core CPU | 1.5 times faster than the M2, 4 performance and 6 efficiency cores |
| 10 core GPU | 4 times faster than the M2 |
| 120GB/s memory bandwith | 1.2 times faster than the M2 |
| 16 core Neural Engine | |
| 38 trillion operations/second | |
| 28 billion transistors | |

## Resources

* https://en.wikipedia.org/wiki/System_on_a_chip
* https://www.apple.com/newsroom/2020/06/apple-announces-mac-transition-to-apple-silicon/
* https://youtu.be/5AwdkGKmZ0I
* https://www.youtube.com/watch?v=q5D55G7Ejs8
* https://www.apple.com/newsroom/2021/10/introducing-m1-pro-and-m1-max-the-most-powerful-chips-apple-has-ever-built/
* https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/
* https://www.apple.com/newsroom/2022/06/apple-unveils-m2-with-breakthrough-performance-and-capabilities/
* https://www.apple.com/newsroom/2022/06/13-inch-macbook-pro-with-m2-available-to-order-starting-friday-june-17/
* https://www.apple.com/newsroom/2023/01/apple-unveils-macbook-pro-featuring-m2-pro-and-m2-max/
* https://www.apple.com/macbook-pro-14-and-16/
* https://www.apple.com/ipad-pro/
* https://en.wikipedia.org/wiki/Apple_M3

[Next >>](070-chapter-06.md)
