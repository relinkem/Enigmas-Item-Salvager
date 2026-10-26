# Changelog

## 0.1.4
- New Swap button for the armor stand window of Enigma's Expanded Armor Stands. It sits under Drop and only shows while a stand window is open. It does nothing without that mod (it needs version 0.1.22 or later).
- The buttons beside a chest or other container are now placed one under the other from Take downwards, so a hidden button leaves no gap. The spacing is the same in every window.
- In the armor stand window only Take, Drop and Swap are shown. Stack and Sort are hidden there, because the stand only accepts certain items in certain cells.

## 0.1.3
- Now works with [MultiCraft](https://thunderstore.io/c/valheim/p/MaxiMods/MultiCraft/) by MaxiMods (written for 1.5.0). With it installed, its + and - counter sets how many of a stack the Salvage tab scraps or breaks down (Scrap, creature heads and Core Wood), up to the size of the stack. Ctrl+click on + picks the whole stack, and the counter goes back to 1 after each use. The buttons are greyed for single items and normal salvage, and MultiCraft's repeat-craft no longer runs on the Salvage tab. Without MultiCraft nothing changes: the whole stack is used at once.
- Looting a tombstone (the Take button or the E key) no longer goes through the hotbar reservation or the sort after Take All, so items stay in the exact slots they came from and ExtraSlots can restore its equipment slots and auto equip. This also holds in multiplayer when another player owns the tombstone.
- Fixed the container buttons (Take, Stack, Sort and Drop) going missing or landing in the wrong place after you leave to the main menu and load back into a world. The buttons are now lined up again every time you load in, so you no longer have to restart the game.

## 0.1.2
- New Sort button for your inventory. It merges partial stacks of the same item and arranges the bag by category (equipment, ammo, trinkets, tools, materials, trophies, food). The hotbar row and any slots added by other mods (such as ExtraSlots) are never used for sorting. Use the button on the inventory panel, the button under Place All in a chest or other container (it sorts that container), or press Ctrl+S to sort your bag. With ExtraSlots installed, Sort also fills its empty armor, trinket, food, ammo and misc slots with the best matching items and equips the armor (slots that already hold something are never changed). Controller: click the right stick (not tested on a controller).
- The hotbar is now kept for weapons, tools, shields, torches, bows, food and ammo. Armor, materials, trophies and other items only land there when the bag is full, for both picking things up and Take All. Take All now puts tools and weapons first. Turn it off with the ReserveHotbar setting.
- New Drop button in chests and other containers: moves everything in your bag below the hotbar into the container, filling existing stacks first, then sorts the container. Take All now sorts your inventory afterwards (SortAfterTakeAll setting).
- Core Wood can now be chopped into Wood at the Workbench. Each Core Wood gives 4 Wood, and the whole stack is chopped at once. The list is editable with the new LogTable setting.
- The squares on the Salvage tab now show only the low to high range of what you will get back.

## 0.1.1
No gameplay changes. Added screenshots and a support link to the page, and set the project link.

## 0.1.0
First release.
- New Salvage tab in the crafting window at the Workbench, Forge, Black Forge and Galdr Table.
- Returns based on your Crafting skill and the new Salvaging skill.
- New Salvaging skill (levels up as you salvage, adds to the return and shortens the salvage time).
- Scrap: hold the button to delete items that have no recipe.
- Creature heads can be salvaged into materials at the Workbench.
- Config file, plus editable ingredient weights and item sayings.
