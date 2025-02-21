# VOIP DE MACHITA
Mise en place d'un serveur téléphonique IP sur machine virtuelle Debian et installation de client VoIP sur smartphones afin de réaliser des appels via un serveur.

Asterisk est un logiciel open source permettant de mettre en œuvre un autocommutateur privé (PBX).
Il permet aux téléphones connectés de passer des appels entre eux et de se connecter à d'autres services téléphoniques, tels que le réseau téléphonique public commuté (RTPC) et les services de voix sur IP (VoIP). Son nom fait référence au symbole de l'astérisque, « * ».

**Etape première:**
Installation des paquets nécessaires, exécutez la commande suivante : `sudo apt install build-essential wget libncurses5-dev libssl-dev libxml2-dev libsqlite3-dev uuid-dev perl libwww-perl sox mpg123 `

Installer et configurer un serveur Asterisk : Pour installer les paquets nécessaires, exécutez la commande suivante: 


- Configurer PJSIP pour la gestion des appels VoIP.
- Mettre en place des extensions et des règles d'appel.
- Configurer la messagerie vocale.
- Intégrer GoogleTTS pour la synthèse vocale.
- Automatiser l'ajout d'utilisateurs à partir d'un fichier CSV.
- Sécuriser le serveur VoIP avec des certificats TLS.

## Installation

Pour installer le serveur VoIP, suivez les instructions dans [INSTALL.md](INSTALL.md).

## Configuration

Pour configurer Asterisk, PJSIP, les extensions, et la messagerie vocale, consultez [CONFIGURATION.md](CONFIGURATION.md).

## Documentation

La documentation complète du projet est disponible dans le dossier [DOCS/](DOCS/).

## Scripts

Des scripts d'automatisation sont disponibles dans le dossier [SCRIPTS/](SCRIPTS/).
