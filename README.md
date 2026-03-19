#  Lab Cybersécurité — Tests d'intrusion

**Projet personnel | BTS SIO SISR | Mars 2026**

## - Objectif
Mettre en place un environnement virtuel complet d'attaque et de défense pour pratiquer les techniques de pentest professionnelles.

## - Environnement
- **Machine attaquante :** Kali Linux (192.168.1.95)
- **Machine cible :** Metasploitable 2 (192.168.1.32)
- **Réseau :** Isolé via VirtualBox

## - Ce que j'ai réalisé
- Scan réseau avec **Nmap** — 23 ports ouverts identifiés
- Recherche de CVE avec **Searchsploit**
- Exploitation **vsftpd 2.3.4** (CVE-2011-2523) → accès root obtenu
- Exploitation **Samba** (CVE-2007-2447) → second accès root obtenu
- Scan web avec **Nikto** — 27 vulnérabilités identifiées
- **Injection SQL** sur DVWA — données exposées
- **Brute Force** avec Hydra sur formulaire de connexion

## - Outils utilisés
`Kali Linux` `VirtualBox` `Nmap` `Searchsploit` `Metasploit Framework` `Nikto` `Hydra`

## - Rapport
Le rapport de pentest complet est disponible dans le dossier `/rapport`

## - Avertissement
Toutes les attaques ont été réalisées dans un environnement isolé à but éducatif. Aucun système réel n'a été compromis.
