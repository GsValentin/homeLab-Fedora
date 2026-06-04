# Tests de connectivité réseau

## Objectif

Vérifier que toutes les machines virtuelles du lab communiquent entre elles sur le réseau Host-Only.

---

## Machine utilisée pour les tests

VM5 - Admin

IP : 192.168.56.14

---

## Tests réalisés

Depuis la VM Admin, les commandes suivantes ont été exécutées :

```bash
ping 192.168.56.10
ping 192.168.56.11
ping 192.168.56.12
ping 192.168.56.13
