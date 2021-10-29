# scott-graham-brossons

a clicker template to accelerate development for the boys


# 🛑 This will only work with specific settings. 🛑

The following is required for this to function properly.
```bash
1. Edit -> Project Settings -> Maps & Modes -> Game Instance -> Game Instance Class -> zmodeinstance
```

The following is recommended, not required:
```bash
1. Edit -> Editor Settings -> General -> Appearance -> User Interface -> Asset Editor Open Location -> Main Window
```

# Widgets 

## a simple zombie clicker game, using UMG for UI rendering.
## 🛑🛑 YOU MAY HAVE TO ASSIGN SPRITES AND SO ON YOURSELF 🛑🛑
### 🛑🛑🛑🛑🛑🛑🛑🛑🛑SEE THE CUSTOMASSETS FOLDER🛑🛑🛑🛑🛑🛑🛑🛑🛑

## Level Blueprint //
```bash
Blueprints -> Open Level Blueprint
```
This is where I initialise the game screen binding to the viewport and allowing the mouse to be displayed

## PlayerController //

here for reference purposes not currently in use yet

## NewWidgetBlueprint //

(sorry for the name) 

contained within the Graph view is the updating of the HUD logic

contained within the Designer view is the current layout of the zombie game and what is shown when you press play.

## zmodeinstance //

This is a game mode instance class 

contained within is the custom event function to update the zombiecount variable bound to the game instance which is accessible anywhere

## CustomAssets //

Contained within are the...
> 1. buy button sprite which is assigned within the widget blueprint.
> 2. Halloween Morning font by WOODCUTTER MMXXI http://www.woodcutter.es (Used in the Zombie Game text)
> 3. hell-beast-idle.uasset is an asset containing multiple sprites.
> 4. hell-beast-idle_Sprite_2.uasset* these are individual sprites extracted from the hellbeast multiple sprite asset.

## Contributing //

Any custom assets you use will need to be added to Widgets/CustomAssets due to restricting what content gets uploaded to not bloat the repo. Custom assets are things like audio files, images(often referred to as Sprites) etc. 
Otherwise, the repo should pick up any blueprint & world changes you make. If not please DM me.