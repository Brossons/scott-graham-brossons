# scott-graham-brossons
a home for scotts work


Note before: This will only work with specific settings.

1. Edit -> Project Settings -> Maps & Modes -> Game Instance -> Game Instance Class -> zmodeinstance

Recommended:

1. Edit -> Editor Settings -> General -> Appearance -> User Interface -> Asset Editor Open Location -> Main Window


Widgets 

a simple zombie clicker game, using UMG for UI rendering.

Level Blueprint //

Blueprints -> Open Level Blueprint

This is where I initialise the game screen binding to the viewport and allowing the mouse to be displayed

PlayerController //

here for reference purposes not currently in use yet

NewWidgetBlueprint //

(sorry for the name) 

contained within the Graph view is the updating of the HUD logic

contained within the Designer view is the current layout of the zombie game and what is shown when you press play.

zmodeinstance //

This is a game mode instance class 

contained within is the custom event function to update the zombiecount variable bound to the game instance which is accessible anywhere