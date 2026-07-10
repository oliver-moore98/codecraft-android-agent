# AgentML CodeCraft Android v1.0.0 - mobile AI coding agent 2026

> **A mobile-first Android AI coding agent that brings together multi-provider models, terminal and git workflows, MCP support, and local offline-capable execution in version 1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-Android-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliver-moore98/codecraft-android-agent?style=flat-square)](https://github.com/oliver-moore98/codecraft-android-agent)

---

<p align="center">
  <a href="https://oliver-moore98.github.io/codecraft-android-agent/">
    <img src="https://img.shields.io/badge/Download-AgentML%20CodeCraft%20Android%20Latest-brightgreen?style=for-the-badge" alt="Download AgentML CodeCraft Android">
  </a>
</p>

> **[Direct Download - AgentML CodeCraft Android v1.0.0](https://oliver-moore98.github.io/codecraft-android-agent/)**

---

[Download Latest Build](https://oliver-moore98.github.io/codecraft-android-agent/)

---

## Overview

AgentML CodeCraft Android is an Android-focused AI coding workspace built for people who want programming support without relying on a separate desktop machine. It packages model-assisted development into a handheld interface so you can plan, edit, and coordinate coding tasks from a single device.

The project is set up to work with multiple providers, including Claude, OpenAI, and Ollama, and it also includes MCP-based integrations. With terminal access, git support, built-in developer tooling, and multi-agent coordination, it is intended to make practical software work possible directly on Android.

---

## Capabilities

- Android-native AI coding environment for mobile use
- Multi-provider LLM orchestration across Claude, OpenAI, and Ollama
- Multi-agent swarm coordination for layered task handling
- Built-in developer tools for coding-focused workflows
- MCP protocol support for external tool and context integration
- Local model support through Ollama for offline-capable use
- Git and terminal integration for repository and command-line tasks
- Cloud sync with encryption for cross-device continuity

---

## Installation

1. Download the latest build from the project download page.
2. If you are installing from a repository checkout, clone it first:
   `git clone https://github.com/oliver-moore98/codecraft-android-agent.git
3. Open the Android project in your preferred build environment.
4. Build and install the app on a compatible Android device or emulator.
5. Launch the app and configure your provider credentials or local model endpoint before starting a session.

---

## How to Use It

Once installed, open the app and pick either a model provider or a local runtime.

Typical workflow:
1. Open a coding session.
2. Connect a provider such as Claude, OpenAI, or Ollama.
3. Use the editor and terminal tools to inspect, edit, and run project work.
4. Enable MCP connections if you need external context or tool access.
5. Use git integration to review repository state, changes, and version history.
6. Save or sync your workspace if you want encrypted cloud continuity across devices.

---

## Configuration

Most settings live inside the app, with provider setup and workflow preferences stored in the Android configuration area.

Example configuration shape:

{
  "provider": "ollama",
  "model": "local-model-name",
  "mcp_enabled": true,
  "git_integration": true,
  "cloud_sync": true,
  "encrypted_sync": true
}

Adjust provider endpoints, local model options, and sync preferences according to your environment and access requirements.

---

## Requirements

- Android device or emulator
- Compatible Android runtime for the app build
- Access to at least one supported provider, such as Claude or OpenAI, if you are not using a local model
- Ollama-compatible local model setup for offline-oriented use
- Network access for cloud provider features and encrypted sync
- Storage space for app data, model assets, and repository files

---

## FAQ

### Does it work with multiple providers?
Yes. The project is built around multi-provider LLM orchestration, including Claude, OpenAI, and Ollama.

### Can I use it without a server or desktop machine?
The setup is centered on mobile use and includes offline-oriented local support, so Android can serve as the main environment depending on your model choice and workflow.

### Where do I change settings?
Configuration is handled inside the app, including provider selection, tool access, and sync preferences.

### How do I troubleshoot startup issues?
Check your Android version, provider credentials, local model setup, and available storage. If a feature depends on network access or external tools, verify those connections first.

### Is there support for external tools?
Yes. MCP support is included for connecting compatible tools and context sources.

### How are updates delivered?
Use the latest build from the project download page and follow the repository release or build instructions for your installation method.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
