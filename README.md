📌 Project Motivation

I wanted to build a personal media server that I could access securely from anywhere, especially on my mobile device.
While my computer is mainly used for work and learning, my phone is my primary device for entertainment. This naturally led me to explore Jellyfin as a self-hosted alternative to cloud streaming services.

While working in a Network Operations Center (NOC) at an ISP, I often found myself asking:

How do real-world services like FTP servers, media servers, and VPNs remain reachable and secure from anywhere on the internet, while most home services stay limited to private networks?

Initially, I built my Jellyfin server only for local use.
However, when I wanted to access it securely from my mobile device outside my home network, I realized this was the perfect opportunity to move beyond theory and truly understand real networking concepts in practice.

This project became a problem-driven learning journey, not just a media server setup.

🎯 Purpose of This Repository

This repository documents my hands-on exploration of how services are:

Exposed securely

Protected from common risks

Designed in ways similar to real ISP / NOC environments

Rather than following a single tutorial, this project reflects:

Real questions

Real mistakes

Real fixes

Gradual improvement over time

🧠 What This Project Covers

This repository will progressively document my learning and implementation of:

Self-hosting fundamentals

Reverse proxies

SSL/TLS and certificate handling

DNS & Dynamic DNS

Secure exposure using tunnels

Docker-based service deployment

VPN-based private access

MikroTik RouterOS networking labs

Each topic is added step by step, following how the problems were discovered and solved in real life.

🛠️ Technologies Used (So Far)

Jellyfin — Media Server

DuckDNS — Dynamic DNS

Cloudflare Tunnel — Secure outbound tunneling

Caddy — Reverse Proxy (learning phase)

Nginx Proxy Manager — Reverse Proxy with Docker

Docker & Docker Desktop (WSL-based)

WireGuard VPN — Private remote access

MikroTik RouterOS — PPP, VPN, routing, firewall labs

📘 Learning Philosophy

This is not a copy-paste tutorial project.

It is a problem-driven learning log, very similar to how issues are identified, tested, and solved in real NOC and ISP environments.

## 🧩 Architecture:

![Secure Jellyfin Architecture](architecture.png)


