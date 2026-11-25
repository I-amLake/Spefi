# Spefi

One-click USB tethering companion for macOS and Android. Streamlines ADB port forwarding + SOCKS5 proxy setup so you can share your phone’s 5G/4G connection with your Mac with a single button.

## Current Setup Being Streamlined

- **Android**: Every Proxy running as a SOCKS5 server on port `1080`
- **macOS**: ADB port forwarding + system SOCKS proxy + DNS override + background keepalive script
- Goal: Replace the manual process with a clean GUI on both platforms

## Status

- [x] SSH + Git setup complete
- [ ] macOS companion app (SwiftUI)
- [ ] Android companion / improved proxy service
- [ ] One-click experience end-to-end

## Planned Features

### macOS App
- Big “Tether On / Off” button
- Automatic ADB forward setup
- System SOCKS proxy + DNS configuration
- Background keepalive / health check
- Status indicator (device connected, proxy active, last check)

### Android App (later)
- Easier control of the proxy service
- Better background reliability (Doze / battery optimization handling)
- Optional custom persistent SOCKS5 server

## Tech Stack (planned)

- **macOS**: SwiftUI
- **Android**: Kotlin (or existing proxy app + companion)
- **Tools**: Grok CLI / Grok 4.7, Gemini, GitHub

## Getting Started

```bash
git clone git@github.com:I-amLake/Spefi.git
cd Spefi
