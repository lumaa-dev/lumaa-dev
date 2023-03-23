# Install my Fabric mods
*We will use [The Backrooms Mod](https://github.com/lumaa-dev/BackroomsMod) as an example*

***

- Install [Fabric](https://fabricmc.net/use/installer/) on the correct version (*see [correct versions](#correct-versions)*)
  - For this example, we will use the version `Beta A0.1.2` using the 1.19.3 version.

<img src="https://user-images.githubusercontent.com/93350976/224516085-4055f40a-b806-4926-8126-5a46b3ce88c5.png" width=600>  

- Install the latest version of my mod on [GitHub](https://github.com/lumaa-dev/BackroomsMod/releases/latest), [Modrinth](https://modrinth.com/mod/backrooms/versions).
  - On Github, click the `.jar` file
  - On Modrinth, click the **Download** button
 
 ![Dependencies](https://user-images.githubusercontent.com/93350976/192139971-3e8bc90e-c04d-4e45-bc01-75143b8c0e83.png)  
- Install the required dependencies in 1.19.3 if there are.
  - For this example we need [Fabric API](https://modrinth.com/mod/fabric-api/versions) and **optionally** [Yet Another Config Lib](https://modrinth.com/mod/yacl/versions)

- Launch the Fabric Minecraft without mods once and close Minecraft
- Go to `.minecraft/mods` and move the mod and the dependencies in it
- Open Minecraft and enjoy the mods!

***

### Correct Versions
This board only applies on the **latest version** of each mods

|                                                                | 1.19   | 1.19.1  | 1.19.2  | 1.19.3   |
|----------------------------------------------------------------|--------|---------|---------|----------|
| [The Backrooms Mod](https://modrinth.com/mod/backrooms)        | ❌    | ❌      | ❌      | ✅      |
| [LibuLib](https://modrinth.com/mod/libu)                       | ❌    | ❌      | ❌      | ✅      |
  
*`*` maybe works*

# How to setup my JavaScript Discord bots
*We will use [Keymey](https://github.com/lumaa-dev/Keymey) as an example*

***

- Install [NodeJS](https://nodejs.org/en/download/) v16.9 (*NPM is included with NodeJS*)
- Check if NodeJS and NPM installed properly by opening a command prompt and typing `node --version` and `npm version`
  - You should get a result like this:  
![Versions](https://user-images.githubusercontent.com/93350976/197408646-01520267-3ab9-4cbc-ac10-e91985dd30e3.png)
- Download the [GitHub .zip file](https://github.com/lumaa-dev/Keymey/archive/refs/heads/master.zip) and extract it
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
