I work on tooling for computer security, OS internals, binary analysis,
instrumentation, reverse engineering, game security research, and fuzzing.

## Technical focus

- **Systems security:** hypervisors, virtual machine introspection, debuggers
- **Binary analysis and instrumentation:** runtime inspection and internals, process injection
- **Research operations:** curated knowledge bases, reproducible environments, automation
- **Vulnerability research tooling:** fuzzing techniques (snapshot-based, stateful, structure-aware)

## Languages and tools

<div align="center">

![Skills](https://skillicons.dev/icons?i=linux,bash,py,rust,&theme=dark)

</div>

## Public work

Selected public repositories and substantial forks grouped by area. Archived projects are kept visible
as research notes or historical experiments rather than active maintenance
targets.

### Systems security, virtualization, and memory

| Project | Description | Stack |
| --- | --- | --- |
| [xenith](https://github.com/zeishr/xenith) | Research-focused hypervisor for Xen-based debugging, virtual machine introspection, and automation. <sub>archived</sub> | Rust |
| [awesome-anti-virtualization](https://github.com/zeishr/awesome-anti-virtualization) | Curated reference list for anti-virtualization and VM-detection techniques. | Research list |
| [libMMU](https://github.com/zeishr/libMMU) | Rust crate for rebuilding virtual address spaces from memory dumps, inspired by the OS-agnostic MMU reconstruction techniques explored in `mmushell`. <sub>archived</sub> | Rust / Nix |
| [mmushell](https://github.com/zeishr/mmushell) | Substantial fork of EURECOM's memory-forensics PoC; added module packaging, a Nix development shell, MkDocs documentation, and architecture/exporter cleanup. <sub>archived</sub> | Python |
| [secmalloc](https://github.com/zeishr/secmalloc) | Secure allocator experiment around malloc/realloc/free-style semantics. <sub>archived</sub> | C |

### Fuzzing

| Project | Description | Stack |
| --- | --- | --- |
| [snapchange](https://github.com/zeishr/snapchange) | Fork of awslabs' KVM snapshot fuzzer with dependency updates, container and template fixes, `LD_PRELOAD` support, fuzzer virtual-memory mapping, clearer VM-exit diagnostics, and `snapshell` tooling. <sub>archived</sub> | Rust / Python / KVM |

### Runtime instrumentation and game security

| Project | Description | Stack |
| --- | --- | --- |
| [mono-injector](https://github.com/zeishr/mono-injector) | Rust CLI and GUI for injecting managed assemblies into Unity and other Mono-hosted Windows processes. | Rust |
| [mono-rt](https://github.com/zeishr/mono-rt) | Dynamic Rust bindings to the Mono runtime for injected tooling and runtime inspection. | Rust |
| [strafthack](https://github.com/zeishr/strafthack) | Managed Unity mod for STRAFTAT private-session testing and controlled client-side experimentation. | C# |
| [Pity](https://github.com/zeishr/Pity) | Legacy Garry's Mod scripting project kept as an archive. <sub>archived</sub> | Lua |

<!--## GitHub activity

<div align="center">
  <img
    height="165"
    alt="GitHub statistics"
    src="https://github-readme-stats.vercel.app/api?username=zeishr&show_icons=true&hide_title=true&hide_border=true&include_all_commits=true&count_private=true&line_height=28&bg_color=0d1117&title_color=e2c16b&text_color=c9d1d9&icon_color=e2c16b&ring_color=b89b53"
  />
  <img
    height="165"
    alt="Most used languages"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=zeishr&layout=compact&hide_border=true&langs_count=8&bg_color=0d1117&title_color=e2c16b&text_color=c9d1d9&icon_color=e2c16b"
  />
</div>-->
