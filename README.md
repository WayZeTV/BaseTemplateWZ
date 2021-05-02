# Base Template par WayZe#0001

Bonjour à tous je vous présente aujourd'hui cette Base Template qui tourne en Double Job sur la première version de l'es_extended réalisé dans le but de vous faciliter la création de vos Serveurs FiveM. Cette base comporte toutes les ressources essentiels au bon fonctionnement de votre serveur. 

Je vous prie de ne pas vous attribuer cette base et de la vendre, toute personne qui s'appropriera ma base assumera les conséquences 🙂

# Preview

Vidéo de présentation de la base :
 - 🎥 [Base Preview](https://youtu.be/I_hxzDWOHlg)  

Vidéo Tutoriel d'Installation de la base en Local Host :
 - 🎥 [Installation de la base en Local Host](https://youtu.be/AyelMd8qzTI)

Vidéo Tutoriel d'Installation de la base sur Hébergeur :
 - 🎥 [Installation de la base sur un Hébergeur](https://youtu.be/ThM0fOr7oi4)
 
# Installation FR 

Pour utiliser cette ressource vous devez télécharger l'artifact de FiveM
- [Artifact Windows](https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/) 
- [Artifact Linux](https://runtime.fivem.net/artifacts/fivem/build_proot_linux/master/) 
-----------------------------------------------------
Une fois l'artifact installé, vous devez configurer le start.bat en changement le chemin d'accès aux lignes suivantes :
Lignes 23 / 29 / 30 / 45

Si vous n'y parvenez pas vous pouvez utiliser le start.bat classique qui est plus simple :

- `cd /d D:\NomDossierServeur`
- `D:\NomDossierServeur\FXServer.exe +exec server.cfg`
-----------------------------------------------------
Vous pouvez retrouver dans le dossier "SQL" un fichier se nommant basetemplate.sql
Pour l'installer il suffit de l'importer dans votre base de donnée (EX : XAMPP)

Il faut également que vous changiez la ligne de liaison SQL dans le `server.cfg`.
Pour cela il sufit de changer le nom de la BDD dans la ligne `6`.

Une fois cela effectué vous pouvez démarrer le `start.bat` et profiter de la base !

- Si vous avez besoin d'aide pour l'installation : https://discord.gg/eX9GXWN 🌐

# Documentation FR 

- [Documentation FR](https://github.com/WayZeTV/BaseTemplateWZ/blob/main/documentation.md) 

# Author 
Discord : WayZe#0001 | Youtube : WayZe | Twitter : @WayZeTV

### License
Base Template - Base Template réalisé sur la V1 de ESX

Copyright (C) 2021 WayZe

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
