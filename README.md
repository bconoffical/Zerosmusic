# ZerosMusic

A Windows music player that brings your local library and streaming sources into one app.

## Features
- Unified library: local files, SoundCloud, YouTube
- Queue, playlists, and gapless playback
- Synced lyrics and album art
- Global media-key support and system tray controls
- Themes (dark, light, system)

## Install
Download the latest `.msi` from [Releases](../../releases).

## Build from source
```bash
git clone https://github.com/<you>/tunehub.git
cd tunehub
npm install
npm run tauri dev      # run
npm run tauri build    # produce installer
```
Requires Node 20+, Rust stable, and WebView2 (preinstalled on Windows 11).

## Roadmap
- [ ] Local library scanner + player
- [ ] SoundCloud integration
- [ ] YouTube integration
- [ ] Spotify / Apple Music connectors
- [ ] Equalizer and crossfade

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).

## License
MIT
