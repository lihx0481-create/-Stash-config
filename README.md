# Stash iOS Tile Panel

A Stash iOS Tile panel configuration with network monitoring tools.

## Current Version

**V2.0**

**Updated:** 2026-08-15

## Features

- 🛰️ International Exit
- 🌐 Network Control Center
- ⚡ Node Health
- 📊 Network Quality
- 🚀 QUIC / HTTP3
- 🧬 Stash 3.6 Protocol Capability
- 🧠 DNS Detection
- 🛡️ WebRTC Detection
- ▶️ YouTube
- 🎵 TikTok
- 𝕏 X
- 📷 Instagram
- 🔎 Google
- 🎬 Netflix
- 📋 Loog

## Detection Interval

### Core Checks

- International Exit — 24 hours
- Network Control Center — 24 hours
- Node Health — 24 hours
- Network Quality — 24 hours
- QUIC / HTTP3 — 24 hours
- Stash 3.6 Protocol Capability — 24 hours
- DNS — 24 hours
- WebRTC — 24 hours

### Third-Party Services

- YouTube — 7 days
- TikTok — 7 days
- X — 7 days
- Instagram — 7 days
- Google — 7 days
- Netflix — 7 days

## Changelog

### V2.0 — 2026-08-15

- Rebuilt the entire Tile panel
- Added Stash 3.6 protocol information
- Added XHTTP / Gecko information
- Improved node health latency classification
- Improved DNS status display
- Improved WebRTC status information
- Improved QUIC / HTTP3 detection
- Unified third-party service detection
- Core checks run every 24 hours
- Third-party checks run every 7 days
- Removed duplicate DNS and Node Health Tiles
- Added `#!replace` to prevent duplicate Tile definitions

## Installation

Add `Default.yaml` to Stash and enable the Tile configuration.

## License

MIT
