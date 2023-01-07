# Installer mes mods Fabric
*Pour cette exemple, nous utiliserons le mod [The Backrooms](https://github.com/u-lumaa/BackroomsMod)*

***

- Installez [Fabric](https://fabricmc.net/use/installer/) avec la version correcte (*voir [versions correctes](#versions-correctes)*)
  - Pour cet exemple, nous utiliserons la version `Alpha A0.0.3` qui utilise la version 1.19.1.

<img src="https://user-images.githubusercontent.com/93350976/192139538-e5237bf0-53e0-4f44-be0e-2854bbf966ac.png" width=500>  <img src="https://user-images.githubusercontent.com/93350976/192139568-12cfc423-f466-48bb-bd95-7bdfcc8f6560.png" width=500>    
- Installez la version la plus récente sur [Github](https://github.com/u-lumaa/BackroomsMod/releases/latest), [Modrinth](https://modrinth.com/mod/backrooms/versions) ou [CurseForge](https://www.curseforge.com/minecraft/mc-mods/thebackrooms/files).
  - Sur Github, cliquez sur le fichier `.jar`
  - Sur Modrinth, cliquez sur le bouton **Download**
 
 ![Dépendances](https://user-images.githubusercontent.com/93350976/192139971-3e8bc90e-c04d-4e45-bc01-75143b8c0e83.png)  
- Installez les dépendances nécessaires si il y en a.
  - Pour cet exemple nous avons besoin du [Fabric API](https://modrinth.com/mod/fabric-api/versions) et de [Cloth Config](https://modrinth.com/mod/cloth-config/versions)

- Lancez le Minecraft Fabric sans mods et puis refermez-le
- Allez dans `.minecraft/mods` et déplacez les mods et dépendances dedans
- Ouvrez Minecraft

***

### Versions Correctes

| Mod \ Version        | 1.19   | 1.19.1  | 1.19.2  | 1.20   |
|----------------------|--------|---------|---------|--------|
| The Backrooms        | ❌    | ✔️      | ✔️     | Bientôt      |
| LibuLib              | ❌    | ✔️      | ✔️     | Bientôt     |
| Your Name Your Death | ❌    | ✔️*     | ✔️     | Bientôt      |
  
*`*` fonctionne peut-être*

# Comment mettre en place mes Bots Discord JavaScript
*Pour cette exemple, nous utiliserons le bot [Keymey](https://github.com/u-lumaa/Keymey)*

***

- Installez [NodeJS](https://nodejs.org/en/download/) v16.9 (*NPM est inclu avec NodeJS*)
- Verifiez si NodeJS et NPM sont bien installé en ouvrant une invite de commande et tapez `node --version` et `npm version`
  - Vous devriez avoir un résultat comme celui-ci :  
![Versions](https://user-images.githubusercontent.com/93350976/197408646-01520267-3ab9-4cbc-ac10-e91985dd30e3.png)
- Téléchargez le [fichier .zip du GitHub](https://github.com/u-lumaa/Keymey/archive/refs/heads/master.zip) et extrayez-le
- Créez le fichier `config.json`
  - Allez dans `dossier_bot/functions` et créez `config.json`
  - Ensuite, écrivez [ça](#contenu-configjson) avec vos informations 


- Ouvrez une invite de commande et tapez `cd [chemin du dossier]` puis entrez
- Puis tapez `node main`
- Votre invite de commande devrait vous dire que c'est Ready !

* * *

### Contenu config.json
```json
{
    "ownerId": "Identifiant Discord",
    "token": "Token du Bot",
    "devPrefix": "Préfixe du développeur (pour créer des commandes)",
}
```
