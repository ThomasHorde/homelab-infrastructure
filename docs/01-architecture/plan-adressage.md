# Plan d'adressage IP



## Réseau du homelab


| Élément | Adresse IP | Rôle |
| --- | ---: | --- |
| PC hôte VirtualBox | 192.168.56.1 | Poste d'administration |
| LAB-DC01 | 192.168.56.10 | Contrôleur de domaine, DNS |
| LAB-SRV-LNX01 | 192.168.56.20 | Serveur Linux |
| LAB-CLI01 | 192.168.56.100 | Poste client du domaine |



- Réseau : '192.168.56.0/24'
- Masque : '255.255.255.0'
- Domain Active Directory : 'lab.local'
- Serveur DNS principal : '192.168.56.10'

