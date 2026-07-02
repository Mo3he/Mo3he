# Hi, I'm Moshe

I build software for the edge, mostly for Axis network cameras. My ACAPs let
cameras run things they were never designed to run: VPN clients, media
servers, and a self-contained event automation engine.

## Axis camera projects

| Project | What it does |
|---|---|
| [Axis_Cam_Tailscale](https://github.com/Mo3he/Axis_Cam_Tailscale) | Tailscale running natively on the camera. Remote access with no NVR or port forwarding. |
| [Event-Engine-ACAP](https://github.com/Mo3he/Event-Engine-ACAP) | If-this-then-that automation running entirely on the camera. |
| [Axis_Cam_MediaMTX](https://github.com/Mo3he/Axis_Cam_MediaMTX) | MediaMTX on the camera for RTSP, WebRTC, HLS and SRT. |
| [Axis_Cam_WireGuard](https://github.com/Mo3he/Axis_Cam_WireGuard) | WireGuard VPN on the camera. |
| [Axis_Cam_ZeroTier](https://github.com/Mo3he/Axis_Cam_ZeroTier) | ZeroTier on the camera. |

Most of these follow the same pattern: a minimal C supervisor wrapping a
statically compiled Go binary, with GitHub Actions tracking upstream
releases automatically.

## Other things I make

Native iOS apps, homelab tooling, and integrations for Home Assistant
and Telegraf.

## Elsewhere

- YouTube: [MoMakesThings](https://youtube.com/@MoMakesThings)
- Sponsor this work: [GitHub Sponsors](https://github.com/sponsors/Mo3he)
