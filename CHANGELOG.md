# Changelog

## [0.3.0] - 2024-01-04

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
#### Mine and Slash General Updates
- New EXPERIMENTAL Character Loadout feature! You can now have multiple characters saved on your account. You can switch between them through the Hub.
- Mine and Slash maps now have rollable tiers from 1-100. At higher tiers, more powerful Uniques will drop, and monsters will be more difficult and rewarding. The rarity of the map determines the rarity of map that can drop in the map. For instance, only Rare, Epic, and Legendary maps can drop in Epic maps.
- Map experience in lower tiers is reduced greatly. You will find better items and get more experience in higher tier maps (by a lot).
- Upped Map drop rates by 20%.
- Dual-wielding weapons is now official supported. Weapons in the offhand provide 25% of their stats and will increase your attack speed by 20%. I have made a quest to explain this.
- Spears are now two-handed. Their base stats have been buffed to compensate.
- Increased Spear attack range from 3.5 to 4.0.
- Reduced Energy costs of basic attacks for all weapons except Staff and Dagger.
- Gear implicits have changed drastically. Each type of weapon can now roll different implicits.
- Bosses now always spawn at Rare rarity, with the exception of Blue Skies bosses and the Ender Dragon which always spawn at Common.
- Blue Skies bosses have 20% less HP. They also now take double damage from spells and staff hits (in this case, any non-projectile spell should damage them). This change doesn't fix it, but hopefully helps in the meantime.
- Nerfed the Starlit Crusher walls to always be common and spawn with half health.
- Upped mob damage early on.
- Ender Dragon is apparently hurtable by Skills so I have increased its Health and given it stats.
- Added Nethers Delight Machetes compat with MNS.
- Updated Lifesteal and Manasteal descriptions to be more accurate.
- Nerfed Mob Evasive affix.
- Armor/Magic Shield/Dodge prefixes have been changed back to Gear's Defense stats. The percent values have been readjusted (increased) since they won't be global anymore.
- Elemental Spell Damage stat has now been changed to Elemental Skill Damage so it should affect any Skill, not just Int-tagged ones.
- Nerfed Block Chance multiplier sources (not flat sources).
- Increased player's base Health, Mana, and Energy.
- Increased player's base Mana and Health Regen.
- Increased Mana Regen and Health Regen per point from Int and Str stats.
- Added a new stat for boots that provides Move Speed.
- Summon damage per level has increased.
- Summon health at lower levels has increased.
- Summons no longer chase neutral mobs.
- Summon Energy Cost on hit has reduced by 60%.
- Summons can now leech resources.
- Crits can now apply to DoTs too. As in, the DoT can crit.
- Added some leeway with experience penalties when mob is a different level. If they are within 2 levels, you will get the full experience. That also means at 3+ level difference the drop off may seem harder.
- You can now rank down Profession Materials through recipe for a 1:1 exchange rate.
- Gems now combine into the next tier via crafting recipe instead of the clicks.
- Running out of Energy is a little more punishing now. You will also receive Hunger for a short duration.
- Updated some quest descriptions regarding Professions benches being tied to players and also for Runewords.

#### Mine and Slash Talent Tree Updates
- You can now search nodes in the Talent Tree!
- Buffed Mantra Gamechanger.
- Guardian Support has been changed to give Block Chance multiplier and Health percent rather than flat Block Chance.

#### Mine and Slash Crafting Updates
- You can now obtain Soul modifiers that make your soul item always create a type of armor (cloth/leather/plate).
- Lowered rollable Gear's Weapon Damage percent stats.
- Lowered Mining Profession EXP.
- Lowered Combat to Profession rested EXP.
- Enchanting Profession EXP has increased by 50%.
- Increased the chances of getting Mine and Slash Profession materials from the Miner.
- Better Mine and Slash Profession materials from the Miner are now available in the pool.
- Mine and Slash Fishing materials can now be earned from the Fisherman.
- Mine and Slash Lesser/Medium/Greater materials can now be earned from the Enchanter.
- Mine and Slash items can be earned from the Nether Miner/Worker.
- Mine and Slash Farming materials can now be earned randomly from dirt blocks.

