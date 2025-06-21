Hey! My name is Adrian, and I'm a well-rounded software engineer with over 10 years of programming experience. I've been working professionally for the last 5 years and in that time I've worked with a large amount of languages like Rust, C/C++, Java, Javascript/Typescript, PHP, Python, Kotlin, Swift, C#, x86 assembly, and many more. I also have experience with an ever-increasing number of related technologies including React/NextJS, Vue/Nuxt, Tailwind, HTMX, Axum, Express, Fastify, PostgreSQL, MongoDB, Docker, Kubernetes, and Git just to name a few.

Over the years I've had the opportunity to explore many different fields such as web development, mobile development, systems programming, embedded firmware development, game/graphics programming, compiler engineering, operating system development, and many others. Currently I'm employed full-time at [Adom Industries Inc.](https://github.com/adom-inc) where I work all across the software (and hardware) stack tackling exciting problems in robotics and distributed systems.

<p align="left"> <img src="https://komarev.com/ghpvc/?username=wowkster&label=Profile%20views&color=0e75b6&style=flat" alt="wowkster" /> <a href='https://wakatime.com/@14712074-e7e9-4ac6-91dd-cf3f62547828'><img src="https://wakatime.com/badge/user/14712074-e7e9-4ac6-91dd-cf3f62547828.svg" alt="wowkster" /></a> </p>

## Contact
You can contact me on Discord (preferred) at `@wowkster` or by email at `contact@adrianwowk.com` for inquiries. If you are contacting me about an issue with a project, please open a GitHub issue on that repository instead. I will tend to it as soon as I can.

## Open Source Work Projects

* [kicad_lib](https://github.com/adom-inc/kicad_lib) - A Rust library for working with Kicad files
* [mcp2518fd](https://github.com/adom-inc/mcp2518fd) - A `#![no_std]` Rust driver library for the MCP2518FD CAN FD controller
* [tmc2240](https://github.com/adom-inc/tmc2240) - A `#![no_std]` Rust driver library for the Trinamic TMC2240 stepper motor driver chip
* [ads123x](https://github.com/adom-inc/ads123x) - A `#![no_std]` Rust driver library for the TI ADS123x series of Delta-Sigma ADC chips

## Notable Personal Projects

### [drip](https://github.com/RiptideOS/drip)

A from-scratch compiler for a custom systems programming language I'm working on. My goal with this project is to self-host the compiler and then use the language to write a full OS kernel and userspace with no dependencies. 

The language itself is inspired by several other languages, notably Rust, C, and C++ with most of the syntax borrowed from Rust.

  * Bootstrap compiler written in Rust
  * Hand-written parser and type checker with a focus on providing good diagnostics
  * Fully custom backend (no LLVM here) with an SSA optimization pipeline
  * Hindley-Milner style type system
  * Manual memory management without many of the footguns
    * Built-in Option and Result types
    * RAII guards for dynamic allocations similar to C++
  * IDE support (LSP and Syntax Highlighting) coming soon
  * Syntax-level macro system coming soon

### [floppier](https://github.com/wowkster/floppier)

A implementation of musical floppy drives in Rust

  * Server written in Rust
    * Parses MIDI files
    * Sends MIDI events over USB serial to hardware client
  * Embedded hardware client written in Rust
    * Runs on Raspberry Pi Pico
    * Custom USB serial protocol using CBOR
    * Parallel and interrupt driven floppy drive driver

### [dinOS](https://github.com/wowkster/dinOS)

A 32-bit hobby operating system written in x86 assembly made to explore low level computing and the x86 architecture. It features a multi-stage bootloader which includes FAT12 drivers and a spec compliant BIOS disk IO wrapper.  The kernel is still in the very early stages but supports interrupt handling, VGA text mode drivers, and memory paging.

  * Stage 1 bootloader written in x86 assembly
    * BIOS disk IO wrapper
    * FAT12 file system driver
    * Stage 2 loader
    * Error tolerant design with error messages
    * All fits into 512 byte boot sector (448 bytes when you subtract space occupied by BPB)
  * Stage 2 bootloader written in x86 assembly
    * Kernel loader
    * GDT initializer
    * 32-bit protected mode initializer
  * Kernel written in x86 assembly (for now)
    * VGA text mode drivers
    * PIC programming
    * IDT setup
    * Interrupt handling
    * Memory Paging
    * PS/2 Keyboard Drivers

### [Cloaks+](https://github.com/CloaksPlus) (Founder/Previously CTO)
  A character customization utility for Minecraft

  * Backend in Node/Rust
  * Frontend with Next.js and TS
  * Discord Bot in Discord.js and TS
  * Various Java/Kotlin Plugins
  * Desktop App in Tauri, React, and TS
  * etc

<img src="https://user-images.githubusercontent.com/49880655/230960140-ff465d11-eec3-4a3d-8163-df86bc133afe.png" width="500">

### [PixelMousepads](https://pixelmousepads.com)
  A webstore for stylish pixel art mousepads

  * Backend in TS with Fastify
  * Frontend with Next.js and TS

<img src="https://user-images.githubusercontent.com/49880655/230960693-78ff38aa-5f9f-4bbd-984b-bcd18039c541.png" width="500">

### [farba](https://github.com/wowkster/farba)

  A CPU graphics library written in pure Rust
  
  * Supports 2D drawing primatives (lines, circles, triangles, etc)
  * Also has helpers for 3D graphics (depth buffering, projection matrices, etc)

### Smaller Side Projects (In various stages of completion)

* [Leek - A programming language for edge computing](https://github.com/leek-lang/leek)
* [Drown - A lightweight SQL database server and client implementation](https://github.com/wowkster/drown)
* [Rust wrapper for olive.c](https://github.com/wowkster/olivec)
* [PNG sequence to Minecrtaft animation CLI tool](https://github.com/wowkster/StackPNG)
* [Rust-based malware for windows](https://github.com/wowkster/repulse)
* [VIM-style terminal text editor in Rust](https://github.com/wowkster/rim)
* [Typescript Minecraft Server Implementation](https://github.com/wowkster/HydrogenServer)
* [Cards Against Humanity Online](https://github.com/wowkster/CardsAgainstHumanity)
* [Adding Wi-Fi support for my TI-84 calculator](https://github.com/wowkster/TI-RC)
* [Rust JVM implementation](https://github.com/wowkster/RustJVM)
* Remaking my personal website

## My GitHub Stats

[![Wowkster's Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wowkster&layout=compact&theme=algolia&langs_count=10)](https://github.com/anuraghazra/github-readme-stats)
