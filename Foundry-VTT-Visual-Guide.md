# Foundry VTT Visual Guide

This is a quick visual reference guide for players for Foundry Virtual Tabletop, the software we're using to playing Dungeons & Dragons remotely.

> Note: we are using some modules for Foundry which alter the default user interface & experience.

# Navigating the user interface

> Protip: when uncertain of which tabs are which, hover over the icon to bring up its label.

![ui-diagram-labelled](./assets/00-ui-diagram-labelled.jpg)

<details closed>
<summary>DEMO: Moving the canvas with <code>right click</code></summary>
<img src='./assets/00-move-canvas.gif'/>
</details>

<details closed>
<summary>DEMO: Zooming in & out of the canvas with <code>mouse wheel</code></summary>
<img src='./assets/00-zoom-canvas.gif'/>
</details>

### Right sidebar
* __🗨️ Chat Messages__ - player messaging, dice roll results
    <details closed>
    <summary>DEMO: Expanding a dice roll with <code>left click</code></summary>
    <img src='./assets/01-expand-dice-roll.gif'/>
    </details>
    <details closed>
    <summary>DEMO: Linking any item in chat with <code>Alt</code> + <code>left click</code></summary>
    <img src='./assets/02-link-item-to-chat.gif'/>
    </details>
* __⚔️ Combat Encounters__ - initiative tracker *during combat only*
    <details closed>
    <summary>DEMO: Popping out the initiative tracker with <code>right click</code></summary>
    <img src='./assets/03-pop-out-initiative-tracker.gif'/>
    </details>
* __👤 Actors__ - players, NPCs, & creatures you have access to 
* __💼 Items__
* __📖 Journal__ - DM-shared documents, campaign notes
* __🗒️ Rollable Tables__ - Most likely not using this
* __🃏 Card Stacks__ - Most likely not using this
* __🎵 Playlists__ - global & individual playlist volume controls
* __📘 Compendium Packs__ - quick in-game reference
    <details closed>
    <summary>DEMO: Accessing the basic game rules through a compendium</summary>
    <img src='./assets/04-access-basic-game-rules.gif'/>
    </details>

### Token combat controls
You can right click your token to bring up its controls. This is different than the token controls menu at the top left of the UI.

