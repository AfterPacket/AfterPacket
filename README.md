<!-- ========================================================= -->
<!-- AFTERPACKET PROFILE                                       -->
<!-- ========================================================= -->
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0D1117,20:161B22,40:1F6FEB,70:58A6FF,100:79C0FF&text=AFTERPACKET&fontColor=FFFFFF&fontSize=70&fontAlignY=38&desc=Open%20Source%20Cybersecurity%20Developer&descSize=18&descAlignY=58" width="100%"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=600&lines=Deception+Engineering;Threat+Intelligence;AI+Red+Teaming;Internet+Measurement" alt="Typing SVG"/>
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=AfterPacket&label=Profile+Views&color=1F6FEB&style=for-the-badge" alt="Profile views"/>
<img src="https://img.shields.io/github/followers/AfterPacket?style=for-the-badge&color=1F6FEB" alt="Followers"/>
<img src="https://img.shields.io/github/stars/AfterPacket?style=for-the-badge&color=1F6FEB" alt="Stars"/>
</p>

---

## Whoami

I got my handle at DefCon 25  August 2017, first time there, didn't have an
official name beyond a gaming tag, and a name generator spat out "AfterPacket."
It stuck. Everything since has been under that banner.

I build open-source tools for defenders who'd rather **understand** attackers
than just block them. That means honeypots that lie convincingly, proof-of-work
systems that don't need CAPTCHAs, red-team platforms that break LLMs on
purpose, and internet-scale monitoring that watches when the wires go dark.

I don't trust third-party services with my data  so I self-host everything,
document it, and ship it open source. If you can't read the code, you can't
trust the defense.

---

## Carnivorous Plants

My honeypot framework is named after carnivorous plants. Each one traps
attackers differently  that's not a metaphor, it's the design spec.

### Drosera — the sundew

<a href="https://github.com/AfterPacket/Drosera">
<img src="https://opengraph.githubassets.com/3cff993722e70e6d2779adf30105d3b52e0d9d2ec0b2018f8dadf5699627a2af/AfterPacket/Drosera" width="100%" alt="Drosera"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/Drosera?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/Drosera/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/Drosera?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/Drosera)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/Drosera?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/Drosera/commits)

Multi-protocol deception. Impersonates real services, tarpits the attacker,
records every byte, and turns those bytes into threat intelligence. Sundews
trap by adhesion — you stick to it, and the longer you struggle the more it
learns about you.

### Utricularia — the bladderwort

<a href="https://github.com/AfterPacket/Utricularia">
<img src="https://opengraph.githubassets.com/67489ad697819060119105aa46caa5d32a5ad2a8c4c52c5241f636de48b14671/AfterPacket/Utricularia" width="100%" alt="Utricularia"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/Utricularia?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/Utricularia/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/Utricularia?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/Utricularia)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/Utricularia?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/Utricularia/commits)

ICS/SCADA honeypot. Presents a Schneider Modicon PLC over Modbus/TCP and
EtherNet/IP. Behind it: a simulated pump station, a tiered loot chain that
rewards deep exploration, per-address scoring, tarpitting, and an SSH-tunneled
dashboard so you can watch the attackers in real time. Bladderworts trap by
suction — one wrong probe and you're inside with no way back out.

---

## What the Sundew Catches

### Drosera Threat Intel

