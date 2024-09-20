# VPN Personnel
![a-tunnel-with-a-green-light-at-the-end-the-tunnel--NOVEuCMTR9-N_MCXWxmelw-tJLDF3sfQjWgqTbEfk24Vg](https://github.com/user-attachments/assets/7bef042a-d58e-40e6-9431-841343552fe0)

## Desciption

## Outils

- **Système d'exploitation :** Debian (version 11)
- **Logiciel VPN :** OpenVPN
- **Client VPN :** OpenVPN Connect (Android, iOS, Windows, macOS, Linux)
- **Générateur de certificats :** EasyRSA

## Fonctionnalités
- Chiffrement du trafic internet pour protéger la confidentialité des données
- Masquage de l'adresse IP de l'utilisateur pour préserver l'anonymat
- Accès sécurisé aux réseaux locauxaux, fichiers et services en ligne 

### Diagramme de Réseau

![image](https://github.com/user-attachments/assets/3cd7b463-f390-4416-a867-cb42941b979c)

## Installation / Configuration

1. **Installation du serveur OpenVPN**
   - Installez OpenVPN sur le serveur Debian en utilisant la commande `apt-get install openvpn`.
2. **Génération des certificats**
   - Utilisez EasyRSA pour générer les certificats nécessaires pour le serveur et les clients VPN.
3. **Configuration du serveur OpenVPN**
   - Modifiez le fichier de configuration du serveur OpenVPN pour définir les paramètres de sécurité, d'authentification et de routage.
4. **Configuration des clients VPN**
   - Créez des configurations de client OpenVPN pour les différents appareils à connecter au VPN.
5. **Connexion au VPN**
   - Utilisez le client OpenVPN Connect pour vous connecter au VPN.

### Diagramme Conceptuel
![image](https://github.com/user-attachments/assets/b5d55b4a-e07f-432f-bf06-9ac2ca13015c)


## Résultats / Conclusion

- Le VPN est opérationnel et permet de chiffrer le trafic internet de manière sécurisée.
- Les utilisateurs peuvent se connecter au VPN depuis différents appareils et accéder aux réseaux locaux et aux services en ligne.
- Les configurations de serveur et de client sont documentées et faciles à reproduire.
