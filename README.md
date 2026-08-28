<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Yaroslav — безопасность сетей и приложений" src="assets/hero-light.svg">
</picture>

**Русский** · [English](README.en.md)

Специалист по информационной безопасности и разработчик из Челябинска.
Совладелец и ведущий разработчик двух продуктов, которые работают у живых
пользователей и приносят деньги.

[![Telegram](https://img.shields.io/badge/Telegram-%40yaroslav__mv-111111?style=flat-square&logo=telegram&logoColor=white)](https://t.me/yaroslav_mv) [![Proton Mail](https://img.shields.io/badge/Mail-unicorn__rm%40proton.me-4A4A4A?style=flat-square&logo=protonmail&logoColor=white)](mailto:unicorn_rm@proton.me)

## Работы

<table>
<tr>
<td width="50%" valign="top">

<a href="https://asterio-ai.com"><img src="assets/asterio.png" alt="Главный экран Asterio"></a>
<h3><a href="https://asterio-ai.com">Asterio</a></h3>
<p><b>Первый официальный ИИ-агрегатор в России.</b> Доступ к нейросетям без VPN: чат, генерация изображений и видео, ИИ-агенты, оплата картой.</p>
<p><b>Роль:</b> совладелец, ведущий разработчик и специалист по кибербезопасности.</p>
<p><b>Веду:</b> сайт, бэкенд и серверную часть. Платёжный и юридический контур, антибот-защита, ускорение загрузки — бандл ужат с 977 КБ до 276 КБ код-сплитом, в 3,5 раза.</p>
<p><code>React</code> <code>TypeScript</code> <code>FastAPI</code> <code>Cloudflare</code></p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vantage-guardian"><img src="assets/vantage-guardian.png" alt="Главный экран VANTAGE GUARDIAN"></a>
<h3><a href="https://github.com/unicorn-rm/vantage-guardian">VANTAGE GUARDIAN</a></h3>
<p>Клиент сетевой защиты для компьютерных клубов. Гость нажимает одну кнопку — поднимается туннель до игрового узла. Локальные сети зала при этом не трогаются никогда.</p>
<p><b>Роль:</b> совладелец. Разработка клиента и серверной части, безопасность, юридический контур.</p>
<p><b>Сделал:</b> сканер установленных игр для шести лаунчеров, раздельная маршрутизация, чистый DNS, каталог с запуском игр из окна, выездные прогоны на клубных машинах.</p>
<p><code>Rust</code> <code>Tauri</code> <code>AmneziaWG</code> <code>Windows</code></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://www.unicorn-web.ru/"><img src="assets/unicorn-web.png" alt="unicorn-web.ru"></a>
<h3><a href="https://www.unicorn-web.ru/">unicorn-web.ru</a></h3>
<p>Личный сайт-портфолио: опыт, образование, сертификаты, проекты, CTF и компании, с которыми работал. Загрузочный экран, терминальная подача, тёмная тема.</p>
<p><b>Роль:</b> вёрстка, наполнение, публикация. Основа — открытый шаблон, авторство макета сохранено в репозитории намеренно.</p>
<p><code>HTML</code> <code>CSS</code> <code>JavaScript</code></p>

</td>
<td width="50%" valign="top">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stand-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stand-light.svg">
  <img alt="Схема переносного защищённого стенда" src="assets/stand-light.svg">
</picture>
<h3>Переносной защищённый стенд</h3>
<p>Карманный роутер прячет весь трафик подключённого устройства в обфусцированный туннель и не даёт ничему утечь мимо него. Аплинк — телефон по USB, SIM в роутере нет намеренно.</p>
<p><b>Роль:</b> проектирование, сборка, испытания. Модель угроз сформулирована честно: цель — поднять порог обнаружения и стоимость анализа, а не обещать неотслеживаемость.</p>
<p><code>OpenWrt</code> <code>AmneziaWG</code> <code>nftables</code> <code>Cudy TR3000</code></p>

</td>
</tr>
</table>

## Исследование: локальный LLM-агент

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/llm-bench-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/llm-bench-light.svg">
  <img alt="Замер: 1 ток/с до и 16 после установки драйвера" src="assets/llm-bench-light.svg">
</picture>

Поставил локальную модель агентом в opencode на ноутбуке с RTX 3060. Она выдавала
**1 токен в секунду** и падала по таймаутам. Перебор квантов и режимов ничего не дал —
корень оказался в другом месте: **в системе не было драйвера NVIDIA**, и GPU считал
через открытый Vulkan. После установки драйвера с CUDA и прокси, отключающего «думанье»
модели, — **16 токенов в секунду** и рабочий tool-calling.

Ценность кейса не в цифрах, а в том, что дорогая гипотеза (квантование) оказалась
неверной, а дешёвая проверка окружения — верной.

<code>Ollama</code> <code>opencode</code> <code>CUDA</code> <code>Python</code>

## Учебные стенды

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/vuln-login"><img src="assets/vuln-login.png" alt="SQL-инъекция в стенде vuln-login"></a>
<h3><a href="https://github.com/unicorn-rm/vuln-login">vuln-login</a></h3>
<p>Учебный стенд по веб-пентесту: намеренно уязвимая форма входа и рядом, в той же папке, исправленная версия. Видно и саму SQL-инъекцию, и то, чем она лечится.</p>
<p><code>Python</code> <code>Flask</code> <code>SQLite</code></p>

</td>
<td width="50%" valign="top">

<a href="https://github.com/unicorn-rm/password-tool"><img src="assets/password-tool.png" alt="Экран password-tool"></a>
<h3><a href="https://github.com/unicorn-rm/password-tool">password-tool</a></h3>
<p>Разбор стойкости паролей: оценка энтропии, проверка по словарям утечек и генератор. Веб-интерфейс, считает на сервере.</p>
<p><code>Python</code> <code>Flask</code></p>

</td>
</tr>
</table>

## Арсенал

<table>
<tr><td><b>Разведка</b></td><td><code>nmap</code> <code>masscan</code> <code>maltego</code> <code>spiderfoot</code> <code>enum4linux</code></td></tr>
<tr><td><b>Веб-приложения</b></td><td><code>Burp Suite</code> <code>sqlmap</code> <code>ffuf</code> <code>gobuster</code> <code>nikto</code> <code>dirb</code> <code>wpscan</code></td></tr>
<tr><td><b>Пароли и доступ</b></td><td><code>hashcat</code> <code>John the Ripper</code> <code>hydra</code> <code>impacket</code> <code>responder</code></td></tr>
<tr><td><b>Сеть и трафик</b></td><td><code>Wireshark</code> <code>tcpdump</code> <code>netcat</code> <code>aircrack-ng</code></td></tr>
<tr><td><b>Эксплуатация и реверс</b></td><td><code>Metasploit</code> <code>exploitdb</code> <code>SET</code> <code>radare2</code> <code>binwalk</code></td></tr>
</table>

## Стек разработки

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg">
  <img alt="Стек: языки, каркасы и среды, инфраструктура, данные" src="assets/stack-light.svg">
</picture>

## Сертификаты

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

## Связаться

Открыт к предложениям в информационной безопасности и разработке.

- Telegram — [@yaroslav_mv](https://t.me/yaroslav_mv)
- Почта — [unicorn_rm@proton.me](mailto:unicorn_rm@proton.me)
- Сайт — [unicorn-web.ru](https://www.unicorn-web.ru/)
