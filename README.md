# Voice REPL 🎤➡️⌨️➡️🔊

A universal voice-powered REPL (Read-Eval-Print Loop) that lets you interact with coding assistants like Gemini CLI, Claude, and others using only your voice.

> **Note:** This project is in active development. Expect breaking changes.

## ✨ Features

- **🗣️ Voice Input:** Speak your prompts instead of typing them
- **🤖 LLM Agnostic:** Works with any command-line LLM (Gemini, Claude, etc.)
- **💾 File Generation:** Automatically creates files from `<file:path>` code blocks
- **🔊 Voice Feedback:** Hear responses spoken back to you with Edge-TTS
- **⚡ CPU-Only:** Runs efficiently on laptops without GPUs
- **🔧 Configurable:** Adjust ASR model, sensitivity, and LLM command

## 🚀 Quick Start

### Prerequisites

1. **Python 3.10+** and `uv` (modern Python package manager)
2. **FFmpeg** for audio playback: `sudo apt install ffmpeg` (Linux/WSL)
3. An LLM CLI like **Gemini CLI**: `npm install -g @google/gemini-cli`

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/voice-repl.git
cd voice-repl

# Install with uv
uv sync

# Install Gemini CLI (if you haven't already)
npm install -g @google/gemini-cli
```
