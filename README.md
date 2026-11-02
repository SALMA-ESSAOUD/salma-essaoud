<div align="center">

<img src="./banner.svg" alt="Salma Essaoud, SOC et Blue Team" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=640&lines=Pour+d%C3%A9tecter+une+attaque%2C+il+faut+savoir+la+mener.;J'%C3%A9cris+des+r%C3%A8gles+de+d%C3%A9tection+qui+attrapent+les+attaquants.;%C3%89l%C3%A8ve+ing%C3%A9nieure+en+Cybers%C3%A9curit%C3%A9+%7C+5%C3%A8me+ann%C3%A9e;%F0%9F%8E%AF+%C3%80+la+recherche+d'un+stage+PFE+en+SOC+%2F+Blue+Team)](https://github.com/SALMA-ESSAOUD)

![Wazuh](https://img.shields.io/badge/SIEM-Wazuh-005571?style=for-the-badge)
![Splunk](https://img.shields.io/badge/SIEM-Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![ELK](https://img.shields.io/badge/SIEM-ELK_Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Graylog](https://img.shields.io/badge/Logs-Graylog-FF3633?style=for-the-badge)
![FortiGate](https://img.shields.io/badge/Firewall-FortiGate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)
![Suricata](https://img.shields.io/badge/IDS%2FIPS-Suricata-EF3B2D?style=for-the-badge)
![MITRE](https://img.shields.io/badge/MITRE-ATT%26CK-C0392B?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salma_Essaoud-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/salma-essaoud)
[![Email](https://img.shields.io/badge/Email-Me_contacter-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:s.essaoudsalmaa@gmail.com)

</div>

---

## 🟣 Mon approche : la Purple Team

```
   🔴 Red Team          🔵 Blue Team
   je simule        →   je détecte
   l'attaque            je corrèle, j'investigue
        \                  /
         \                /
          🟣  Purple Team
     une règle de détection n'est fiable
     que si je l'ai testée contre l'attaque
```

Mon fil rouge : **attaquer en labo, détecter en production**. Chaque projet ci-dessous suit la même boucle : simuler l'attaque, écrire la règle, valider, affiner (tuning), mesurer.

---

## 💻 `whoami`

```bash
$ whoami
salma-essaoud

$ cat profile.txt
role      : Élève ingénieure en Cybersécurité (5ème année)
school    : FST Marrakech, Université Cadi Ayyad
focus     : SOC · Détection · Corrélation · Réponse à incident
mindset   : Purple Team
languages : Arabe · Français · Anglais
status    : 🟢 Disponible pour un stage PFE (SOC / Blue Team)
```

---

## 🚨 Dernière alerte détectée

```json
{
  "rule": {
    "level": 12,
    "description": "Profil SOC / Blue Team détecté : candidate PFE",
    "mitre": { "id": "T1078", "technique": "Valid Accounts" }
  },
  "agent": { "name": "salma-essaoud", "location": "Marrakech, MA" },
  "full_log": "Action recommandée : contacter pour un stage PFE"
}
```

---

## 🛡️ Projets phares

### 🔍 Mini-SOC Purple Team *(stage chez Iventeq)*
> Wazuh · OPNsense · Suricata · OpenVPN · YARA

Un SOC complet sur laboratoire isolé multi-VM. Règles et décodeurs personnalisés (brute force SSH/RDP, scan Nmap, injection SQL, path traversal), simulation de vol d'identifiants VPN, Active Response de type EDR/XDR, et blocage automatique d'IP via l'API REST d'OPNsense. Résultat : couverture MITRE ATT&CK et KPIs (MTTD, faux positifs) mesurés sur **+6300 événements**.

### 🤖 SOC Loop *(en cours)*
> FortiGate · Graylog · Coraza WAF · T-Pot · Cortex · MISP · OpenCTI · DFIR-IRIS · Python

Une architecture de détection et de réponse automatisée par IA : logs centralisés, enrichissement CTI, gestion de cas, blocage avec **validation humaine**, virtual patching WAF, et un agent IA qui trie les alertes et les mappe sur MITRE ATT&CK et OWASP Top 10.

### 🏰 Active Directory : Attack & Defense Lab
> Windows Server 2019 · Kali · BloodHound · Impacket · Hashcat

Kill chain complète : AS-REP Roasting, Kerberoasting, Pass-the-Hash, DCSync. Chaque étape est documentée et accompagnée d'un rapport CVSS.

### 🧱 Architecture d'entreprise sécurisée
> pfSense · Suricata inline · OpenVPN · Ubuntu · Wireshark

Réseau segmenté WAN/LAN, VPN avec PKI interne, IDS/IPS inline, hardening Linux (SSH ED25519, PAM, GRUB, UFW, sysctl), attaques simulées et validées via Wireshark.

### 🔬 Recherche et cryptographie

| Projet | En bref |
|---|---|
| [Post-Quantum Cryptography : Kyber](https://github.com/SALMA-ESSAOUD/Post-Quantum-Cryptography-Kyber-Study-Implementation) | Étude et implémentation de ML-KEM |
| [CVE-2024-38063](https://github.com/SALMA-ESSAOUD/CVE-CVSS--CVE-2024-38063-IPv6-TCP-IP-Remote-Code-Execution-Analysis) | Analyse d'une RCE IPv6 et scoring CVSS |
| [DES, 3DES, AES](https://github.com/SALMA-ESSAOUD/Performance-Analysis-of-DES-3DES-and-AES-Algorithms-Using-ECB-CBC-and-CFB-Modes) | Comparaison de performance ECB, CBC, CFB |

---

## 🧰 Boîte à outils

<details open>
<summary><b>🔵 Défense : SOC / Blue Team</b></summary>
<br>

**SIEM et logs :** `Wazuh` `Splunk` `ELK Stack` `Graylog` `Sysmon` `Syslog`

**Détection :** `Suricata (IDS/IPS)` `YARA` `FIM` `VirusTotal` `MITRE ATT&CK` `Honeypot T-Pot`

**Pare-feu et WAF :** `FortiGate` `pfSense` `OPNsense` `Coraza WAF` `OWASP CRS`

**CTI et réponse à incident :** `Cortex` `MISP` `OpenCTI` `DFIR-IRIS` `AbuseIPDB`

**Réseau et VPN :** `OpenVPN` `PKI` `Wireshark`

**🌱 En apprentissage :** `Microsoft Sentinel` `IBM QRadar` `Sigma` `Zeek`
</details>

<details>
<summary><b>🔴 Attaque : Red Team</b></summary>
<br>

`Nmap` `Hydra` `BloodHound` `CrackMapExec` `Impacket` `Hashcat` `Kerberoasting` `AS-REP Roasting` `Pass-the-Hash` `DCSync` `Ghidra` `Frida` `GoPhish` `CVE / CVSS`
</details>

<details>
<summary><b>💻 Dev, IA et systèmes</b></summary>
<br>

`Python` `C` `Java` `JavaScript` `PHP` `Laravel` `Spring Boot` `React` `MySQL`
`scikit-learn` `pandas` `Random Forest` `LLM`
`Linux` `Windows` `Active Directory` `Docker` `Git` `GitLab CI/CD`
</details>

<details>
<summary><b>🔐 Cryptographie</b></summary>
<br>

`AES` `RSA` `Diffie-Hellman` `SHA-256` `ML-KEM (Kyber)` `ML-DSA (Dilithium)`
</details>

---

## 🏆 Compétitions et certifications

- 🥷 **MACC2026** (DGSSI & SecDojo) : compétition nationale de cybersécurité
- 🚩 **ST4F1T CTF 2025** (GCDSTE / ENSA Marrakech) : reverse, web, crypto, pwn, forensics
- 🏜️ **Rally IA FutureLab, Merzouga** : parmi +1000 jeunes talents des 12 régions du Maroc, thème Security & Sovereignty
- 🎓 **Fortinet NSE 3** · **TryHackMe** (Cybersecurity 101, SOC Level 1, AI Security) · **Cisco** (Introduction à la cybersécurité, Ethical Hacker)

---

<div align="center">

### 🤝 Parlons SOC, détection et stage PFE

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Me_contacter-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/salma-essaoud)
[![Email](https://img.shields.io/badge/Email-Écrire_un_message-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:s.essaoudsalmaa@gmail.com)

<sub>Tous les labs sont réalisés dans des environnements isolés, à des fins pédagogiques.</sub>


</div>
