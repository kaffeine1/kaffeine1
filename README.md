# Michele Dipace

Software engineer working across web platforms, infrastructure automation and low-level systems. My professional work includes PHP, MySQL, Moodle, Linux and service integrations. My open-source work explores cross-architecture compatibility, operating-system internals and native software for the Amiga family.

<!-- kaffeine-project:start -->
## Kaffeine

[Kaffeine](https://github.com/kaffeine1/kaffeine) develops experimental 68k-to-AArch64 dynamic translation for AROS. The proposed `m68kjit.library` is an optional engine beneath AROS's `m68kemu.library` interpreter. The [engine interface is merged upstream](https://github.com/aros-development-team/AROS/pull/2359); the [JIT engine is under review](https://github.com/aros-development-team/AROS/pull/2360). The latter has passed host checks and small native tests under QEMU, but has not been validated with real applications in that upstream configuration or on physical hardware. Read the [technical case study](https://github.com/kaffeine1/kaffeine/blob/master/docs/kaffeine/jit-case-study.md) for the architecture, evidence and limits.
<!-- kaffeine-project:end -->

## Other selected work
- **[Amigram](https://github.com/kaffeine1/telegram-amiga)** — A native Telegram client, formerly TelegramAmiga, written in C for AmigaOS 3 and 4, MorphOS and AROS. It shares a protocol engine between graphical and Shell clients; the public repository documents its beta releases and platform coverage.
- **[EdgeSnap](https://github.com/kaffeine1/edgesnap)** and **[EdgeSnap classic](https://github.com/kaffeine1/edgesnap-classic)** — Window snapping and tiling for AmigaOS, MorphOS and AROS. A portable C89 core drives system-specific libraries, commodities and preferences; the classic branch supports 68k AmigaOS.
- **[BebboSSH for AROS](https://github.com/kaffeine1/bebbossh-aros)** and **[bebboget for AROS](https://github.com/kaffeine1/bebboget-aros)** — AROS ports of Stefan “Bebbo” Franke's SSH and HTTPS tools for i386, x86-64 and AArch64. The original authorship and licenses remain with their respective upstream projects.

## Contributions to AROS

I contribute fixes and tests to [AROS](https://github.com/aros-development-team/AROS), including 68k compatibility, native structure layouts, DOS and graphics behavior, and Raspberry Pi AArch64 support. Examples already merged upstream include the [optional 68k execution-engine interface](https://github.com/aros-development-team/AROS/pull/2359), [target-correct native structure offsets](https://github.com/aros-development-team/AROS/pull/2341), [root stack, process streams and argument handling](https://github.com/aros-development-team/AROS/pull/2273), [aligned seglist links](https://github.com/aros-development-team/AROS/pull/2243), [graphics text bounds](https://github.com/aros-development-team/AROS/pull/2346), and [Raspberry Pi bootstrap fixes](https://github.com/aros-development-team/AROS/pull/2331).

The 68k-to-AArch64 engine remains a [separate open proposal](https://github.com/aros-development-team/AROS/pull/2360). Kaffeine's earlier application demonstrations use its legacy library or local development builds; they are not evidence that the proposed upstream engine supports those applications.

## Areas of work

**Professional:** PHP, MySQL, Moodle, Linux operations, automation, REST integrations.

**Open source:** C and C++, AArch64, dynamic binary translation, emulation, ABI boundaries, native UI, cross-platform ports and reproducible testing.

<!-- patreon-support:start -->
## Support development

My open-source projects and documentation are available without a subscription. If you would like to support their development, you can [join my Patreon](https://www.patreon.com/c/kaffeine1) or [make a one-time contribution on Ko-fi](https://ko-fi.com/kaffeine1).
<!-- patreon-support:end -->

## Links

[LinkedIn](https://www.linkedin.com/in/kaffeine/) · [Development notes](https://androidlab.it/en/retrolab/)
