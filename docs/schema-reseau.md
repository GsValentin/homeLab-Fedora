# Schéma réseau

```text
                    PC Hôte
                 192.168.56.1
                        |
------------------------------------------------

VM1 - DNS Server
192.168.56.10

VM3 - Client 2
192.168.56.11

VM2 - Client 1
192.168.56.12

VM4 - Monitoring
192.168.56.13

VM5 - Admin
192.168.56.14
```

## Description

Toutes les machines virtuelles sont connectées au réseau Host-Only VirtualBox :

192.168.56.0/24

Chaque machine possède une adresse IP statique afin de faciliter l'administration et les tests réseau.
