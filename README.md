# 🚀 ApexNova Hosting
> Enterprise-grade hosting solutions for the next generation of gamers and developers.

[![Build Status](https://img.shields.io/badge/Status-Development-orange.svg)](https://github.com/ZENVYREX/ApexNova)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Pterodactyl-blue.svg)](#)

ApexNova Hosting is a performance-focused hosting provider specializing in low-latency Minecraft nodes, lightweight web hosting, and 24/7 Discord bot environments. Built on a "Sister-Host" partnership model, we prioritize stability and community-driven support.

---

## 🛠️ The Tech Stack

ApexNova is built using a combination of industry-standard tools and custom-configured hardware:

* **Panel:** [Pterodactyl](https://pterodactyl.io/) (High-performance game management)
* **Billing:** WHMCS / [Payment Gateway Integration]
* **Web Server:** Nginx with Tailwind CSS Frontend
* **Protection:** 3 Tbps Volumetric DDoS Protection via Anycast Network
* **Runtime:** Java 17/21 (Minecraft), Node.js (Discord Bots), PHP 8.2 (Web)

---

## 🏗️ Project Architecture

Currently, ApexNova operates on a hybrid infrastructure:
1.  **Production Nodes:** Enterprise hardware managed via our partnership infrastructure.
2.  **Edge Services:** Discord bots and static web content hosted on optimized local environments.
3.  **Network Layer:** Secured via Cloudflare Tunnels to ensure home-hosting privacy and security.

---

## 📂 Repository Structure

```text
├── frontend/               # Website source code (HTML/Tailwind)
├── bot/                    # ApexNova Discord Utility Bot
├── configs/                # Pterodactyl Egg exports & Nginx configs
└── docs/                   # Setup guides and partnership documentation
