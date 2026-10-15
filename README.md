# 🥷 Ninja Platformer

A 3-level 2D action platformer I built solo in **Unreal Engine 4** using **Blueprints** and **Paper2D**, as a college project at Belfast Metropolitan College.

<!-- Replace with a GIF of gameplay once recorded: ![Gameplay](media/gameplay.gif) -->

**🎬 Demo video:** https://youtu.be/9Neo5mr7hUg

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_4-0D1117?style=for-the-badge&logo=unrealengine&logoColor=00FF41)
![Blueprints](https://img.shields.io/badge/Blueprints-0D1117?style=for-the-badge&logo=unrealengine&logoColor=00FF41)
![Paper2D](https://img.shields.io/badge/Paper2D-0D1117?style=for-the-badge&logoColor=00FF41)

## 🎮 Features

- **Combat:** sword attacks and throwable kunai, on the ground and mid-jump
- **Animated character:** flipbook animations for idle, run, jump, attack, throw, jump-attack, jump-throw and death
- **Hazards:** exploding traps and kunai traps
- **Pickups:** collectable spinning coins and health pickups
- **UI:** title menu, in-game HUD and game-over screen, built with UMG widgets
- **Three levels:** an end-of-level trigger moves the player on through each level

## 🛠️ How it's built

| Area | What I did |
|---|---|
| Character | Extended the UE4 2D Side Scroller template character with melee and ranged attacks, health and death |
| Gameplay logic | All game logic written in **Blueprints**: pickups, traps, damage, level completion |
| Animation | Imported sprite sheets, created Paper2D sprites and flipbooks for every action |
| UI | Designed the HUD, title menu and game-over screen as widgets |
| Level design | Built three levels from a tileset with platforms, hazards and pickups |

## 📁 Project structure

```
Config/        Project settings
Content/
├── Character/     Player animations (sprites + flipbooks)
├── Items/         Coin, health and kunai pickups
├── Items/Traps/   Exploding trap
├── LevelItems/    Floor tiles and level pieces
├── Levels/        Game levels
├── EndLevel/      Level-complete logic
└── Widgets/       HUD, title menu, game-over screen
Source/        Original sprite and tileset art files
LisanAlGaib.uproject
```

## ▶️ How to run

1. Install **Unreal Engine 4** via the Epic Games Launcher.
2. Clone this repo and double-click `LisanAlGaib.uproject`.
3. Open `Content/Levels/Level1` and press **Play**.

## 🙏 Credits

- Built on the Unreal Engine 4 **2D Side Scroller** template
- Character sprites and tileset art: free assets from [GameArt2D](https://www.gameart2d.com/freebies.html)
- Coin sound effect: from *Super Mario Bros.* (© Nintendo), included for educational purposes only. All rights belong to their respective owners.
