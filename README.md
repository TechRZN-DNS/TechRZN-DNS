<div align="center">

<img src="https://capsule-render.vercel.app/render?type=kalo&color=7957d5&height=160&section=header&text=TechRZN%20DNS%20MASTER%20CORE&fontSize=50&animation=twinkling&fontAlignY=35" width="100%" />

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE_INFRASTRUCTURE-00C853?style=for-the-badge&logo=statuspage&logoColor=white" />
  <img src="https://img.shields.io/badge/DATABASE-1M%2B_HARDENED_RULES-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/UPLINK-2.5_GBIT%2F_S_BACKBONE-7957d5?style=for-the-badge&logo=wi-fi&logoColor=white" />
</p>

---

## 🛰️ The Mission: High-Performance DNS Filtration
**Maximale Privatsphäre. Null Latenz. 100% Bereinigt.**

Willkommen im **TechRZN Filter-Hub**. Dieses System liefert täglich synchronisierte, de-duplizierte und verifizierte Blocklisten für **AdGuard Home, Pi-hole und Technitium**. Optimiert für deutsche High-Speed-Netzwerke und validiert auf dedizierter Bare-Metal-Hardware.

---

## 🏆 DIE MASTER-LISTE (Empfohlen)
### **TechRZN-DNS Master-Collection**
*Die ultimative All-in-One Lösung. Vereint alle 11 Sicherheits-Module in einer einzigen, performanten Engine.*

<a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt">
  <img src="https://img.shields.io/badge/DOWNLOAD_MASTER_LIST-CLICK_HERE-7957d5?style=for-the-badge&logo=github&logoColor=white" height="40" />
</a>

`https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_blocklist.txt`

---

## 🧩 Modulare Filter-Architektur
*Wähle spezifische Schutzbereiche für dein individuelles Setup:*

<table width="100%">
  <tr>
    <th>Modul</th>
    <th>Fokus / Schutzbereich</th>
    <th>Raw-Link</th>
  </tr>
  <tr>
    <td>🥇 <b>HaGeZi Pro</b></td>
    <td>Globaler All-in-One Schutz (Gold Standard)</td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/hagezi_pro.txt">Link</a></td>
  </tr>
  <tr>
    <td>🇩🇪 <b>German Core</b></td>
    <td><b>Spezial-Optimierung für DE/AT/CH Netzwerke</b></td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/german_filter.txt">Link</a></td>
  </tr>
  <tr>
    <td>🏴‍☠️ <b>Threat Intel</b></td>
    <td>Cyber-Angriffe, Botnets & C2-Infrastruktur</td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/threat_intel.txt">Link</a></td>
  </tr>
  <tr>
    <td>📺 <b>Smart-TV</b></td>
    <td>Unterbindung von TV-Tracking & Ad-Injection</td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/smart_tv.txt">Link</a></td>
  </tr>
  <tr>
    <td>💻 <b>Windows Spy</b></td>
    <td>MS Telemetrie, Office & OS-Hardening</td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/windows_spy.txt">Link</a></td>
  </tr>
  <tr>
    <td>⚠️ <b>Fake DNS</b></td>
    <td>Scam, Phishing & Fake-Shops Detection</td>
    <td><a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/fake_dns.txt">Link</a></td>
  </tr>
</table>

---

## 🛠️ Advanced Whitelisting & Referral Fix
*Um "Overblocking" zu vermeiden und nützliche Weiterleitungen (E-Mails, Preisvergleiche) zu erhalten:*

* **Zweistufiges Verfahren:** Integration der *HaGeZi Referral Whitelist* + manuelle *TechRZN Custom Whitelist*.
* **Referral Fix:** Verhindert defekte Login-Seiten (z.B. Telekom) und Affiliate-Probleme (Amazon, eBay).
* **Integration:** Kopiere den Inhalt der `ALLOWLIST_REF.txt` in deine benutzerdefinierten Filterregeln.

---

## ⚙️ Optimale AdGuard Home Konfiguration
*Empfohlene Settings für maximale Stabilität bei 1M+ Regeln:*

| Bereich | Einstellung | Wert |
| :--- | :--- | :--- |
| **DNS-Cache** | Cache-Größe | `104.857.600` (100 MB) |
| **DNS-Cache** | Optimistisches Caching | **Aktiviert** ✅ |
| **TTL** | Minimalwert / Höchstwert | `3600` / `86400` |
| **Konfiguration** | DNSSEC & Sperrmodus | **Aktiviert** / **Standard** |
| **Local DNS** | Private Reverse-DNS | **Aktiviert** (Router-IP eintragen) |

---

## 🏗️ The Backbone: Bare-Metal Power
*TechRZN operiert auf einer dedizierten High-Performance-Umgebung in Kleve, Germany.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117;">
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/server.png" width="30" /> <b>Compute:</b> UGREEN NAS | 64 GB RAM
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/ssd.png" width="30" /> <b>Cache:</b> 2x 2TB Samsung 990 Pro
    </td>
  </tr>
  <tr>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/ethernet-switch.png" width="30" /> <b>Fabric:</b> Zyxel 2.5G Managed
    </td>
    <td align="left" width="50%" style="padding: 15px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/router.png" width="30" /> <b>WAN:</b> FRITZ!Box 7690 | 250M Hybrid
    </td>
  </tr>
</table>

---

## 📊 Analytics
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TechRZN-DNS&show_icons=true&theme=tokyonight&hide_border=true&title_color=7957d5" height="180" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TechRZN-DNS&layout=compact&theme=tokyonight&hide_border=true&title_color=7957d5" height="180" />
</div>

---

## ❤️ Support & Connect
*Die Pflege von 1 Million Regeln und der 24/7 Betrieb der Test-Infrastruktur erfordern Zeit und Ressourcen.*

**[⭐ Star this Project]** • **[Report an Issue]** • **[Patreon (Soon)]**

<br>
<img src="https://capsule-render.vercel.app/render?type=soft&color=7957d5&height=30&section=footer" width="100%" />

**Engineered with precision by TechRZN-DNS • Kleve, Germany**
</div>
