<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Yaroslav — network and application security" src="assets/hero-light.svg">
</picture>

[Русский](README.md) · **English**

Information security specialist and developer based in Chelyabinsk, Russia.
Co-owner and lead developer of two products with live users and real revenue.

[![Telegram](https://img.shields.io/badge/Telegram-%40yaroslav__mv-111111?style=flat-square&logo=telegram&logoColor=white)](https://t.me/yaroslav_mv) [![Proton Mail](https://img.shields.io/badge/Mail-unicorn__rm%40proton.me-4A4A4A?style=flat-square&logo=protonmail&logoColor=white)](mailto:unicorn_rm@proton.me)

## Work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://asterio-ai.com"><img src="assets/asterio.png" alt="Asterio"></a>
<h3><a href="https://asterio-ai.com">Asterio</a></h3>
<p><b>Russia's first official AI aggregator.</b> Access to neural networks without a VPN: chat, image and video generation, AI agents, card payments.</p>
<p><b>Role:</b> co-owner, lead developer and security specialist.</p>
<p><b>I run:</b> the site, the backend and the server side. Payment and legal layers, anti-bot protection, and load-time work — the bundle went from 977 KB down to 276 KB through code splitting, a 3.5x cut.</p>
<p><code>React</code> <code>TypeScript</code> <code>FastAPI</code> <code>Cloudflare</code></p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vantage-guardian"><img src="assets/vantage-guardian.png" alt="VANTAGE GUARDIAN main screen"></a>
<h3><a href="https://github.com/unicorn-rm/vantage-guardian">VANTAGE GUARDIAN</a></h3>
<p>Network protection client for gaming venues. One button raises a tunnel to the game node; the venue's own local networks are never touched.</p>
<p><b>Role:</b> co-owner. Client and server-side development, security, and the legal layer.</p>
<p><b>Built:</b> installed-game scanner across six launchers, split routing, clean DNS, an in-app catalogue that launches games directly, and on-site test runs on venue machines.</p>
<p><code>Rust</code> <code>Tauri</code> <code>AmneziaWG</code> <code>Windows</code></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://www.unicorn-web.ru/"><img src="assets/unicorn-web.png" alt="unicorn-web.ru"></a>
<h3><a href="https://www.unicorn-web.ru/">unicorn-web.ru</a></h3>
<p>Personal portfolio site: experience, education, certifications, projects, CTF and the companies I have worked with. Boot screen, terminal styling, dark theme.</p>
<p><b>Role:</b> build, content and deployment. Based on an open template; the original design credit is kept in the repository on purpose.</p>
<p><code>HTML</code> <code>CSS</code> <code>JavaScript</code></p>

</td>
<td width="50%" valign="top">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stand-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stand-light.svg">
  <img alt="Diagram of the portable hardened network stand" src="assets/stand-light.svg">
</picture>
<h3>Portable hardened network stand</h3>
<p>A pocket router hides all traffic from the attached device inside an obfuscated tunnel and lets nothing leak around it. The uplink is a phone over USB; there is deliberately no SIM in the router.</p>
<p><b>Role:</b> design, build and testing. The threat model is stated honestly: the goal is to raise the detection threshold and the cost of analysis, not to promise untraceability.</p>
<p><code>OpenWrt</code> <code>AmneziaWG</code> <code>nftables</code> <code>Cudy TR3000</code></p>

</td>
</tr>
</table>

## Case study: a local LLM agent

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/llm-bench-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/llm-bench-light.svg">
  <img alt="Benchmark: 1 tok/s before and 16 after installing the driver" src="assets/llm-bench-light.svg">
</picture>

I put a local model to work as an agent in opencode on a laptop with an RTX 3060. It
produced **1 token per second** and kept timing out. Cycling through quantisations and
modes changed nothing — the root cause was elsewhere: **the system had no NVIDIA driver**,
so the GPU was computing through open Vulkan. After installing the driver with CUDA and a
proxy that disables the model's "thinking", it reached **16 tokens per second** with
working tool calls.

The value here is not the numbers. It is that the expensive hypothesis (quantisation) was
wrong and the cheap one — check the environment — was right.

<code>Ollama</code> <code>opencode</code> <code>CUDA</code> <code>Python</code>

## Lab work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vuln-login"><img src="assets/vuln-login.png" alt="SQL injection against the vuln-login lab"></a>
<h3><a href="https://github.com/unicorn-rm/vuln-login">vuln-login</a></h3>
<p>A web pentest lab: a deliberately vulnerable login form with the fixed version next to it in the same repository. You see both the SQL injection and what cures it.</p>
<p><code>Python</code> <code>Flask</code> <code>SQLite</code></p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/password-tool"><img src="assets/password-tool.png" alt="password-tool screen"></a>
<h3><a href="https://github.com/unicorn-rm/password-tool">password-tool</a></h3>
<p>Password strength analysis: entropy scoring, breach-wordlist lookups and a generator, behind a web interface with the work done server-side.</p>
<p><code>Python</code> <code>Flask</code></p>

</td>
</tr>
</table>

## Arsenal

<table>
<tr><td><b>Recon</b></td><td><code>nmap</code> <code>masscan</code> <code>maltego</code> <code>spiderfoot</code> <code>enum4linux</code></td></tr>
<tr><td><b>Web applications</b></td><td><code>Burp Suite</code> <code>sqlmap</code> <code>ffuf</code> <code>gobuster</code> <code>nikto</code> <code>dirb</code> <code>wpscan</code></td></tr>
<tr><td><b>Passwords and access</b></td><td><code>hashcat</code> <code>John the Ripper</code> <code>hydra</code> <code>impacket</code> <code>responder</code></td></tr>
<tr><td><b>Network and traffic</b></td><td><code>Wireshark</code> <code>tcpdump</code> <code>netcat</code> <code>aircrack-ng</code></td></tr>
<tr><td><b>Exploitation and reversing</b></td><td><code>Metasploit</code> <code>exploitdb</code> <code>SET</code> <code>radare2</code> <code>binwalk</code></td></tr>
</table>

## Development stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg">
  <img alt="Stack: languages, frameworks and runtimes, infrastructure, data" src="assets/stack-light.svg">
</picture>

## Certifications

<table>
<tr align="center">
<td width="25%"><a href="https://www.credly.com/badges/3b72c93b-d79b-435a-bfb1-0c6e2faaced6/public_url"><img src="assets/cert-cisco.png" width="104" alt="Cisco — Introduction to Cybersecurity"></a><br><b>Introduction to Cybersecurity</b><br><sub>Cisco Networking Academy</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/543454fd-40f6-4fe4-8400-578562a5fb24/public_url"><img src="assets/cert-isc2.png" width="104" alt="ISC2 Candidate"></a><br><b>Candidate</b><br><sub>ISC2</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/b7b62e7a-6793-4245-9d05-0a972284ec0f/public_url"><img src="assets/cert-ibm.png" width="104" alt="IBM SkillsBuild — Cybersecurity Fundamentals"></a><br><b>Cybersecurity Fundamentals</b><br><sub>IBM SkillsBuild</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/76fc8218-eb89-4ae9-a47b-06b5a93230f2/public_url"><img src="assets/cert-fortinet-fcf.png" width="104" alt="Fortinet Certified Fundamentals Cybersecurity"></a><br><b>Certified Fundamentals</b><br><sub>Fortinet</sub></td>
</tr>
<tr align="center">
<td><a href="https://www.credly.com/badges/e9353225-9f92-4fc0-893b-bc2c303a70af/public_url"><img src="assets/cert-nse1.png" width="104" alt="Fortinet NSE 1 Certified in Cybersecurity"></a><br><b>NSE 1 Certified</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/6708838b-a448-439f-8563-c124c2cb4d35/public_url"><img src="assets/cert-nse2.png" width="104" alt="Fortinet NSE 2 Certified in Cybersecurity"></a><br><b>NSE 2 Certified</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/313d559e-8e60-45c2-8621-835406dd4132/public_url"><img src="assets/cert-threat.png" width="104" alt="Introduction to the Threat Landscape 3.0"></a><br><b>Threat Landscape 3.0</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/1de506d2-2c2a-4bf8-995f-497b95e4e8e1/public_url"><img src="assets/cert-techintro.png" width="104" alt="Technical Introduction to Cybersecurity 3.0"></a><br><b>Technical Introduction 3.0</b><br><sub>Fortinet</sub></td>
</tr>
</table>

## Contact

Open to offers in information security and development.

- Telegram — [@yaroslav_mv](https://t.me/yaroslav_mv)
- Email — [unicorn_rm@proton.me](mailto:unicorn_rm@proton.me)
- Site — [unicorn-web.ru](https://www.unicorn-web.ru/)
