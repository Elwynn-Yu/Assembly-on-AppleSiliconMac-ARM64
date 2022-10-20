# **Assembly-on-AppleSiliconMac-ARM64**

Apple migrated the Mac architecture from intel's AMD64 architecture to ARM AArch64 architecture. This series, aimed at developers using Apple Silicon Macs, provides a systematic introduction to assembly language for the AArch64 architecture.

It should be noted that this series of articles I have written is not intended to make the reader an expert in the underpinnings of macOS but rather to make it easy for developers with an Apple Silicon Mac to get started with assembly language.

This series aims to enable developers with no exposure to assembly language to read and write assembly language, write some high-performance code in assembly language, and read and understand the inverse of binary software. Only the AArch64 architecture is used with the macOS operating system. Therefore, in this series of articles, most of the knowledge is about concepts applicable across systems and platforms, and some ideas unique to macOS will not be highlighted. But don't worry. This series’s processes and steps can be performed natively on macOS.

# **Required Basic knowledge**

* C Programming language
* Computer Organization and Architecture Themes and Variations

# **Better Understanding**
* if you read the book ahead <<Computer Systems A Programmer's Perspective>>

# **The programming environment**

* Chips: Apple M1 Max

* Operating system: macOS 12.6

* Operating system kernel: arm64-apple-darwin21.6.0

* XNU source code version: xnu-8020.101.4

* clang version: Apple clang version 14.0.0 (clang-1400.0.29.102)