#### Mine and Slash Item Updates
- Sockets have been reworked a bit. All gear can roll multiple sockets up to a max rather than just 1. Lower rarities have higher max sockets. Runewords can be crafted on any rarity, as long as it has the necessary sockets. Note that Uniques and Mythics can only roll a max of 1 socket.
- 7 new Support Gems: Accuracy (Lv. 10), Summon Health (Lv. 10), Effect Duration (Lv. 20), Threat (Lv. 20), Minion Threat (Lv. 20), Swift Affliction (Lv. 30), Brutality (Lv. 30), and Reduced Projectile Speed (Lv. 30). The quest Support Gem shops have been updated.
- Added over 30 new uniques: 2 axes, 2 bows, 2 crossbows, 1 spear, 1 hammer, 2 daggers, 4 swords, 3 staves, 5 helmets, 2 rings, 3 amulets, 5 boots, 3 chestplates.
- Added over 20 new Runewords.
- Greater Mana Cost and Greater Cooldown Reduction Support Gems are no longer available in the shop. They are also now level 40 gems and are fairly rare.
- Cooldown Reduction Support Gem mana cost multi has been reduced from 1.2 to 1.1.
- New Plus to Skill level stats have been introduced.
- Master Bag is now cheaper to craft.
- Buffed a lot of Uniques defense/damage.
- Runewords are no longer "crafted" through the Rune GUI. Instead they act similarly to Diablo II, where you socket them into gear.
- Gem stats now scale to level.

#### UI Overhauls
- Certain Uniques now have custom models/textures. Huge thanks to Nozium for this!
- Updated Mine and Slash UI - basically an overhaul. Huge thanks to Skullbushi for this!
- Vanilla GUI has been updated. Thanks again to Skullbushi! You can overwrite this still with your own custom resource pack if you want.
- New custom assets are being used for cloth/leather/plate armors so they don't all look the same anymore.
- Mine and Slash GUI elements have been updated. You can now see effects on mobs in their health bars, and MnS effects are also separate from Vanilla effects on the player GUI.
- Moved some stats around in Main Hub so hopefully less instances of stats being cutoff in the tooltips will occur.

#### Mine and Slash Class & Spell Updates
- Particle effects for many projectile spells have been improved (more splashy).
- Some Skills have been changed to cost Energy instead of Mana: Arrow Barrage, Boomerang, Pull, Recoil Shot, Shred, Whirlwind.
- Some Skills have been changed to cost Energy in ADDITION to Mana: Explosive Arrow, Flame Strike, Wind Slasher, Gong Strike, Meteor Arrow, Tidal Strike, Charged Bolt.
- Skill Tags have been updated.
- Most Skills have had their resource costs rebalanced (mostly lowered).
- Execute, Arrow Storm, Black Hole, Summon Skeletal Army are no longer "long cooldown ultimate Skills". They're just moderate cooldown skills and have been toned down a bit.
- Chain Lightning and Boomerang travel more slowly.
- Spells that chain now deal less damage each chain.
- Lowered spell projectile tracking range for spells that track.
- Buffed Song and Curse effects.
- Added a new Armageddon Skill in the Sorcerer tree which summons 3 comets in a concentrated area that deal AOE damage.
- Meteor and Ice Comet fall faster now.
- Frozen Orb explosion damage and area has been reduced substantially.
- Mage Circle no longer teleports you.
- Fighters have 2 new Skills: Fighter Stance and Defender Stance. Fighter Stance increases movement and attack speed, but increases damage taken. Defender Stance does the opposite, and also periodically taunts nearby enemies while active. Additionally, each Stance augments Fighter Skills. Fighter Stance will augment them to be more offensive, and Defensive Stance will augment them to be more defensive/utility.
- Gong Strike health scaling has increased.
- Added a new Quake Skill in the Warrior tree which deals physical damage in subsequent explosions.
- Flame Strike now also shoots out a small Fireball upon swing, which also explodes and deals damage.
- Flame and Tidal Strike visuals have been improved.
- Shred skill now rapidly thrashes 3 times. Damage has been lowered to compensate.
- Shred effect which reduces armor and elemental resists has been reduced to compensate for above change. One cast of Shred should apply all 3 stacks of the effect if none miss.
- Wind Slasher no longer has egregious amounts of knockback.
- Replaced Execute in the Warrior tree with Quake.
- Fighter Skill Taunt has been removed.
- Warlocks Skills have been reworked a bit. Certain Skills can generate Soul stacks which last 5s. At max stacks, other Skills will become more powerful for as long as you keep up the stacks. For instance, Chilling Touch, Poison Ball, and the Curses can generate stacks. At max (5) stacks, Explode Minions will also deal Chaos damage in addition to the regular Fire damage, or Black Hole's AOE for the suction will double.
- Added a new Explode Minions Skill in the Warlock tree which explodes your minions to deal damage.
- Shaman Lightning Skills and Charged Arrow now apply a stack of Static to nearby allies upon cast. Each stack of Static provides percent Critical Hit chance and flat Mana Regeneration. You can have up to 10 stacks of Static.
- Increased Chain Lightning damage and mana scaling.
- Increased Lightning Nova mana scaling.
- Added a new Garden of Thorns Skill in the Shaman tree which damages nearby enemies based on your Energy, and also applies stacks of Thorns. Basic attack an enemy to expend a stack of Thorns to deal extra damage. Using the Skill also applies Inner Calm on self which increase Mana Regen.
- Reduced Totem spell damage. Lightning Totem is much weaker now.
- Rejuvenating and Astral Totem Health and Mana heal amounts have increased drastically.
- Magma Totem has been reworked to deal AOE damage to the nearest enemy rather than an AOE in an area around itself.
- Fire, Frost, and Poison Traps now apply Enflamed, Encased, and Entrenched, respectively. These effects trigger on basic attacks and deal damage in an area. They also apply their own unique effects.
- Increased Trap Skill damage.
- Bard Skills have had their visuals and sounds somewhat improved.

