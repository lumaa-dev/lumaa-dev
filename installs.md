# Install my Fabric mods
*We will use [The Backrooms Mod](https://github.com/u-lumaa/BackroomsMod) as an example*

***

- Install [Fabric](https://fabricmc.net/use/installer/) on the correct version (*see [correct versions](#correct-versions)*)
  - For this example, we will use the version `Alpha A0.0.3` using the 1.19.1 version.

<img src="https://user-images.githubusercontent.com/93350976/192139538-e5237bf0-53e0-4f44-be0e-2854bbf966ac.png" width=500>  <img src="https://user-images.githubusercontent.com/93350976/192139568-12cfc423-f466-48bb-bd95-7bdfcc8f6560.png" width=500>    
- Install the latest version of my mod on [Github](https://github.com/u-lumaa/BackroomsMod/releases/latest), [Modrinth](https://modrinth.com/mod/backrooms/versions) or [CurseForge](https://www.curseforge.com/minecraft/mc-mods/thebackrooms/files).
  - On Github, click the `.jar` file
  - On Modrinth, click the **Download** button
 
 ![Dependencies](https://user-images.githubusercontent.com/93350976/192139971-3e8bc90e-c04d-4e45-bc01-75143b8c0e83.png)  
- Install the required dependencies in 1.19.1 if there are.
  - For this example we need [Fabric API](https://modrinth.com/mod/fabric-api/versions) and [Cloth Config](https://modrinth.com/mod/cloth-config/versions)

- Launch the Fabric Minecraft without mods once and close Minecraft
- Go to `.minecraft/mods` and move the mod and the dependencies in it
- Open Minecraft

***

### Correct Versions

| Mod \ Version        | 1.19   | 1.19.1  | 1.19.2  | 1.20   |
|----------------------|--------|---------|---------|--------|
| The Backrooms        | ❌    | ✔️      | ✔️      | Coming soon      |
| Your Name Your Death | ❌    | ✔️*     | ✔️      | Coming soon      |
| Need Config?         | ❌    | ❌      | ❌      | Coming soon      |  
  
*`*` maybe works*

# How to setup my JavaScript Discord bots
*We will use [Keymey](https://github.com/u-lumaa/Keymey) as an example*

***

- Install [NodeJS](https://nodejs.org/en/download/) v16.9 (*NPM is included with NodeJS*)
- Check if NodeJS and NPM installed properly by opening a command prompt and typing `node --version` and `npm version`
  - You should get a result like this:  
![Versions](https://user-images.githubusercontent.com/93350976/197408646-01520267-3ab9-4cbc-ac10-e91985dd30e3.png)
- Download the [GitHub .zip file](https://github.com/u-lumaa/Keymey/archive/refs/heads/master.zip) and extract it
- Create the config file
  - Go in `bot_folder/functions` and create `config.json`
  - Then write [this](#configjson-content) with your information 


- Open a command prompt and type `cd [folder path]` then enter
- Then type `node main`
- Your command prompt should say that it's ready!

* * *

### config.json Content
```json
{
    "ownerId": "Discord ID",
    "token": "Bot Token",
    "devPrefix": "Developper Prefix (to create commands)",
}
```
