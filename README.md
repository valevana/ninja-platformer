# Ninja Platformer

A 2D ninja platformer I made on my own in Unreal Engine 4 for my Level 3 IT course at Belfast Met. It has three levels, and you fight your way through them with a sword and throwing kunai, dodging traps and picking up coins and health along the way.

Demo video: https://youtu.be/9Neo5mr7hUg

## What's in it

You can attack with the sword or throw kunai, both on the ground and in the air. There are exploding traps and kunai traps to avoid, coins to collect and mushrooms that give you health back. Reach the end of a level and it takes you to the next one. There's also a title menu, a HUD showing your health and coins, and a game over screen.

## How I made it

I started from Unreal's 2D Side Scroller template and built the game on top of it, with everything done in Blueprints (no C++).

Most of the work went into the character. I imported the sprite sheets, turned them into Paper2D flipbooks for each move (idle, run, jump, attack, throw, jump attack, jump throw and death) and then wired up the logic for switching between them, attacking, throwing kunai, taking damage and dying. After that I built the pickups, the traps, the end-of-level trigger and the UI widgets, and put the three levels together from a tileset.

It was my first proper game in Unreal, so it taught me a lot about how Blueprints, animation and game logic fit together.

## Running it

You'll need Unreal Engine 4 from the Epic Games Launcher. Clone the repo, open `LisanAlGaib.uproject`, load `Content/Levels/Level1` and press Play.

## Credits

- Unreal Engine 4 2D Side Scroller template
- Character and tileset art: free packs from [GameArt2D](https://www.gameart2d.com/freebies.html)
- Coin sound: from Super Mario Bros. (© Nintendo), used for educational purposes only
