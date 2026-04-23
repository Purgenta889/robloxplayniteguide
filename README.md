# How To Add Roblox as a Game To Playnite on Windows
This is a guide on how to add Roblox as a game to Playnite on Windows. You can also view this guide on Rentry:
https://rentry.co/robloxplayniteguide

# Guide
## 1. Add a Game Manually

Go to "Add Game", and click "Manually...".

<img width="719" height="147" alt="image" src="https://github.com/user-attachments/assets/7c3764d7-e8c8-4750-99c5-3f1259693ce5" />

## 2. Adding Actions

Edit your game, and navigate to "Actions". From there, click "New Action" to create a new action, if there isn't one already present. With this new action, copy these settings:

<img width="1034" height="269" alt="image" src="https://github.com/user-attachments/assets/94bade98-5935-4f92-9584-fbc888991221" />

Name (Optional): Roblox

Play Action: Toggled On

Type: Link

Tracking Mode: Folder

Path: `roblox-player:1+launchmode:play`

Tracking Path: `C:\Users\(Your User)\AppData\Local\Roblox\Versions`

**Replace `(Your User)` with your Windows user.**

## 3. Save Changes

Save your changes. Now, when you launch the Roblox Player, it will track and monitor the .exe properly. 

You have now successfully added Roblox as a game on Playnite!

# FAQ
## Why Not Simply Add The RobloxPlayerBeta.exe?
This will only work temporarily. Once the Roblox Player updates, the version will change, changing the directory of the RobloxPlayerBeta.exe. As a result, when the Roblox Player updates, you'll have to manually change the directory every single time. This isn't great for people who want seamless setups, such as couch gaming.
