# Fedora Home Lab - BTS SIO SISR

Projet personnel réalisé dans le cadre de ma reconversion vers l'informatique et de ma préparation au BTS SIO option SISR.

## Objectifs

* Administration Linux
* Réseau
* DNS
* SSH
* Firewall
* Monitoring
* Virtualisation
* Documentation technique

Le but de ce projet est de construire une infrastructure réseau complète sous Fedora et de documenter chaque étape comme dans un environnement professionnel.

---

## Architecture

| VM  | Rôle       | IP            |
| --- | ---------- | ------------- |
| VM1 | DNS Server | 192.168.56.10 |
| VM2 | Client 1   | 192.168.56.12 |
| VM3 | Client 2   | 192.168.56.11 |
| VM4 | Monitoring | 192.168.56.13 |
| VM5 | Admin      | 192.168.56.14 |

Réseau Host-Only VirtualBox :

```text
192.168.56.0/24
```

---

## Fonctionnalités réalisées

### Réseau

* Réseau Host-Only VirtualBox configuré
* Adressage IP statique sur les 5 VM
* Tests de connectivité validés entre toutes les machines

État : ✅ Opérationnel

### DNS

* Installation de BIND 9 (bind9-next)
* Activation du service named
* Vérification du fonctionnement du service

État : ✅ Opérationnel

### SSH

* Administration à distance entre les machines

État : ✅ Opérationnel

### Monitoring

État : 🔄 En cours

### Firewall

État : ⏳ À faire

---

## Documentation

* docs/architecture.md
* docs/schema-reseau.md
* docs/tests-connectivite.md

---

## Compétences développées

* Linux Fedora Server
* VirtualBox
* Réseau TCP/IP
* DNS
* SSH
* Git
* GitHub
* Documentation technique
* Administration système
