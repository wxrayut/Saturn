<div align="center">
    <img src="https://upload.wikimedia.org/wikipedia/en/e/ef/Arena_of_Valor_Logo_2021.png" width="130" alt="ArenaOfValor Logo" />
    <h2>skins-diffusion.exe</h2>
</div>


<p>An executable file for modifying <i><a href="https://en.wikipedia.org/wiki/Arena_of_Valor">Arena of Valor</a></i> game files, allowing users to create in-game skins for your favorite heroes.</p>


> [!CAUTION]
>
> **skins-diffusion.exe** is archived and no longer actively maintained.
> While the repository remains accessible, no further updates or bug fixes will be provided.
> Bugs may be addressed, but this is not guaranteed. Please use this tool "as-is."
> If you encounter any issues, you can attempt to troubleshoot on your own. 

### 🖥️ Supported Operating Systems

- [x] Windows
- [ ] macOS
- [ ] Linux


### ✨ Features

- [x] Skill Effects
- [x] Recall Effects
- [x] Haste Effects

> [!IMPORTANT]  
>
> New skins introduced after version `1.52.1` will not support Recall Effects and Haste Effects.

- [x] Skin Icon and Background
- [ ] Dimension Breaker Skin Assets
- [ ] Skin Label
- [x] Sound Effects
- [x] Model


### 🚀 Usage

- Go to the [Releases](https://github.com/wxrayut/skins-diffusion.exe/releases) page and download the latest `skins-diffusion.exe`.
- Make sure to place the necessary game resources in the `Resources` folder.
- Pick your desired skin(s) from the `skins` folder.
- Copy the selected skin(s) into the `Tasks` folder.
- Then run the `skins-diffusion.exe`.

### 📂 File Overview Structure

    skins-diffusion.exe/
    ├── ...
    ├── Resources/ # Necessary game resources should be stored here.
    │   ├── Ages
    │   │   └── Prefab_Characters
    │   │       └── Prefab_Hero
    │   │           │── Actor_*_Actions.pkg.bytes
    │   │           │── ...
    │   │           └── CommonActions.pkg.bytes
    │   ├── Databin
    │   │   └── Client
    │   │       ├── Actor
    │   │       │   └── heroSkin.bytes
    │   │       ├── Skill
    │   │       │   │── liteBulletCfg.bytes
    │   │       │   └── skillmark.bytes
    │   │       └── Sound
    │   │           │── BattleBank.bytes
    │   │           │── ChatSound.bytes
    │   │           │── HeroSound.bytes
    │   │           │── LobbyBank.bytes
    │   │           └── LobbySound.bytes
    │   └── Prefab_Characters
    │       ├── Actor_*_Infos.pkg.bytes
    │       └── ...
    ├── skins/  # List of skins you can modify will be store here, 
    │       │   # you can pick one or more skins and paste into the Tasks folder.
    │       └── ... 
    ├── Tasks/
    │       └── # Whatever skins you want to modify, should be here.
    ├── skins-diffusion.exe # The executable file should be here.
    ...


### 🎯 Apply the Mod Skin(s)

- #### Android (For Android version ≤ 10)

    - Extract the .zip file and copy all subfolders:

        `Ages` `AssetRefs` `Databin` `Prefab_Characters`

    - Navigate to: `Android/Data/com.garena.game.kgth/files/Resources/(GAME PATCH)/`

    - Paste the copied subfolders into the directory above.
    
    - When prompted, select "**Apply to all files**" to overwrite the necessary files.

    - Tap "**REPLACE**" to complete the installation.

- #### iOS

    On **iOS**, you cannot access the game directory unless you install the game using a **.ipa** file (which you can find on sites like [decrypt.day](https://decrypt.day/)) by using some sideloader tool. In this way you can access the game directory.

    > [!WARNING]  
    >
    > Make sure you **.ipa** file is **Anti-Ban** (Don’t worry, this is not directly related to the mod skin.).

    Open the **Files app → On My iPhone → AoV** (or the app name you set during installation). Follow the same steps as **Android** to apply the mod skins—the process is identical.


### 👎 Failure

If you encounter the warning message:
`Network failure, Please reconnect` while using the mod skin:

<div align="center">
    <img src="https://f.ptcdn.info/595/076/000/r8en56pwaaK7Ks0m3OAu-o.jpg" width="700" alt="ArenaOfValor WarningMessage" />
</div>
<h4>💭 Possible Causes & Solutions:</h4>
<ol>
    <li><b>Outdated Resources</b> – Your <b>Resources</b> folder may not be up to date. Try manually updating it to the latest version.
    </li>
    <li><b>Skin Compatibility Issues</b> – Some skins require additional modifications. Unfortunately, all you can do is wait. If this is a known issue, it may be addressed in future versions (if applicable).</li>
</ol>


### 📜 Disclaimer

- Modifying game files is against the **terms of service** of Arena of Valor and may lead to account suspension or a ban.
- By using this tool, you **accept full responsibility** for any consequences that may arise.
- Use at **your own risk**.


### < / > Source Code

This tool is not open source. I am not ready to release the source code at this time.


### 📄 License

This software is distributed under an End-User License Agreement (EULA).
