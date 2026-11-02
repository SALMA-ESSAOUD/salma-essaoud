# Salma Essaoud

**Élève ingénieure en Cybersécurité (5ᵉ année) | SOC & Blue Team | Recherche de stage PFE**

FST Marrakech – Université Cadi Ayyad · Marrakech, Maroc

[![LinkedIn](https://img.shields.io/badge/LinkedIn-salma--essaoud-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/salma-essaoud)
[![Email](https://img.shields.io/badge/Email-s.essaoudsalmaa%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:s.essaoudsalmaa@gmail.com)

---

## À propos

Élève ingénieure en Sécurité IT, je me spécialise dans la défense des systèmes d'information et le travail d'analyste SOC.

Mon approche est **Purple Team** : simuler des attaques pour concevoir des règles de détection fiables, investiguer les alertes et orchestrer la réponse. Mes laboratoires et mon stage SOC m'ont permis de me former à la détection, à la corrélation et à la réponse aux incidents.

**Je recherche un stage PFE en SOC / Blue Team** afin de contribuer à la protection d'un environnement réel.

---

## Expérience

**Stagiaire SOC Analyst – Purple Team (Wazuh SIEM)** · Iventeq, Mohammadia · Août – Sept. 2026
- Conception d'un mini-SOC sur laboratoire isolé multi-VM : Wazuh, OPNsense, Suricata (Syslog → Wazuh).
- Règles et décodeurs personnalisés (brute force SSH/RDP, scan Nmap, injection SQL, path traversal sur OWASP Juice Shop), validés avant/après tuning.
- Simulation de vol d'identifiants VPN (impossible travel, hors-horaires) avec alertes email, mappée à MITRE T1078.
- Détection de malwares (FIM, VirusTotal, YARA) avec Active Response de type EDR/XDR.
- SOAR : enrichissement AbuseIPDB et blocage d'IP sur OPNsense via API REST ; couverture MITRE ATT&CK et KPIs SOC (MTTD, faux positifs) sur plus de 6300 événements.

**Stagiaire en Sécurité des Applications Web** · Norsys Afrique, Marrakech · Juillet 2025
- Application de gestion de rendez-vous : Spring Security, authentification JWT, gestion des rôles, DevSecOps avec GitLab CI/CD.

---

## Projets principaux

| Projet | Description | Technologies |
|---|---|---|
| **Mini-SOC Purple Team** | Laboratoire de détection et de réponse : règles personnalisées, Active Response, SOAR, couverture MITRE ATT&CK | Wazuh, OPNsense, Suricata, YARA, OpenVPN |
| **SOC Loop** *(en cours)* | Architecture de détection et de réponse à incident automatisée par IA : centralisation des logs, enrichissement CTI, gestion de cas, blocage avec validation humaine, agent IA de triage | FortiGate, Graylog, Coraza WAF, T-Pot, Cortex, MISP, OpenCTI, DFIR-IRIS, Python |
| **Active Directory Attack & Defense Lab** | Kill chain complète sur un domaine Windows, du premier accès au DCSync, avec rapport CVSS | Windows Server 2019, Kali, BloodHound, Impacket, Hashcat, CrackMapExec |
| **Architecture d'entreprise sécurisée** | Infrastructure multi-VM segmentée, VPN avec PKI interne, IDS/IPS inline et hardening Linux | pfSense, Suricata, OpenVPN, Ubuntu Server, Wireshark |
| **Post-Quantum Cryptography** | Étude et implémentation de Kyber (ML-KEM) | [Voir le dépôt](https://github.com/SALMA-ESSAOUD/Post-Quantum-Cryptography-Kyber-Study-Implementation) |
| **Analyse CVE-2024-38063** | Analyse CVE/CVSS d'une vulnérabilité d'exécution de code à distance IPv6 | [Voir le dépôt](https://github.com/SALMA-ESSAOUD/CVE-CVSS--CVE-2024-38063-IPv6-TCP-IP-Remote-Code-Execution-Analysis) |
| **Performance de DES, 3DES et AES** | Comparaison des algorithmes selon les modes ECB, CBC et CFB | [Voir le dépôt](https://github.com/SALMA-ESSAOUD/Performance-Analysis-of-DES-3DES-and-AES-Algorithms-Using-ECB-CBC-and-CFB-Modes) |

---

## Compétences techniques

| Domaine | Outils et technologies |
|---|---|
| **Sécurité défensive (SOC / Blue Team)** | Wazuh, Splunk, ELK Stack, Graylog, Sysmon, Suricata, YARA, VirusTotal, FIM, MITRE ATT&CK, Syslog |
| **CTI & réponse à incident** | Cortex, MISP, OpenCTI, DFIR-IRIS, T-Pot, AbuseIPDB |
| **Pare-feu, réseau & VPN** | pfSense, OPNsense, FortiGate, WAF (Coraza + OWASP CRS), OpenVPN, Wireshark |
| **Sécurité offensive** | Nmap, Hydra, BloodHound, CrackMapExec, Kerberoasting, AS-REP Roasting, Pass-the-Hash, DCSync, Ghidra, Frida, GoPhish, CVE/CVSS |
| **Hardening** | SSH (ED25519), PAM, GRUB, UFW, sysctl |
| **Cryptographie** | AES, RSA, Diffie-Hellman, SHA-256, ML-KEM (Kyber), ML-DSA (Dilithium) |
| **Programmation & web** | Python, C, Java, JavaScript, PHP, Laravel, Spring Boot, React, MySQL |
| **IA appliquée à la sécurité** | scikit-learn, pandas, Random Forest, classification de payloads, règles assistées par LLM |
| **Systèmes & outils** | Linux, Windows, Active Directory, Docker, Git, GitHub, GitLab |

---

## Certifications

- Fortinet NSE 3
- TryHackMe : Cybersecurity 101, SOC Level 1, AI Security
- Cisco Networking Academy : Introduction à la cybersécurité, Ethical Hacker

## Compétitions

- **MACC2026** (DGSSI & SecDojo) : compétition nationale de cybersécurité
- **ST4F1T CTF** (GCDSTE / ENSA Marrakech, 2025) : reverse engineering, web, cryptographie, pwn, forensics
- **Rally IA FutureLab, Merzouga** (juin 2026) : parmi plus de 1000 jeunes talents des 12 régions du Maroc, thème Security & Sovereignty

## Langues

Arabe (langue maternelle) · Français (courant) · Anglais (courant)

---

*Les projets de laboratoire présentés ici sont réalisés dans des environnements isolés, à des fins pédagogiques.*
