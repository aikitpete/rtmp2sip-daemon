# rtmp2sip-daemon

> **Status:** historical prototype, not maintained. Contains third-party code under its own licence (see NOTICE.md; the repository is distributed under GPL-3.0).

A C++ prototype for bridging RTMP video streams into SIP-based communication flows.

## What this repo contains
The repository is organized into two top-level areas:

- `daemon/`
- `flex/`

## Purpose
The project explores real-time media interoperability: taking a stream in one protocol (RTMP) and converting or relaying it into a format usable in SIP/VoIP calling scenarios.

## Tech
- C++
- real-time media / streaming concepts
- SIP / RTMP interoperability

## Origin
A university-era prototype. Parts of the code (RTMP implementation, MD5) were written by other authors and carry their own licences, see [NOTICE.md](NOTICE.md).
