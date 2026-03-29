<div align="center">

<br>

<p align="center">
  <img src="techrzn.png" width="650" alt="TechRZN DNS Filter-Hub" />
</p>

<p align="center">
  Sprache: 🇩🇪 <b>[Deutsch]</b> | 🇺🇸 <a href="README.en.md">[English]</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-INFRASTRUKTUR_AKTIV-00C853?style=for-the-badge&logo=statuspage&logoColor=white" />
  <img src="https://img.shields.io/badge/DATENBANK-2.2M%2B_REGELN-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/UPLINK-2.5_GBIT_BACKBONE-7957d5?style=for-the-badge&logo=wi-fi&logoColor=white" />
</p>

---

## 🛰️ Mission & Vision
> **High-Performance Blocklisten • Täglich aktualisiert • 100% Bereinigt**

Willkommen beim **TechRZN Filter-Hub**. Dieses Repository bietet eine hochoptimierte "All-in-One" Lösung für **AdGuard Home, Pi-hole und Technitium**. Durch automatisierte Deduplizierung und eine intelligente Whitelist garantieren wir Schutz ohne "Overblocking".

---

## ❤️ Support & Community
Wenn dir der **TechRZN Filter-Hub** hilft, dein Netzwerk sicherer zu machen, freue ich mich über deine Unterstützung auf Patreon!

<p align="center">
  <a href="https://patreon.com/TechRZN">
    <img src="https://img.shields.io/badge/PATREON-UNTERSTÜTZER_WERDEN-orange?style=for-the-badge&logo=patreon&logoColor=white" height="45" />
  </a>
  <br>
  <img src="https://img.shields.io/badge/Status-Community_Projekt-orange?style=for-the-badge&logo=patreon" height="25" />
  <img src="https://img.shields.io/github/stars/TechRZN-DNS/TechRZN-Blocklist-Collection?style=for-the-badge&logo=github&color=7957d5" height="25" />
</p>

---

## 🚀 Direkt-Einbindung (Schnellzugriff)
> **Wichtiger Hinweis:** Aufgrund der massiven Größe (>100MB) ist die Master-Liste in zwei Teile aufgeteilt. **Bitte abonniere beide Teile**, um den vollen Schutz zu erhalten.

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_part1.txt">
    <img src="https://img.shields.io/badge/MASTER_TEIL_1-LINK_KOPIEREN-7957d5?style=for-the-badge&logo=adguard&logoColor=white" height="45" />
  </a>
  &nbsp;&nbsp;
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_part2.txt">
    <img src="https://img.shields.io/badge/MASTER_TEIL_2-LINK_KOPIEREN-7957d5?style=for-the-badge&logo=adguard&logoColor=white" height="45" />
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/whitelist.txt">
    <img src="https://img.shields.io/badge/WHITELIST-LINK_KOPIEREN-blue?style=for-the-badge&logo=github&logoColor=white" height="35" />
  </a>
</p>

---

## 🔞 Jugendschutz & Adult-Content (Optional)
> [!WARNING]
> **Bewusste Trennung:** Diese Listen sind **NICHT** in der Master-Liste enthalten, um jedem Nutzer die freie Wahl zu lassen.

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/techrzn_porn.txt">
    <img src="https://img.shields.io/badge/TECHRZN_PORN-LINK_KOPIEREN-red?style=for-the-badge&logo=unstop&logoColor=white" height="40" />
  </a>
  &nbsp;&nbsp;
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/techrzn_jugendschutz.txt">
    <img src="https://img.shields.io/badge/TECHRZN_JUGENDSCHUTZ-LINK_KOPIEREN-red?style=for-the-badge&logo=familysearch&logoColor=white" height="40" />
  </a>
</p>

---

## 🛠️ Einrichtung & Optimierung

<details>
<summary><b>📖 Schritt-für-Schritt Installation (AdGuard & Pi-hole)</b></summary>
<br>
<blockquote>
<h3>🛡️ AdGuard Home</h3>
1. Gehe zu <b>Filter</b> ➔ <b>DNS-Sperrlisten</b>.<br>
2. Klicke auf <b>Sperrliste hinzufügen</b> ➔ <b>Benutzerdefinierte Liste</b>.<br>
3. Füge <b>Teil 1</b> und dann <b>Teil 2</b> als separate Listen hinzu.<br>
4. <b>Pro-Tipp:</b> Aktiviere <i>Optimistisches Caching</i> für maximale Geschwindigkeit.

