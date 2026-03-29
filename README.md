<div align="center">

<br>

<p align="center">
  <img src="techrzn.png" width="650" alt="TechRZN DNS Filter-Hub" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-INFRASTRUKTUR_AKTIV-00C853?style=for-the-badge&logo=statuspage&logoColor=white" />
  <img src="https://img.shields.io/badge/DATENBANK-2.2M%2B_REGELN-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/UPLINK-2.5_GBIT_BACKBONE-7957d5?style=for-the-badge&logo=wi-fi&logoColor=white" />
</p>

---

## 🛰️ Mission & Vision
> **High-Performance Blocklisten • Täglich aktualisiert • 100% Bereinigt**

Willkommen im **TechRZN Filter-Hub**. Wir bieten eine hochoptimierte "All-in-One" Lösung für **AdGuard Home, Pi-hole und Technitium**. Durch automatisierte Deduplizierung und eine intelligente Whitelist garantieren wir Schutz ohne "Overblocking".

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

## 🚀 Direkt-Einbindung
*Nutze die Master-Liste (aufgeteilt in 2 Teile) für kompletten Schutz oder die Whitelist.*

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_part1.txt">
    <img src="https://img.shields.io/badge/MASTER_TEIL_1-LINK-7957d5?style=for-the-badge&logo=adguard&logoColor=white" height="45" />
  </a>
  &nbsp;&nbsp;
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/combined_part2.txt">
    <img src="https://img.shields.io/badge/MASTER_TEIL_2-LINK-7957d5?style=for-the-badge&logo=adguard&logoColor=white" height="45" />
  </a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/whitelist.txt">
    <img src="https://img.shields.io/badge/WHITELIST-LINK_KOPIEREN-blue?style=for-the-badge&logo=github&logoColor=white" height="35" />
  </a>
</p>

---

## 🛠️ Setup-Anleitungen
<details>
<summary><b>👉 Klicke hier für die AdGuard Home Einrichtung</b></summary>
<br>
<blockquote>
1. Gehe zu <b>Filter</b> ➔ <b>DNS-Sperrlisten</b>.<br>
2. Klicke auf <b>Sperrliste hinzufügen</b> ➔ <b>Benutzerdefinierte Liste</b>.<br>
3. Füge <b>Teil 1</b> und <b>Teil 2</b> als separate Listen hinzu.<br>
4. <b>Pro-Tipp:</b> Aktiviere <i>Optimistisches Caching</i> für maximale Geschwindigkeit.
</blockquote>
</details>

<details>
<summary><b>👉 Klicke hier für die Pi-hole Einrichtung</b></summary>
<br>
<blockquote>
1. Gehe zu <b>Adlists</b> im linken Menü.<br>
2. Füge beide URLs nacheinander in das Feld <b>Address</b> ein.<br>
3. Klicke auf <b>Add</b>.<br>
4. <b>Wichtig:</b> Führe unter <i>Tools</i> ➔ <i>Update Gravity</i> ein Update aus.
</blockquote>
</details>

---

## 🛠️ TechRZN Spezial-Module (Inland-Kuration)
*Diese Listen werden direkt in Kleve gepflegt und auf maximale Präzision optimiert.*

| Status | Modul | Fokus | Link |
| :---: | :--- | :--- | :---: |
| 🛡️ | **Ads & Tracking** | Werbenetzwerke & Analyse-Dienste | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_ads.txt) |
| 🦠 | **Malware Defense** | Schadsoftware & C2-Server | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_malware.txt) |
| 🎣 | **Phishing Guard** | Fake-Logins & Scam-Seiten | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_phishing.txt) |
| 🛑 | **Threat Intel** | Aktive Botnetze & Angriffswellen | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_threat_intel.txt) |
| 🛍️ | **Fakeshops** | Betrugsshops & Abofallen | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_fakeshops.txt) |
| 🔞 | **Porn & Adult** | Explizite Inhalte (Vollfilter) | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/techrzn_porn.txt) |
| 🏠 | **Typosquatting** | Schutz vor Tippfehler-Domains | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_domain_squatting.txt) |
| 🎰 | **Gambling** | Casinos & Wettanbieter | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_gambling.txt) |
| 🧒 | **Jugendschutz** | Family-Filter für Kinder | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/techrzn_jugendschutz.txt) |
| 🪙 | **Crypto-Shield** | Mining & Krypto-Betrug | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_crypto.txt) |
| ❤️ | **Dating Filter** | Partnerbörsen & Portale | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_dating.txt) |
| 🧪 | **Fake Science** | Desinformation & Pseudo-Wissenschaft | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_fake_science.txt) |
| 📧 | **Spam Control** | Marketing-Schleudern | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_spam.txt) |
| 🔓 | **Bypass Block** | VPN- & Proxy-Umgehungen | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/blocklists/techrzn_bypass.txt) |

---

## 🧩 Die 14 Core-Module (Externe Basis)
*Diese Module bilden das bewährte Fundament der Sammlung.*

| Einsatz | Modul | Fokus | Link |
| :---: | :--- | :--- | :---: |
| ✅ | **HaGeZi Pro** | Gold Standard (Weltweit) | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_pro.txt) |
| ✅ | **Threat Intel** | Botnetze & Cyberangriffe | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_threat.txt) |
| ✅ | **German Filter** | Optimierung (DE/AT/CH) | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/adguard_german.txt) |
| ✅ | **URLHaus** | Malware-Echtzeit-Schutz | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/urlhaus_malicious.txt) |
| ✅ | **Banking** | Phishing-Schild (Banken) | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/phishing_de.txt) |
| ✅ | **Fakeshop** | Schutz vor Betrugsshops | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/notserious.txt) |
| ✅ | **Windows Spy** | Telemetrie & Office-Tracker | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_windows.txt) |
| ✅ | **Smart TV** | Unterbindet TV-Tracking | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/smart_tv.txt) |
| ✅ | **Bypass** | Tunnel- & Proxy-Filter | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_bypass.txt) |
| ✅ | **Gambling** | Glücksspiel & Wetten | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_gambling.txt) |
| ✅ | **Fake DNS** | Betrug & Phishing-DNS | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/hagezi_fake.txt) |
| ✅ | **Dan Pollock** | Hosts-File Klassiker | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/dan_pollock.txt) |
| ✅ | **TechRZN IPs** | Eigene bösartige IPs | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/techrzn_ips.txt) |
| ✅ | **Fake Science** | Pseudo-Wissenschaft | [🔗](https://raw.githubusercontent.com/TechRZN-DNS/TechRZN-Blocklist-Collection/main/lists/fake_science.txt) |

---

## 🏗️ Hardware Backbone (Kleve, NRW)
*Validierung auf Enterprise-Hardware für absolute Zuverlässigkeit.*

<table align="center" width="100%" style="border-collapse: collapse; background-color: #0d1117; border-radius: 12px; overflow: hidden; border: 1px solid #30363d;">
  <tr>
    <td align="left" style="padding: 20px;">
      <b>CORE NODE</b><br>UGREEN NAS DXP4800 Plus<br>
      <img src="https://img.shields.io/badge/64_GB_DDR5_ECC-7957d5?style=flat-square" alt="RAM" />
    </td>
    <td align="left" style="padding: 20px;">
      <b>SSD SPEICHER</b><br>Samsung 990 Pro RAID<br>
      <img src="https://img.shields.io/badge/NVMe_Gen4-FF6B6B?style=flat-square" alt="NVMe" />
    </td>
  </tr>
  <tr>
    <td align="left" style="padding: 20px;">
      <b>NETZWERK</b><br>2.5 Gbit Hybrid-Power<br>
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