[![Stars](https://img.shields.io/github/stars/AfterPacket/drosera-threat-intel?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/drosera-threat-intel/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/drosera-threat-intel?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/drosera-threat-intel/commits)
[![TLP](https://img.shields.io/badge/TLP-WHITE-FFFFFF?style=flat-square&labelColor=161B22)](https://github.com/AfterPacket/drosera-threat-intel)
<!--TIMESTAMP:{"mode": "relative", "badge": true, "label": "Last Intel Push", "color": "1F6FEB"}-->

Every capture from the Drosera honeypot gets a full writeup: YARA rule,
Suricata rules, IOC feed, firewall block entries, and a report explaining
**why each indicator is in and why each candidate was left out.** I don't
ship signatures that would false-positive across a real estate. Shared CDN
ranges never make the feed.

**Master blocklist** — newline-delimited IPs and domains, safe to `curl` on
a cron:https://raw.githubusercontent.com/AfterPacket/drosera-threat-intel/main/blocklist.txt


---

## Other Projects

### Vexor — LLM red-team platform

<a href="https://github.com/AfterPacket/vexor">
<img src="https://opengraph.githubassets.com/5d6dfbf0d4a301bc1f6e5f0ef3ee2549fb2b4bd8f2e155a6ffd4366290484254/AfterPacket/vexor" width="100%" alt="Vexor"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/vexor?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/vexor/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/vexor?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/vexor)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/vexor?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/vexor/commits)

Full OWASP GenAI Top 10 red-teaming. Multi-provider, automated jailbreak
testing, mutation engines, PromptFoo imports, synthetic attack generation. If
your model has a weakness, Vexor will find it before someone else does.

### Pow-Shield — proof-of-work, no CAPTCHA

<a href="https://github.com/AfterPacket/pow-shield-php">
<img src="https://opengraph.githubassets.com/8fc5a474362bb53727c63c47d911e3d0c74791e77d96897dabf1290df0486e75/AfterPacket/pow-shield-php" width="100%" alt="Pow-Shield"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/pow-shield-php?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/pow-shield-php/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/pow-shield-php?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/pow-shield-php)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/pow-shield-php?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/pow-shield-php/commits)

Adaptive SHA-256 puzzles for PHP and WordPress. No CAPTCHA, no JS
fingerprinting, no third-party services. Bots solve math; humans never see
anything. That's the whole pitch.

### partially.online — internet outage monitoring

<a href="https://github.com/AfterPacket/partially.online">
<img src="https://opengraph.githubassets.com/df2f314c34694a94e1ff950ab42adebf6496964a8e7e608a75197663e0a4c7d9/AfterPacket/partially.online" width="100%" alt="partially.online"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/partially.online?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/partially.online/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/partially.online?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/partially.online)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/partially.online?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/partially.online/commits)

Aggregates IODA, GDELT, Cloudflare Radar, and RIPE Atlas to watch the internet
go dark in real time. Built for correlating outages against real-world events —
because when a country drops off the map, the "why" matters more than the
"what."

### Social Hunt — OSINT platform

<a href="https://github.com/AfterPacket/Social-Hunt">
<img src="https://opengraph.githubassets.com/00874718520ae451e1eae59ddf94b37c54f2e64f6f2fab86bc5d681e98033a00/AfterPacket/Social-Hunt" width="100%" alt="Social Hunt"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/Social-Hunt?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/Social-Hunt/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/Social-Hunt?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/Social-Hunt)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/Social-Hunt?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/Social-Hunt/commits)

Username enumeration, face correlation, breach intel, metadata extraction,
multi-provider searching. Open source, self-hosted, no API keys required to
start.

### Secure Blog CMS — flat-file, security-first

<a href="https://github.com/AfterPacket/secure-blog-cms">
<img src="https://opengraph.githubassets.com/722116ac73b51965d9145e6903a0b8a7f5ea829f80be216147cf8cf439bc5980/AfterPacket/secure-blog-cms" width="100%" alt="Secure Blog CMS"/>
</a>

