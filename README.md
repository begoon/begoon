# Alexander Demin

**Staff Software Engineer** · London, UK · [demin.ws](https://demin.ws) · [LinkedIn](https://www.linkedin.com/in/alexanderdemin/)

I design and build distributed systems and cloud infrastructure, currently at [iProov](https://www.iproov.com) (biometric identity verification). 20+ years of engineering across backend, platform, embedded and low-level work. Writing code on GitHub since 2009.

Away from work I write compilers, emulators and solvers, mostly for Soviet-era 8-bit machines and classic algorithms. Things that are slightly closer to the metal, and occasionally problems that probably did not need solving.

## What I do professionally

<!-- TODO: replace these with concrete scope and numbers (traffic, team size, systems owned). -->

- Architecture and ownership of production distributed systems: service boundaries, data flows, reliability and cost on public cloud.
- Platform and developer-experience work: CI/CD, infrastructure as code, observability, release engineering.
- Technical leadership across teams: design reviews, mentoring, setting engineering standards, turning vague product goals into shippable systems.
- Deep debugging when it matters: protocols, performance, memory, and the layers below the framework.

**Languages and stack:** Go, Python, TypeScript/JavaScript, C, Zig, Assembly (Intel 8080/Z80), Svelte, WASM, GCP, Kubernetes, Docker, GitHub Actions.

## Highlights

| Project | Why it is interesting | |
|---|---|---|
| [i8080-core](https://github.com/begoon/i8080-core) | Cycle-accurate Intel 8080 (KR580VM80A) core in C, verified against the 8080/8085 CPU exercisers; the basis of several emulators | ★83 |
| [rapira](https://github.com/begoon/rapira) | Full interpreter for the Soviet educational language Rapira in TypeScript, with an [online playground](https://begoon.github.io/rapira) and `npx rapira` | ★57 |
| [rk86-js](https://github.com/begoon/rk86-js) | Радио-86РК emulator with built-in debugger, assembler, C and PL/M compilers, shipped as a web component on [rk86.ru](https://rk86.ru) and in the terminal via `npx rk86` | ★28 |
| [dissertation](https://github.com/begoon/dissertation) | Combined Method for Integer Linear Programming: a four-stage MILP solver (LP relaxation, vector-lattice search, filter row, bounded final search), with implementation, analysis and benchmarks | |
| [gomoku-zig](https://github.com/begoon/gomoku-zig) | Gomoku AI in Zig/WASM: Minimax with alpha-beta pruning, local move pre-sorting and quiescence deepening to mitigate the horizon problem ([play](https://demin.ws/gomoku-zig/)) | |
| [go-tcpspy](https://github.com/begoon/go-tcpspy) | TCP/IP proxy and traffic spy in Go, with [Python](https://github.com/begoon/py-tcpspy) and [Erlang](https://github.com/begoon/erl-tcpspy) ports | ★53 |

The full list of public repositories sorted by stars is in [stars.md](stars.md).

## Language implementation

Compilers, interpreters and assemblers, all written from scratch and runnable in the browser or via `npx`.

- [c8080-js](https://github.com/begoon/c8080-js) - Intel 8080 C compiler ported to TypeScript (`npx c8080`, [online](https://rk86.ru/beta/c8080))
- [plm80](https://github.com/begoon/plm80) - PL/M compiler for Intel 8080 and Радио-86РК (`npx plm80`)
- [asm8](https://github.com/begoon/asm8) - Intel 8080 assembler in TypeScript (`npx asm8080`, [online](https://begoon.github.io/asm8/))
- [asm8080](https://github.com/begoon/asm8080) - Intel 8080 macro assembler in C
- [easy](https://github.com/begoon/easy) - compiler for the EASY language (`npx @begoon/easyc`, [online](https://begoon.github.io/easy/))
- [snobol](https://github.com/begoon/snobol) - SNOBOL4 interpreter in TypeScript (`npx snobol`)
- [trac](https://github.com/begoon/trac) - TRAC 64 interpreter (`npx trac64i`, [online](https://begoon.github.io/trac/))
- [nor](https://github.com/begoon/nor) - one-instruction CPU (OISC) based on NOR: DSL, compiler and executor
- [rapira](https://github.com/begoon/rapira) - Rapira ([Рапира](https://github.com/begoon/rapira/blob/main/RAPIRA.md)) interpreter, see Highlights

## Emulation and reverse engineering

- [rk86-js](https://github.com/begoon/rk86-js) - Радио-86РК emulator, see Highlights; also available as a [web component](https://rk86.ru/web)
- [i8080-js](https://github.com/begoon/i8080-js) - Intel 8080 core in JavaScript (★48)
- [rk86-tape](https://github.com/begoon/rk86-tape) - WAV tape decoder for Радио-86РК, with a [signal visualiser](https://demin.ws/rk86-tape/) and a [write-up of the encoding](https://github.com/begoon/rk86-tape/blob/main/README-RU.md)
- [rk86-monitor](https://github.com/begoon/rk86-monitor) - annotated disassembly of the original 2 KB ROM monitor
- [rk86-reverse](https://github.com/begoon/rk86-reverse) - Claude Code skills for disassembling and reverse-engineering Intel 8080 programs
- Byte-exact annotated disassemblies and remakes of 1980s Радио-86РК games:
  [Volcano](https://github.com/begoon/volcano),
  [Лестница](https://github.com/begoon/lestnica),
  [Диверсант](https://github.com/begoon/diverse),
  [Алмаз](https://github.com/begoon/aliaz1),
  [ПВО](https://github.com/begoon/pvo),
  [Клад](https://github.com/begoon/klad),
  [SPACE](https://github.com/begoon/space)

## Algorithms and research

- [dissertation](https://github.com/begoon/dissertation) - Combined Method for ILP, see Highlights
- [svg-draw](https://github.com/begoon/svg-draw) - web playground for a JavaScript DSL that draws scientific illustrations ([online](https://begoon.github.io/svg-draw))
- [gomoku-zig](https://github.com/begoon/gomoku-zig) - Gomoku AI agent, see Highlights
- [zig-sokoban-solver](https://github.com/begoon/zig-sokoban-solver) - Sokoban solver in Zig and WASM ([online](https://demin.ws/zig-sokoban-solver/)), plus [60 Sokoban maps](https://github.com/begoon/sokoban-maps) (★49)
- [etudes-vegenere](https://github.com/begoon/etudes-vegenere) - Vigenère cipher breaker, the etude from Wetherell's "Etudes for Programmers"
- [ssb](https://github.com/begoon/ssb) - in-browser demonstration of Single Side Band radio modulation ([online](https://begoon.github.io/ssb))
- [Mayne-James compression](https://github.com/begoon/tmpz/tree/main/mayne-james-compression) (an LZ precursor) and the [GPM macro processor](https://github.com/begoon/tmpz/tree/main/gpm-macro)

## Systems and tooling

- [xc](https://github.com/begoon/xc) - portable single-file dual-panel file manager with a VFS layer (S3, GCS, SSH), `uvx xcfm` from [PyPI](https://pypi.org/project/xcfm/)
- [go-tcpspy](https://github.com/begoon/go-tcpspy) - TCP/IP proxy and spy, see Highlights
- [http-server](https://github.com/begoon/http-server) - the same minimal HTTP REST server implemented in many languages, down to assembly (★37)
- [go-svelte](https://github.com/begoon/go-svelte) - Svelte + Go hybrid SPA/MPA application (★32)
- [ghasha](https://github.com/begoon/ghasha) - GitHub Action exposing SHA, SHORT_SHA and BRANCH for the current commit ([marketplace](https://github.com/marketplace/actions/ghasha-sha-and-branch))
- [ghasecret](https://github.com/begoon/ghasecret) - GitHub Action for debugging CI: encodes a value so it survives the workflow log masking ([marketplace](https://github.com/marketplace/actions/ghasecret))
- [tfl](https://github.com/begoon/tfl) - Transport for London timetable and line status viewer

## Games

Browser remakes of classic and Soviet-era games, playable online.

- [paratrooper](https://github.com/begoon/paratrooper) - the 1982 arcade classic ([play](https://begoon.github.io/paratrooper))
- [fighter](https://github.com/begoon/fighter) - Fighter from the Агат-7 ([play](https://begoon.github.io/fighter))
- [kling](https://github.com/begoon/kling) - Космические Войны from the Агат-9 ([play](https://begoon.github.io/kling))
- [skittles](https://github.com/begoon/skittles) - a web reimagining of Городки ([play](https://begoon.github.io/skittles))
- [durak](https://github.com/begoon/durak) - the card game Переводной Дурак ([play](https://begoon.github.io/durak))
- [psycho](https://github.com/begoon/psycho) - a reflexive game "Платный психолог" ([play](https://begoon.github.io/psycho))
- [conix](https://github.com/begoon/conix) - port of `conix` to Python and TypeScript
- [ucl](https://github.com/begoon/ucl) - HTML/JS remake of the 1996 UCL DOS demo ([view](https://demin.ws/ucl))

## Writing

I have been writing the blog "Программирование - это просто!" (Programming DIY) at [demin.ws](https://demin.ws) since 2009, mostly about low-level programming, emulation and algorithms.
