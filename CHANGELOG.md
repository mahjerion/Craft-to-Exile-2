# Changelog

## [0.2.2] - 2023-11-21

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