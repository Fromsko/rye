<div align="center">
  <img src="docs/static/favicon.svg" width="100">
  <p><strong>Rye:</strong> 一个无麻烦的Python体验</p>
</div>

----
<div align="center">

[![Rye](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/rye/main/artwork/badge.json)](https://rye.astral.sh)
[![](https://dcbadge.vercel.app/api/server/drbkcdtSbg?style=flat)](https://discord.gg/drbkcdtSbg)

</div>

Rye是Python的一个全面的项目和包管理解决方案。
Rye诞生于[其创作者](https://github.com/mitsuhiko)希望为所有Python用户建立一个一站式服务的愿望，它提供了统一的体验来安装和管理Python安装、基于`pyproject.toml`的项目、依赖和虚拟环境。
它旨在适应复杂的项目、单体库仓库，并促进全局工具的安装。你好奇吗？[观看介绍视频](https://youtu.be/q99TYA7LnuA)。

对于每个层次的Python开发者来说，这是一个无麻烦的体验。

<div align="center">
  <a href="https://youtu.be/q99TYA7LnuA">
    <img src="https://img.youtube.com/vi/q99TYA7LnuA/hqdefault.jpg" alt="Watch the instruction" width="40%">
  </a>
  <p><em>点击缩略图观看16分钟的介绍视频</em></p>
</div>

## 包含的内容

Rye选择并提供正确的工具，让你可以在几分钟内开始：

* **引导Python：** 它提供了一种自动化的方式来访问令人惊叹的[Indygreg Python Builds](https://github.com/indygreg/python-build-standalone/)以及PyPy二进制发行版。
* **代码检查和格式化：** 它捆绑了[ruff](https://github.com/astral-sh/ruff)，并通过`rye lint`和`rye fmt`使其可用。
* **管理虚拟环境：** 它在内部使用了广泛使用的virtualenv库。
* **构建Wheel包：** 它主要委托给[build](https://pypi.org/project/build/)来完成这项工作。
* **发布：** 它的发布命令使用[twine](https://pypi.org/project/twine/)来完成这个任务。
* **锁定和依赖安装：** 目前使用[uv](https://github.com/astral-sh/uv)来实现，如果不可用，则回退到[unearth](https://pypi.org/project/unearth/)和[pip-tools](https://github.com/jazzband/pip-tools/)。
* **工作区支持：** Rye允许你处理由多个库组成的复杂项目。

## 安装

安装只需一分钟：

* **Linux和macOS：**

    ```
    curl -sSf https://rye.astral.sh/get | bash
    ```

* **Windows：**

    下载并运行安装程序（[64位(x86-64)](https://github.com/astral-sh/rye/releases/latest/download/rye-x86_64-windows.exe)或[32位(x86)](https://github.com/astral-sh/rye/releases/latest/download/rye-x86-windows.exe)）。

有关更多详细信息和其他选项，请参阅[安装说明](https://rye.astral.sh/guide/installation/)。

## 了解更多

我激发了你的兴趣吗？

* [访问网站](https://rye.astral.sh/)
* [阅读文档](https://rye.astral.sh/guide/)
* [在问题跟踪器中报告问题](https://github.com/astral-sh/rye/issues)

## 更多

* [讨论论坛](https://github.com/astral-sh/rye/discussions)，在GitHub
