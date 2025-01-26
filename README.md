# Projet Réseaux et Télécommunications - Gestion des Services sur VM  

## 📋 Description du projet  
Ce projet a pour objectif de configurer et administrer des services réseau sur une machine virtuelle (VM) dans le cadre de la formation en BUT Réseaux et Télécommunications.  

### Objectifs principaux  
- Comprendre et mettre en œuvre des services réseau courants (DNS, DHCP, HTTP, etc.).  
- Déployer et configurer une machine virtuelle pour simuler un environnement réseau.  
- Tester et documenter les configurations réalisées.  

Cependant, la **partie configuration des services sur la VM** n’a pas encore été réalisée et reste à finaliser. Ce README détaille l’avancement actuel, les étapes prévues et les tâches restantes.  

---

## 🛠️ Étapes réalisées  
1. **Création et configuration de la VM** :  
   - Installation de la VM avec **VirtualBox** (ou VMware).  
   - Installation d’un système d’exploitation (**Linux Ubuntu Server**).  
   - Configuration réseau de base :  
     - Attribution d’une IP fixe.  
     - Connexion à Internet via NAT ou pont réseau.  

2. **Préparation de l’environnement** :  
   - Installation des outils nécessaires :  
     - Serveur SSH (OpenSSH) pour l’accès distant.  
     - Mise à jour des paquets système.  

3. **Documentation** :  
   - Étapes d’installation et de configuration de la VM documentées pour une reproduction facile.  

---

## 🕗 Étapes à réaliser  
### Partie "Service" à configurer :  
1. **Serveur DHCP** :  
   - Installer et configurer un service DHCP pour attribuer des adresses IP dynamiques dans un réseau local simulé.  

2. **Serveur DNS** :  
   - Déployer un service DNS local pour résoudre les noms de domaine.  
   - Ajouter des zones DNS personnalisées pour tester la résolution.  

3. **Serveur HTTP/HTTPS** :  
   - Installer un serveur web (**Apache ou Nginx**).  
   - Héberger une page web simple pour tester la disponibilité du service.  

4. **Serveur de fichiers** :  
   - Configurer un partage de fichiers via **Samba** ou **NFS**.  

5. **Sécurisation des services** :  
   - Mettre en place des règles de pare-feu pour autoriser uniquement les ports nécessaires (exemple : ufw ou iptables).  
   - Installer un certificat SSL pour sécuriser le serveur web.  

---

## 📌 Contraintes et objectifs pédagogiques  
- **Documentation continue** : toutes les configurations devront être expliquées en détail (commandes utilisées, fichiers modifiés).  
- **Réutilisabilité** : les configurations doivent être reproductibles facilement par d’autres étudiants ou enseignants.  
- **Sécurité** : les services doivent être configurés avec les meilleures pratiques en matière de sécurité.  

---

## 💻 Technologies utilisées  

- **OS** : Ubuntu Server 20.04  
- **Outils** : VirtualBox, SSH, ufw  
- **Services cibles** : DHCP, DNS, Apache/Nginx, Samba  

---

## 🤝 Contributions  

Les contributions sont les bienvenues !  
Si vous avez des suggestions ou des améliorations, n’hésitez pas à ouvrir une issue ou à soumettre une pull request.  

---

## 📧 Contact  

Pour toute question ou assistance, veuillez contacter :  
- **Nom** : SCHER Florian
- **Email** : florian.scher.pro@gmail.com  
- **LinkedIn** : 
