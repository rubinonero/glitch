glitch
======

This is the first readme for Glitch, a roguelike adventure/interactive novel/rpg.


Classes
======
Location: this would be a complex setting to be fully explored. Contains one or more Scenes.
Scene: a single view of a place. It has a background picture, some texts and eventually one or more Characters that follow a script and multiple choices.
Event: this would be a single action occurring in the game, such as acquiring an Item, changing an image or a Link between two objects
Character: a person/animal interacting with the player. Can have an inventor of objects and mantain Links with the Player, a Location or an Item.
Task: a list of Event that must be triggered. Can trigger an Event itself.
Item: an object that can have properties an have Links to other objects.
Link: a complex relationship between objects.