<h3>🥧 Pi-hole</h3>
1. Gehe zu <b>Adlists</b> im linken Menü.<br>
2. Füge beide URLs (Teil 1 & 2) nacheinander ein.<br>
3. <b>Wichtig:</b> Führe unter <i>Tools</i> ➔ <i>Update Gravity</i> ein Update aus.
</blockquote>
</details>

<details>
<summary><b>⚙️ Optimale AdGuard Home Einstellungen (Empfohlen)</b></summary>
<br>
<blockquote>
Für maximale Performance bei 2.2M+ Regeln (getestet auf <b>UGREEN NAS / 2,5 Gbit/s</b>):<br><br>
<b>1. DNS-Cache & TTL</b><br>
* Cache-Größe: <code>104.857.600</code> (100 MB)<br>
* Optimistisches Caching: <b>Aktiviert</b> ✅<br>
* TTL-Minimalwert: <code>3600</code> (1 Stunde)<br><br>
<b>2. Sicherheit & Filterung</b><br>
* DNSSEC: <b>Aktiviert</b> ✅<br>
* Sperrmodus: <code>Null-IP</code><br>
* Gültigkeitsdauer blockierter Antwort: <code>300</code> Sek.
</blockquote>
</details>

---

## 📦 Die Inhalts-Struktur
*Der TechRZN-Hub kombiniert eigene Spezial-Listen mit weltweiten Core-Modulen.*

| Bereich | Modul | Fokus | Link |
| :---: | :--- | :--- | :---: |
| 🛡️ | **TechRZN Ads** | Werbenetzwerke & Popups | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_ads.txt) |
| 🕵️‍♂️ | **TechRZN Tracking** | Datensammler & Telemetrie | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_tracking.txt) |
| 🦠 | **TechRZN Malware** | Schadsoftware & C2-Server | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_malware.txt) |
| 🎣 | **TechRZN Phishing** | Fake-Logins & Scam-Seiten | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_phishing.txt) |
| 🛑 | **TechRZN Threat** | Aktive Botnetze & Angriffe | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_threat_intel.txt) |
| 🛍️ | **TechRZN Fakeshop** | Betrugsshops & Abofallen | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_fakeshops.txt) |
| 🎰 | **TechRZN Gambling** | Casinos & Wettanbieter | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_gambling.txt) |
| 🪙 | **TechRZN Crypto** | Mining & Krypto-Betrug | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_crypto.txt) |
| 🔓 | **TechRZN Bypass** | VPN- & Proxy-Umgehungen | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_bypass.txt) |
| 🏆 | **HaGeZi Pro** | Weltweiter Schutz-Standard | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_pro.txt) |
| 🇩🇪 | **German Filter** | Optimierung für DE / AT / CH | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/adguard_german.txt) |
| 📺 | **Smart TV** | Unterbindet TV-Tracking | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/smart_tv.txt) |

---

## 🏗️ Hardware Backbone (Kleve, Deutschland)
*Validierung auf Enterprise-Hardware für absolute Zuverlässigkeit.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117; border-radius: 12px; overflow: hidden; border: 1px solid #30363d;">
  <tr>
    <td align="left" style="padding: 20px;">
      <b>CORE NODE</b><br>UGREEN NAS DXP4800 Plus<br>
      <img src="https://img.shields.io/badge/64_GB_DDR5_ECC-7957d5?style=flat-square" alt="RAM" />
    </td>
    <td align="left" style="padding: 20px;">
      <b>SSD ACCELERATION</b><br>Samsung 990 Pro RAID<br>
      <img src="https://img.shields.io/badge/NVMe_Gen4-FF6B6B?style=flat-square" alt="NVMe" />
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 20px;">
      <b>NETWORK</b><br>2.5 Gbit Hybrid-Power<br>
      <img src="https://img.shields.io/badge/Zyxel_Managed-00D2FF?style=flat-square" alt="Switch" />
    </td>
    <td align="left" style="padding: 20px;">
      <b>HDD STORAGE</b><br>80 TB WD Red Pro<br>
      <img src="https://img.shields.io/badge/RAID_5_ZFS-00C853?style=flat-square" alt="ZFS" />
    </td>
  </tr>
</table>

---

**Gepflegt mit ❤️ von Jörg Berns in Kleve • Stand: März 2026**
<br>
<img src="https://capsule-render.vercel.app/render?type=soft&color=7957d5&height=30&section=footer" width="100%" />

</div>