[![Stars](https://img.shields.io/github/stars/AfterPacket/secure-blog-cms?style=flat-square&color=1F6FEB&labelColor=161B22)](https://github.com/AfterPacket/secure-blog-cms/stargazers)
[![Language](https://img.shields.io/github/languages/top/AfterPacket/secure-blog-cms?style=flat-square&color=58A6FF&labelColor=161B22)](https://github.com/AfterPacket/secure-blog-cms)
[![Last commit](https://img.shields.io/github/last-commit/AfterPacket/secure-blog-cms?style=flat-square&color=79C0FF&labelColor=161B22)](https://github.com/AfterPacket/secure-blog-cms/commits)

No database. Argon2id sessions, CSP headers, 2FA, alerting. I wrote it because
every other flat-file CMS treated security as an afterthought.

### Smaller projects

| Repo | What it does |
| --- | --- |
| War Room | Geopolitical intelligence dashboard |
| CDN Origin Audit | Finds exposed origins behind CDNs |
| Network Tools | Packet analysis and debugging |
| AI Security Labs | Prompt injection / jailbreak research notes |
| Cryptography Experiments | Applied crypto — PoW, signed cookies, adaptive difficulty |
| Web Security Utilities | Misc defensive tooling |

---

## Stack

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Infrastructure:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

**Security tooling:**
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge&logo=suricata&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-0A0A0A?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C31E39?style=for-the-badge)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge)

---

## Activity

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=AfterPacket&theme=github-azure&hide_border=true&area=true&color=1F6FEB&line=58A6FF&point=79C0FF" alt="Activity Graph" width="100%"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=AfterPacket&theme=github-dark-blue&hide_border=true" alt="Streak stats"/>
</p>

<p align="center">
<img height="170em" src="https://github-readme-stats.vercel.app/api?username=AfterPacket&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub stats"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AfterPacket&layout=compact&theme=github_dark&hide_border=true" alt="Top languages"/>
</p>

<!-- The contribution snake eats through the graph above.
     Generated daily by GitHub Actions → output branch.
     Matches the carnivorous plants theme: the snake consumes. -->
<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AfterPacket/AfterPacket/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AfterPacket/AfterPacket/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/AfterPacket/AfterPacket/output/github-snake.svg" />
</picture>
</p>

### Recent Activity

<!--GITHUB_ACTIVITY:{"rows": 5, "style": "compact", "showDate": true}-->

### Coding Time

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

---

## What I'm working on right now

- **Drosera v1.0** — getting the core platform to a stable release
- **Utricularia protocol expansion** — adding DNP3 and S7comm so the PLC
  deception covers more vendor ecosystems
- **Attacker replay system** — record a session from one honeypot, replay it
  against another to see if detection catches it
- **Public REST API** for honeypot telemetry so other tools can pull feeds
  programmatically
- **AI-powered IOC enrichment** — correlating captures against threat feeds
  without manual triage
- **Internet censorship timeline** — a historical record, not just a live view

---

## How I think about this work

I'd rather watch an attacker for an hour than block them in a second. Blocking
teaches you nothing. Every probe, every credential attempt, every lateral
move is a data point — and enough data points become a profile, and enough
profiles become a pattern, and patterns are what actually let you get ahead
of the next attack instead of reacting to the last one.

I build everything privacy-first and self-hostable because defenders shouldn't
have to hand their telemetry to a third party to get value from it. If I
wouldn't run it on my own infrastructure, I don't ship it.

Open source isn't charity — it's force multiplication. Every person who runs
Drosera makes the blocklist smarter. Every person who runs Vexor makes the
next LLM harder to jailbreak. That's the whole point.

---

## Contact

<p align="center">
<a href="https://github.com/AfterPacket"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
<a href="https://mastodon.social/@AfterPacket"><img src="https://img.shields.io/badge/Mastodon-6364FF?style=for-the-badge&logo=mastodon&logoColor=white" alt="Mastodon"/></a>
<a href="https://x.com/AfterPacket"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x" alt="X"/></a>
<a href="mailto:AfterPacketTru@protonmail.com"><img src="https://img.shields.io/badge/ProtonMail-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
<a href="https://buymeacoffee.com/galorr"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy me a coffee"/></a>
<a href="https://paypal.me/ThatGuyJ89"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal"/></a>
</p>

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0D1117,20:161B22,40:1F6FEB,70:58A6FF,100:79C0FF" width="100%"/>
</p>

<p align="center">
<b>Build. Defend. Share.</b><br/>
<i>Every attacker interaction is an opportunity to learn.</i>
</p>
