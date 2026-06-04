# Architecture du Home Lab

## Réseau

Réseau Host-Only VirtualBox :

192.168.56.0/24

Machine hôte :

192.168.56.1

---

## Machines virtuelles

### VM1 - DNS Server

Nom : dns-server

IP : 192.168.56.10

Rôle :

* Serveur DNS
* Résolution des noms internes du lab

---

### VM2 - Client 1

Nom : client1

IP : 192.168.56.12

Rôle :

* Tests DNS
* Tests SSH
* Validation des services réseau

---

### VM3 - Client 2

Nom : client2

IP : 192.168.56.11

Rôle :

* Simulation d'un second poste utilisateur
* Tests de connectivité réseau

---

### VM4 - Monitoring

Nom : monitoring

IP : 192.168.56.13

Rôle :

* Supervision de l'infrastructure
* Monitoring des serveurs avec Zabbix

---

### VM5 - Admin

Nom : admin

IP : 192.168.56.14

Rôle :

* Administration distante
* Gestion des serveurs via SSH
* Maintenance de l'infrastructure
