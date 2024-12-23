Disregard the files above and use the latest release on the right.

# MagicFinder
<img src="https://github.com/user-attachments/assets/ee30501e-74ff-4e29-ab52-e729116b352e" width="75%">

MagicFinder is a custom pack for the Guild Wars 2 addon [Reffect](https://github.com/Zerthox/gw2-reffect/) that makes it easy to keep track of your Magic Find buffs when you're bag farming in the Mad King's Labyrinth.

Icons for Magic Find buffs are displayed in one or two columns that can be dragged anywhere on the screen. Buffs currently active on the character are displayed at full opacity, while missing and expired buffs are greyed-out or colored red so you can quickly see what needs to be reapplied. Key buffs pop-up above the skill bar when expired. 

## Effects
Effects are loosely grouped into three sections according to expiration and availability. On the two-column layout only (as of this release), key expired buffs are colored red while in the Labyrinth. This way, effects can be easily monitored anywhere but only call extra attention while Lab running.

<img src="https://github.com/user-attachments/assets/b9018c29-287e-4026-b73c-ef8f21c9f2f8" width="6%">  <img src="https://github.com/user-attachments/assets/2a41aadb-1fff-4c45-9e0d-54f7d32795e7" width="8%">

Some effects use alternate icons to more easily distinguish them. For example, the _Ace Racer,_ _Approval of the Mad King_, and _Grudging Approval_ buffs all use the same icon on your in-game effects monitor, so MagicFinder uses a racing beetle and cat icon for the first and last, respectively.

### Popup Bar

Key buffs, when expired, will pop-up in a row above the action bars. These are the buffs assumed to be easy and quick for a lab runner to reapply at will. The pop-ups are only visible in the Labyrinth.

<img src="https://github.com/user-attachments/assets/2f68bb48-f456-408b-b6bc-fd744c121ef6" width="43.5%">  <img src="https://github.com/user-attachments/assets/db153267-3637-461e-8b1d-1eb9b8db1af0" width="50%">

---
All trackable Magic Find buffs that apply in the Labyrinth are included in the main columns (see the wiki for a [complete list of Magic Find buffs and sources](https://wiki.guildwars2.com/wiki/Magic_Find#Attribute)). These are:
* Magic Find Boost, +50% MF (Bonfire, MF/Enchanted Booster, Fireworks)
* Celebration Bonus, +100% MF (Birthday/Celebration Booster)
* Guild Magic Find Banner Boost, +15% (Guild Gold and Magic Find Banners, Guild Heroes Banners, and Guild Anniversary Banners)
* Spirit Banner Boost, +10% MF (Spirit Banner)
* Item Booster (effect), +50% MF (Candy Corn Gobbler, Item/Heroic/Enchanted Booster)
* New Year's Gift, +10% MF (Fireworks)
* Nourishment, +3%-40% MF (Various food)
* Enhancement, +30% MF (Various utility consumables)
* Ace Racer, +25% MF (Lab Mount Race)
* Approval of the Mad King, +25%-125% MF (Lab Boss Kills)
* Grudging Approval, +25% MF (Madame Cookie)
* Enlightenment, +10% MF (Training Ground)
* Guild Item Research, +10% MF (Bartender in Guild Hall)
* Ward's Remembrance, +15% MF (Astral Ward Memorial)
* Black Lion Boost, +100% MF (Black Lion Statuettes)

The Extra Life and Welcome Back bonuses are not tracked since they can't be applied or removed.

---
### Food
**Included Food:**
* Chocolate Omnomberry Cream 9987
* Peppermint Omnomberry Bar 34188
* Spicy Pumpkin Cookie / Court Chef 15260

The food effects commonly recommended for the Lab are implemented, but users may manually add the effect IDs for whichever other nourishment they're using ([see this wiki page](https://wiki.guildwars2.com/wiki/Guild_Wars_2_Wiki:Projects/Nourishment_effect_ids) for nourishment effect IDs). All utility consumables with Magic Find are implemented (there are only three).

<img src="https://github.com/user-attachments/assets/0ef47c05-3144-4cd8-83e0-c746eb9d9d8d" width="50%">

## Installation
Download the latest MagicFinder.json file from the right sidebar on Github and place it in ``Guild Wars 2\addons\reffect\packs``. Enable it in-game under Nexus "Addons" and drag the icons wherever you want them on your screen.

To choose between the one- or two-column configuration, open Nexus in-game and click "Configure" on the Addons pane. Expand _MagicFinder by DominantNostril_ and select the _Single Column_ or _Two Column_ layout by checking or unchecking the "Enabled" boxes.

<img src="https://github.com/user-attachments/assets/9bfde240-f706-4867-8b9f-181406e6d904" width="50%">

## Contact
You can reach DominantNostril.4753 in-game for compliments and recriminations.

