<p align="center">
  <img src="assets/logo-dark.png#gh-light-mode-only" width="480" alt="YCAIR 晏呈空氣" />
  <img src="assets/logo-white.png#gh-dark-mode-only" width="480" alt="YCAIR 晏呈空氣" />
</p>

<h1 align="center">劉晏呈 <sub>Liu Yan-cheng</sub></h1>

<p align="center">
  <b>AI Agent Architect</b>&nbsp;&nbsp;|&nbsp;&nbsp;<b>Web3 Security Researcher</b>&nbsp;&nbsp;|&nbsp;&nbsp;<b>P2P Network Engineer</b>
</p>

<p align="center">
  <a href="https://ycair.space"><img src="https://img.shields.io/badge/ycair.space-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://ycair.online"><img src="https://img.shields.io/badge/ycair.online-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="mailto:ycair.support@gmail.com"><img src="https://img.shields.io/badge/Email-ycair.support%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/THU-CS-AIM-Lab"><img src="https://img.shields.io/badge/THU--CS--AIM--Lab-00E5FF?style=for-the-badge&logo=googleclassroom&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1200&color=00E5FF&center=true&vCenter=true&width=600&lines=%E2%9A%A1+Building+AI+Agents+%26+P2P+Tunnels.;%F0%9F%9B%A0%EF%B8%8F+Turning+complex+network+routing+into+elegant+code.;%F0%9F%94%92+Auditing+Web3+transactions%2C+one+block+at+a+time.;%F0%9F%90%8D+Fueled+by+coffee%2C+code%2C+and+a+Ball+Python+named+Cache." alt="Typing SVG" />
</p>

---

## About

這裡是一名來自台灣的資訊工程學生與獨立開發者，同時也是 **YCAIR 晏呈空氣** 工作室的創辦人。

I'm a CSIE student and independent developer from Taiwan, running a solo studio called **YCAIR**. My work sits at the intersection of AI agent architectures, P2P network tunneling, and Web3 blockchain security — I turn graph theory and algorithms into practical open-source tools, and occasionally into Discord RPG bots. Also a proud custodian of a Ball Python named Cache 🐍.

```
🎓 Background       : CSIE, Taiwan — Independent Developer & Studio Founder
🏫 Lab              : THU-CS-AIM-Lab — Prof. Shyh-Wei Chen's Research Group, THU CS
🏗️ Current focus    : AI Agent harnesses · P2P tunneling · Web3 transaction security
🔬 Research xp      : ICD-10 auto-coding (DR-CAML) · Medical NLP · Restaurant optimization (ILP/CSP)
🛡️ Web3 defense     : Browser extension security · Chainalysis API · Bloom filter auditing
💬 Discord          : @ycair
🐍 Fun fact         : My Ball Python is literally named "Cache"
🌐 Studio           : YCAIR 晏呈空氣 — ycair.space · ycair.online
🤝 Open to          : Agent systems, network infrastructure, Web3 security, research collaboration
```

---

## Arsenal

<p>
  <img src="https://skillicons.dev/icons?i=python,go,rust,cpp,ts,docker,nextjs,pytorch,postgresql,cloudflare,git,linux" />
</p>

---

## Featured Work

### 🏥 ICD-10 Auto-Coding — `icd10-drcaml`

DR-CAML based extreme multi-label classification for automated ICD-10 disease coding.

- Trained on real clinical records from Taichung Veterans General Hospital; validated on MIMIC-IV
- **Tunghai Clean Pipeline**: reduced label space from 14,789 → 2,099 via F-code removal + 4-char truncation
- Focal Loss (γ=2) + Description Regularization → +6% Macro F1 over BCE baseline
- Domain gap quantified: MIMIC-IV vs. Taiwanese EHR text length (median 3,207 vs. 422 tokens)
- Repo: [github.com/ycair/icd10-drcaml](https://github.com/ycair/icd10-drcaml)

### 🛡️ Web3 Defense — `web3-defense`

A Chrome extension that intercepts and audits blockchain transactions before they are signed.

- **16+ heuristic checks**: unlimited approval detection, fake address similarity, honeypot screening
- Integrates GoPlus contract security API, Chainalysis sanctions screening, and Tenderly transaction simulation
- Built with Plasmo framework + TypeScript; fully local — zero data leaves the browser
- Bloom filter-based address auditing for fast lookups against known malicious addresses
- Repo: [github.com/ycair/web3-defense](https://github.com/ycair/web3-defense)

### 🍽️ RSO — Restaurant Seating Optimization

An ILP + CSP + graph-theory engine for real-time restaurant table allocation.

- Modeled on real topology of **Oh My! Yaki-Yan** (王品原燒) Taichung branch — 27 tables, 4 combinable pairs
- Handles spatial (combinable tables), temporal (120-min dining + reservations), and personnel (waiter load) constraints
- Configuration rigidity locks, shadow intervals for reservation protection, 12-guest special-case routing
- Research roadmap: heuristic scoring → ADP value functions (Task B) → MARL orchestrator (Task C)
- Repo: [github.com/ycair/RSO](https://github.com/ycair/RSO)

### 🎮 PF UTOPIA — `PF-UTOPIA`

A Discord MMORPG text game with 55+ slash commands: combat, economy, lottery, pets, and world bosses.

- 20-node graph-theory map with safe zones, radiation zones, and train stations
- Persistent HP across battles; death/revive mechanics; boss leaderboards
- 6 turtle stocks with 3x daily price updates; lottery (3/20 number pick); pet gacha system
- Stack: Python 3.13 + discord.py + PostgreSQL 16 (asyncpg) + aiohttp web server
- Deployed behind Cloudflare Tunnel at [utopia.ycair.space](https://utopia.ycair.space)
- Repo: [github.com/ycair/PF-UTOPIA](https://github.com/ycair/PF-UTOPIA)

---

## GitHub Pulse

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ycair&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ycair&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=ycair&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ycair/ycair/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</p>

---

## Connect

<p align="center">
  <a href="https://ycair.space"><img src="https://img.shields.io/badge/ycair.space-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://ycair.online"><img src="https://img.shields.io/badge/ycair.online-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://github.com/THU-CS-AIM-Lab"><img src="https://img.shields.io/badge/THU--CS--AIM--Lab-00E5FF?style=for-the-badge&logo=googleclassroom&logoColor=white" /></a>
  <a href="https://discord.com/users/663213825289486336"><img src="https://img.shields.io/badge/Discord-ycair-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
</p>

<p align="center">
  <a href="mailto:ycair.support@gmail.com"><img src="https://img.shields.io/badge/Email-ycair.support%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/ycair"><img src="https://img.shields.io/badge/GitHub-ycair-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>
