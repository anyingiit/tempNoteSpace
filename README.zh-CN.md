[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:f27b394a648d7518 -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# TempNoteSpace

一个已归档的个人笔记仓库，内容是四篇关于多线程概念（原子操作、互斥量、死锁与线程安全）的简短中文学习笔记，没有任何源代码、软件包清单或构建配置。

[![License](https://img.shields.io/github/license/anyingiit/tempNoteSpace)](LICENSE)

[报告问题](https://github.com/anyingiit/tempNoteSpace/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/tempNoteSpace/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">开始使用</a></li>
    <li><a href="#usage">用法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

TempNoteSpace 是 anyingiit 的个人仓库之一，现已归档。它的全部内容是四篇用中文写的简短笔记，存放在一个目录名意为"多线程"的单一目录下（具体的、逐字节一致的文件名见下方"用法"一节）。第一篇笔记把 atomic 解释为一种修饰符，使变量的读写操作不可分割，并举了 C++ 的 `atomic<int>` 和 Java 的 `AtomicInteger` 作为例子，最后在一条分隔线之后附了一段更简短的复述。第二篇笔记解释了互斥量的锁定与解锁两种状态，提到了 C++ 的 `std::mutex` 和 Java 的 `ReentrantLock`，并在结尾引用了第四篇笔记。第三篇用一个"两个线程、两把锁"的例子定义了死锁。第四篇区分了程序员自己实现的锁与操作系统层面的互斥机制，并用一个共享账户余额的例子定义了线程安全，同样在分隔线之后附了一段复述。

除了这四篇笔记之外，仓库中没有任何应用代码、依赖清单或构建配置，`facts.json` 中的 `manifests` 和 `entry_points` 字段也都是空的。

## 开始使用

### 环境要求

- 一个能够正确显示简体中文的文本编辑器或 Markdown 查看器即可；本仓库没有任何软件包清单、依赖列表或构建配置。

### 安装

没有构建步骤，也没有任何依赖需要安装。克隆仓库即可得到这些笔记的本地副本：

```sh
git clone https://github.com/anyingiit/tempNoteSpace.git
cd tempNoteSpace
```

## 用法

用编辑器打开四篇笔记中的任意一篇：

```sh
$EDITOR 多线程/什么是atomic.md
$EDITOR 多线程/什么是mutex.md
$EDITOR 多线程/什么是死锁.md
$EDITOR "多线程/锁 互斥 线程安全.md"
```

## 参与贡献

欢迎参与。[CONTRIBUTING.md](CONTRIBUTING.md) 说明如何提交 issue 或 pull request，[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 说明对所有参与者的行为要求。

请不要在公开的 issue 或 pull request 中报告安全问题。[SECURITY.md](SECURITY.md) 说明了私下报告的方式。

## 许可证

以 MIT 许可证分发。详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/tempNoteSpace](https://github.com/anyingiit/tempNoteSpace)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
