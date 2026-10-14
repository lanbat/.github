## LAN BAT — homelab infrastructure you can fork

Real, running home infrastructure published as code: declarative, CI-tested and written to be read, borrowed from or forked whole.

| Project | What it is |
|---|---|
| [**nixconf**](https://github.com/lanbat/nixconf) | Two-machine NixOS homelab (x86 server + Raspberry Pi 5): one SSO across 20+ self-hosted services, encrypted storage tiers, deploy-rs, agenix, disko. An extensible reference flake. |
| [**openwrt-kestrel**](https://github.com/lanbat/openwrt-kestrel) | OpenWrt toolkits: isolated guest/IoT Wi-Fi with push-notified join approval, plus WireGuard split-routing by domain. Plain shell + nftables. |
| [**runpod-llm-fleet**](https://github.com/lanbat/runpod-llm-fleet) | Open-weight Qwen models on scale-to-zero RunPod serverless: one for coding agents (opencode), one for Home Assistant tool calling. |
| [**parking-guard**](https://github.com/lanbat/nixos-lanbat-justpark-parking) | Frigate licence-plate recognition checked against JustPark bookings, with alerts over MQTT, Pushover or Telegram. A plugin for nixconf. |

**Start here:** [lanbat.github.io](https://lanbat.github.io/) · Issues and PRs are welcome on every repo.
