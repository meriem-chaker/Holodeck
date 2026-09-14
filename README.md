# 🚀 Holodeck

## Machines Virtuelles Web pour les Ingénieurs de Starfleet

Projet réalisé dans le cadre du Bachelor IT - Cybersécurité.

Holodeck est une infrastructure composée de machines virtuelles Debian permettant de mettre en place différents services réseau, web et systèmes.

## 🖥️ Architecture

### Holodeck-Server
Serveur Debian 12 sans interface graphique.

Services prévus :
- DHCP
- DNS
- Nginx
- PHP 7
- PHP 8
- MariaDB
- phpMyAdmin
- LDAP
- FTP

### Starfleet-Client
Machine cliente Debian avec interface graphique et navigateur web.

Elle permet de tester les différents services du serveur.

## 🌐 Services Web

| Domaine | Service |
|---|---|
| `www8.starfleet.lan` | Site PHP 8 |
| `www7.starfleet.lan` | Site PHP 7 |
| `php.starfleet.lan` | phpMyAdmin |
| `admin.starfleet.lan` | Administration |

## 🌐 Réseau

- Réseau LAN : `192.168.100.0/24`
- Serveur : `192.168.100.1`
- Domaine DNS : `starfleet.lan`

## 🛠️ Technologies

- Debian 12
- Nginx
- PHP
- MariaDB
- phpMyAdmin
- BIND9
- DHCP
- LDAP
- FTP
- VMware Workstation
- Git / GitHub

## 👥 Projet

Projet réalisé en équipe dans le cadre de la formation Bachelor IT Cybersécurité.

## 📌 État du projet

Le projet est en cours de développement et de configuration.

Les services sont progressivement installés, configurés et testés sur l'infrastructure virtuelle.
