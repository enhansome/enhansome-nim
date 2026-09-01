# Awesome nim with stars

<h1> <a href="https://nim-lang.org"><img src="asset/awesome-nim-logo.svg" alt="Awesome-nim-logo" width="600"/></a><a href="https://awesome.re"><img align="right" src="https://awesome.re/badge.svg"></a> </h1>

> A curated list of awesome Nim frameworks, libraries, software and resources.

[Nim](https://nim-lang.org/) is a statically typed compiled systems programming language. Good for everything from shell scripting to web front & backend, to ML, HPC, and embedded.

<h2> Contents </h2>

* [Language Features](#language-features)
  * [Implementations](#implementations)
  * [Standard Libraries](#standard-libraries)
  * [Package Repositories](#package-repositories)
  * [Editors](#editors)
  * [Async IO](#async-io)
  * [Threading](#threading)
  * [Error Handling](#error-handling)
  * [Contracts](#contracts)
  * [Object-Oriented Programming](#object-oriented-programming)
  * [Functional Programming](#functional-programming)
  * [Pattern Matching](#pattern-matching)
  * [Iteration](#iteration)
  * [Macros](#macros)
* [Operating System](#operating-system)
  * [System API](#system-api)
  * [IO](#io)
  * [Processes](#processes)
  * [Date and Time](#date-and-time)
  * [Randomization](#randomization)
  * [Scripting](#scripting)
* [System Tools](#system-tools)
  * [Backups](#backups)
  * [Prometheus exporters](#prometheus-exporters)
* [Hardware](#hardware)
  * [Embedded](#embedded)
* [Science](#science)
* [Data](#data)
  * [Database](#database)
    * [Driver](#driver)
    * [ORM](#orm)
  * [Data Structures](#data-structures)
  * [Data Processing](#data-processing)
  * [Parsing](#parsing)
  * [Serialization](#serialization)
  * [Standards](#standards)
* [Text](#text)
  * [String Types](#string-types)
  * [Translation](#translation)
  * [Markdown](#markdown)
* [Multimedia](#multimedia)
  * [Audio](#audio)
  * [Images](#images)
  * [Documents](#documents)
* [Algorithms](#algorithms)
  * [Math](#math)
    * [Symbolic](#symbolic)
    * [FFT](#fft)
    * [Vector](#vector)
    * [Matrix](#matrix)
  * [Deep Learning](#deep-learning)
  * [Bigints](#bigints)
  * [Cryptography](#cryptography)
  * [Blockchain](#blockchain)
  * [Compression](#compression)
* [User Interface](#user-interface)
  * [Terminal](#terminal)
  * [Design](#design)
  * [GUI](#gui)
    * [Crossplatform](#crossplatform)
    * [Windows](#windows)
    * [Linux](#linux)
    * [Web Technology](#web-technology)
    * [Lightweight](#lightweight)
  * [Plotting](#plotting)
* [Mobile](#mobile)
* [Web](#web)
  * [Protocols](#protocols)
    * [DNS](#dns)
    * [QUIC](#quic)
    * [Websockets](#websockets)
    * [Messaging](#messaging)
    * [Multicast](#multicast)
  * [HTML Parsers](#html-parsers)
  * [HTTP Servers](#http-servers)
  * [Gemini Servers](#gemini-servers)
  * [Frameworks](#frameworks)
  * [Template Engines](#template-engines)
  * [Authentication](#authentication)
* [Game Development](#game-development)
  * [Game Libraries](#game-libraries)
  * [Game Frameworks](#game-frameworks)
  * [Game Engines](#game-engines)
  * [Rules Engines](#rules-engines)
* [Development Tools](#development-tools)
  * [Editor Integration](#editor-integration)
  * [REPL](#repl)
  * [Binding Generators](#binding-generators)
  * [Build Systems / Package Management](#build-systems--package-management)
  * [Logging](#logging)
  * [Testing](#testing)
  * [Fuzzing](#fuzzing)
  * [Benchmarking](#benchmarking)
  * [Command-Line Interface Automation](#command-line-interface-automation)
  * [Static Analysis](#static-analysis)
* [Resources](#resources)
  * [Books](#books)
  * [Blogs](#blogs)
  * [Community](#community)
  * [Tutorials](#tutorials)
  * [Videos](#videos)
  * [Footnotes](#footnotes)

## Language Features

### Implementations

* [Nim](https://github.com/nim-lang/Nim) ⭐ 18,210 | 🐛 2,188 | 🌐 Nim | 📅 2026-09-01 - Nim (formerly known as "Nimrod") is a compiled, garbage-collected systems programming language which has an excellent productivity/performance ratio. Nim's design focuses on efficiency, expressiveness, elegance (in the order of priority).
* [nlvm](https://github.com/arnetheduck/nlvm) ⭐ 776 | 🐛 15 | 🌐 Nim | 📅 2026-08-31 - LLVM backend for Nim.

### Standard Libraries

Nim provides unique features for seamless and transparent interoperability with other technologies. Some users found it useful to make other standard libraries usable from Nim.

* [Node.js](https://github.com/juancarlospaco/nodejs) ⭐ 225 | 🐛 0 | 🌐 Nim | 📅 2026-07-31 - Node.js standard library for Nim.
* [cpython](https://github.com/juancarlospaco/cpython) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2026-07-30 - Python standard library for Nim.

Also, unlike those above, which requires runtime dependancy, some pure-Nim libraries are implemented.

* [pylib](https://github.com/nimpylib/pylib) ⭐ 78 | 🐛 11 | 🌐 Nim | 📅 2026-07-04 - Pure Nim implementation for Python builtins, libraries and sugars.

### Package Repositories

* [Nim packages](https://github.com/nim-lang/packages) ⭐ 501 | 🐛 18 | 🌐 Nim | 📅 2026-08-31 - List of packages for Nimble.
* [Nim package directory](https://nimble.directory/) - Explore Nim packages known to Nimble.

### Editors

* [moe](https://github.com/fox0430/moe) ⭐ 719 | 🐛 46 | 🌐 Nim | 📅 2026-09-01 - A vim-like editor made with Nim, also supports C, Rust, Javascript, etc.
* [Nev](https://github.com/Nimaoth/Nev) ⭐ 199 | 🐛 7 | 🌐 Nim | 📅 2026-07-06 - A keyboard focused GUI and terminal text editor.
* [Nim Playground](https://play.nim-lang.org/) - Code and run Nim online.
* [DoongJohn's Nim playground](https://doongjohn.github.io/nim-playground/) - An alternative implementation of the Nim playground.

### Async IO

* [chronos](https://github.com/status-im/nim-chronos) ⭐ 413 | 🐛 57 | 🌐 Nim | 📅 2026-08-31 - An efficient library for asynchronous programming.
* [cps](https://github.com/disruptek/cps) ⭐ 15 | 🐛 0 | 🌐 Nim | 📅 2025-04-29 - Continuation-Passing Style for Nim.
* [std/async](https://nim-lang.org/docs/async.html) - Async/await implementation in Nim's stdlib (aka asyncdispatch).

### Threading

* [weave](https://github.com/mratsim/weave) ⭐ 585 | 🐛 44 | 🌐 Nim | 📅 2024-06-29 - A state-of-the-art multithreading runtime: message-passing based, fast, scalable, ultra-low overhead.
* [malebolgia](https://github.com/Araq/malebolgia) ⭐ 159 | 🐛 4 | 🌐 HTML | 📅 2026-03-04 - A powerful library in Nim that simplifies the implementation of concurrent and parallel programming.
* [taskpools](https://github.com/status-im/nim-taskpools) ⭐ 123 | 🐛 11 | 🌐 Nim | 📅 2026-08-24 - Lightweight, energy-efficient, easily auditable threadpools.
* [synthesis](https://github.com/mratsim/Synthesis) ⭐ 99 | 🐛 1 | 🌐 Nim | 📅 2020-04-21 - A compiletime, procedure-based, low-overhead, no-allocation, state-machine generator optimized for communicating processes and threads.
* [sync](https://github.com/planetis-m/sync) ⚠️ Archived - Useful synchronization primitives.
* [shared](https://github.com/genotrance/shared) ⭐ 12 | 🐛 0 | 🌐 Nim | 📅 2019-07-31 - A Nim library for shared types.
* [timerpool](https://github.com/mikra01/timerpool) ⭐ 8 | 🐛 1 | 🌐 Nim | 📅 2020-05-10 - Threadsafe timerpool implementation for event purposes.
* [threadlogging](https://codeberg.org/pswilde/threadlogging) - A thread safe logging library using Nim's own logging module

### Error Handling

* [result](https://github.com/arnetheduck/nim-result/) ⭐ 178 | 🐛 12 | 🌐 Nim | 📅 2026-08-30 - Friendly, exception-free value-or-error returns, similar to Option\[T].
* [questionable](https://github.com/status-im/questionable) ⭐ 124 | 🐛 3 | 🌐 Nim | 📅 2026-04-22 - Elegant optional types for Nim.
* [optionsutils](https://github.com/PMunch/nim-optionsutils) ⭐ 38 | 🐛 2 | 🌐 Nim | 📅 2021-06-30 - Utility macros for easier handling of options in Nim.

### Contracts

* [contracts](https://github.com/Udiknedormin/NimContracts) ⭐ 81 | 🐛 10 | 🌐 Nim | 📅 2024-07-19 - Used to make contracts - elegant promises that pieces of code will fulfill certain conditions.
* [contra](https://github.com/juancarlospaco/nim-contra) ⭐ 57 | 🐛 3 | 🌐 Nim | 📅 2022-01-26 - Lightweight and fast self-documenting design by contract programming.

### Object-Oriented Programming

* [classes](https://github.com/jjv360/nim-classes) ⭐ 102 | 🐛 2 | 🌐 Nim | 📅 2026-04-13 - Python-style class system for Nim.
* [oop\_utils](https://github.com/bluenote10/oop_utils) ⭐ 37 | 🐛 4 | 🌐 Nim | 📅 2021-06-09 - Nim macros for building OOP class hierarchies.
* [interfaced](https://github.com/andreaferretti/interfaced) ⭐ 34 | 🐛 4 | 🌐 Nim | 📅 2017-10-23 - Interfaces for Nim.
* [traitor](https://github.com/beef331/traitor) ⭐ 33 | 🐛 0 | 🌐 Nim | 📅 2026-01-18 - A macro heavy trait library made from boredom.
* [classy](https://github.com/nigredo-tori/classy) ⚠️ Archived - Haskell-style typeclasses for Nim.

### Functional Programming

* [zero-functional](https://github.com/zero-functional/zero-functional) ⭐ 340 | 🐛 3 | 🌐 C++ | 📅 2022-09-19 - A library providing (almost) zero-cost chaining for functional abstractions in Nim.
* [nimfp](https://github.com/vegansk/nimfp) ⭐ 133 | 🐛 11 | 🌐 Nim | 📅 2024-06-19 - Nim functional programming library.
* [cascade](https://github.com/citycide/cascade) ⭐ 104 | 🐛 2 | 🌐 Nim | 📅 2024-05-13 - Method & assignment cascades for Nim, inspired by Smalltalk & Dart.
* [pipe](https://github.com/5paceToast/pipe) ⭐ 68 | 🐛 2 | 🌐 Nim | 📅 2021-07-26 - Pipe operator for Nim, as seen in functional languages.
* [nim-pipexp](https://github.com/ShalokShalom/nim-pipexp) ⭐ 7 | 🐛 0 | 🌐 Nim | 📅 2022-12-10 - Expression-based pipe operators with placeholder argument for Nim.

### Pattern Matching

* [npeg](https://github.com/zevv/npeg) ⭐ 340 | 🐛 6 | 🌐 Nim | 📅 2024-08-22 - PEGs for Nim, another take.
* [patty](https://github.com/andreaferretti/patty) ⭐ 280 | 🐛 6 | 🌐 Nim | 📅 2023-04-04 - A pattern matching library for Nim.
* [regex](https://github.com/nitely/nim-regex) ⭐ 244 | 🐛 18 | 🌐 Nim | 📅 2026-08-25 - Pure Nim regex engine with linear time match.
* [ast\_pattern\_match](https://github.com/krux02/ast-pattern-matching) ⭐ 108 | 🐛 2 | 🌐 Nim | 📅 2023-11-29 - A library to do pattern matching on the AST.
* [gara](https://github.com/alehander42/gara) ⭐ 104 | 🐛 13 | 🌐 Nim | 📅 2020-06-16 - Macro-based pattern matching library.
* [glob](https://github.com/citycide/glob) ⭐ 70 | 🐛 5 | 🌐 Nim | 📅 2024-02-27 - Pure library for matching file paths against Unix style glob patterns.
* [tinyre](https://github.com/khchen/tinyre) ⭐ 45 | 🐛 0 | 🌐 Nim | 📅 2026-07-31 - A tiny regex engine based on Rob Pike's VM implementation.
* [awk](https://github.com/greencardamom/awk) ⭐ 31 | 🐛 0 | 🌐 Nim | 📅 2026-05-22 - A library of awk functions in Nim.
* [razaberi](https://github.com/Beglaa/razaberi) ⭐ 26 | 🐛 0 | 🌐 Nim | 📅 2025-10-25 - Pattern matching library, 2000+ test cases, exhaustiveness checking, deep destructuring support.

### Iteration

* [itertools](https://github.com/narimiran/itertools) ⭐ 143 | 🐛 1 | 🌐 Nim | 📅 2022-12-19 - Nim rewrite of a very popular Python module of the same name.
* [iterrr](https://github.com/hamidb80/iterrr) ⭐ 73 | 🐛 3 | 🌐 Nim | 📅 2023-12-30 - Macros-based functional-style, lazy-like, extensible iterator library.
* [loopfusion](https://github.com/numforge/loopfusion) ⭐ 42 | 🐛 4 | 🌐 Nim | 📅 2023-05-11 - Iterate efficiently over a variadic number of containers.
* [looper](https://github.com/b3liever/looper) ⭐ 10 | 🐛 0 | 🌐 Nim | 📅 2020-11-28 - For loop macros for Nim.

### Macros

* [with](https://github.com/zevv/with) ⭐ 89 | 🐛 2 | 🌐 Nim | 📅 2023-01-29 - The `with` macro for Nim.
* [memo](https://github.com/andreaferretti/memo) ⭐ 83 | 🐛 5 | 🌐 Nim | 📅 2022-02-25 - Memoization for Nim.
* [macroutils](https://github.com/PMunch/macroutils) ⭐ 68 | 🐛 4 | 🌐 Nim | 📅 2021-12-03 - A package that makes creating macros easier.
* [unpack](https://github.com/technicallyagd/unpack) ⭐ 57 | 🐛 0 | 🌐 Nim | 📅 2019-03-05 - Sequence/object unpacking/destructuring.
* [nimacros](https://github.com/FemtoEmacs/nimacros) ⭐ 43 | 🐛 3 | 🌐 Nim | 📅 2022-05-11 - Documentation for Nim macros.

## Operating System

### System API

* [winim](https://github.com/khchen/winim) ⭐ 515 | 🐛 22 | 🌐 Nim | 📅 2026-08-31 - Nim's Windows API and COM Library.
* [serial](https://github.com/euantorano/serial.nim) ⭐ 75 | 🐛 8 | 🌐 Nim | 📅 2024-01-24 - A Nim library for accessing serial ports.
* [nimbluez](https://github.com/Electric-Blue/NimBluez) ⭐ 28 | 🐛 1 | 🌐 Nim | 📅 2023-04-01 - Nim modules for access to system Bluetooth resources.
* [tempdir](https://github.com/euantorano/tempdir.nim) ⭐ 8 | 🐛 0 | 🌐 Nim | 📅 2021-03-25 - A Nim library to create and manage temporary directories.

### IO

* [faststreams](https://github.com/status-im/nim-faststreams) ⭐ 134 | 🐛 1 | 🌐 Nim | 📅 2026-08-25 - Nearly zero-overhead input/output streams for Nim.
* [lockfreequeues](https://github.com/elijahr/lockfreequeues) ⭐ 50 | 🐛 3 | 🌐 Nim | 📅 2026-09-01 - Lock-free queue implementations for Nim.
* [ioselectors](https://github.com/xflywind/ioselectors) ⭐ 25 | 🐛 2 | 🌐 Nim | 📅 2024-11-26 - The ioselectors plus for Nim.
* [wepoll](https://github.com/xflywind/wepoll) ⭐ 23 | 🐛 1 | 🌐 Nim | 📅 2024-11-26 - Windows epoll wrapper for Nim.
* [std/selectors](https://nim-lang.org/docs/selectors.html) - Epoll/Kqueue/Select implementation in Nim's stdlib.

### Processes

* [shell](https://github.com/Vindaar/shell) ⭐ 162 | 🐛 7 | 🌐 Nim | 📅 2024-02-09 - A mini Nim DSL to execute shell commands more conveniently.
* [schedules](https://github.com/soasme/nim-schedules) ⭐ 67 | 🐛 4 | 🌐 Nim | 📅 2021-07-23 - A Nim scheduler library that lets you kick off jobs at regular intervals.
* [psutil](https://github.com/johnscillieri/psutil-nim) ⭐ 63 | 🐛 5 | 🌐 Nim | 📅 2022-03-18 - A port of Python's psutil to Nim.
* [daemon](https://github.com/status-im/nim-daemon) ⭐ 37 | 🐛 1 | 🌐 Nim | 📅 2019-01-08 - Cross-platform process daemonization library for the Nim language.

### Date and Time

* [chrono](https://github.com/treeform/chrono) ⭐ 83 | 🐛 3 | 🌐 Nim | 📅 2026-05-25 - A timestamps, calendars, and timezones library.
* [timezones](https://github.com/GULPF/timezones) ⭐ 43 | 🐛 4 | 🌐 Nim | 📅 2021-06-29 - Nim timezone library compatible with the standard library.
* [datetime2human](https://github.com/juancarlospaco/nim-datetime2human) ⭐ 10 | 🐛 0 | 🌐 Nim | 📅 2023-10-12 - Calculate date & time with precision from seconds to millenniums. Human friendly date time as string. ISO-8601.

### Randomization

* [random](https://github.com/oprypin/nim-random) ⚠️ Archived - Random number generation library for Nim, inspired by Python's "random" module.
* [alea](https://github.com/andreaferretti/alea) ⭐ 46 | 🐛 3 | 🌐 Nim | 📅 2023-04-24 - Define and compose random variables.
* [sysrandom.nim](https://github.com/euantorano/sysrandom.nim) ⭐ 12 | 🐛 0 | 🌐 Nim | 📅 2018-10-03 - A Nim library to generate random numbers and random ranges of bytes using the system's PRNG.
* [drand48](https://github.com/JeffersonLab/drand48) ⭐ 2 | 🐛 1 | 🌐 Nim | 📅 2020-12-22 - Nim implementation of the standard Unix drand48 random number generator.

### Scripting

* [nimcr](https://github.com/PMunch/nimcr) ⭐ 87 | 🐛 4 | 🌐 Nim | 📅 2021-08-09 - Running Nim code with Shebangs.
* [nimr](https://github.com/Jeff-Ciesielski/nimr) ⭐ 47 | 🐛 1 | 🌐 Nim | 📅 2020-07-28 - Run Nim programs like scripts.
* [nimbang](https://github.com/jabbalaci/nimbang) ⭐ 7 | 🐛 1 | 🌐 Nim | 📅 2026-08-18 - Running Nim programs as scripts with shebang.

## System Tools

### Backups

* [norg](https://codeberg.org/pswilde/norgbackup) - A portable wrapper for borg and restic.

### Prometheus exporters

* [node-exporter-lite](https://github.com/twekkel/node_exporter-lite) ⭐ 1 | 🐛 0 | 🌐 Nim | 📅 2026-05-22 - An ultra‑light [node\_exporter](https://github.com/prometheus/node_exporter) ⭐ 13,748 | 🐛 300 | 🌐 Go | 📅 2026-08-31 replacement.
* [unbound-exporter-lite](https://github.com/twekkel/unbound_exporter-lite) ⭐ 1 | 🐛 0 | 🌐 Nim | 📅 2026-05-22 - An ultra‑light [unbound\_exporter](https://github.com/letsencrypt/unbound_exporter) ⭐ 275 | 🐛 18 | 🌐 Go | 📅 2026-06-04 replacement.

## Hardware

* [nimvisa](https://github.com/leeooox/nimvisa) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2020-11-04 - Wrapper for NI-VISA instrument control library.
* [ftd2xx](https://github.com/leeooox/ftd2xx) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2022-03-18 - Wrapper for FTDI ftd2xx library (USB to JTAG/SPI/I2C/Bitbang etc.).

### Embedded

* [Nesper](https://github.com/elcritch/nesper) ⭐ 246 | 🐛 7 | 🌐 C | 📅 2026-01-10 - Program the ESP32 using Nim. Library on top of esp-idf.
* [ratel](https://github.com/PMunch/ratel) ⭐ 131 | 🐛 4 | 🌐 Nim | 📅 2022-10-16 - Next-generation, zero-cost abstraction microconroller programming in Nim.
* [ardunimo](https://github.com/gokr/ardunimo) ⭐ 49 | 🐛 0 | 🌐 C | 📅 2016-02-25 - Nim wrapper for Arduino + LinkIt ONE SDK by Mediatek.
* [avr\_io](https://github.com/Abathargh/avr_io) ⭐ 28 | 🐛 0 | 🌐 Nim | 📅 2026-02-07 - Nim register bindings and utilities for AVR microcontrollers.
* [boneIO](https://github.com/xyz32/boneIO) ⭐ 16 | 🐛 0 | 🌐 Nim | 📅 2017-05-22 - GPIO implementation for the BeagleBone Black for Nim.
* [stm32f3](https://github.com/mwbrown/nim_stm32f3) ⭐ 14 | 🐛 0 | 🌐 Nimrod | 📅 2016-06-09 - Run Nim on STM32F3 micro-controller (16KB of RAM).
* [avrman](https://github.com/Abathargh/avrman) ⭐ 8 | 🐛 0 | 🌐 Nim | 📅 2026-02-07 - A tool for managing Nim and C projects targetting AVR microcontrollers.
* [ardunimesp](https://gitlab.com/NetaLabTek/Arduimesp) - Nim wrapper for Arduino ESP8266 framework + A tool for flashing, compiling and making a Nim project into an Arduino project.
* [msp430f5510](https://gitlab.com/jalexander8717/msp430f5510-nim) - Run Nim on MSP430f5510 micro-controller (6KB of RAM).

## Science

* [unchained](https://github.com/SciNim/Unchained) ⭐ 121 | 🐛 5 | 🌐 Nim | 📅 2025-11-20 - A fully type safe, compile time only units library.
* [qex](https://github.com/jcosborn/qex) ⭐ 60 | 🐛 4 | 🌐 Nim | 📅 2026-08-31 - High-level framework for lattice field operations.
* [orbits](https://github.com/treeform/orbits) ⭐ 56 | 🐛 0 | 🌐 Nim | 📅 2026-08-23 - Orbital mechanics library for Nim.
* [units](https://github.com/Udiknedormin/NimUnits) ⭐ 42 | 🐛 0 | 🌐 Nim | 📅 2018-12-23 - Statically-typed quantity units library for the Nim language.
* [metric](https://github.com/mjendrusch/metric) ⭐ 20 | 🐛 0 | 🌐 Nim | 📅 2018-08-07 - A small library providing type-level dimensional analysis.

## Data

### Database

#### Driver

* [litestore](https://github.com/h3rald/litestore) ⚠️ Archived - A lightweight, self-contained, RESTful, searchable, multi-format NoSQL document store.
* [redis](https://github.com/nim-lang/redis) ⭐ 131 | 🐛 12 | 🌐 Nim | 📅 2026-08-13 - Official redis wrapper for Nim.
* [nimongo](https://github.com/SSPkrolik/nimongo) ⭐ 101 | 🐛 21 | 🌐 Nim | 📅 2022-01-11 - Pure Nim lang MongoDB driver.
* [tiny\_sqlite](https://github.com/GULPF/tiny_sqlite) ⭐ 86 | 🐛 3 | 🌐 Nim | 📅 2023-07-10 - Very lightweight and safe SQLite library.
* [asyncpg](https://github.com/cheatfate/asyncpg) ⭐ 62 | 🐛 10 | 🌐 Nim | 📅 2021-10-04 - Asynchronous PostgreSQL driver for Nim.
* [SQLiteral](https://github.com/olliNiinivaara/SQLiteral) ⭐ 59 | 🐛 0 | 🌐 Nim | 📅 2026-07-31 - A high level SQLite API for Nim.
* [limdb](https://github.com/capocasa/limdb) ⭐ 45 | 🐛 4 | 🌐 Nim | 📅 2026-02-11 - Very high performance, persistent and safe key-value store based on LMDB with Nim table-like interface.
* [anonimongo](https://github.com/mashingan/anonimongo) ⭐ 44 | 🐛 11 | 🌐 Nim | 📅 2026-06-20 - Another Nim pure Mongo DB driver.
* [rocksdb](https://github.com/status-im/nim-rocksdb) ⭐ 41 | 🐛 3 | 🌐 Nim | 📅 2026-09-01 - Nim wrapper for RocksDB, a persistent key-value store for flash and RAM Storage.
* [amysql](https://github.com/bung87/amysql) ⭐ 31 | 🐛 4 | 🌐 Nim | 📅 2025-07-03 - Async MySQL Connector write in pure Nim.
* [db\_connector](https://github.com/nim-lang/db_connector) ⭐ 27 | 🐛 19 | 🌐 Nim | 📅 2026-02-11 - Unified db connector in Nim.
* [KoutenDB](https://github.com/puffball1567/koutendb) ⭐ 16 | 🐛 1 | 🌐 Nim | 📅 2026-08-29 - Locality-aware NoSQL document/vector database built around rings and orbit-inspired retrieval.
* [surrealdb.nim](https://github.com/Xkonti/surrealdb.nim) ⭐ 15 | 🐛 2 | 🌐 Nim | 📅 2025-11-21 - SurrealDB driver for Nim.
* [asyncmysql](https://github.com/tulayang/asyncmysql) ⭐ 12 | 🐛 3 | 🌐 Nim | 📅 2020-10-10 - Asynchronous MySQL connector written in pure Nim.
* [mycouch](https://github.com/hamidb80/mycouch) ⭐ 8 | 🐛 1 | 🌐 Nim | 📅 2023-08-06 - Multisync CouchDB driver for Nim.
* [sqlcipher](https://github.com/status-im/nim-sqlcipher) ⭐ 5 | 🐛 4 | 🌐 Nim | 📅 2021-07-28 - SQLCipher wrapper.
* [kuzu](https://github.com/mahlonsmith/nim-kuzu) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2026-08-29 - Wrapper for Kuzu - an embedded graph database built for query speed and scalability.

#### ORM

* [norm](https://github.com/moigagoo/norm) ⭐ 415 | 🐛 21 | 🌐 Nim | 📅 2026-08-05 - Norm is an object-oriented, framework-agnostic ORM for Nim that supports SQLite and PostgreSQL.
* [ormin](https://github.com/Araq/ormin) ⭐ 199 | 🐛 10 | 🌐 Nim | 📅 2026-04-29 - Prepared SQL statement generator , A lightweight ORM.
* [allographer](https://github.com/itsumura-h/nim-allographer) ⭐ 170 | 🐛 15 | 🌐 Nim | 📅 2026-04-04 - A query\_builder/ORM library inspired by Laravel/PHP and Orator/Python for Nim.
* [gatabase](https://github.com/juancarlospaco/nim-gatabase) ⭐ 123 | 🐛 3 | 🌐 Nim | 📅 2022-10-10 - Connection-Pooling Compile-Time ORM for Nim.

### Data Structures

* [kdtree](https://github.com/jblindsay/kdtree) ⭐ 43 | 🐛 0 | 🌐 Nim | 📅 2020-11-10 - A pure Nim k-d tree implementation for efficient spatial querying of point data.
* [StashTable](https://github.com/olliNiinivaara/StashTable) ⭐ 35 | 🐛 1 | 🌐 Nim | 📅 2023-08-24 - Concurrent hash tables for Nim.
* [RTree](https://github.com/StefanSalewski/RTree) ⭐ 26 | 🐛 1 | 🌐 Nim | 📅 2021-04-03 - Generic R-tree implementation for Nim.
* [rbtree](https://github.com/Nycto/RBTreeNim) ⭐ 24 | 🐛 0 | 🌐 Nim | 📅 2023-09-30 - A Red/Black tree implementation in Nim.
* [sorta](https://github.com/narimiran/sorta) ⭐ 21 | 🐛 2 | 🌐 Nim | 📅 2020-06-07 - SortedTables in Nim, based on B-trees.
* [binaryheap](https://github.com/bluenote10/nim-heap) ⭐ 20 | 🐛 1 | 🌐 Nim | 📅 2021-06-09 - Simple binary heap implementation in Nim.
* [BitVector](https://github.com/MarcAzar/BitVector) ⭐ 17 | 🐛 2 | 🌐 Nim | 📅 2026-06-15 - A high-performance Nim implementation of BitVectors.
* [bloom](https://github.com/boydgreenfield/nimrod-bloom) ⭐ 16 | 🐛 1 | 🌐 Nim | 📅 2023-05-26 - Bloom filter implementation in Nim.
* [faststack](https://github.com/Vladar4/FastStack) ⭐ 14 | 🐛 0 | 🌐 Nimrod | 📅 2016-08-19 - Dynamically resizable data structure for fast iteration over large arrays of similar elements.
* [quadtree](https://github.com/Nycto/QuadtreeNim) ⭐ 10 | 🐛 1 | 🌐 Nim | 📅 2019-03-27 - A Quadtree library for Nim.
* [BipBuffer](https://github.com/MarcAzar/BipBuffer) ⭐ 6 | 🐛 0 | 🌐 Nim | 📅 2026-01-14 - A Nim implementation of Simon Cooke's Bib Buffer
* [minmaxheap](https://github.com/StefanSalewski/minmaxheap) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2019-03-15 - A Nim implementation of a Minimum-Maximum heap.

### Data Processing

* [NimData](https://github.com/bluenote10/NimData) ⭐ 342 | 🐛 30 | 🌐 Nim | 📅 2021-06-09 - DataFrame API written in Nim, enabling fast out-of-core data processing.
* [Datamancer](https://github.com/SciNim/Datamancer) ⭐ 151 | 🐛 9 | 🌐 Nim | 📅 2025-04-16 - A dataframe library with a dplyr like API.
* [nimhdf5](https://github.com/Vindaar/nimhdf5) ⭐ 30 | 🐛 14 | 🌐 Nim | 📅 2024-11-08 - Wrapper and some simple high-level bindings for the HDF5 library for Nim.
* [mpfit](https://github.com/Vindaar/nim-mpfit) ⭐ 19 | 🐛 2 | 🌐 C | 📅 2025-03-18 - A wrapper for the cMPFIT library for Nim.
* [nimdataframe](https://github.com/qqtop/nimdataframe) ⭐ 15 | 🐛 0 | 🌐 Nim | 📅 2019-07-25 - Dataframe for Nim.

### Parsing

* [NimYAML](https://github.com/flyx/NimYAML) ⭐ 209 | 🐛 5 | 🌐 Nim | 📅 2026-05-30 - YAML implementation for Nim.
* [parsetoml](https://github.com/NimParsers/parsetoml) ⭐ 131 | 🐛 11 | 🌐 Nim | 📅 2025-01-12 - A Nim library to parse TOML files.
* [Binarylang](https://github.com/sealmove/binarylang) ⭐ 64 | 🐛 6 | 🌐 Nim | 📅 2023-06-18 - Extensible Nim DSL for creating binary parsers/encoders in a symmetric fashion.
* [beautifulparser](https://github.com/TelegramXPlus/beautifulparser) ⭐ 16 | 🐛 0 | 🌐 Nim | 📅 2025-08-29 - Simple library for parsing HTML documents inspired by beautifulsoup4.
* [Marvdown](https://github.com/openpeeps/marvdown) ⭐ 13 | 🐛 1 | 🌐 Nim | 📅 2026-08-31 - A stupid simple Markdown parser.
* [iniplus](https://codeberg.org/onbox/iniplus) - Extended INI parser with support for arrays and tables.

### Serialization

* [protobuf-nim](https://github.com/PMunch/protobuf-nim) ⭐ 175 | 🐛 12 | 🌐 Nim | 📅 2023-10-17 - Protobuf implementation in pure Nim that leverages the power of the macro system to not depend on any external tools.
* [flatty](https://github.com/treeform/flatty) ⭐ 95 | 🐛 1 | 🌐 Nim | 📅 2026-08-13 - Tools and serializer for plain flat binary files.
* [serialization](https://github.com/status-im/nim-serialization) ⭐ 78 | 🐛 12 | 🌐 Nim | 📅 2026-08-24 - A modern and extensible serialization framework for Nim.
* [json-serialization](https://github.com/status-im/nim-json-serialization) ⭐ 55 | 🐛 8 | 🌐 Nim | 📅 2026-08-25 - Flexible JSON serialization not relying on run-time type information.
* [frosty](https://github.com/disruptek/frosty) ⭐ 49 | 🐛 1 | 🌐 Nim | 📅 2021-11-12 - Marshal native Nim objects via streams, sockets.
* [toml-serialization](https://github.com/status-im/nim-toml-serialization) ⭐ 46 | 🐛 4 | 🌐 Nim | 📅 2026-08-24 - Flexible TOML serialization `not` relying on run-time type information.
* [protobuf-serialization](https://github.com/status-im/nim-protobuf-serialization) ⭐ 27 | 🐛 6 | 🌐 Nim | 📅 2026-08-25 - The nim-protobuf-serialization.
* [bingo](https://github.com/planetis-m/bingo) ⭐ 20 | 🐛 5 | 🌐 Nim | 📅 2024-04-05 - Binary serialization framework for Nim.
* [ssz-serialization](https://github.com/status-im/nim-ssz-serialization) ⭐ 11 | 🐛 4 | 🌐 Nim | 📅 2026-08-18 - Nim implementation of Simple Serialize (SSZ) serialization and merkleization.
* [tnetstring](https://github.com/mahlonsmith/nim-tnetstring) ⭐ 0 | 🐛 0 | 🌐 Nim | 📅 2025-06-28 - Parsing and serializing for the TNetstring format.
* [nesm](https://xomachine.gitlab.io/NESM/) - NESM is a tool that generates serialization and deserialization code for a given object.

### Standards

* [isocodes](https://github.com/kraptor/isocodes) ⭐ 14 | 🐛 3 | 🌐 Nim | 📅 2024-11-07 - ISO codes for Nim (ISO 3166-1, ISO 3166-2, ISO 3166-3, ISO 15924, ISO 15924, ISO 639-2, ISO 639-5)

## Text

### String Types

* [ssostrings](https://github.com/planetis-m/ssostrings) ⭐ 17 | 🐛 4 | 🌐 Nim | 📅 2024-10-07 - Small String Optimized (SSO) string implementation.
* [cowstrings](https://github.com/planetis-m/cowstrings) ⭐ 17 | 🐛 3 | 🌐 Nim | 📅 2024-10-07 - Copy-On-Write string implementation according to nim-lang/RFCs#221.

### Translation

* [tinyslation](https://github.com/juancarlospaco/nim-tinyslation) ⭐ 12 | 🐛 0 | 🌐 Nim | 📅 2019-06-06 - Text string translation from free online crowdsourced API.

### Markdown

* [HastyScribe](https://github.com/h3rald/hastyscribe) ⚠️ Archived - Self-contained markdown compiler generating self-contained HTML documents.
* [markdown](https://github.com/soasme/nim-markdown) ⭐ 155 | 🐛 19 | 🌐 Nim | 📅 2025-12-09 - A beautiful Markdown Parser in the Nim world.
* [lester](https://github.com/madprops/lester) ⭐ 6 | 🐛 0 | 🌐 Nim | 📅 2022-01-24 - Create quick documents out of Markdown, into HTML.

## Multimedia

### Audio

* [omni](https://github.com/vitreo12/omni) ⭐ 202 | 🐛 58 | 🌐 Nim | 📅 2024-03-29 - A DSL for low-level audio programming.
* [paramidi](https://github.com/paranim/paramidi) ⭐ 76 | 🐛 2 | 🌐 Nim | 📅 2023-03-16 - A Nim library for making MIDI music.
* [wave](https://github.com/jiro4989/wave) ⭐ 22 | 🐛 1 | 🌐 Nim | 📅 2023-10-11 - A tiny WAV sound module.
* [parasound](https://github.com/paranim/parasound) ⭐ 13 | 🐛 0 | 🌐 Nim | 📅 2022-02-06 - A library to provide Nim bindings for miniaudio and dr\_wav.
* [jacket](https://github.com/SpotlightKid/jacket) ⭐ 8 | 🐛 0 | 🌐 Nim | 📅 2025-06-22 - A Nim wrapper for the libjack C library to write clients for the JACK audio server.

### Images

* [pixie](https://github.com/treeform/pixie) ⭐ 810 | 🐛 18 | 🌐 Nim | 📅 2026-08-23 - A full-featured 2D graphics library for Nim.
* [nimsvg](https://github.com/bluenote10/NimSvg) ⭐ 147 | 🐛 3 | 🌐 Nim | 📅 2022-10-10 - A Nim-based DSL allowing generation of SVG files and GIF animations.
* [nimpng](https://github.com/jangko/nimPNG) ⭐ 93 | 🐛 7 | 🌐 Nim | 📅 2025-04-17 - PNG (Portable Network Graphics) decoder and encoder written in Nim.
* [nimbmp](https://github.com/jangko/nimBMP) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2021-01-23 - BMP decoder and encoder written in Nim.
* [pnm](https://github.com/jiro4989/pnm) ⭐ 6 | 🐛 2 | 🌐 Nim | 📅 2021-03-20 - Library for PNM (Portable Anymap) in Nim.

### Documents

* [nimpdf](https://github.com/jangko/nimpdf) ⭐ 187 | 🐛 12 | 🌐 Nim | 📅 2025-11-26 - PDF document writer, written in Nim.

## Algorithms

### Math

#### Symbolic

* [symbolicnim](https://github.com/HugoGranstrom/symbolicnim) ⭐ 40 | 🐛 0 | 🌐 Nim | 📅 2020-10-25 - A symbolic library written purely in Nim.

#### FFT

* [impulse](https://github.com/SciNim/impulse) ⭐ 17 | 🐛 0 | 🌐 Nim | 📅 2024-12-30 - Impulse will be a collection of primitives for signal processing (FFT, Convolutions).

#### Vector

* [vmath](https://github.com/treeform/vmath) ⭐ 116 | 🐛 2 | 🌐 Nim | 📅 2026-08-07 - Math vector library for graphical things.
* [vectorize](https://github.com/SciNim/vectorize) ⭐ 17 | 🐛 1 | 🌐 Nim | 📅 2020-05-30 - SIMD vectorization backend.

#### Matrix

* [neo](https://github.com/unicredit/neo) ⭐ 258 | 🐛 19 | 🌐 HTML | 📅 2024-08-28 - A matrix library.
* [manu](https://github.com/planetis-m/manu) ⚠️ Archived - Nim MAtrix NUmeric package - a port of JAMA, adapted to Nim.
* [nlopt](https://github.com/Vindaar/nimnlopt) ⭐ 14 | 🐛 2 | 🌐 Nim | 📅 2022-02-08 - A wrapper for the nonlinear optimization library Nlopt.

### Deep Learning

* [Arraymancer](https://github.com/mratsim/Arraymancer) ⭐ 1,407 | 🐛 165 | 🌐 Nim | 📅 2026-05-26 - A fast, ergonomic and portable tensor library in Nim with a deep learning focus for CPU, GPU, OpenCL and embedded devices.
* [NimTorch](https://github.com/sinkingsugar/nimtorch) ⭐ 473 | 🐛 10 | 🌐 Nim | 📅 2019-06-08 - PyTorch - Python + Nim. A Nim front-end to PyTorch's native backend, combining Nim's speed, productivity and portability with PyTorch's latest implementations.
* [laser](https://github.com/numforge/laser) ⭐ 295 | 🐛 19 | 🌐 Nim | 📅 2024-01-04 - Carefully-tuned primitives for running tensor and image-processing code on CPU, GPUs and accelerators.

<!-- - [flambeau](https://github.com/SciNim/flambeau) - Nim bindings to libtorch. -->

### Bigints

* [bigints](https://github.com/nim-lang/bigints) ⭐ 128 | 🐛 28 | 🌐 Nim | 📅 2025-11-24 - Bigints for Nim.
* [stint](https://github.com/status-im/nim-stint) ⭐ 93 | 🐛 17 | 🌐 Nim | 📅 2026-08-30 - Stack-based arbitrary-precision integers. Fast and portable with natural syntax for resource-restricted devices.
* [theo](https://github.com/SciNim/theo) ⭐ 27 | 🐛 2 | 🌐 Nim | 📅 2022-03-02 - An optimized bigint and number theory library for Nim.

### Cryptography

* [constantine](https://github.com/mratsim/constantine) ⭐ 496 | 🐛 95 | 🌐 Nim | 📅 2026-08-04 - Constant time pairing-based of elliptic curve based cryptography and digital signatures.
* [nimcrypto](https://github.com/cheatfate/nimcrypto) ⭐ 218 | 🐛 15 | 🌐 Nim | 📅 2026-07-06 - Nim cryptographic library.
* [nimaes](https://github.com/jangko/nimAES) ⭐ 55 | 🐛 3 | 🌐 Nim | 📅 2022-08-09 - Advanced Encryption Standard, Rinjdael Algorithm written in Nim.
* [hashlib](https://github.com/khchen/hashlib) ⭐ 39 | 🐛 2 | 🌐 Nim | 📅 2023-11-30 - Hash library that contains almost all the hash functions for Nim.
* [bslcurve](https://github.com/status-im/nim-blscurve) ⭐ 27 | 🐛 6 | 🌐 Nim | 📅 2026-08-24 - Nim implementation of BLS signature scheme (Boneh-Lynn-Shacham) over Barreto-Lynn-Scott (BLS) curve BLS12-381.
* [xxhash.nim](https://github.com/OpenSystemsLab/xxhash.nim) ⭐ 20 | 🐛 0 | 🌐 Nim | 📅 2025-03-20 - A wrapper for the xxhash hashing library in Nim.
* [xxtea](https://github.com/xxtea/xxtea-nim) ⭐ 19 | 🐛 1 | 🌐 HTML | 📅 2021-05-24 - XXTEA encryption algorithm library.
* [crc32](https://github.com/juancarlospaco/nim-crc32) ⭐ 18 | 🐛 0 | 🌐 Nim | 📅 2026-04-02 - CRC32 for Nim. Just pass the thing you want to do CRC.
* [rollinghash](https://github.com/MarcAzar/RollingHash) ⭐ 16 | 🐛 0 | 🌐 Nim | 📅 2019-04-02 - High performance Nim implementation of a Cyclic Polynomial Hash, aka BuzHash, and the Rabin-Karp algorithm.
* [NiMPC](https://github.com/markspanbroek/nimpc) ⭐ 11 | 🐛 0 | 🌐 Nim | 📅 2020-06-18 - A secure multi-party computation (MPC) library for the Nim programming language.
* [murmurhash](https://github.com/cwpearson/nim-murmurhash) ⭐ 8 | 🐛 0 | 🌐 Nim | 📅 2019-08-22 - Pure Nim implementation of MurmerHash
* [shimsham](https://github.com/apense/shimsham) ⭐ 8 | 🐛 1 | 🌐 Nimrod | 📅 2015-09-17 - A collection of hash functions, including JH, SHA-2, SHA-3, SipHash, Tiger, and Whirlpool.
* [bncurve](https://github.com/status-im/nim-bncurve) ⭐ 6 | 🐛 2 | 🌐 Nim | 📅 2026-07-07 - Nim implementation of Barreto-Naehrig pairing-friendly elliptic curve.
* [des](https://github.com/LucaWolf/des.nim) ⭐ 6 | 🐛 0 | 🌐 Nim | 📅 2019-09-24 - DES/3DES, DUKPT and MAC in Nim.
* [bcryptrocks](https://codeberg.org/penguinite/bcryptrocks) -  Nim wrapper of Solar Designer's `crypt_blowfish` library

### Blockchain

* [nimbus-eth2](https://github.com/status-im/nimbus-eth2) ⭐ 661 | 🐛 225 | 🌐 Nim | 📅 2026-09-01 - Efficient implementation of the Ethereum 2.0 blockchain.
* [nimbus-eth1](https://github.com/status-im/nimbus-eth1) ⭐ 628 | 🐛 112 | 🌐 Nim | 📅 2026-09-01 - An Ethereum 1.0 and 2.0 client for resource-restricted devices.
* [eth](https://github.com/status-im/nim-eth) ⭐ 93 | 🐛 46 | 🌐 Nim | 📅 2026-09-01 - Common utilities for Ethereum.
* [evmc](https://github.com/status-im/nim-evmc) ⭐ 15 | 🐛 1 | 🌐 Nim | 📅 2025-02-17 - Ethereum VM binary compatible interface.
* [ethash](https://github.com/status-im/nim-ethash) ⭐ 6 | 🐛 6 | 🌐 Nim | 📅 2025-02-24 - A pure-Nim implementation of Ethash, the Ethereum proof of work.
* [contract-abi](https://github.com/status-im/nim-contract-abi) ⭐ 3 | 🐛 1 | 🌐 Nim | 📅 2025-12-10 - Implements encoding of parameters according to the Ethereum Contract ABI specification.

<!-- - [web3](https://github.com/status-im/nim-web3) - The humble beginnings of a Nim library similar to web3.[js|py]. -->

<!-- - [abc](https://github.com/status-im/nim-abc) - Experimental asynchronous blockchain. -->

<!-- - [nitro](https://github.com/status-im/nim-nitro) - Highly experimental implementation of the Nitro statechannels protocol in Nim. -->

### Compression

* [zippy](https://github.com/guzba/zippy) ⭐ 282 | 🐛 21 | 🌐 Nim | 📅 2026-08-20 - Pure Nim implementation of deflate, zlib, gzip and zip.
* [supersnappy](https://github.com/guzba/supersnappy) ⭐ 94 | 🐛 1 | 🌐 Nim | 📅 2025-12-26 - Dependency-free and performant Nim Snappy implementation.
* [zip](https://github.com/nim-lang/zip) ⭐ 57 | 🐛 18 | 🌐 C | 📅 2024-11-26 - Wrapper for the zip library.
* [snappy](https://github.com/status-im/nim-snappy) ⭐ 28 | 🐛 1 | 🌐 Nim | 📅 2026-09-01 - Nim implementation of Snappy compression algorithm.

## User Interface

### Terminal

* [illwill](https://github.com/johnnovak/illwill) ⭐ 469 | 🐛 5 | 🌐 Nim | 📅 2026-05-15 - Simple cross-platform terminal library inspired by (n)curses.
* [jn](https://github.com/joereynolds/jn) ⭐ 64 | 🐛 40 | 🌐 Nim | 📅 2026-08-20 - A CLI note taker and task manager.
* [Nimmm](https://github.com/joachimschmidt557/nimmm) ⭐ 51 | 🐛 1 | 🌐 Nim | 📅 2026-05-30 - A terminal file manager for Linux.
* [pnimrp](https://github.com/bloomingchad/pnimrp) ⭐ 5 | 🐛 1 | 🌐 Nim | 📅 2026-08-15 - Stream your favorite radio stations at the comfort of your terminal.
* [prettyterm](https://github.com/CodeLibraty/prettyterm) ⭐ 3 | 🐛 0 | 🌐 Nim | 📅 2025-08-13 - Library for creating beautiful terminal interfaces in Nim.
* [niffler](https://github.com/gokr/niffler) ⭐ 2 | 🐛 1 | 🌐 Nim | 📅 2026-08-31 - Command line AI assistant written in Nim.
* [pager](https://git.sr.ht/~reesmichael1/nim-pager) - A simple command line pager library, written in Nim.

### Design

* [typography](https://github.com/treeform/typography) ⭐ 150 | 🐛 2 | 🌐 Nim | 📅 2026-08-23 - Fonts, typesetting and rasterization.
* [chroma](https://github.com/treeform/chroma) ⭐ 109 | 🐛 1 | 🌐 Nim | 📅 2026-05-25 - Everything you want to do with colors, in Nim.
* [trick](https://github.com/exelotl/trick) ⭐ 32 | 🐛 2 | 🌐 Nim | 📅 2026-05-16 - Library for GBA/NDS image conversion, and more!
* [HexToAnsi](https://github.com/farias-hecdin/HexToAnsi/blob/main/src/nim/README.md) ⭐ 0 | 🐛 0 | 🌐 Nim | 📅 2024-10-02 - Convert hexadecimal colors to ANSI colors.

### GUI

#### Crossplatform

* [nimx](https://github.com/yglukhov/nimx) ⭐ 1,191 | 🐛 35 | 🌐 Nim | 📅 2026-07-25 - Desktop, Mobile & Web GUI framework in Nim.
* [NiGui](https://github.com/trustable-code/NiGui) ⭐ 784 | 🐛 65 | 🌐 Nim | 📅 2026-04-07 - A cross-platform, desktop GUI toolkit.
* [Owlkettle](https://github.com/can-lehmann/owlkettle) ⭐ 451 | 🐛 20 | 🌐 Nim | 📅 2026-07-20 - Declarative user interface framework based on GTK.
* [SDL2](https://github.com/nim-lang/sdl2) ⭐ 254 | 🐛 3 | 🌐 Nim | 📅 2026-04-21 - Official wrapper for SDL 2.x.
* [ui](https://github.com/nim-lang/ui) ⭐ 244 | 🐛 18 | 🌐 Nim | 📅 2023-01-25 - Wrapper for libui. Beginnings of what might become Nim's official UI library.
* [uing](https://github.com/neroist/uing) ⭐ 192 | 🐛 2 | 🌐 Nim | 📅 2026-07-08 - Wrapper & bindings for libui-ng, an updated and maintained fork of libui.
* [SDL2](https://github.com/Vladar4/sdl2_nim) ⭐ 148 | 🐛 8 | 🌐 Nim | 📅 2022-05-07 - A wrapper for SDL 2.
* [iup](https://github.com/nim-lang/iup) ⭐ 51 | 🐛 4 | 🌐 Nim | 📅 2021-09-20 - Wrapper for IUP. Beginnings of what might become Nim's official UI library.
* [libtray](https://github.com/neroist/libtray) ⭐ 16 | 🐛 0 | 🌐 Nim | 📅 2024-05-29 - Nim wrapper for Tray (dmikushin's fork), a library to create system tray/menu bar icon with a popup menu.

#### Windows

* [wNim](https://github.com/khchen/wNim) ⭐ 352 | 🐛 34 | 🌐 Nim | 📅 2024-07-19 - Nim's Windows GUI Framework.

#### Linux

* [gintro](https://github.com/StefanSalewski/gintro) ⭐ 301 | 🐛 103 | 🌐 Nim | 📅 2023-05-19 - High-level GObject-Introspection based GTK3/GTK4 bindings for Nim.
* [nimqml](https://github.com/filcuc/nimqml) ⭐ 174 | 🐛 6 | 🌐 Nim | 📅 2025-02-05 - Qt QML bindings for the Nim programming language.

#### Web Technology

* [Neel](https://github.com/Niminem/Neel) ⭐ 252 | 🐛 1 | 🌐 Nim | 📅 2023-11-30 - A library for making Electron-like HTML/JS GUI apps.
* [webui](https://github.com/webui-dev/nim-webui) ⭐ 164 | 🐛 10 | 🌐 HTML | 📅 2026-03-24 - Nim bindings and wrapper for WebUI.
* [nimview](https://github.com/marcomq/nimview) ⭐ 163 | 🐛 8 | 🌐 Nim | 📅 2022-09-18 - A Nim/Webview based helper to create desktop/server applications with Nim and HTML/CSS.
* [webgui](https://github.com/juancarlospaco/webgui) ⭐ 146 | 🐛 4 | 🌐 Nim | 📅 2026-08-17 - Web technologies based cross-platform GUI Framework with a dark theme.
* [webview](https://github.com/neroist/webview) ⭐ 50 | 🐛 3 | 🌐 Nim | 📅 2026-05-03 - Nim bindings and wrapper for Webview.
* [fidget2](https://github.com/treeform/fidget2) ⭐ 39 | 🐛 4 | 🌐 Nim | 📅 2026-08-23 - Library for natively compiled cross platform UIs - Web with HTML5 (WASM), Windows, macOS, Linux with OpenGL.

#### Lightweight

* [imgui](https://github.com/nimgl/imgui) ⭐ 151 | 🐛 4 | 🌐 C++ | 📅 2025-12-20 - ImGui bindings for Nim via cimgui.
* [koi](https://github.com/johnnovak/koi) ⭐ 112 | 🐛 0 | 🌐 Nim | 📅 2026-01-01 - Immediate mode UI for Nim.
* [nimAntTweakBar](https://github.com/krux02/nimAntTweakBar) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2021-09-19 - Wrapper for AntTweakBar.

### Plotting

* [ggplotnim](https://github.com/Vindaar/ggplotnim) ⭐ 188 | 🐛 27 | 🌐 Nim | 📅 2026-02-24 - A port of ggplot2 for Nim.
* [plotly](https://github.com/SciNim/nim-plotly) ⭐ 185 | 🐛 23 | 🌐 Nim | 📅 2024-04-09 - A plotly wrapper for Nim.
* [graph](https://github.com/stisa/graph) ⭐ 28 | 🐛 0 | 🌐 Nim | 📅 2020-08-28 - A basic plotting library in Nim.
* [nimgraphviz](https://github.com/Aveheuzed/nimgraphviz) ⭐ 11 | 🐛 0 | 🌐 Nim | 📅 2026-04-25 - A Nim library for making graphs with GraphViz and DOT.
* [nimgnuplot](https://github.com/nervecenter/nimgnuplot) ⭐ 11 | 🐛 0 | 🌐 Nim | 📅 2025-10-17 - A simple gnuplot interface for Nim, compatible with Datamancer dataframes.
* [nimetry](https://github.com/refaqtor/nimetry) ⭐ 7 | 🐛 0 | 📅 2019-06-16 - Simple plotting in pure Nim.

## Mobile

* [react-native-nim](https://github.com/siddarthkay/react-native-nim) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2026-05-28 - A react-native template which demonstrates nim interop with iOS/Android mobile client from react-native.

## Web

### Protocols

* [libp2p](https://github.com/status-im/nim-libp2p) ⭐ 321 | 🐛 105 | 🌐 Nim | 📅 2026-09-01 - A Nim implementation of the libp2p networking stack.
* [puppy](https://github.com/treeform/puppy) ⭐ 206 | 🐛 12 | 🌐 Nim | 📅 2026-05-25 - Puppy fetches HTML pages for Nim.
* [netty](https://github.com/treeform/netty) ⭐ 130 | 🐛 0 | 🌐 Nim | 📅 2026-07-14 - Reliable UDP connection library for games in Nim.
* [json-rpc](https://github.com/status-im/nim-json-rpc) ⭐ 101 | 🐛 9 | 🌐 Nim | 📅 2026-08-29 - Nim library for implementing JSON-RPC clients and servers.
* [presto](https://github.com/status-im/nim-presto) ⭐ 84 | 🐛 9 | 🌐 Nim | 📅 2026-08-25 - An efficient REST API framework.
* [nmqtt](https://github.com/zevv/nmqtt) ⭐ 53 | 🐛 9 | 🌐 Nim | 📅 2026-08-16 - Native Nim MQTT client library.
* [yahttp](https://github.com/mishankov/yahttp) ⭐ 30 | 🐛 7 | 🌐 Nim | 📅 2026-07-01 - Awesome simple HTTP client.
* [http-utils](https://github.com/status-im/nim-http-utils) ⭐ 28 | 🐛 2 | 🌐 Nim | 📅 2026-08-25 - HTTP helper procedures.
* [webdavclient](https://github.com/beshrkayali/webdavclient) ⭐ 10 | 🐛 1 | 🌐 Nim | 📅 2026-06-06 - WebDAV client for Nim.
* [gemini](https://github.com/benob/gemini) ⭐ 4 | 🐛 1 | 🌐 Nim | 📅 2021-03-20 - Building blocks for creating Gemini servers and clients.
* [libp2p-dht](https://github.com/status-im/nim-libp2p-dht) ⭐ 3 | 🐛 17 | 🌐 Nim | 📅 2026-08-03 - DHT based on the libp2p kademlia spec.
* [stomp](https://github.com/subsetpark/nim-stomp) ⭐ 0 | 🐛 0 | 🌐 Nim | 📅 2018-04-06 - A pure-Nim client library for interacting with Stomp compliant message brokers.

#### DNS

* [ndns](https://github.com/rockcavera/nim-ndns) ⭐ 27 | 🐛 1 | 🌐 Nim | 📅 2025-10-21 - A pure Nim Domain Name System (DNS) client.
* [dnsprotocol](https://github.com/rockcavera/nim-dnsprotocol) ⭐ 20 | 🐛 0 | 🌐 Nim | 📅 2025-02-06 - Domain Name System (DNS) protocol for Nim programming language.

#### QUIC

* [quic](https://github.com/status-im/nim-quic) ⭐ 46 | 🐛 6 | 🌐 Nim | 📅 2025-11-05 - QUIC for Nim. This is very much a work in progress, and not yet in a usable state.
* [ngtcp2](https://github.com/status-im/nim-ngtcp2) ⭐ 5 | 🐛 1 | 🌐 Nim | 📅 2025-10-16 - A wrapper around ngtcp2: an effort to implement IETF QUIC protocol.

#### Websockets

* [ws](https://github.com/treeform/ws) ⭐ 265 | 🐛 8 | 🌐 Nim | 📅 2026-05-25 - Simple WebSocket library for Nim.
* [websocket.nim](https://github.com/niv/websocket.nim) ⭐ 103 | 🐛 8 | 🌐 Nim | 📅 2022-12-04 - WebSockets for Nim.
* [websock](https://github.com/status-im/nim-websock) ⭐ 92 | 🐛 17 | 🌐 Nim | 📅 2026-09-01 - An implementation of the WebSocket protocol for Nim.
* [news](https://github.com/Tormund/news) ⭐ 36 | 🐛 0 | 🌐 Nim | 📅 2023-04-01 - Nim Easy WebSocket. Based on ws.
* [jswebsockets](https://juancarlospaco.github.io/nodejs/nodejs/jswebsockets) - WebSockets optimized for JavaScript targets.

#### Messaging

* [nwaku](https://github.com/status-im/nwaku) ⭐ 248 | 🐛 250 | 🌐 Nim | 📅 2026-09-01 - Implementation of the Waku v1 and v2 protocols.
* [dimscord](https://github.com/krisppurg/dimscord) ⭐ 240 | 🐛 4 | 🌐 Nim | 📅 2026-06-21 - A Discord Bot & REST Library for Nim.
* [telebot.nim](https://github.com/ba0f3/telebot.nim) ⭐ 192 | 🐛 0 | 🌐 Nim | 📅 2026-08-20 - Async client for Telegram Bot API in pure Nim.
* [status](https://github.com/status-im/nim-status) ⭐ 9 | 🐛 37 | 🌐 Nim | 📅 2021-09-14 - Nim implementation of the Status protocol.

#### Multicast

* [nimMulticast](https://github.com/enthus1ast/nimMulticast) ⭐ 14 | 🐛 0 | 🌐 Nim | 📅 2024-05-20 - UDP Multicast made simple.

### HTML Parsers

* [Nimquery](https://github.com/GULPF/nimquery) ⭐ 139 | 🐛 0 | 🌐 Nim | 📅 2022-12-06 - Library for querying HTML using CSS selectors, like JavaScript's `document.querySelector`.

### HTTP Servers

* [httpbeast](https://github.com/dom96/httpbeast) ⭐ 473 | 🐛 19 | 🌐 Nim | 📅 2024-01-07 - A highly performant, multi-threaded HTTP 1.1 server ([top 10 in FrameworkBenchmarks](https://www.techempower.com/benchmarks/#section=data-r18\&test=json)).
* [Mummy](https://github.com/guzba/mummy) ⭐ 339 | 🐛 9 | 🌐 Nim | 📅 2026-04-30 - A multi-threaded HTTP 1.1 server with first-class support for WebSockets.
* [httpx](https://github.com/ringabout/httpx) ⭐ 100 | 🐛 12 | 🌐 Nim | 📅 2024-11-26 - Cross platform web server for Nim. A fork of httpbeast adding Windows support.
* [GuildenStern](https://github.com/olliNiinivaara/GuildenStern) ⭐ 96 | 🐛 0 | 🌐 Nim | 📅 2026-07-26 - Genuinely multithreading integrated HTTP/1.1 + WebSocket v13 Server for POSIX-compliant OSes.
* [netkit](https://github.com/iocrate/netkit) ⭐ 67 | 🐛 0 | 🌐 Nim | 📅 2020-09-24 - Out-of-the-box, stable and secure network facilities and utilities written in pure Nim.
* [jshttp2](https://juancarlospaco.github.io/nodejs/nodejs/jshttp2) - Async HTTPS 2.0 web server.

### Gemini Servers

* [Geminim](https://github.com/ardek66/geminim) ⭐ 40 | 🐛 2 | 🌐 Nim | 📅 2022-07-09 - A Gemini server.
* [Nemini](https://codeberg.org/pswilde/Nemini) - A very simple Gemini server for serving static gemtext files.

### Frameworks

* [Jester](https://github.com/dom96/jester) ⭐ 1,629 | 🐛 67 | 🌐 Nim | 📅 2026-07-29 - The sinatra-like web framework for Nim. Jester provides a DSL for quickly creating web applications in Nim.
* [prologue](https://github.com/planety/prologue) ⭐ 1,353 | 🐛 45 | 🌐 Nim | 📅 2026-08-19 - A fullstack web framework written in Nim.
* [karax](https://github.com/karaxnim/karax) ⭐ 1,167 | 🐛 15 | 🌐 Nim | 📅 2026-07-12 - A framework for developing single page applications in Nim.
* [happyx](https://github.com/HapticX/happyx) ⭐ 666 | 🐛 17 | 🌐 Nim | 📅 2026-06-03 - A macro-oriented full stack asynchronous web framework written in Nim.
* [basolato](https://github.com/itsumura-h/nim-basolato) ⭐ 252 | 🐛 16 | 🌐 Nim | 📅 2026-05-08 - A fullstack web framework for Nim based on Jester.
* [rosencrantz](https://github.com/andreaferretti/rosencrantz) ⭐ 195 | 🐛 9 | 🌐 Nim | 📅 2022-11-28 - DSL to write web servers, inspired by Spray and its successor Akka HTTP.
* [nim\_websitecreator](https://github.com/ThomasTJdev/nim_websitecreator) ⭐ 178 | 🐛 13 | 🌐 Nim | 📅 2024-02-23 - Nim fullstack website framework - deploy a website within minutes.
* [whip](https://github.com/mattaylor/whip) ⭐ 88 | 🐛 1 | 🌐 Nim | 📅 2020-06-11 - Simple and fast HTTP server for Nim based on httpbeast and nest for high performance routing.
* [scorper](https://github.com/bung87/scorper) ⭐ 87 | 🐛 17 | 🌐 Nim | 📅 2025-07-03 - A micro and elegant web framework written in Nim.
* [Jazzy](https://github.com/canermastan/jazzy-framework) ⭐ 57 | 🐛 3 | 🌐 Nim | 📅 2026-07-28 - The Productive Framework. Developer-friendly, lightning fast, and designed for rapid development.
* [Supranim](https://github.com/supranim/supranim) ⭐ 41 | 🐛 0 | 🌐 Nim | 📅 2026-08-28 - A simple web framework for creating REST APIs and beautiful web apps. Model View Controller structure and other cool things.
* [starlight](https://github.com/planety/starlight) ⭐ 28 | 🐛 0 | 🌐 Nim | 📅 2020-10-16 - Flask-like web framework written in Nim.
* [nim-palladian](https://github.com/itsumura-h/nim-palladian) ⭐ 27 | 🐛 2 | 🌐 Nim | 📅 2023-10-03 - Palladian is a Nim front-end framework based on and wrapped around Preact.

### Template Engines

* [nimja](https://github.com/enthus1ast/nimja) ⭐ 222 | 🐛 14 | 🌐 Nim | 📅 2026-06-09 - Typed and compiled template engine inspired by jinja2, twig and onionhammer/nim-templates for Nim.
* [templates](https://github.com/onionhammer/nim-templates) ⭐ 97 | 🐛 2 | 🌐 Nim | 📅 2019-10-20 - A simple string templating library for Nim.
* [mustache](https://github.com/soasme/nim-mustache) ⭐ 75 | 🐛 2 | 🌐 Nim | 📅 2023-03-19 - A full implementation of v1.2.1 of the Mustache spec.
* [html-dsl](https://github.com/juancarlospaco/nim-html-dsl) ⭐ 68 | 🐛 0 | 🌐 Nim | 📅 2020-04-14 - Nim HTML DSL.
* [Tim](https://github.com/openpeeps/tim) ⭐ 68 | 🐛 5 | 🌐 Nim | 📅 2026-08-31 - A high-performance template engine & markup language.
* [smalte](https://github.com/roquie/smalte) ⭐ 36 | 🐛 1 | 🌐 Nim | 📅 2021-12-08 - It is a dead simple and lightweight template engine. Specially designed for configure application before start in Docker.
* [Nim Source Code filters](https://nim-lang.org/docs/filters.html) - Nim's powerful built-in feature which can be used as a templating system or a preprocessor.
* [temple](https://codeberg.org/onbox/temple) - Simple run-time templating library for Nim.

### Authentication

* [oauth](https://github.com/CORDEA/oauth) ⭐ 72 | 🐛 0 | 🌐 Nim | 📅 2024-08-04 - OAuth library for Nim.

## Game Development

### Game Libraries

* [GLAD](https://github.com/Dav1dde/glad) ⭐ 4,594 | 🐛 32 | 🌐 C | 📅 2026-06-18 - Multi-Language Vulkan/GL/GLES/EGL/GLX/WGL Loader-Generator based on the official specs.
* [enu](https://github.com/dsrw/enu) ⭐ 484 | 🐛 19 | 🌐 Nim | 📅 2026-07-28 - 3D live coding with a Logo-like DSL for Godot, implemented in Nim.
* [nimgl](https://github.com/nimgl/nimgl) ⭐ 409 | 🐛 23 | 🌐 Nim | 📅 2024-07-15 - NimGL is a Nim library that offers bindings for popular libraries used in computer graphics.
* [glm](https://github.com/stavenko/nim-glm) ⭐ 101 | 🐛 3 | 🌐 Nim | 📅 2026-05-18 - Port of the popular glm C++ library to Nim.

### Game Frameworks

* [nico](https://github.com/ftsf/nico) ⭐ 666 | 🐛 23 | 🌐 Nim | 📅 2024-07-09 - Nim Game Framework based on Pico-8.
* [naylib](https://github.com/planetis-m/naylib) ⚠️ Archived - safe Raylib wrapper.
* [natu](https://github.com/exelotl/natu) ⭐ 251 | 🐛 0 | 🌐 Nim | 📅 2025-02-15 - Toolkit for writing Game Boy Advance games in Nim.
* [paranim](https://github.com/paranim/paranim) ⭐ 117 | 🐛 0 | 🌐 Nim | 📅 2023-10-05 - A game library based around carefully chosen abstractions.
* [c4](https://github.com/c0ntribut0r/cat-400) ⭐ 93 | 🐛 9 | 🌐 Nim | 📅 2023-12-18 - Modular and extensible 2D and 3D game framework for Nim.

### Game Engines

* [NimForUE](https://github.com/jmgomez/NimForUE) ⭐ 544 | 🐛 14 | 🌐 Nim | 📅 2025-11-18 - Nim plugin for UE5 with native performance, hot reloading and full interop that sits between C++ and Blueprints.
* [godot-nim](https://github.com/pragmagic/godot-nim) ⭐ 505 | 🐛 32 | 🌐 Nim | 📅 2022-12-17 - Nim bindings for Godot Engine.
* [nimgame2](https://github.com/Vladar4/nimgame2) ⭐ 179 | 🐛 7 | 🌐 Nim | 📅 2025-09-11 - A simple 2D game engine for Nim.
* [rod](https://github.com/yglukhov/rod) ⭐ 140 | 🐛 10 | 🌐 Nim | 📅 2026-02-05 - Cross-platform 2D and 3D game engine.
* [alasgar](https://github.com/abisxir/alasgar) ⭐ 115 | 🐛 0 | 🌐 Nim | 📅 2026-08-10 - Pure nim 3D game engine based on OpenGL.
* [semicongine](https://github.com/saemideluxe/semicongine) ⭐ 51 | 🐛 0 | 🌐 Nim | 📅 2025-06-01 - Cross-platform, (almost) dependency-free game engine.
* [frag](https://github.com/Tail-Wag-Games/frag) ⭐ 22 | 🐛 0 | 🌐 Nim | 📅 2023-05-10 - Cross-platform 2D/3D game engine.
* [norx](https://github.com/tankfeud/norx) ⭐ 21 | 🐛 0 | 🌐 Nim | 📅 2026-08-15 - A complete wrapper of the ORX 2.5D cross platform game engine library.
* [saohime](https://github.com/glassesneo/saohime) ⭐ 19 | 🐛 3 | 🌐 Nim | 📅 2024-10-04 - An extensible 2D game engine for Nim, inspired by Bevy Engine.

### Rules Engines

* [pararules](https://github.com/paranim/pararules) ⭐ 155 | 🐛 3 | 🌐 Nim | 📅 2023-10-05 - A RETE-based rules engine made for games.
* [turn\_based\_game](https://github.com/JohnAD/turn_based_game) ⭐ 20 | 🐛 0 | 🌐 HTML | 📅 2020-01-02 - A game rules engine for simulating or playing turn-based games.

## Development Tools

### Editor Integration

* [Editor Support](https://github.com/nim-lang/Nim/wiki/editor-support) ⭐ 18,210 | 🐛 2,188 | 🌐 Nim | 📅 2026-09-01 - Official list of editor plugins for Nim.
* [nimlsp](https://github.com/PMunch/nimlsp) ⭐ 445 | 🐛 45 | 🌐 Nim | 📅 2026-02-09 - The Language Server Protocol implementation for Nim.
* [nim.nvim](https://github.com/alaviss/nim.nvim) ⭐ 215 | 🐛 15 | 🌐 Vim Script | 📅 2025-04-12 - Nim plugin for NeoVim.
* [vscode-nim](https://github.com/saem/vscode-nim) ⭐ 172 | 🐛 56 | 🌐 Nim | 📅 2026-08-11 - Language support for the Nim programming language for VS Code.

### REPL

* [INim](https://github.com/AndreiRegiani/INim) ⭐ 683 | 🐛 28 | 🌐 Nim | 📅 2026-02-08 - Interactive Nim Shell.
* [jupyternim](https://github.com/stisa/jupyternim) ⭐ 168 | 🐛 5 | 🌐 Nim | 📅 2022-12-30 - A Jupyter kernel for Nim.
* [Reploid](https://github.com/RowDaBoat/reploid) ⭐ 9 | 🐛 0 | 🌐 Nim | 📅 2026-01-21 - A Nim REPL running on top of a `nim c` or a `nimscript` VM, `import [anything]`.

### Binding Generators

* [nimpy](https://github.com/yglukhov/nimpy) ⭐ 1,590 | 🐛 34 | 🌐 Nim | 📅 2026-06-27 - Generate Python wrappers and call Python from Nim.
* [c2nim](https://github.com/nim-lang/c2nim) ⭐ 527 | 🐛 42 | 🌐 Nim | 📅 2026-05-15 - c2nim is a tool to translate Ansi C code to Nim.
* [Futhark](https://github.com/PMunch/futhark) ⭐ 505 | 🐛 48 | 🌐 Nim | 📅 2026-07-06 - Automatic wrapping of C headers in Nim with libclang.
* [nimterop](https://github.com/nimterop/nimterop) ⭐ 374 | 🐛 62 | 🌐 Nim | 📅 2023-04-03 - A Nim package that leverages tree-sitter to make C/C++ interop seamless. Superseded by Futhark.
* [jnim](https://github.com/yglukhov/jnim) ⭐ 212 | 🐛 0 | 🌐 Nim | 📅 2025-08-19 - Nim - Java bridge.
* [nimgen](https://github.com/genotrance/nimgen) ⭐ 114 | 🐛 9 | 🌐 C | 📅 2021-09-01 - nimgen is a helper for c2nim to simplify and automate the wrapping of C libraries. Superseded by nimterop.

<!-- - [rnim](https://github.com/SciNim/rnim) - A bridge between R and Nim. Currently this is a barely working prototype. -->

### Build Systems / Package Management

* [Nimble](https://github.com/nim-lang/nimble) ⭐ 1,400 | 🐛 259 | 🌐 Nim | 📅 2026-09-01 - Nimble can be used as a build system.
* [nimph](https://github.com/disruptek/nimph) ⭐ 163 | 🐛 44 | 🌐 Nim | 📅 2026-06-27 - Nim package hierarchy manager from the future.
* [Nake](https://github.com/fowlmouth/nake) ⭐ 151 | 🐛 13 | 🌐 Nim | 📅 2025-07-30 - Describe your Nim builds as tasks.
* [Atlas](https://github.com/nim-lang/atlas) ⭐ 148 | 🐛 9 | 🌐 Nim | 📅 2026-08-31 - The Atlas Package cloner. It manages an isolated workspace that contains projects and dependencies.
* [ChooseNim](https://github.com/nim-lang/choosenim) ⭐ 133 | 🐛 28 | 🌐 Nim | 📅 2026-01-09 - Installing and switching between Nim versions (à la rustup, pyenv).
* [nimby](https://github.com/treeform/nimby) ⭐ 45 | 🐛 1 | 🌐 Nim | 📅 2026-08-27 - A very simple and unofficial package manager for Nim.
* [nifty](https://github.com/h3rald/nifty) ⚠️ Archived - A decentralized pseudo package manager and script runner.
* [Nawabs](https://github.com/Araq/nawabs) ⭐ 20 | 🐛 0 | 🌐 Nim | 📅 2021-07-06 - A build system that throws away version numbering in favor of git hashes.
* [nsis](https://github.com/nim-libs/nsis) ⭐ 4 | 🐛 0 | 🌐 NSIS | 📅 2021-12-13 - Nim programming language setup tool.
* [nim-agent-template](https://github.com/Vyrnexis/nim-agent-template) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-08-20 - Scaffolding generator and template featuring AI agent skills, MCP tooling, and multi-toolchain build profiles.
* [GrabNim](https://codeberg.org/janAkali/grabnim) - Install and switch between multiple Nim compiler versions. (Alternative to ChooseNim).

### Logging

* [chronicles](https://github.com/status-im/nim-chronicles) ⭐ 176 | 🐛 17 | 🌐 Nim | 📅 2026-08-25 - A crafty implementation of structured logging for Nim.
* [kslog](https://github.com/c-blake/kslog) ⭐ 14 | 🐛 0 | 🌐 Nim | 📅 2026-06-18 - Minimalistic Kernel-Syslogd For Linux in Nim.
* [threadlogging](https://codeberg.org/pswilde/threadlogging) - A thread safe logging library using Nim's own logging module.

### Testing

* [balls](https://github.com/disruptek/balls) ⭐ 70 | 🐛 9 | 🌐 Nim | 📅 2026-02-16 - A unittest macro to save the world, or at least your Sunday.
* [einheit](https://github.com/jyapayne/einheit) ⭐ 46 | 🐛 1 | 🌐 Nim | 📅 2019-11-05 - A Nim unit testing library inspired by Python's unit tests.
* [faker](https://github.com/jiro4989/faker) ⭐ 45 | 🐛 12 | 🌐 Nim | 📅 2026-06-19 - A Nim package that generates fake data for you.
* [unittest2](https://github.com/status-im/nim-unittest2) ⭐ 31 | 🐛 12 | 🌐 Nim | 📅 2026-08-24 - Fork of the "unittest" Nim module focusing on parallel test execution, test-level scoping and strict exception handling.
* [asynctest](https://github.com/status-im/asynctest) ⭐ 14 | 🐛 2 | 🌐 Nim | 📅 2025-04-08 - Complements the standard unittest module in Nim to allow testing of asynchronous code.

### Fuzzing

* [drchaos](https://github.com/status-im/nim-drchaos) ⭐ 72 | 🐛 6 | 🌐 Nim | 📅 2023-05-10 - A powerful and easy-to-use fuzzing framework in Nim for C/C++/Obj-C targets.
* [libfuzzer](https://github.com/planetis-m/libfuzzer) ⚠️ Archived - LibFuzzer's interface bindings.

### Benchmarking

* [benchy](https://github.com/treeform/benchy) ⭐ 59 | 🐛 6 | 🌐 Nim | 📅 2026-05-25 - Simple benchmarking to time your code.
* [timeit](https://github.com/xflywind/timeit) ⭐ 37 | 🐛 1 | 🌐 Nim | 📅 2022-11-06 - Measuring execution times written by Nim.
* [golden](https://github.com/disruptek/golden) ⭐ 29 | 🐛 10 | 🌐 Nim | 📅 2021-01-14 - A benchmark for compile-time and/or runtime Nim.
* [criterion](https://github.com/disruptek/criterion) ⭐ 24 | 🐛 2 | 🌐 Nim | 📅 2025-01-10 - Statistic-driven micro-benchmark framework.
* [nimbench](https://github.com/ivankoster/nimbench) ⭐ 18 | 🐛 1 | 🌐 HTML | 📅 2020-04-28 - A micro benchmark module for Nim.
* [stopwatch](https://gitlab.com/define-private-public/stopwatch) - A fork of rbmz's stopwatch that adds extra features.

### Command-Line Interface Automation

* [cligen](https://github.com/c-blake/cligen) ⭐ 582 | 🐛 0 | 🌐 Nim | 📅 2026-08-29 - Infer & generate command-line interace/option/argument parsers.
* [docopt.nim](https://github.com/docopt/docopt.nim) ⭐ 215 | 🐛 6 | 🌐 Nim | 📅 2023-09-18 - Command-line args parser.
* [argparse](https://github.com/iffy/nim-argparse) ⭐ 126 | 🐛 12 | 🌐 Nim | 📅 2024-08-16 - Argument parsing for Nim.
* [cliche](https://github.com/juancarlospaco/cliche) ⭐ 85 | 🐛 2 | 🌐 Nim | 📅 2026-04-19 - AutoMagic CLI argument parsing is so cliché.
* [confutils](https://github.com/status-im/nim-confutils) ⭐ 69 | 🐛 16 | 🌐 Nim | 📅 2026-08-24 - Simplified handling of command line options and config files
* [loki](https://github.com/beshrkayali/loki) ⭐ 34 | 🐛 0 | 🌐 Nim | 📅 2026-06-06 - A small library for writing line-oriented command interpreters in Nim.
* [clapfn](https://github.com/oliversandli/clapfn) ⭐ 17 | 🐛 0 | 🌐 Nim | 📅 2026-07-06 - Argument parsing similar to Python's argparse.
* [cozycliparser](https://github.com/indiscipline/cozycliparser) ⭐ 5 | 🐛 0 | 🌐 Nim | 📅 2026-04-24 - Lean, feature-rich, DSL-free CLI parser based on `std/parseopt`. [Docs](https://indiscipline.github.io/cozycliparser/).
* [Cmdos](https://github.com/farias-hecdin/Cmdos) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2024-09-13 - A simple way to process cli arguments and help messages.
* [Cliquet](https://github.com/RowDaBoat/cliquet) ⭐ 2 | 🐛 0 | 🌐 Nim | 📅 2026-05-26 - A CLI args and config file parser merging both into a single object, with automatic help generation.
* [easyargs](https://github.com/nervecenter/easyargs) ⭐ 1 | 🐛 0 | 🌐 Nim | 📅 2026-08-22 - Dead simple data-oriented argument parsing for Nim.

### Static Analysis

* [nimalyzer](https://github.com/thindil/nimalyzer) ⭐ 45 | 🐛 0 | 🌐 Nim | 📅 2026-04-27 - Static code analyzer for Nim, inspired by AdaControl.
* [DrNim](https://nim-lang.org/docs/drnim.html) - Combines the Nim frontend with the Z3 proof engine, in order to allow verify/validate software.

## Resources

### Books

* [Nim in Action](https://book.picheta.me/) - Book in Manning's "in Action" series, teaching Nim through 3 practical projects including CLI chat apps, web apps and parsers.
* [Computer Programming with Nim](https://www.nimprogrammingbook.com/book/nimprogramming_colorful.pdf) - A gentle introduction to the Nim programming language.
* [Nim Basics](https://narimiran.github.io/nim-basics/) - Tutorial for beginners and people just starting with Nim.
* [Nim Style Guide](https://status-im.github.io/nim-style-guide/) - Status style guide for the Nim language.
* [Mastering Nim](https://www.amazon.com/Mastering-Nim-complete-programming-language/dp/B0B4R7B9YX) - A complete guide to the programming language.

### Blogs

* [Nim Blog](http://nim-lang.org/blog.html) - Official Nim blog.
* [Goran Krampe](http://goran.krampe.se/nim/) - Wrapping C, Arduino, performance, links.
* [HookRace](https://hookrace.net/blog/nim/) - Blog with multiple articles on Nim.
* [Rants from the Ballmer Peak](https://gradha.github.io/tags/nim.html) - Posts on Nim and other languages.
* [Yuriy Glukhov's blog](https://yglukhov.github.io/) - Making and shipping a game in Nim.
* [Araq's Musings](https://nim-lang.org/araq) - Blog on Nim from the creator himself.
* [Nim on dev.to](https://dev.to/t/nim) - Nim blogs on `dev.to`.

### Community

* [The Nim forum](http://forum.nim-lang.org/)
* [The Nim IRC channel](http://webchat.freenode.net/?channels=nim)
* [The Nim Gitter channel](https://gitter.im/nim-lang/Nim)
* [The Nim Discord channel](https://discord.gg/ptW3Rb3)
* [The Nim mailing list (forum archive)](https://www.mail-archive.com/nim-general@lists.nim-lang.org/)
* [The Nim subreddit](http://reddit.com/r/nim)
* [The Nim Telegram](https://t.me/nim_lang)
* [The Nim Telegram in Spanish](https://t.me/NimArgentina)
* [The Nim Matrix room](https://matrix.to/#/#nim-lang:matrix.org)

### Tutorials

* [Nim for Python programmers](https://github.com/nim-lang/Nim/wiki/Nim-for-Python-Programmers) ⭐ 18,210 | 🐛 2,188 | 🌐 Nim | 📅 2026-09-01 - Guide to Nim for people with experience in Python.
* [nimNx](https://github.com/dkgitdev/nimNx) ⭐ 12 | 🐛 0 | 🌐 Nim | 📅 2022-12-03 - A Nintendo Switch Homebrew example project, written in Nim.
* [nimNxStatic](https://github.com/dkgitdev/nimNxStatic) ⭐ 3 | 🐛 0 | 🌐 Makefile | 📅 2023-02-13 - A static library example aiming to help integrate Nim code into the current Homebrew C projects for Nintendo Switch
* [Nim Days](https://xmonader.github.io/nimdays/) - A project to document my journey with Nim with mini applications, libraries documented from A to Z and also to provide new Nim users with some extra in depth information.
* [How I start](https://howistart.org/posts/nim) - Great guide going from 0 to a bf interpreter and then a bf to Nim compiler.
* [Learn Nim in Y minutes](https://learnxinyminutes.com/docs/nim/) - Whirlwind tour.
* [Nim by Example](https://nim-by-example.github.io) - Series of pages and examples for learning the Nim programming language.
* [Nim on Rosetta Code](https://rosettacode.org/wiki/Category:Nim) - Thousands of solutions for various tasks using Nim.
* [Nim Memory](http://zevv.nl/nim-memory/) - A small tutorial explaining how Nim stores data in memory.
* [Nim ARC](http://zevv.nl/nim-memory/nim-arc.html) - A friendly explanation of ARC and its implications for the programmer.

### Videos

* [Nim's Official Channel](https://www.youtube.com/channel/UCDAYn_VFt0VisL5-1a5Dk7Q/videos) - Official videos introduce the powerful and interesting part in Nim language.
* [Nim for Beginners](https://www.youtube.com/user/kiloneie/playlists) - This is a video series meant to teach people programming in Nim to people who have never programmed before, or are new to Nim.
* [Make a website with Nim](https://www.youtube.com/watch?v=ndzlVRWqT2E\&list=PL6RpFCvmb5SGw7aJK1E4goBxpMK3NvkON) - This is a video series meant to teach people make a website with Nim using `jester`.
* [Learning Nim](https://www.youtube.com/watch?v=I_Y94G37iR4\&list=PLu-ydI-PCl0PqxiYXQMmLh7wjQKm5Cz-H) - Tutorial video series on learning Nim showcasing various features of the language and its libraries.
* [araq twitch](https://www.twitch.tv/araq4k) - The live broadcast regarding Nim language.
* [alehander42 twitch](https://www.twitch.tv/alehander42) - The live broadcast regarding Nim language.
* [clyybber twitch](https://www.twitch.tv/clyybber) - The live broadcast regarding Nim language.
* [d0m96 twitch](https://www.twitch.tv/d0m96) - The live broadcast regarding Nim language.
* [disruptek twitch](https://www.twitch.tv/disruptek) - The live broadcast regarding Nim language.
* [Nim Tutorials](https://www.youtube.com/playlist?list=PLYBJzqz8zpWaiGbFcSdlh08zlpe8Tl_Gh) - YouTube video series that teaches how to program in Nim and goes over various standared libraries.

***

### Footnotes

*Awesome-Nim logo is based on the "Nim Crown" logo by Joseph Wecker, used with permission from the Nim project.*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