* __🔥 Toggle Torch__ - light or extinguish your torches
* __⌃ Token Elevation__ - height in feet of the token above ground level
* __⚙️ Token Settings__ - settings to modify token display name, image, and top or bottom resource bars 
* __🎯 Target__ - used for targeted abilities; we most likely won't be using this
* __👤 Assign Status Effects__ - allows assigning conditions to your token; the DM can handle this, and you should use the token action HUD instead of this button if assigning conditions yourself.
* __⚔️ Toggle Combat Status__ - the DM will handle this
* __🩸 Player Hitpoints__ - see [Taking damage & healing](#taking-damage--healing)

### Top left - token action HUD & map controls
* __👀 Token Action HUD__ - see [section on token action HUD](#token-action-hud)
* __Map Controls__ - each of the left-most menus have their own submenus, which include the functionalities below:
  * __👤 Token Controls__ - select, target, and measure distance between tokens
  * __📐 Measurement Controls__ - place, select, and delete spell templates of various shapes
    * To select, click the template. To delete, press the `delete` key on your keyboard.
  * __✏️ Drawing Tools__ - draw various shapes or freeform; select & delete your drawings.
  * __🏷️ Journal Notes__ - toggle time & map notes display. create note linked to journal entries / notes

### Bottom left - time indicator & hotbar
* __🕥 In-game Time Indicator__ - shows rough in-game time
* __🔥 Macro & Action Hotbar__ - contains macros & actions for easy access. If we're to use macros, they'll be provided by the DM, so no need to worry about them.
    <details closed>
    <summary>DEMO: Adding an action to the hotbar by dragging & dropping</summary>
    <img src='./assets/05-add-action-to-hotbar.gif'/>
    </details>

## Character sheet
The character sheet is where you keep your character's stats, roll actions & checks, and track character progress.

![character-sheet-diagram-labelled](./assets/06-character-sheet-diagram-labelled.jpg)

### Accessing your character sheet
There are two ways to access your character sheet:

<details closed>
<summary>DEMO: From the Actors menu</summary>
<img src='./assets/07-actors-access-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using a token in the playable area, if present, using <code>double click</code></summary>
<img src='./assets/08-token-access-char-sheet.gif' />
</details>

### Character sheet configuration
You can customize the theme & appearance of your character sheet. Our default character sheet theme, the Tidy 5e sheet, includes a favorites system not present in other character sheets, so it's recommended to keep it.

<details closed>
<summary>DEMO: Changing default sheet theme from light to dark</summary>
<img src='./assets/09-change-char-sheet-theme.gif' />
</details>

## Token action HUD

The token action HUD (heads-up display) is a quick way to access most aspects about your character without having to open the character sheet. Your token needs to be present in the current map for the HUD to be visible.

To have the HUD always display even when your token isn't selected, claim a character through your user configuration. You only need to do this once.

<details closed>
<summary>DEMO: Claiming a character through user configuration</summary>
<img src='./assets/10-claim-a-character.gif' />
</details>

### Token action HUD configuration
You may need to adjust the HUD to expand downwards prior to first use. You only need to do this once.

<details closed>
<summary>DEMO: Changing HUD style and expansion direction</summary>
<img src='./assets/11-change-token-hud-settings.gif' />
</details>

# Using the "X-Card"
See [Social Contract > Safety Tools](./Social-Contract.md#safety-tools) for details about when this should be used.

<details closed>
<summary>DEMO: Using the Anonymous Player's X-Card</summary>
<img src='./assets/11-use-x-card.gif' />
</details>

# Pinging the canvas
The canvas is the main playable area.

<details closed>
<summary>DEMO: Pinging the canvas by holding down <code>left click</code></summary>
<img src='./assets/12-ping-canvas.gif' />
</details>

# Moving your character token
You will need to move your token(s) during combat. You may not do this while the game is paused. There are three ways to move your character's token:

<details closed>
<summary>DEMO: Using <code>WASD</code> keys</summary>
<img src='./assets/13-move-wasd.gif' />
</details>
<details closed>
<summary>DEMO: Dragging & dropping with the mouse</summary>
<img src='./assets/14-move-drag.gif' />
</details>
<details closed>
<summary>DEMO: Using the token control ruler tool</summary>
<img src='./assets/15-move-ruler.gif' />
</details>

# Rolling with advantage / disadvantage
You can roll all things with advantage or disadvantage using the controls below.

<details closed>
<summary>DEMO: 🎲🎲➕ Advantage: <code>Shift</code> + <code>left click</code></summary>
<img src='./assets/16-roll-advantage.gif' />
</details>
<details closed>
<summary>DEMO: 🎲🎲➖ Disadvantage: <code>Ctrl</code> + <code>left click</code></summary>
<img src='./assets/17-roll-disadvantage.gif' />
</details>

# Rolling skill checks
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/18-skill-check-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<img src='./assets/19-skill-check-hud.gif' />
</details>

# Rolling ability checks & saving throws
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/20-ability-check-saving-throw-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<img src='./assets/21-ability-check-saving-throw-hud.gif' />
</details>

# Rolling arbitrary dice
You can use the chat functionality to roll arbitrary dice.

<details closed>
<summary>DEMO: Rolling <code>3d4 + 3</code></summary>
<img src='./assets/22-roll-3d4+3.gif' />
</details>
<details closed>
<summary>DEMO: Rolling 1d20 with advantage & disadvantage</summary>
<img src='./assets/23-roll-advantage-disadvantage.gif' />
</details>

> Protip: the chat functionality can also do math problems! This is great for splitting up gold.

<details closed>
<summary>DEMO: Doing arbitrary math</summary>
<img src='./assets/24-roll-math.gif' />
</details>

# Rolling initiative
<details closed>
<summary>DEMO: Using combat tracker</summary>
<img src='./assets/25-roll-initiative-combat-tracker.gif' />
</details>
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/25-roll-initiative-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<img src='./assets/26-roll-initiative-hud.gif' />
</details>

# Attacking with weapons
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/27-attack-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<p>If using token action HUD, the weapon must be equipped before it'll show up.</p>
<img src='./assets/28-attack-hud.gif' />
</details>

# Casting spells
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/29-cast-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<p>If using token action HUD, the spell must be prepared before it'll show up.</p>
<img src='./assets/30-cast-hud.gif' />
</details>

# Taking damage & healing
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/31-damage-heal-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token controls</summary>
<img src='./assets/32-damage-heal-token-controls.gif' />
</details>

# Using active abilities
Passive abilities don't need activation, so we don't need to worry about them. Active abilities need to be activated, with two ways:

<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/33-active-ability-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<img src='./assets/34-active-ability-hud.gif' />
</details>

# Short / long rests
<details closed>
<summary>DEMO: Using character sheet</summary>
<img src='./assets/35-short-long-rest-char-sheet.gif' />
</details>
<details closed>
<summary>DEMO: Using token action HUD</summary>
<img src='./assets/36-short-long-rest-hud.gif' />
</details>

# Equipping items & preparing 1st level and higher spells
This needs to be done from the character sheet.

<details closed>
<summary>DEMO: Equipping an item & preparing a spell</summary>
<img src='./assets/37-equip-item-prepare-spell.gif' />
</details>

# Favoriting items, spells, and features
Favoriting will make an item, spell, or feature appear in the first tab of the character sheet. This needs to be done from the character sheet. It's also only a feature of the Tidy 5e sheet module we're using.

<details closed>
<summary>DEMO: Favoriting something</summary>
<img src='./assets/38-favorite-item.gif' />
</details>

# Adding & editing items
This needs to be done from the character sheet. It's recommended to create an item directly into your character sheet instead of the `Items` menu tab, so you own the item from the start.

<details closed>
<summary>DEMO: Creating a rat tail loot item</summary>
<img src='./assets/39-create-item.gif' />
</details>

# Importing items from Plutonium
This needs to be done from the character sheet. Plutonium is our main module for importing content. Often times, items you've bought or found do not need to be created from scratch because they already exist in Plutonoum, so importing them is the quickest way.

> Protip: you can import all the things, not just items. This includes but isn't limited to: spells, classes, and pets. Please don't import things you're not supposed to have -- importing & creating your own items is a privilege, and we are operating on a system of trust.

<details closed>
<summary>DEMO: Importing a Potion of Healing</summary>
<img src='./assets/40-import-item.gif' />
</details>

# Popping out a window
Popping out an in-game window puts it into a separate browser window.

<details closed>
<summary>DEMO: Popping out an in-game window</summary>
<img src='./assets/41-pop-out-window.gif' />
</details>

# Minimizing a window
<details closed>
<summary>DEMO: Minimizing an in-game window with <code>double click</code></summary>
<img src='./assets/42-minimize-window.gif' />
</details>
