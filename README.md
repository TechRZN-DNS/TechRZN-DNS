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
*Die physische Infrastruktur hinter TechRZN. Jede Blockliste wird auf dedizierter Enterprise-Hardware prozessiert, validiert und verteilt.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117;">
  <tr>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/server.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>High-Performance Compute Node</b></span><br>
      <b>UGREEN NAS DXP4800 Plus</b> | Massive <b>64 GB RAM Upgrade</b> für verzögerungsfreie Datenbank-Operationen und parallele Container-Prozesse.
    </td>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/ssd.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>Ultra-Fast I/O Storage Layer</b></span><br>
      2x 2TB <b>Samsung 990 Pro NVMe</b> (Raid 1 Cache). Garantiert extrem niedrige Lese-/Schreibzugriffe während der Filter-Kompilierung.
    </td>
  </tr>
  <tr>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/hdd.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>Redundant Data Array</b></span><br>
      <b>80 TB Raw / 60 TB Netto</b> (4x 20TB <b>WD Red Pro</b> | RAID 5). Hardened Storage für Langzeit-Logs und Backup-Infrastruktur.
    </td>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/ethernet-switch.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>Multi-Gigabit Internal Fabric</b></span><br>
      Managed <b>Zyxel Switch</b> mit durchgehendem <b>2.5 Gbit/s Backbone</b>. Keine Flaschenhälse zwischen Core-Node und Verteilungspunkten.
    </td>
  </tr>
  <tr>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/router.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>Hybrid-Power WAN Gateway</b></span><br>
      <b>AVM FRITZ!Box 7690</b> (2.5G WAN) | <b>250 Mbit/s Hybrid-Uplink</b>. Redundante Internetanbindung für unterbrechungsfreie tägliche Updates.
    </td>
    <td align="left" width="50%" style="padding: 20px; border: 1px solid #30363d;">
      <img src="https://img.icons8.com/fluency/48/docker.png" width="35" style="vertical-align: middle; margin-right: 10px;" />
      <span style="font-size: 17px;"><b>Virtualized Orchestration Layer</b></span><br>
      <b>Docker & Portainer</b>. Isolierte Umgebungen für DNS-Resolver, Python-Automatisierung und Sicherheits-Datenbanken.
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