#### Quest Updates
- Updating starting armor set from the Prologue quest line to be level 3 instead of 1, and gave them slightly more useful stats.

#### Other Updates
- New Gateway Pearls have replaced the "per mob" Pearls. Quests have been updated to reflect this.
- Added a bunch of new Gateway Pearls. There is a new type of Gateaway that introduces "endless" waves. You will be able to craft them. Currently, there's an endless Blaze Pearl, Deeper Darker Pearl, and Undergarden Pearl.
- It is now possible to get certain enchantments on other items. Eg. Infinity on bows, Looting on Staves, etc. It is also possible to enchant shields and horse armor.
- Changed chat name colour to something brighter.
- Cosmic Foxes are now cageable.
- Increased the spawn rate of some Alex's Mobs.
- New Anvil Upgrade for Sophisticated Backpacks.
- Feather Falling now prevents farmland trampling
- Looting enchant also affects Vanilla experience.
- Infinity no longer requires a single arrow (tbh I don't know if it already is like this).
- Mimicream can no longer be used to duplicate items.
- Minecolonists should be able to kill passive animals more easily now.
- You can now teleport between Waystones with pets.
- Supplementaries Cages can now capture more animals (mostly from Alex's Mobs) and the failure message has been updated to make more sense.
- Money Mending cost has increased from 1 copper to 4.
- Advancements now how all criteria.
- Updated some sleep messages.
- Persistent Shop prices have been updated to better reflect rarity.
- Create Pressing and Cutting can now be done on stacks in bulk.
- Schematic Cannon delay has been tripled.

### Fixes
- Fixed Looming Shade giving more instead of flat.
- Localization fixes.
- Shaders are no longer on by default. I accidentally forgot to turn them off.
- Changed Machete recipe, which should fix a conflict as well.
- Nos Rune is now properly giving percent instead of flat Gear's Weapon Damage.
- Fixed one of the flat Gear's Weapon Damage stats giving percent instead.
- Hopefully fixed Hymns not providing Song damage buff.
- Fixed a messed up Runeword.
- Disabled using Nature's Compass in Blue Skies dimensions.
- Disabled the Unsettling Kimono.
- Removed instances of Reflect stat which should inifite loop crash.
- Players no longer finish their cast after they've respawned after a death if they were in the middle of casting something.
- You can no longer apply Souls to stacks of items.
- Fixed an issue where Skill charges were affected by cooldown more than they should have been.
- Fixed an issue where getting reduced cooldown would make some spells never finish cooling down.
- Summons should no longer kill fish.
- Fixed an issue with Profession blocks.
- Fixed an issue where certain Positive effects were not applying such as Song Damage from Hymns. Actually they were technically applying, but they were always level 1 and permanent once cast...
- Fixed server issue with colonists not working when further away.
- Fixed an issue where Arrow Barrage was using Arrow Storm damage scaling... It was unintentionally too strong.
- Orb of Imbalance no longer upgrades from Common to Mythic.
- First attempt at fixing Blue Skies weapons not doing full damage. As of now all Axes and Swords should work...
- Some changes were made that should help with tooltip overflow.
- Disabled Stellarity Altar crafting for now.
- Miner Mobs should no longer be able to break blocks in Maps.
- Fixed stats centering weirdly in GUI. Might affect Item Tooltip centering too, but that's okay.
- Fixed Sweet Lance being a sword.
- Polymorph is fixed.
- Gateways not giving proper experience has a workaround.
- Fixed an issue where X per Y stats like from Diamond Will/Diamond Grip were not applying properly.
- Totem Duration stat is fixed.
- Cases where EXP was not earned due to anti-cheese mod has been fixed.
- Movement Speed stat crash has been fixed.
- Picking a hotbar spell now returns you to Skill Gem screen.
- Fixed Maps showing up as ???.
- Fixed an issue with Villagers not working properly from far away.
- Removed Sculk Transmitter from chest in Deeper Darker as it was causing crashes.

### Mod Updates
- Updated Mine and Slash, AmbientSounds, Embeddium, Kotlin, Patchouli, Gateways to Eternity, Chunk Sending, Moonlight Lib, AttributeFix, Collective, CraftPresence, Create Additions, Curios, Enchantment Descriptions, Enhanced AI, Friends and Foes, Kobolds, MineColonies, Resourceful Lib, Structure Gel API, Stylecolonies, Placebo, Highlighter, Curios, CraftTweaker, Mutant Monsters, Sophisticated mods, Supplementaries, Supplementaries Squared, Aquaculture, FLAN, FTB Quests, GeckoLib, ModernFix, Puzzles Lib, Supermartijn's Core Lib, Xaero's, and a bunch more...
- Added Torchmaster.
- Added Apothic Attributes.
- Added Universal Enchants.
- Added Waystones Teleport Pets.
- Added Packet Fixer.
- Added Better Chunk Loading.
- Added Not Enough Recipe Book - removes recipe book for performance.
- Removed Majruszs Accessories - has a mixin issue with Mine and Slash, messing with Professions.
- Removed Easy NPC.
- Removed World Border.
- Removed TownTalk.
- Removed Giacomo's HUD Configurator.

## [0.2.1c] - 2023-11-21

### Reminders
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Fixes
- Fixed Mine and Slash serverconfig error.

## [0.2.1b] - 2023-11-21

### Reminders
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
- Changed Strength to provide Weapon Damage % instead of flat.
- Increased Frozen Orb tick rate and lowered damage to compensate.
- Increased Frozen Orb cooldown.
- Changed default Spear to the Vanilla Trident.
- Started Supporter Gems are now uncommon.
- Reverted Quest visibility change.
- Removed Diamond and Netherite Coin rewards from Bountiful.
- Increased rarity of higher tier Coins in Bounties.
- Increased experience penalty when over or under leveled. Before, a 5 level difference meant getting 25% less experience. You now get 50% less experience.

### Fixes
- Fixed Prestissimo, Power Surge, and Protection have a max level of 1.
- "Fixed" Frozen Orb not working properly. It was technically working but it was moving so fast that it wasn't working as intended.
- Disabled Explorer's Compass working in Blue Skies due to memory leak.
- Disabled Blister Bombs in maps.
- Fixed custom Support Gem, Aura Gem, and Map Affixes not applying...
- Fixed broken Bounties causing players to have tens of tasks for some Diamond Coins.

### Mod Updates
- Updated Clickable Advancements, Mine and Slash.

## [0.2.1] - 2023-11-21

### Reminders
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
- Core stat slight rework:
- Strength now provides Weapon Damage, Summon Health, Critical Damage, Health Regen, Armor instead of Weapon Damage, Health Regen, Armor.
- Intelligence now provides Spell Damage (NOT SKILL DAMAGE), Health Strength, Summon Damage, Mana Regen, Magic Shield instead of Mana, Mana Regen, Magic Shield, Magic Shield Regen.
- Dexterity now provides Projectile Damage, Attack Speed, Critical Hit, Energy Regen, Dodge instead of Energy, Energy Regen, Dodge.
- Increased base Magic Shield Regeneration stat by 60%.
- Reduced the projectile speed of Poison Blast, Ice Shard, and Boomerang by 25%.
- Reduced the projectile life ticks of Poison Blast and Boomerang by about 40%.
- Lowered the drop rates of some Majrusz Accessories.
- Changed Enhanced Visuals values to be less intrusive and also changed the textures to something more Vanilla-friendly.
- Reimplemented the Gamechanger Talent True Hit.
- Added Nature's Aura weapon compat with Mine and Slash.
- Gong Strike stun is now 0.5s instead of 0.25s.
- Reduced instances of Cast Speed.
- Updated some Alchemy recipes to use more of the farming materials. Healing potions are also generally easier to craft now since they no longer need Nether Wart.
- Gateway implicit buffs per wave to mobs has been reduced DRASTICALLY. Instead of having twice as much health and damage by wave 4, it's now 1.2x.
- Introduced new Illager and Ice Gateway Pearls that can be used to summon the Invoker and certain mobs from Aquamirae for Act I and Act III.
- Some Gateway Pearls are now provided in the Campaign.
- Cheapened the crafting cost of Gateway Pearls.
- Added some particle effects to the negative Mine and Slash effects. Also made existing ones more obvious.
- Mob scaling has increased greatly, but damage has been lowered early on.
- Changed Act III Maze Mother quest area. You no longer need to kill the Maze Mother to continue the quest line.
- Split Act III Waystones quest into Warp Stone (Act I) and Waystone (Act III).
- Updated some Act IV quest descriptions.
- New Traveler's Titles.
- Doubled the pool of available map affixes and rebalanced some of them.
- Added new Mob affix Evasive.
- Slightly reduced spawn rate of Dungeons Arise structures.
- Updated the description of the Alchemist quest in Act IV explaining the projectiles immunity.
- Changed Handcrafted Plate and Sheet recipes, and Sophisticated Backpack's Restock Upgrade to avoid recipe conflicts.
- Cheapened the Sophisticated Backpack and Storage upgrades by an entire Stone rarity.
- Upped Lemurian spawns.
- Quintupled Mutant Mob spawns.
- Reduced Magma Cube EXP and loot drops.
- Added new Persistent Trader items.
- Adjusted Profession material drop rates to be slightly higher.
- Increased energy cost of bows/crossbows.
- Increased mana recovery of bows/crossbows.
- Quests now only show when startable rather than having their dependencies visible.
- Effects that modify Vanilla stats like attack speed or movement speed no longer override eachother.
- New Attack Speed stat.
- Added some new Attack Speed affixes.
- Warrior now has an Attack Speed passive instead of Armor Penetration.
- Added some Attack Speed nodes to the Talent Tree.
- Doubled Block Energy cost.
- You can no longer find Adventurer's Guides in chests (I don't know if there are any other sources).
- Improved Skill and Spell tooltips. FYI Skills are all actives on the Classes tree, whereas Spells are only "magic" Skills such as Fireball, Meteor, Magma Totem, etc.
- Improved Puzzle Dungeon loot table greatly.
- Reset Potions are now brewed via Alchemy Profession rather than normal crafting. They have also been added to the Professions quest line.
- Runes that provide resource on hit for the weapon slot have been changed. The Mana one now gives Magic Find, Health gives Gear's Weapon Damage, and Energy gives Attack Speed instead.
- Reduced base weapon damage.
- Increased basic attack damage multiplier on weapons.
- Chocobos can once again fly.
- You can no longer use Endersoul Hand in Maps.

### Fixes
- Fixed some misleading descriptions in the Prologue quests, and added some warnings for some of them.
- Fixed starting perks missing names.
- Fixed missing icons for Shatter and Shock Proc Chance Talents.
- Fixed the starting area for The Staff, The Bow, The Axe, and The Spear in the Talent Tree. I missed some early connection points.
- Fixed a passive skill increasing mana cost instead of reducing it.
- Fixed a missing connection to an AOE node in the top left.
- Fixed X per Y Gamechanger Talents being backwards.
- Fixed Quickstack having keybinds which messed with some other keybinds.
- Fixed some incorrect Alchemy recipe quests.
- Fixed none of the Enhanced AI configs applying. The config location changed...
- Fixed Maze Mother and Maze Captain drops.
- Fixed Mining and Farming not granting any XP.
- Fixed Frost Flower not using correct scaling.
- Quest item reward tooltips missing has been fixed.
- Fixed Runeword search crash.
- Fixed lanterns bugging out when placed as wall lanterns.
- Fixed Wraithlord unique giving 1% more maximum summons instead of +1.
- Fixed a Ultiminer quest not auto giving EXP.
- Ice Shard and Lightning Spear not doing damage should be fixed.
- Fixed some Skills being mislabeled as Spell, Ranged, or Melee.

### Mod Updates
- Updated Moonlight, Nature's Aura, Supplementaries, Textrues Embeddium Options, Aggro Indicator, Doggy Talents Next, Farsight, Kotlin for Forge, libIPN, MineColonies, Cuisine Delight, FTB Quests, Kobolds, Crabber's Delight, serverCore, AmbientSounds, Better Archeaology, BlockUI, Chat Heads, Connectivity, CraftTweaker, FLAN, Rubidium Extra, Should Surfing, Supplementaries, Smooth Chunk, FerriteCore, Login Protection, Neruina, PuzzlesLib, Sophisticated mods, Structure Essentials, YUNG's Better Ocean Monuments.
- Downgraded Majruszs Library and Accessories as there was a mixin conflict with Mine and Slash - some of the items will disappear.
- Added Not Enough Animations.

## [0.2.0] - 2023-11-13

### Reminders
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
- Added PlayCDU's server.
- Completely revamped the Talent Tree. It's now much larger and has 6 different starting points.
- You can now earn Talent Points from certain quests as a reward! It is possible to get 25 Talent Points this way.
- Classes now have passive skills. You get 1 point every 2 levels and they are allocated in the Classes GUI.
- Added a completely new Act IV, check out the Everbright and Everdawn and their mobs and dungeons!
- Campaign bosses now have unique stats to them. For example, the Wildfire in Act II has 50% of its Physical Damage converted to Fire Damage. You can see these stats in the relevant quests!
- Revamped Act III quest line - explore the Deep Ocean (enhanced by Aquamirae) as part of the quest line!
- Revamped Mine and Slash professions. A lot of the recipes have been reworked to use lesser, medium, and greater resources more appropriately, and experience has been increased for higher rarity crafts. Gathering skills are also more streamlined, no more needing to be level 41 to get max benefits out of mining Copper ore...
- Added 26 new unique items: 1 ring, 2 tomes, 1 axe, 2 spears, 3 daggers, 3 hammers, 2 shields, 2 totems, 3 bows, 2 crossbows, 1 sword, 2 boots, 1 necklace, 1 helmet. One of these items is very rare and powerful...
- Buffed totem spells.
- Starting icons are much more noticeable and have their own icon now.
- Skill damage has been lowered across the board.
- Doubled mana on hit from basic attacks.
- Increased base damage on weapons.
- Lowered base energy regen slightly.
- New Lightning Totem spell in the Shaman tree.
- Ice Shard now pierces enemies.
- New Ritardando spell in the Minstrel tree - a slow moving projectile that deals a lot of damage upon hit. Also slows enemies.
- New Prestissimo spell in the Minstrel tree - increase nearby allies attack speed, cooldown reduction, and energy regeneration.
- Song buffs now last 15s instead of 30s.
- New Protection spell in the Fighter tree - increase nearby allies armor and elemental resists.
- New Power Surge spell in the Shaman tree - increase your cast speed and critical damage.
- Increased cost of crafted Waystones slightly.
- Gong Strike stun has been lowered to 0.25s instead of 3s.
- Gong Strike health scaling has been reduced.
- Maps are now available starting at level 60. You need a Dragon Head to craft the Teleporter.
- Added a persistent trader available in the pack via the shop block (see quest in Act II). You can buy things such as some hard-to-find quest items, Profession's materials, basic blocks, etc.
- Added the ability to gamble away Netherite coins for a random unique (unlocked later in Campaign).
- Greatly improved server-side performance.
- Increased mob stats and damage per level scaling.
- Improved Classes GUI.
- Increased summon mob health scaling per level.
- Lowered Pillager damage by 20%.
- You can now interact with crafting tables in claims.
- Increased the frequency of some structure spawns (especially Pillager Outposts).
- Removed fish weight.
- Changed the first Illager quest to something even MORE manageable than last time.
- A bunch of new Majrusz's Accessories have been added.
- Increased Spice of Life food queue for diversity from 32 to 64 foods.
- Increased gem drop rate (the socketable ones).
- Rebalanced support gems.
- Spell mana costs have been rebalanced and now go up per level instead of down. The mana cost at max level is about the same as it was before, so it should be much easier early game.
- Players have 25% more base mana regen.
- Added modded ores to Mine and Slash mining experience table.
- Added pumpkin and modded crops to Mine and Slash farming experience table.
- Map rewards have been nerfed.
- Totems and Chilling Field no long knockback.
- Updated some FLAN default permissions.
- It takes 10s instead of 15s to get a FLAN block.
- FLAN depth is now set to 20 (note that the depth changes dynamically as you dig).
- Warp Stones now have a longer cooldown.
- Lowered recipe cost of the Disenchanter.
- Reduced rewards from Shiraz Palace and Keep Kayra.
- Trading with players now requires players to be closer to each other.
- Seagulls can no longer steal your lunchboxes.
- Chocobos, wolves, horses, and various other passive mobs can now be caged.
- Levels are now shown by default on any server in the scoreboard. Thanks to RickieGamer for the datapack!
- Lootr chests are now breakable by default (except on official server).
- You can receive Ambergris from Bountiful bounties now.
- Colonies citizens now do more damage.
- Colonists no longer require potions or Cuisine Delight foods to recruit.
- Various new quests and quest updates.
- Some Mine and Slash dungeons have been made less harsh - thanks Michu!
- Disabled Incendium and Stellarity special weapons from dropping.
- Increased Chocobo health to make them less prone to accidental deaths.
- Re-enabled the Demagnetization Coils.
- Dodge rolling now has some invulnerability frames. You get 4 ticks of invulnerability out of the 8 tick roll.
- Rebalanced some of the existing uniques.
- Mining profession now gives ore blocks rather than the ingots straight up. They now require smelting or blasting (compatibility with Create).
- Minecolonies mining lucky ore chance now has a chance to give Mine and Slash mining profession resources and Create Zinc Ores.
- Added Mine and Slash items to almost every vanilla chest loot table!
- Changed Mine and Slash Profession station recipes.
- Minecolonies Supply Camps and Ships no longer spawn in chests.
- Plate and Leather armor now give a small boost to health.
- The following changes are a bit of a refresh to existing negative and beneficial effects, as well as my first passthrough for improving class identity. This time, I've focues on the Mage, giving a bit more reason to go Fire vs. Frost other than RP. I will eventually go through other classes too.
- Wounds effect reduces healing received rather than healing dealt.
- Charm effect has been buffed.
- Blind no longer reduces attack damage and speed by 100%. It now reduces accuracy by 33% and attack speed by 25%.
- Slow effect attack speed reduction has been increased from -10% to -25%.
- Frost skills now apply Slow effect. The duration varies depending on the skill.
- Fire Skills now apply Elemental Weakness effect. The duration varies depending on the skill.
- Elemental Weakness effect reduces elemental (not Chaos) resistance by 10%.

### Fixes
- Fixed Stoneborn not spawning frequently enough in The Undergarden.
- Fixed Steady Hand giving crit damage twice.
- Fixed mobs reflecting a bunch of damage even without Reflect affix (disabled Zombie Bite).
- Fixed spell tooltip support slot not updating properly.
- Fixed issues where players could allocate points into the negative.
- Fixed issues where some spells were not casting properly (Hymns).
- Actually fixed mob spawns this time.
- Fixed Summon Zombie spell datapack not applying.
- Fixed a mistyped stat for a lightning mob affix.
- Fixed an issue where you could have multiple of the same Support Gem equipped.
- Fixed some missing localization.
- Fixed some side quest issues.
- Disabled Necromancers from raids, and disabled their spawn.
- Fixed an issue where custom Bountiful bounties were not applying.
- Neptunium Axe is now considered an axe.
- Hammers can be used for spell casting now.
- Fixed an issue where Chorundrum was considered an axe.
- Reduced experience gain slightly.
- Mine and Slash packs have been fixed.
- Fixed profession blocks not being dropped when destroyed.
- The pack now comes prepackaged with Complimentary shaders.
- Fixed fishing not dropping lesser/medium/greater fish.
- Fixed salvaging profession giving no experience.
- Fixed Totem of Illusion being useable in maps.
- Fixed Ender Dragon not spawning.
- Fixed a bug where some Mine and Slash effects were modifying Vanilla stats by 100x the amount they should have been (eg. 2000% attack speed instead of 20%).

### Mod Updates
- Updated Mine and Slash, Citadel, Supermartijn Core Lib, Supplementaries, Embeddium, Library of Exile, Moonlight, Domum Ornamentum, Easy NPC, FootprintParticles, ModernFix, Simple Magnets, MineColonies, APT, BlockUI, Bookshelf, CreativeCore, Cupboard, DeeperDarker, Domum, Dungeons Arise, Embeddium, Enhanced Visuals, Friendly Fire, Friends&Foes, Goblin Traders, Handcrafted, InsaneLib, Jade, NBTac, Resourceful Lib, Should Surfing, Sophisticated mods, Structurize, Supplementaries, Xaero's, Lightman's Currency, AmbientSounds, Curios, IPN, Polymorph, FTB Quests, CraftPresence, Terralith, Rubidium Extra, Collective, Combat Roll, choiceTheorem's Overhauled Village, GeckoLib, Incendium, Let Me Despawn, Puzzles Lib, Customizable Elytra, AttributeFix, Axes Are Weapons, Create, Illager Invasion, Item Filters, Kobolds, Refined Storage, Steam Rails, The Undergarden, Tips, Iceberg, CraftTweaker, AmbientSounds, Village Spawn Point, Death Backup, Chat Heads, Bells and Whistles, Crabber's Delight.
- Added Server Core.
- Added Blue Skies.
- Added Structure Gel API.
- Added Easy Magic - improves Enchantment Table.
- Added Doggy Talents Next.
- Added Beautified Chat.
- Added Air Hop - adds an enchantment that lets you jump multiple times.
- Added Comforts - portable beds!
- Added Refined Cooking - adds blocks that allow Refined Storage and Cooking for Blockheads to interact with each other.
- Added Nature's Aura - test run of a new magic-based tech mod.
- Added Saturn.
- Added No Telemetry.
- Added Aquamirae.
- Added Oculus.
- Added Quickstack.
- Re-added Neruina.
- Removed APTweaks Spawn.
- Removed DynView.
- Removed FallingTree.
- Removed Timestamp Chat.
- Removed Staaack.
- Removed YUNG's Better End Island.
- Removed RevampedWolf.
- Removed Lootbeams (for now).
- Removed Create Structures (for now).

## [0.1.2] - 2023-10-08

### Updates
- REMINDER: Back up your Xaero's folders and your options.txt file just in case! Also, if you start the game and you have like 3 different things bound to the "R" key, my custom keybinds probably didn't apply for you. You can find them in /config/defaultoptions!
- Added Meowstard Cat's and United's server to the list of default servers.
- Summoned creatures HP and Damage now scale with skill level.
- Disabled Glare spawns.
- Increased mage-related spell damage scaling a bit.
- Changed Frozen Orb to travel in a straight path and then explode dealing excess damage at the end.
- Changed Poison Ball to fire 3 slow homing projectiles that deal damage on impact.
- Lowered Creeper Overhauled Creeper spawn rates.
- Further reduced spawn rate of some structures.
- Lowered the cost of reset potions.
- You now get a Gold Wallet from the Prologue quest.
- Weakened the Mutant Skeleton a bit more, also nerfed other Mutant mobs slightly.
- Lowered spawn rates of Mutant mobs.
- Improved loot and experience rewards from Mutant creatures.
- Telepasses are cheaper to craft.
- Changed the Alchemist quest of Act I to something more manageable.
- You no longer need to hold a ranged weapon to summon the Wolf.
- Taunt now has a max level of 1.
- Reduced reflect damage from reflect mobs (also have been renamed to Reflecting) from 15% > 1%. Gave them increased armor to offset. Also, summon attacks should no longer hurt the caster if the mob has Reflecting.
- Reduced mob scaling per level a bit.
- Increased item drop rates by 25%.
- Added new lightning mob affixes (missing for some reason), and changed weightings of mob affixes a bit.
- Removed Loot Chests from Goblin Traders, didn't seem to work properly.
- Re-enabled explosions. This change does not apply to the Official Server.
- Gem Shop quests are now only visible once startable.
- Act I Gem Shop is now dependent on the Act Lost Page quest rather than The Mastermind.
- Disabled Cockroach spawns and lowered Crow spawn rate.
- Villagers and Piglins now are default to have MobGriefing true (only really used on Official Server).
- Villages and Pillager Outposts are now much less frequent.
- Reduced frequency of special moons.
- Reduced spawner spawn rate in Dungeons Arise dungeons.
- EXPERIMENTAL: implemented some performance mixins.

### Fixes
- Fixed an issue where vanilla mobs were not spawning. Should resolve the Gateway Pearls failing as well (mostly).
- Fixed a bug where resource gain on hit was not working.
- Fixed a bug where skill tooltip was not updating properly as you leveled it.
- Fixed Craft Arrows not showing up in tree.
- Fixed trap doors all opening at once.
- Item Souls doing weird things should be fixed or at least log spam is gone.
- Disabled the ability to place enchanted books on the ground.
- Fixed some items in the prologue quest missing item names.
- Fixed an issue with Mapper Bounty decree rewards.
- Hopefully fixed issue where attacks sometimes only register on one entity per swing.
- Fixed a money dupe bug.

### Mod Changes
- Updated Mine and Slash, Enhanced AI, Moonlight, Repurposed Structures, Easy NPC, CreativeCore, Sky Villages, Supplementaries.
- Replaced Vanilla Zoom Mod with WI Zoom.
- Added Friendly Griefing.

## [0.1.1] - 2023-10-06

### Updates
- Chaos Totem meteors fall at a greater speed.
- Added some level indicators in the Classes GUI.
- Silverfish experience and loot rewards have been toned down.
- Made some changes to AI to improve server-side performance in mob-dense areas.
- Lowered Alex's Mobs spawn rates.
- Lowered energy cost of weapons, in particular the staff.
- Re-added Craft Arrows in the Hunter tree. Forgot to include this last update.
- Buffed Hymn of Vigor, and lowered the values a bit of the other songs.
- Mob and item spawns should be limited now based on player count which should greatly help server performance.

### Fixes
- Fixed a bug where you couldn't specialize into 2 trees.
- Fixed issues regarding stat souls not generating items properly, and custom weapon types not dropping.
- Fixed custom weapon types not dealing the correct amount of damage.
- Fixed Ice Shard having the incorrect damage scaling.

### Mod Changes
- Updated Supplementaries.
- Added Embeddium (testing).
- Added Adaptive Core, Items, and Spawn.
- Removed Guard Villagers.
- Removed Serene Seasons and SeasonHUD.
- Removed Neruina.

## [0.1.0] - 2023-10-05

### Updates
- New class-based system. Ascensions and Skill Gems have been combined. You now can select a class and level up your spells. On the class tree there will also passive stats (similar to Ascensions) that you can put points into for bonuses (not yet implemented). Support and Aura gems are still a thing, and can be attached to learnt spells to augment them. Higher level in the spell = more slots.
- Spell scaling has been adjusted, mage and ranger spells should feel stronger early game.
- Finished Act II-Act IV quests.
- Energy cost has increased for basic attacks, and there is an additional small penalty for hitting more than one mob at a time.
- Mana regained on hit from basic attacks has increased.
- Updated prologue quest to be a bit shorter, and added the extra pages as lost pages to Act I.
- Lowered the spawn rate of various structures.
- SOL Apple Pie health rewards are now more rewarding the more diverse you are with your food.
- Toned down Gateway rewards.
- Lowered experience rewards from Act I slightly.
- Very slightly increased mob strength scaling per level.

### Fixes
- Fixed some missing M&S localization.
- Damage to allies no longer knocks them back.
- Removed buried treasure maps from chests. They were causing crashes.
- Fixed Lootbeams render distance.
- Fixed missing Gateway recipes for the medium-sized pearls.
- Disabled Bison spawns.
- Fixed an issue where level experience penalty was not applying.
- Fixed missing LAN button.
- Fixed some overlapping default keybinds.
- Fixed the missing icons on custom weapon souls.
- Fixed message spam on login and death.
- Easy NPCs are very difficult to kill now.

### Mod Changes
- Various mod updates.
- Added FootprintParticles.
- Removed Daily Rewards.