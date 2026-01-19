# Networking-Homelab-Secure-Self-Hosting-Network-Services

📌 Project Motivation

I wanted to build a personal media server that I could access securely from anywhere, especially on my mobile device.
While my computer is mainly used for work and learning, my phone is my primary device for entertainment. This led me to explore Jellyfin as a self-hosted alternative to cloud streaming services.

While working in a Network Operations Center (NOC) at an ISP, I often wondered:

How do real-world services like FTP servers, media servers, and VPNs remain reachable and secure from anywhere on the internet, while most home services stay limited to private networks?

I originally built a Jellyfin media server only for local use. But when I wanted to access it securely from my mobile device outside my home network, I realized this was the perfect opportunity to deeply understand real networking concepts, not just theory.

This repository documents my hands-on journey through:

Self-hosting

Reverse proxies

SSL/TLS

DNS & Dynamic DNS

VPNs

Docker

MikroTik RouterOS

This is not a tutorial copy-paste project — it’s a problem-driven learning log, very similar to how things are solved in real NOC/ISP environments.

## 🛠️ Technologies Used

- Jellyfin (Media Server)
- DuckDNS (Dynamic DNS)
- Cloudflare Tunnel
- Caddy (Reverse Proxy)
- Nginx Proxy Manager (Docker)
- Docker & Docker Desktop (via WSL)
- WireGuard VPN
- MikroTik RouterOS (PPP, VPN, Routing)

