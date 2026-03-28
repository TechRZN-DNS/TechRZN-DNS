<div align="center">

<img src="https://capsule-render.vercel.app/render?type=kalo&color=7957d5&height=180&section=header&text=TechRZN%20DNS%20MASTER%20CORE&fontSize=50&animation=twinkling&fontAlignY=35" width="100%" />

<br>

<p align="center">
  <img src="techrzn-dns.jpg" width="450" alt="TechRZN Advanced DNS Stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE_INFRASTRUCTURE-00C853?style=for-the-badge&logo=statuspage&logoColor=white" />
  <img src="https://img.shields.io/badge/DATABASE-1M%2B_HARDENED_RULES-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/UPLINK-2.5_GBIT%2F_S_BACKBONE-7957d5?style=for-the-badge&logo=wi-fi&logoColor=white" />
</p>

---

## 🛰️ System Architecture & Mission
**High-Performance Blocklists • Täglich aktualisiert • 100% Bereinigt**

Willkommen beim **TechRZN Filter-Hub**. Dieses Repository bietet eine täglich aktualisierte "All-in-One" Blocklist für **AdGuard Home, Pi-hole und Technitium**. Alle Listen werden automatisch von Duplikaten bereinigt und gegen eine mehrstufige Whitelist geprüft, um maximale Sicherheit bei Null-Latenz zu garantieren.

---

## 🚀 DIE MASTER-LISTE (Empfohlen)
**Die ultimative Lösung für dein Setup. Enthält alle 11 Filter-Module in einer einzigen Datei.**

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt">
    <img src="https://img.shields.io/badge/DOWNLOAD_MASTER_COLLECTION-7957d5?style=for-the-badge&logo=github&logoColor=white" height="45" />
  </a>
</p>

`https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt`

---

## 🧩 Modulare Filter-Architektur (Die 11 Module)
| Modul | Fokus / Schutzbereich | Raw-Link |
| :--- | :--- | :--- |
| 🥇 **HaGeZi Pro** | All-in-One Schutz (Gold Standard) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/hagezi_pro.txt) |
| 🔐 **Bypass Filter** | Blockierung von VPN, Proxy, Tor & Bypass-Methoden | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/bypass.txt) |
| 🏴‍☠️ **Threat Intel** | Schutz vor Cyber-Angriffen & Botnets | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/threat_intel.txt) |
| 🇩🇪 **German Filter** | **Spezial-Optimierung für DE / AT / CH** | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/german_filter.txt) |
| 📺 **Smart-TV** | Unterbindung von TV-Tracking & Werbung | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/smart_tv.txt) |
| 🦠 **URLHaus** | Malware-URLs & Phishing (Echtzeit) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/urlhaus.txt) |
| 💻 **Windows Spy** | Hardening für MS Telemetrie & Office | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/windows_spy.txt) |
| 🎮 **Gambling** | Blokierung von Glücksspiel & Wetten | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/gambling.txt) |
| ⚠️ **Fake DNS** | Schutz vor Scam & Fake-Shops | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/fake_dns.txt) |
| 📜 **Dan Pollock** | Legendärer Hosts-File Klassiker | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/dan_pollock.txt) |
| 📍 **TechRZN IPs** | Eigene Liste bösartiger IP-Adressen | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/techrzn_ips.txt) |

---

## ⚙️ Optimale AdGuard Home Einstellungen
*Konfiguration für maximale Stabilität bei 1M+ aktiven Regeln:*

| Kategorie | Einstellung | Empfohlener Wert |
| :--- | :--- | :--- |
| **DNS-Cache** | Cache-Größe | **100 MB** (104.857.600 Bytes) ✅ |
| **DNS-Cache** | Optimistisches Caching | **Aktiviert** ✅ |
| **TTL** | Minimalwert / Höchstwert | **3600** (1h) / **86400** (24h) |
| **Upstream** | **Upstream-Timeout** | **2 - 5 Sekunden** ⏳ |
| **Upstream** | **Parallele Abfrage** | **Eingeschaltet** (Schnellste Antwort) ⚡ |
| **Antwort** | **Gültigkeitsdauer (Blockiert)** | **300 Sekunden** ✅ |
| **Security** | DNSSEC & Sperrmodus | **Aktiviert** / **Standard** |
| **Inverse DNS** | Private Reverse-DNS | **Aktiviert** (Router-IP eintragen) |

---

## 🏗️ The Backbone: Bare-Metal Power
*Jede Liste wird auf dieser dedizierten Infrastruktur in Kleve prozessiert und validiert.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117; border-radius: 10px; overflow: hidden;">
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <b>Compute Node:</b> UGREEN NAS DXP4800 Plus | <b>64 GB RAM</b>
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <b>IO-Layer:</b> 2x 2TB <b>Samsung 990 Pro</b> NVMe (Cache)
    </td>
  </tr>
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <b>Storage:</b> 80 TB Raw (4x 20TB <b>WD Red Pro</b> RAID 5)
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <b>Fabric:</b> Zyxel Switch | <b>2.5 Gbit/s Backbone</b>
    </td>
  </tr>
</table>

---

## ❤️ Support & Infrastruktur
Der tägliche Betrieb der **2,5 Gbit/s Test-Umgebung** und die Pflege von über 1 Million Regeln erfordern Zeit und Ressourcen. Wenn dir meine Arbeit hilft:

* **Feedback:** Eröffne ein [Issue](https://github.com/TechRZN-DNS/TechRZN-Blocklist-Collection/issues) oder gib dem Projekt einen ⭐.
* **Support:** Da mein Patreon aktuell noch in der Prüfung ist, kontaktiere mich bei Interesse einfach direkt.

<br>
<img src="https://capsule-render.vercel.app/render?type=soft&color=7957d5&height=30&section=footer" width="100%" />

**Maintained with ❤️ by TechRZN in Kleve • Stand: März 2026**
</div>
