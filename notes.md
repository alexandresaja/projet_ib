# Infra

## Réseau

### Vocabulaire

* **Serveur**: Machines dans le réseau répondant aux besoins et aux requêtes de machines clients
* **Topologie réseau**: Architecture ou mode de mise en place du réseau d'entreprise.
* **Client**: Machines dans le réseau emettant des requêtes vers des serveurs.
* **Réseau**: Ensemble constitué de matériel interconnecté et s'échangeant des données
* **Commutateur**(Switch): Equipement réseau créant des connexions entre les différents éléments d'un système informatique.
* **MAC**(Medias Access Control): L'adresse Physique d'une carte réseau.
* **Adresse IP**: L'identifiant unique d'un matériel sur le réseau.
* **Concentrateur**(Hub): Equipement réseau qui diffuse le message sur tous ses ports (En broadcast/sur tout le réseau).
* **Différence entre concentrateur/commutateur(switch vs hub)**: Le commutateur utilise le protocol ARP pour acheminer le message vers la bonne adresse. Le concentrateur il diffuse sur tous les matériels du réseau.
* **Routeur**: Matériel qui va permettre la connexion entre plusieurs réseau. (Cisco, HP, Stormshield, ...)
* **VPN**: (Virtual Private Network): Un tunnel contenant un réseau virtuel, permettant l'echange de donnée chiffrée.
* **Proxy**: Element du réseau informatique qui reçoit des données et les filtres enfonction de la politique mise en place par l'administrateur.
  * Equilibreur de charge
  * API Gateway
  * Proxy-cache
* **Pare-feu**: (Firewall) Matériel ou logiciel permettant le filtrage et la mise en place de politique de sécurité d'un réseau local.
* **LAN** (Local Area Network): Réseau local d'entreprise. Généralement se limite à un étage ou un batiment.
* **MAN** (Metropolitan Area Network): Réseau de ville.
* **WAN** (Wide Area Network): Réseau internet. 
* **VLAN** (Virtual Local Area Network): Réseau privé virtuel permettant de compartimenter notre réseau local en plusieur sous-réseaux.
* **WLAN** (Wireless Local Area Network): Réseau local sans fil.
* **Protocol**: Ensemble de règles qui régissent l'echange de la donnée dans les réseaux.
  * Organismes de normalisation:
    * **IETF**: (Internet Engineering Task Force)
    * **IANA**: (Internet Assign Numbers Authority)
    * **ISO**: Organisation international de normalisation
* **Port**: Point d'entrée/sortie utilisé par un protocol permettant de faire passer le flux de donnée sur un firewall.
* **HTTP**: (Hyper Text Transfer Protocol) protocol utilisé par internet pour afficher les pages web. Port 80
* **HTTPS**: Version chiffrée des pages web. Port 443
* **SSH** (Secure Shell): Permettant la connexion à distance entre deux machines. Port 22
* **Telnet**: Port 23 Version non sécurisée du SSH.
* **FTP** (File Transfert Protocol): Port 21/20 Protocol utilisé pour le transfert de fichiers. Port 20 ===> Data transfert; Port 21 ===> Port d'ecoute.
* **SFTP** (Secure File Transfert Protocol): Echange de données sur le SSH. Port 22 (TCP).
* **IP** (Internet Protocol): Protocole permettant de donner une adresse à un matériel du réseau.
* **DNS** (Domain Name System): Effectue la correspondance entre une adresse IP et un nom de domaine. (On a besoin ici de consulter un annuaire mis en place par un server DNS). Port 53 (UDP).
* **DHCP** (Dynamic Host Configuration Protocol): Attribution dynamique de configuration réseau. (Besoin d'un serveur DHCP.). Port 67 (Serveur) / Port 68 (Client)

#### SSH

* Pré requis:
  * Avoir le service ssh installé sur les machines: **OpenSSH**
  * Port 22 ouvert.
  * Connaitre un utilisateur de la machine distante
  * Avoir le mot de passe de cette utilisateur
  * Avoir l'ip de la machine distante.

```bash
    ssh-keygen
    ssh [utilisateur_distant]@[IP_de_la_machine_distante]
```

### Les topologies réseau:

* Topologie en Bus:
* Topologie en étoile:
* Topologie Maillée:
* Topologie en Anneau:
* Topologie en hiérarchique:


