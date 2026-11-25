# Michele Dipace

**Senior Software Engineer | PHP, Moodle & DevOps | Systems Programming & Open Source**

Software engineer working across web platforms, infrastructure automation and low-level systems. My professional work includes PHP, MySQL, Moodle, Linux and service integrations. My open-source work explores cross-architecture compatibility, operating-system internals and native software for the Amiga family.

<!-- kaffeine-project:start -->
## Kaffeine

[Kaffeine](https://github.com/kaffeine1/kaffeine) is my experimental Amiga compatibility research project and a place to develop ideas for AROS upstream. Its Motorola 68k-to-AArch64 dynamic translator has been adapted into [`m68kjit.library`](https://github.com/aros-development-team/AROS/pull/2360), **merged into the official AROS mainline on 24 November 2026**. It uses the optional execution-engine interface in [`m68kemu.library`](https://github.com/aros-development-team/AROS/pull/2359), also merged upstream, while preserving the interpreter as the default and fallback.

The merged JIT was validated with **71,636 host checks across 28 groups (zero failures)**, randomized differential tests against Moira, and native AROS AArch64 tests under QEMU. Validation of this upstream configuration on physical hardware and with real applications remains future work. The [technical case study](https://github.com/kaffeine1/kaffeine/blob/master/docs/kaffeine/jit-case-study.md) covers the architecture, test evidence and limitations.
<!-- kaffeine-project:end -->

## Other selected work
- **[Amigram](https://github.com/kaffeine1/telegram-amiga)** — A native Telegram client, formerly TelegramAmiga, written in C for AmigaOS 3 and 4, MorphOS and AROS. It shares a protocol engine between graphical and Shell clients; the public repository documents its beta releases and platform coverage.
- **[EdgeSnap](https://github.com/kaffeine1/edgesnap)** and **[EdgeSnap classic](https://github.com/kaffeine1/edgesnap-classic)** — Window snapping and tiling for AmigaOS, MorphOS and AROS. A portable C89 core drives system-specific libraries, commodities and preferences; the classic branch supports 68k AmigaOS.
- **[BebboSSH for AROS](https://github.com/kaffeine1/bebbossh-aros)** and **[bebboget for AROS](https://github.com/kaffeine1/bebboget-aros)** — AROS ports of Stefan “Bebbo” Franke's SSH and HTTPS tools for i386, x86-64 and AArch64. The original authorship and licenses remain with their respective upstream projects.

## Contributions to AROS

I contribute fixes and tests to [AROS](https://github.com/aros-development-team/AROS), including 68k compatibility, native structure layouts, DOS and graphics behavior, and Raspberry Pi AArch64 support. Merged contributions include the [68k-to-AArch64 JIT engine](https://github.com/aros-development-team/AROS/pull/2360), [optional 68k execution-engine interface](https://github.com/aros-development-team/AROS/pull/2359), [target-correct native structure offsets](https://github.com/aros-development-team/AROS/pull/2341), [root stack, process streams and argument handling](https://github.com/aros-development-team/AROS/pull/2273), [aligned seglist links](https://github.com/aros-development-team/AROS/pull/2243), [graphics text bounds](https://github.com/aros-development-team/AROS/pull/2346), and [Raspberry Pi bootstrap fixes](https://github.com/aros-development-team/AROS/pull/2331).

The upstream JIT merge followed reviews of memory allocation, division flags, register use and randomized differential testing. Kaffeine's earlier application demonstrations used its legacy library or local development builds; they are **not** evidence of real-application compatibility for the newly merged upstream engine.

## Areas of work

**Professional:** PHP, MySQL, Moodle, Linux operations, automation, REST integrations.

**Open source:** C and C++, AArch64, dynamic binary translation, emulation, ABI boundaries, native UI, cross-platform ports and reproducible testing.

<!-- patreon-support:start -->
## Support development

My open-source projects and documentation are available without a subscription. If you would like to support their development, you can [join my Patreon](https://www.patreon.com/c/kaffeine1) or [make a one-time contribution on Ko-fi](https://ko-fi.com/kaffeine1).
<!-- patreon-support:end -->

## Links

[LinkedIn](https://www.linkedin.com/in/kaffeine/) · [Development notes](https://androidlab.it/en/retrolab/)
