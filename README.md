# ChatApp Test

A minimal **NiceGUI-based chat application** built with Python.  
It demonstrates how to create a simple, real-time web UI using NiceGUI.

---

##  Overview

- Runs a chat interface at `http://localhost:8080/`
- Each user gets a random avatar generated from [robohash.org](https://robohash.org)
- Messages are displayed instantly on the same page (in-memory storage only)

> Built with [NiceGUI](https://nicegui.io) – a modern Python web UI framework.

---

## ⚙️ Installation & Running

### Option A: Using **Pixi** (recommended for reproducibility)

Make sure you have **Pixi** and **Python** installed.

```bash
# Install all dependencies from pixi.toml
pixi install

# Run the application
pixi run dev
