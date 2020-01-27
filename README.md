# B3 Devops - TP 1 | Steven COPY
-------------------

## But du projet
Automatiser la création d'une VM avec Vagrant

## Objectifs
Initiation à Vagrant et Virtualbox
- Mise en oeuvre de VirtualBox
- Déploiement de VM via Vagrant
- Build de VM via Vagrant

## Infos 
mail: steven.copy@ynov.com  
github_username: theejkb
 
## Librairies
```library
nodejs@12
openssh-server
nginx
```
## Pré-requis
- [Vagrant](https://www.vagrantup.com/downloads.html)  
- [VirtualBox 6.0](https://www.virtualbox.org/wiki/Downloads)  
- [Git Bash](https://gitforwindows.org/)

# Détails
1. Installation d'une **VirtualBox 6.0.16** avec un iso Ubuntu
2. Installation des librairies (*nodejs, openssh-server, nginx*)
3. Configuration de ports forwards sur HTTP, HTTPS, SSH.
3. Accès à la VM avec gitbash et la commande :
```bash
ssh theejkb@127.0.0.1 -p 2201
```

## Vagrant
Commande pour créer une VM à partir des configurations dans *Vagrantfile*
```bash
vagrant up
```
