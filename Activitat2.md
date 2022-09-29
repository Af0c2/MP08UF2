# INSTAL·LACIÓ OWNCLOUD

## Guia instal·lació Owncloud

### Què és Owncloud?

OwnCloud és una aplicació de programari lliure del tipus Servei d'allotjament d'arxius, que permet l'emmagatzematge en línia i aplicacions en línia.

### Requeriments:

Els requeriments que necessitem per instal·lar l'OwnCloud són:

- Linux: Ubuntu 22.04 LTS
- Servidor Web: Apache
- Base de Dades: MariaDB
- PHP versió: 7.3 o 7.4

### Instal·lació:

#### Instal·lació Apache:

1. El primer pas que farem per poder realitzar l'instal·lació de l'OwnCloud serà obrir el terminal, i un cop obert el terminal començarem instal·lant el servidor *apache*. 

"sudo apt install apache2"

![1cap](1.png)

2. El següent que farem serà desactivar el llistat de directoris del servidor. 

"sudo sed -i "s/Options Indexes FollowSymLinks/Options FollowSymLinks/" /etc/apache2/apache2.conf"


