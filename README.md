# 🏗️ Gantry

> **"Gantry is cooking, but we put it in a sandbox so it doesn't delete system32. No cap."**

Gantry is a sleek, terminal-native AI assistant featuring a Gen Z interactive TUI. Run tasks, chat with models via OpenRouter, and build plugins—all while keeping your codebase completely safe from accidental AI writes.

---

## ⚡ Features

* 🛠️ **Fully Sandboxed**: AI generation tools (`write_file`, `delete_file`) are strictly jailed inside the `gantry-output/` directory. No rogue code modifications.
* 💅 **Gen Z Terminal UI**: Real-time streaming status updates ("bro is thinking", "cooking...") with an immersive retro layout.
* 🔌 **Plugin Registry**: Built-in plugins for `file` handling and `git` integration, with support for custom user-defined plugins.
* 🚀 **Powered by OpenRouter**: Hook up any modern LLM via OpenRouter.

---

## 🚀 Getting Started

### Prerequisites

You need [Bun](https://bun.sh) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gantry.git
   cd gantry
