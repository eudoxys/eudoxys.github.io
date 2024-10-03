---
layout: post
title: Qdox tool released
tags: [News,Eudoxys,Tools,Release]
---

*Eudoxys Sciences release `qdox` tool to publish Python module documentation*

The `qdox` tool generates an HTML file from a Python module contents and it's GitHub `README.md` file.

The `qdox` command is designed for simple Python projects. The formatting is designed to use simple text layout as the input so that the same documentation source can be used for both Python `help()` output and the documentation pages.

The `qdox` command loads the module specified in the `pyproject.toml` file and formats the `__doc__` property of the module as the command line documentation. It then formats the python functions and constants, followed by the project metadata.

You can use your project's `pages-build-deployment` workflow to deploy the documentation to `github.io` or to your own custom site by setting the `Pages` options in your project `Settings`.

The `qdox` module can also be called from another Python module using the `main()` function.

For more information on the `qdox` tool, see the **[qdox documentation page](https://www.eudoxys.com/qdox)** or download it from the **[qdox repository on github](https://github.com/eudoxys/qdox)**.
