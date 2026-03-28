<div align="center">

<br>

<p align="center">
  <img src="techrzn-dns.png" width="450" alt="TechRZN Advanced DNS Stack" />
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
**Die ultimative Lösung für dein Setup. Enthält alle 14 Filter-Module in einer einzigen Datei.**

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt">
    <img src="https://img.shields.io/badge/DOWNLOAD_MASTER_COLLECTION-7957d5?style=for-the-badge&logo=github&logoColor=white" height="45" />
  </a>
</p>

`https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt`

---

## 🧩 Modulare Filter-Architektur (Die 14 Module)
| Modul | Fokus / Schutzbereich | Raw-Link |
| :--- | :--- | :--- |
| 🥇 **HaGeZi Pro** | Weltweiter All-in-One Schutz (Gold Standard) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_pro.txt) |
| 🔐 **Bypass Filter** | VPN, Proxy, Tor & Bypass-Methoden | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_bypass.txt) |
| 🏴‍☠️ **Threat Intel** | Schutz vor Cyber-Angriffen & Botnets | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_threat.txt) |
| 🇩🇪 **German Filter** | **Spezial-Optimierung für DE / AT / CH** | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/adguard_german.txt) |
| 📺 **Smart-TV** | Unterbindung von TV-Tracking & Werbung | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/smart_tv.txt) |
| 🦠 **URLHaus** | Malware-URLs & Phishing (Echtzeit) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/urlhaus_malicious.txt) |
| 💻 **Windows Spy** | Hardening für MS Telemetrie & Office | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_windows.txt) |
| 🎮 **Gambling** | Blockierung von Glücksspiel & Wetten | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_gambling.txt) |
| ⚠️ **Fake DNS** | Schutz vor Scam & Fake-Shops | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_fake.txt) |
| 📜 **Dan Pollock** | Legendärer Hosts-File Klassiker | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/dan_pollock.txt) |
| 📍 **TechRZN IPs** | Eigene Liste bösartiger IP-Adressen | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/techrzn_ips.txt) |
| 🛍️ **Anti-Fakeshop** | Schutz vor Abofallen & Betrug (RPiList) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/notserious.txt) |
| 🏦 **Banking-Schutz** | Phishing-Schutz (Banken DE/AT/CH - RPiList) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/phishing_de.txt) |
| 🔬 **Fake-Science** | Schutz vor Scam-Portalen (RPiList) | [Link](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/fake_science.txt) |

---

## 🏗️ The Backbone: Bare-Metal Power
*Jede Liste wird auf dieser dedizierten Infrastruktur in Kleve prozessiert und validiert.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117; border-radius: 10px; overflow: hidden;">
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <code>CORE NODE</code><br><b>UGREEN NAS DXP4800 Plus</b><br><img src="https://img.shields.io/badge/RAM-64_GB_ECC-7957d5?style=flat-square" />
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <code>ACCELERATION</code><br><b>2x 2TB Samsung 990 Pro</b><br><img src="https://img.shields.io/badge/I/O-NVMe_Gen4-FF6B6B?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <code>STORAGE</code><br><b>80 TB WD Red Pro</b><br><img src="https://img.shields.io/badge/ARRAY-RAID_5-00C853?style=flat-square" />
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <code>NETWORK</code><br><b>Zyxel Managed Switch</b><br><img src="https://img.shields.io/badge/FABRIC-2.5_Gbit-white?style=flat-square&logoColor=black" />
    </td>
  </tr>
</table>

---

## 📊 Analytics
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TechRZN&show_icons=true&theme=tokyonight&hide_border=true&title_color=7957d5&text_color=9ece6a" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TechRZN&layout=compact&theme=tokyonight&hide_border=true&title_color=7957d5&text_color=9ece6a" height="170" />
</p>

---

## ❤️ Support & Infrastruktur
Der tägliche Betrieb der **2,5 Gbit/s Test-Umgebung** in Kleve erfordert massiv Zeit und Ressourcen. Wenn dir meine Arbeit hilft:

* **Feedback:** Eröffne ein [Issue](https://github.com/TechRZN-DNS/TechRZN-Blocklist-Collection/issues) oder gib dem Projekt einen ⭐.
* **Support:** Kontaktiere mich bei Interesse an einer Unterstützung einfach direkt.

<br>
<img src="https://capsule-render.vercel.app/render?type=soft&color=7957d5&height=30&section=footer" width="100%" />

**Maintained with ❤️ by TechRZN in Kleve • Stand: März 2026**
</div>
