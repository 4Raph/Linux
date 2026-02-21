# Partie 1
![image1](image/tp4/image2.png)

- IP de la Vm pour ssh : 127.0.0.1

![image1](image/tp4/image1.png)

- Le serveur ssh est bien activé

## Connexion ssh 
![image1](image/tp4/image3.png)

- Connexion en ssh grâce au mot de passe
# Partie 2
## Génération de clé ssh

![image1](image/tp4/image4.png)
- Génération de la clé ssh 

![image1](image/tp4/image5.png)

- Copie de la clé public dans la vm 
- La connexion ssh fonctionne maitenant grâce à la clé

# Partie 3

- Nouvelle adresse ip : 10.97.161.97

![image6](image/tp4/image6.png)
![image7](image/tp4/image7.png)

- Modification des autorisations du ssh

![image8](image/tp4/image8.png)

- connexion avec le nouveau port

![image10](image/tp4/image10.png)
![image9](image/tp4/image9.png)

- Connexion avec l'alias serveur-tp

# Partie 4 - Transferts de fichiers

![image11](image/tp4/image11.png)
![image12](image/tp4/image12.png)

- Transfert du fichier fichier.txt du client au serveur

![alt text](image/tp4/image13.png)

- transfert de fichier grâce au sftp

# Partie 5 – Analyse des logs et sécurité

![alt text](image/tp4/image14.png)

- Récupération des dernières tenteatives de connexion du serveur ssh

![alt text](image/tp4/image15.png)

- Mise en place du service fail2ban .

![alt text](image/tp4/image17.png)

- On voit qu'aucune connexion n'a echoué

# Partie 6 – Tunnel SSH

![alt text](image/tp4/image18.png)

- Création du tunnel local 

![alt text](image/tp4/image19.png)

- Création du tunnel distant

# Partie 7 – Nginx et HTTPS

![alt text](image/tp4/image20.png)

- Serveur nginx lancé

![alt text](image/tp4/image21.png)

- Création de la page index.html du site du serveur Nginx

![alt text](image/tp4/image22.png)

- Mise en place du site dans le serveur

![alt text](image/tp4/image23.png)

- le serveur fonctionne bien 


![alt text](image/tp4/image24.png)

- Création du certificat auto-signé

![alt text](image/tp4/image25.png)

- COnfiguration pour le https

![alt text](image/tp4/image26.png)
![alt text](image/tp4/image27.png)

- le site est bien affiché avec le serveur https et nginx

# Partie 8 – Firewall et permissions

![alt text](image/tp4/image28.png)
![alt text](image/tp4/image29.png)

- Le firewall est bien actif sur notre serveur nginx