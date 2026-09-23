<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.jpg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.jpg">
  <img alt="unicorn — кибербезопасность, разработка, ИИ" src="assets/hero-light.jpg">
</picture>

**Русский** · [English](README.en.md)

Специалист по информационной безопасности и разработчик из Челябинска. Веду два
продукта, которые работают в бою у живых пользователей, и линейку открытых
инструментов для Claude Code. Четвёртый курс по специальности «Комплексное
обеспечение информационной безопасности автоматизированных систем».

Половина работы — созидание: бэкенд, серверы, десктопный клиент, релизы. Вторая
половина — разрушение: аудит собственных систем и пентест-лаборатории. По-моему,
по-настоящему защитить что-то можно, только сам попробовав это сломать.

[![Сайт](https://img.shields.io/badge/unicorn--web.ru-1A1A1A?style=flat-square&logo=safari&logoColor=white)](https://www.unicorn-web.ru/) [![Telegram](https://img.shields.io/badge/Telegram-%40yaroslav__mv-5B564E?style=flat-square&logo=telegram&logoColor=white)](https://t.me/yaroslav_mv) [![Почта](https://img.shields.io/badge/unicorn__rm%40proton.me-5B564E?style=flat-square&logo=protonmail&logoColor=white)](mailto:unicorn_rm@proton.me) [![Открыт к предложениям](https://img.shields.io/badge/-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%20%D0%BA%20%D0%BF%D1%80%D0%B5%D0%B4%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F%D0%BC-E2542B?style=flat-square)](https://t.me/yaroslav_mv)

## В бою

<table>
<tr>
<td width="50%" valign="top">

<a href="https://asterio-ai.com"><img src="assets/raboty/asterio.png" alt="Главный экран Asterio"></a>
<h3><a href="https://asterio-ai.com">Asterio</a></h3>
<p><b>Первый официальный ИИ-агрегатор в России.</b> Доступ к нейросетям без VPN: чат, генерация изображений и видео, ИИ-агенты, оплата картой.</p>
<p><b>Роль:</b> совладелец, ведущий разработчик и специалист по кибербезопасности.</p>
<p><b>Веду:</b> сайт, бэкенд и серверную часть. Платёжный и юридический контур, антибот-защита, ускорение загрузки — бандл ужат с 977 КБ до 276 КБ код-сплитом, в 3,5 раза.</p>
<p>
<img src="assets/chip/react.png" height="30" alt="React"> &nbsp;
<img src="assets/chip/typescript.png" height="30" alt="TypeScript"> &nbsp;
<img src="assets/chip/fastapi.png" height="30" alt="FastAPI"> &nbsp;
<img src="assets/chip/cloudflare.png" height="30" alt="Cloudflare">
</p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vantage-guardian"><img src="assets/raboty/vantage.png" alt="Главный экран VANTAGE GUARDIAN"></a>
<h3><a href="https://github.com/unicorn-rm/vantage-guardian">VANTAGE GUARDIAN</a></h3>
<p>Клиент сетевой защиты для компьютерных клубов. Гость нажимает одну кнопку — поднимается туннель до игрового узла. Локальные сети зала при этом не трогаются никогда.</p>
<p><b>Роль:</b> совладелец. Клиент, серверная часть, безопасность, юридический контур.</p>
<p><b>Сделал:</b> сканер установленных игр для шести лаунчеров, раздельная маршрутизация, чистый DNS, каталог с запуском игр из окна, выездные прогоны на клубных машинах. Работает в сети клубов: три зала, 127 машин, узлы во Франкфурте.</p>
<p>
<img src="assets/chip/rust.png" height="30" alt="Rust"> &nbsp;
<img src="assets/chip/tauri.png" height="30" alt="Tauri"> &nbsp;
<img src="assets/chip/amneziawg.png" height="30" alt="AmneziaWG"> &nbsp;
<img src="assets/chip/python.png" height="30" alt="Python">
</p>

</td>
</tr>
</table>

## Инструменты для Claude Code

Открытые плагины: наборы навыков, агентов и команд, которые превращают Claude Code
в профильного инженера. Оба построены на одном правиле — модель не выдумывает
фактов: каждое утверждение сверяется с первоисточником, а любое действие,
меняющее живую систему, проходит через ворота с проверкой.

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/Claude-cyber"><img src="assets/raboty/claude-cyber.jpg" alt="Claude Cyber"></a>
<h3><a href="https://github.com/unicorn-rm/Claude-cyber">Claude Cyber</a></h3>
<p>Кибербезопасность во всю ширину: <b>29 навыков, 6 агентов, 7 команд</b> — от разведки и веб-эксплуатации до реагирования на инциденты, детект-инжиниринга и комплаенса.</p>
<p>Наступательные действия закрыты воротами авторизации: без подтверждённой области работ агент не запускает ни одной атакующей команды. Выводы опираются на CVE, MITRE ATT&amp;CK, CWE и OWASP, а не на память модели.</p>
<p>
<img src="assets/chip/claude-code.png" height="30" alt="Claude Code"> &nbsp;
<img src="assets/chip/python.png" height="30" alt="Python"> &nbsp;
<img src="assets/chip/markdown.png" height="30" alt="Markdown">
</p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/Claude-DevOps"><img src="assets/raboty/claude-devops.jpg" alt="Claude DevOps"></a>
<h3><a href="https://github.com/unicorn-rm/Claude-DevOps">Claude DevOps</a></h3>
<p>DevOps, SRE и платформенная инженерия: <b>28 навыков, 5 агентов, 8 команд</b> — CI/CD, Kubernetes, Terraform, GitOps, наблюдаемость, дежурства и разбор инцидентов.</p>
<p>Любое изменение живой системы проходит через ворота безопасности: план, оценка радиуса поражения и путь отката. Синтаксис и поля сверяются с официальной документацией инструмента.</p>
<p>
<img src="assets/chip/claude-code.png" height="30" alt="Claude Code"> &nbsp;
<img src="assets/chip/docker.png" height="30" alt="Docker"> &nbsp;
<img src="assets/chip/python.png" height="30" alt="Python">
</p>

</td>
</tr>
</table>

## Стенды и исследования

<table>
<tr>
<td width="50%" valign="top">

<a href="https://www.unicorn-web.ru/"><img src="assets/raboty/unicorn-web.png" alt="unicorn-web.ru"></a>
<h3><a href="https://www.unicorn-web.ru/">unicorn-web.ru</a></h3>
<p>Личный сайт-портфолио: опыт, проекты, сертификаты и CTF, плюс разделы-энциклопедии по пентесту и ИИ, трек TryHackMe и курсы Anthropic Academy. Загрузочный экран, маскот, тёплая «бумажная» тема, две языковые версии.</p>
<p><b>Роль:</b> полная разработка — дизайн, вёрстка, наполнение, серверная часть и публикация. Своя админ-панель с аналитикой посещений.</p>
<p>
<img src="assets/chip/nextjs.png" height="30" alt="Next.js"> &nbsp;
<img src="assets/chip/react.png" height="30" alt="React"> &nbsp;
<img src="assets/chip/typescript.png" height="30" alt="TypeScript"> &nbsp;
<img src="assets/chip/tailwind.png" height="30" alt="Tailwind">
</p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/secure-stand-tr3000"><img src="assets/raboty/stand.jpg" alt="Переносной защищённый стенд"></a>
<h3><a href="https://github.com/unicorn-rm/secure-stand-tr3000">Переносной защищённый стенд</a></h3>
<p>Карманный роутер прячет весь трафик подключённого устройства в обфусцированный туннель и не даёт ничему утечь мимо него. Аплинк — телефон по USB, SIM в роутере нет намеренно.</p>
<p><b>Роль:</b> проектирование, сборка, испытания. Модель угроз сформулирована честно: цель — поднять порог обнаружения и стоимость анализа, а не обещать неотслеживаемость.</p>
<p>
<img src="assets/chip/openwrt.png" height="30" alt="OpenWrt"> &nbsp;
<img src="assets/chip/amneziawg.png" height="30" alt="AmneziaWG"> &nbsp;
<img src="assets/chip/nftables.png" height="30" alt="nftables"> &nbsp;
<img src="assets/chip/bash.png" height="30" alt="Bash">
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/local-llm-agent"><img src="assets/raboty/llm.jpg" alt="Локальный LLM-агент"></a>
<h3><a href="https://github.com/unicorn-rm/local-llm-agent">Локальный LLM-агент</a></h3>
<p>Локальная модель агентом в opencode на ноутбуке с RTX 3060. Выдавала <b>1 токен в секунду</b> и падала по таймаутам. Перебор квантов ничего не дал — в системе просто не было драйвера NVIDIA, и GPU считал через Vulkan. После драйвера с CUDA — <b>16 токенов в секунду</b> и рабочий tool-calling.</p>
<p>Ценность не в цифрах: дорогая гипотеза оказалась неверной, а дешёвая проверка окружения — верной.</p>
<p>
<img src="assets/chip/ollama.png" height="30" alt="Ollama"> &nbsp;
<img src="assets/chip/python.png" height="30" alt="Python"> &nbsp;
<img src="assets/chip/cuda.png" height="30" alt="CUDA">
</p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/win10-hardened-lab"><img src="assets/raboty/win10.jpg" alt="Защищённая Windows 10"></a>
<h3><a href="https://github.com/unicorn-rm/win10-hardened-lab">win10-hardened-lab</a></h3>
<p>Защищённая изолированная Windows 10 в VirtualBox: весь DNS принудительно через Cloudflare DoH, открытый DNS заблокирован, каналы хост↔гость закрыты.</p>
<p>Модель угроз, скрипты развёртывания, проверка изоляции — стенд собирается с нуля по трём сценариям.</p>
<p>
<img src="assets/chip/virtualbox.png" height="30" alt="VirtualBox"> &nbsp;
<img src="assets/chip/cloudflared.png" height="30" alt="cloudflared"> &nbsp;
<img src="assets/chip/powershell.png" height="30" alt="PowerShell">
</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/pentest-lab-writeups"><img src="assets/raboty/pentest.jpg" alt="Разборы уязвимых машин"></a>
<h3><a href="https://github.com/unicorn-rm/pentest-lab-writeups">pentest-lab-writeups</a></h3>
<p>Разборы уязвимых машин от разведки до root: Mr Robot, Kevgir, Empire LupinOne. Полные цепочки атак с командами. Стенд — нестед-виртуализация QEMU/KVM на изолированной сети.</p>
<p>
<img src="assets/chip/nmap.png" height="30" alt="nmap"> &nbsp;
<img src="assets/chip/ffuf.png" height="30" alt="ffuf"> &nbsp;
<img src="assets/chip/metasploit.png" height="30" alt="Metasploit"> &nbsp;
<img src="assets/chip/john.png" height="30" alt="John">
</p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vuln-login"><img src="assets/raboty/vuln-login.jpg" alt="Стенд vuln-login"></a>
<h3><a href="https://github.com/unicorn-rm/vuln-login">vuln-login</a> · <a href="https://github.com/unicorn-rm/password-tool">password-tool</a></h3>
<p><b>vuln-login</b> — учебный стенд по веб-пентесту: намеренно уязвимая форма входа и рядом, в той же папке, исправленная версия. Видно и саму SQL-инъекцию, и то, чем она лечится.</p>
<p><b>password-tool</b> — разбор стойкости паролей: балльная оценка, проверка по словарю частых паролей и генератор на secrets.</p>
<p>
<img src="assets/chip/python.png" height="30" alt="Python"> &nbsp;
<img src="assets/chip/flask.png" height="30" alt="Flask"> &nbsp;
<img src="assets/chip/sqlite.png" height="30" alt="SQLite">
</p>

</td>
</tr>
</table>

## Арсенал

Инструменты по этапам работы. Знаки везде официальные, проектов не придумано:
всё перечисленное прошло через стенд или живую задачу.

<table>
<tr><td valign="middle" width="150"><b>Разведка</b></td><td valign="middle">
<img src="assets/chip/nmap.png" height="30" alt="nmap"> &nbsp;
<img src="assets/chip/masscan.png" height="30" alt="masscan"> &nbsp;
<img src="assets/chip/maltego.png" height="30" alt="Maltego"> &nbsp;
<img src="assets/chip/spiderfoot.png" height="30" alt="SpiderFoot"> &nbsp;
<img src="assets/chip/enum4linux.png" height="30" alt="enum4linux">
</td></tr>
<tr><td valign="middle"><b>Веб-приложения</b></td><td valign="middle">
<img src="assets/chip/burpsuite.png" height="30" alt="Burp Suite"> &nbsp;
<img src="assets/chip/sqlmap.png" height="30" alt="sqlmap"> &nbsp;
<img src="assets/chip/ffuf.png" height="30" alt="ffuf"> &nbsp;
<img src="assets/chip/gobuster.png" height="30" alt="gobuster"> &nbsp;
<img src="assets/chip/nikto.png" height="30" alt="nikto"> &nbsp;
<img src="assets/chip/dirb.png" height="30" alt="dirb"> &nbsp;
<img src="assets/chip/wpscan.png" height="30" alt="wpscan">
</td></tr>
<tr><td valign="middle"><b>Пароли и доступ</b></td><td valign="middle">
<img src="assets/chip/hashcat.png" height="30" alt="hashcat"> &nbsp;
<img src="assets/chip/john.png" height="30" alt="John the Ripper"> &nbsp;
<img src="assets/chip/hydra.png" height="30" alt="hydra"> &nbsp;
<img src="assets/chip/impacket.png" height="30" alt="impacket"> &nbsp;
<img src="assets/chip/responder.png" height="30" alt="responder">
</td></tr>
<tr><td valign="middle"><b>Сеть и трафик</b></td><td valign="middle">
<img src="assets/chip/wireshark.png" height="30" alt="Wireshark"> &nbsp;
<img src="assets/chip/tcpdump.png" height="30" alt="tcpdump"> &nbsp;
<img src="assets/chip/netcat.png" height="30" alt="netcat"> &nbsp;
<img src="assets/chip/aircrack.png" height="30" alt="aircrack-ng">
</td></tr>
<tr><td valign="middle"><b>Эксплуатация<br>и реверс</b></td><td valign="middle">
<img src="assets/chip/metasploit.png" height="30" alt="Metasploit"> &nbsp;
<img src="assets/chip/exploitdb.png" height="30" alt="exploitdb"> &nbsp;
<img src="assets/chip/set.png" height="30" alt="SET"> &nbsp;
<img src="assets/chip/radare2.png" height="30" alt="radare2"> &nbsp;
<img src="assets/chip/binwalk.png" height="30" alt="binwalk">
</td></tr>
</table>

## Стек

<table>
<tr><td valign="middle" width="150"><b>Веб</b></td><td valign="middle">
<img src="assets/chip/html.png" height="30" alt="HTML"> &nbsp;
<img src="assets/chip/css.png" height="30" alt="CSS"> &nbsp;
<img src="assets/chip/javascript.png" height="30" alt="JavaScript"> &nbsp;
<img src="assets/chip/typescript.png" height="30" alt="TypeScript"> &nbsp;
<img src="assets/chip/react.png" height="30" alt="React"> &nbsp;
<img src="assets/chip/nextjs.png" height="30" alt="Next.js"> &nbsp;
<img src="assets/chip/vite.png" height="30" alt="Vite"> &nbsp;
<img src="assets/chip/tailwind.png" height="30" alt="Tailwind"> &nbsp;
<img src="assets/chip/motion.png" height="30" alt="Motion"> &nbsp;
<img src="assets/chip/tauri.png" height="30" alt="Tauri">
</td></tr>
<tr><td valign="middle"><b>Сервер<br>и данные</b></td><td valign="middle">
<img src="assets/chip/python.png" height="30" alt="Python"> &nbsp;
<img src="assets/chip/rust.png" height="30" alt="Rust"> &nbsp;
<img src="assets/chip/cpp.png" height="30" alt="C++"> &nbsp;
<img src="assets/chip/dotnet.png" height="30" alt=".NET"> &nbsp;
<img src="assets/chip/fastapi.png" height="30" alt="FastAPI"> &nbsp;
<img src="assets/chip/flask.png" height="30" alt="Flask"> &nbsp;
<img src="assets/chip/nodejs.png" height="30" alt="Node.js"> &nbsp;
<img src="assets/chip/swagger.png" height="30" alt="Swagger"> &nbsp;
<img src="assets/chip/postgresql.png" height="30" alt="PostgreSQL"> &nbsp;
<img src="assets/chip/sqlite.png" height="30" alt="SQLite"> &nbsp;
<img src="assets/chip/prisma.png" height="30" alt="Prisma">
</td></tr>
<tr><td valign="middle"><b>Инфраструктура</b></td><td valign="middle">
<img src="assets/chip/linux.png" height="30" alt="Linux"> &nbsp;
<img src="assets/chip/debian.png" height="30" alt="Debian"> &nbsp;
<img src="assets/chip/bash.png" height="30" alt="Bash"> &nbsp;
<img src="assets/chip/docker.png" height="30" alt="Docker"> &nbsp;
<img src="assets/chip/nginx.png" height="30" alt="Nginx"> &nbsp;
<img src="assets/chip/cloudflare.png" height="30" alt="Cloudflare"> &nbsp;
<img src="assets/chip/wireguard.png" height="30" alt="WireGuard"> &nbsp;
<img src="assets/chip/openwrt.png" height="30" alt="OpenWrt"> &nbsp;
<img src="assets/chip/letsencrypt.png" height="30" alt="Let's Encrypt"> &nbsp;
<img src="assets/chip/virtualbox.png" height="30" alt="VirtualBox"> &nbsp;
<img src="assets/chip/qemu.png" height="30" alt="QEMU">
</td></tr>
<tr><td valign="middle"><b>Рабочее место</b></td><td valign="middle">
<img src="assets/chip/kali.png" height="30" alt="Kali Linux"> &nbsp;
<img src="assets/chip/vim.png" height="30" alt="Vim"> &nbsp;
<img src="assets/chip/markdown.png" height="30" alt="Markdown"> &nbsp;
<img src="assets/chip/git.png" height="30" alt="Git"> &nbsp;
<img src="assets/chip/github.png" height="30" alt="GitHub"> &nbsp;
<img src="assets/chip/actions.png" height="30" alt="Actions"> &nbsp;
<img src="assets/chip/ollama.png" height="30" alt="Ollama"> &nbsp;
<img src="assets/chip/claude.png" height="30" alt="Claude">
</td></tr>
</table>

## Сертификаты

Все значки кликабельны и ведут на страницу проверки.

<table>
<tr align="center">
<td width="25%"><a href="https://www.credly.com/badges/3b72c93b-d79b-435a-bfb1-0c6e2faaced6/public_url"><img src="assets/sert/cert-cisco.png" width="96" alt="Cisco — Introduction to Cybersecurity"></a><br><b>Introduction to Cybersecurity</b><br><sub>Cisco Networking Academy</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/543454fd-40f6-4fe4-8400-578562a5fb24/public_url"><img src="assets/sert/cert-isc2.png" width="96" alt="ISC2 Candidate"></a><br><b>Candidate</b><br><sub>ISC2</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/b7b62e7a-6793-4245-9d05-0a972284ec0f/public_url"><img src="assets/sert/cert-ibm.png" width="96" alt="IBM SkillsBuild — Cybersecurity Fundamentals"></a><br><b>Cybersecurity Fundamentals</b><br><sub>IBM SkillsBuild</sub></td>
<td width="25%"><a href="https://www.credly.com/badges/76fc8218-eb89-4ae9-a47b-06b5a93230f2/public_url"><img src="assets/sert/cert-fortinet-fcf.png" width="96" alt="Fortinet Certified Fundamentals"></a><br><b>Certified Fundamentals</b><br><sub>Fortinet</sub></td>
</tr>
<tr align="center">
<td><a href="https://www.credly.com/badges/e9353225-9f92-4fc0-893b-bc2c303a70af/public_url"><img src="assets/sert/cert-nse1.png" width="96" alt="Fortinet NSE 1"></a><br><b>NSE 1 Certified</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/6708838b-a448-439f-8563-c124c2cb4d35/public_url"><img src="assets/sert/cert-nse2.png" width="96" alt="Fortinet NSE 2"></a><br><b>NSE 2 Certified</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/313d559e-8e60-45c2-8621-835406dd4132/public_url"><img src="assets/sert/cert-threat.png" width="96" alt="Introduction to the Threat Landscape 3.0"></a><br><b>Threat Landscape 3.0</b><br><sub>Fortinet</sub></td>
<td><a href="https://www.credly.com/badges/1de506d2-2c2a-4bf8-995f-497b95e4e8e1/public_url"><img src="assets/sert/cert-techintro.png" width="96" alt="Technical Introduction to Cybersecurity 3.0"></a><br><b>Technical Introduction 3.0</b><br><sub>Fortinet</sub></td>
</tr>
</table>

### Claude Academy и Google Cloud

<table>
<tr align="center">
<td width="16%"><a href="https://academy.claude.com/verify/103bc906cb670d0a79037af0cee1b44d"><img src="assets/sert/anthropic-claude101.png" width="88" alt="Claude 101"></a><br><sub><b>Claude 101</b></sub></td>
<td width="16%"><a href="https://academy.claude.com/verify/ac51b1061ff9af9f8d1385632f127dd6"><img src="assets/sert/anthropic-claude-code101.png" width="88" alt="Claude Code 101"></a><br><sub><b>Claude Code 101</b></sub></td>
<td width="16%"><a href="https://academy.claude.com/verify/1591cf544313a3329e8f7d4fdbc7de54"><img src="assets/sert/anthropic-platform101.png" width="88" alt="Claude Platform 101"></a><br><sub><b>Platform 101</b></sub></td>
<td width="16%"><a href="https://academy.claude.com/verify/1060e8cb78d2f718bd3d29ed02bb09b9"><img src="assets/sert/anthropic-ai-caps.png" width="88" alt="AI Capabilities and Limitations"></a><br><sub><b>AI Capabilities<br>and Limitations</b></sub></td>
<td width="16%"><a href="https://academy.claude.com/verify/836fa2a3aa578edf59a6c4deafac0a2a"><img src="assets/sert/anthropic-cowork.png" width="88" alt="Introduction to Claude Cowork"></a><br><sub><b>Claude Cowork</b></sub></td>
<td width="16%"><a href="https://me.developers.google.com/u/111424677456767070837"><img src="assets/sert/google.svg" width="88" alt="Google Cloud — Security Command Center"></a><br><sub><b>Security<br>Command Center</b></sub></td>
</tr>
</table>

### TryHackMe · [unicorn224](https://tryhackme.com/p/unicorn224)

<table>
<tr align="center">
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/mr-robot"><img src="assets/sert/thm-mrrobot.png" height="80" alt="Mr. Robot"></a><br><sub>Mr. Robot</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/ice"><img src="assets/sert/thm-ice.png" height="80" alt="Ice"></a><br><sub>Ice</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/web-fund"><img src="assets/sert/thm-webbed.png" height="80" alt="Webbed"></a><br><sub>Webbed</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/hash-cracker"><img src="assets/sert/thm-hashcracker.png" height="80" alt="Hash Cracker"></a><br><sub>Hash Cracker</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/logging-legend"><img src="assets/sert/thm-loganalysis.png" height="80" alt="Logging Legend"></a><br><sub>Logging Legend</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/iac-security"><img src="assets/sert/thm-iacsecurity.png" height="80" alt="Terminated!"></a><br><sub>Terminated!</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/7-day-streak"><img src="assets/sert/thm-streak7.png" height="80" alt="7 Day Streak"></a><br><sub>7 Day Streak</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/3-day-streak"><img src="assets/sert/thm-streak3.png" height="80" alt="3 Day Streak"></a><br><sub>3 Day Streak</sub></td>
<td width="11%"><a href="https://tryhackme.com/unicorn224/badges/first-mobile-quiz"><img src="assets/sert/thm-first-mobile-quiz.png" height="80" alt="First Mobile Quiz"></a><br><sub>First Mobile Quiz</sub></td>
</tr>
</table>

## Связаться

Открыт к предложениям в информационной безопасности и разработке — на месте,
гибридно или удалённо.

- Сайт — [unicorn-web.ru](https://www.unicorn-web.ru/)
- Telegram — [@yaroslav_mv](https://t.me/yaroslav_mv)
- Почта — [unicorn_rm@proton.me](mailto:unicorn_rm@proton.me)
