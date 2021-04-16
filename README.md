# Base Template

Bonjour à tous je vous présente aujourd'hui cette Base Template réalisé dans le but de vous faciliter la création de vos Serveurs FiveM. Cette base comporte toutes les ressources essentiels au bon fonctionnement de votre serveur.

Le nom de la ressource n'est pas modifiable !

-----------------------------------------------------
-----------------------------------------------------

Hello everyone, I present to you today this Base Template created in order to facilitate the creation of your FiveM Servers. This database contains all the resources essential for the proper functioning of your server.

The name of the resource cannot be changed!

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

- Si vous avez besoin d'aide pour l'installation : https://discord.gg/eX9GXWN
- If you need help installing: https://discord.gg/eX9GXWN

# Preview

Vidéo de présentation de la base :
 - [Base Preview](https://youtu.be/6UHVMXqlJ14) 

# Author 
Discord : WayZe#0001 | Youtube : WayZe | Twitter : @WayZeTV

### License
Base Template - Base Template réalisé sur la V1 de ESX

Copyright (C) 2021 WayZe

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
