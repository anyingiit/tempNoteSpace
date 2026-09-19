<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# TempNoteSpace

An archived personal-notes repository containing four short Chinese-language study notes on multithreading concepts (atomic operations, mutexes, deadlocks, and thread safety), with no source code, package manifest, or build configuration of any kind.

**English** · [简体中文](README.zh-CN.md)

[![License](https://img.shields.io/github/license/anyingiit/tempNoteSpace)](LICENSE)

[Report a bug](https://github.com/anyingiit/tempNoteSpace/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/anyingiit/tempNoteSpace/issues/new?template=feature_request.yml)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

TempNoteSpace is one of anyingiit's personal repositories, now archived. Its entire content is four short Markdown notes, written in Chinese, kept under a single directory whose name translates as "multithreading" (see the `Usage` section below for the exact, byte-for-byte file names). The first note explains atomic types as a modifier that makes a variable's reads and writes indivisible, with `atomic<int>` (C++) and `AtomicInteger` (Java) as examples, and closes with a shorter restatement below a divider. The second explains a mutex's locked and unlocked states, points to `std::mutex` (C++) and `ReentrantLock` (Java), and cross-references the fourth note. The third defines deadlock with a two-thread, two-lock example. The fourth distinguishes a programmer-implemented lock from an OS-level mutex and defines thread safety using a shared account-balance example, again followed by a divider and a restatement.

There is no application code, dependency manifest, or build configuration alongside the notes, and `facts.json`'s `manifests` and `entry_points` are both empty.

## Getting Started

### Prerequisites

- A text editor or Markdown viewer able to display Chinese (Simplified) text; the repository has no package manifest, dependency list, or build configuration of any kind.

### Installation

There is no build step and nothing to install. Cloning the repository gets you a local copy of the notes:

```sh
git clone https://github.com/anyingiit/tempNoteSpace.git
cd tempNoteSpace
```

## Usage

Open one of the four notes in your editor to read it:

```sh
$EDITOR 多线程/什么是atomic.md
$EDITOR 多线程/什么是mutex.md
$EDITOR 多线程/什么是死锁.md
$EDITOR "多线程/锁 互斥 线程安全.md"
```

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for how to open an issue or a pull request, and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for the standards expected of everyone taking part.

Please do not report security issues in public issues or pull requests. [SECURITY.md](SECURITY.md) explains how to report them privately.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

Project link: [https://github.com/anyingiit/tempNoteSpace](https://github.com/anyingiit/tempNoteSpace)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
