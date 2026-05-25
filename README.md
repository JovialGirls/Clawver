# ![Clawver Banner](https://iili.io/CJ6JVSt.png)

<div align="center">

<img src="https://iili.io/CJiSXvS.png" width="550">

A cat-tastic open-source command-line package manager.

</div>

---

## Features

- Lightweight command-line package manager
- Install and manage apps from the official Clawver repository
- Support for custom user repositories
- Fast and simple workflow
- TOML-based package manifests
- Cross-platform

---

## Installation

```bash
git clone https://github.com/JovialGirls/Clawver.git
cd clawver
python main.py
```

---

## Example repo.toml

```toml
[AppName]
nam = "AppName"
description = "App Description."
version = "1.0"
url = "https://raw.githubusercontent.com/<your_Github_username>/<your_repository_name>/<branch_name>/<file_name>.<extension_name>"
```
