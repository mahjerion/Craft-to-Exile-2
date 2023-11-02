# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2023-11-XX

### Reminders
- Back up your Xaero's folders and your options.txt file just in case! Also, if you start the game and you have like 3 different things bound to the "R" key, my custom keybinds probably didn't apply for you. You can find them in /config/defaultoptions!

### Updates
- Added PlayCDU's server.
- Completely revamped the Talent Tree. It's now much larger and has 6 different starting points.
- Starting icons are much more noticeable and have their own icon now.
- Classes now have passive skills. You get 1 point every 2 levels and they are allocated in the Classes GUI.
- Revamped Act III quest line - explore the Deep Ocean as part of the quest line!
- Revamped Mine and Slash professions. A lot of the recipes have been reworked to use lesser, medium, and greater resources more appropriately, and experience has been increased for higher rarity crafts.
- Buffed totem spells.
- Skill damage has been lowered across the board.
- Doubled mana on hit from basic attacks.
- Increased base damage on weapons.
- Lowered base energy regen slightly.
- New Lightning Totem spell in the Shaman tree.
- Ice Shard now pierces enemies.
- New Ritardando spell in the Minstrel tree.
- Gong Strike stun has been lowered to 0.25s instead of 3s.
- Gong Strike health scaling has been reduced.
- Maps are now available starting at level 45. You need a Dragon Head to craft the Teleporter.
- Greatly improved server-side performance.
- Increased mob stats and damage per level scaling.
- Improved Classes GUI.
- Ender Dragon has more HP now so it should be able to spawn.
- Increased summon mob health scaling per level.
- You can now interact with crafting tables in claims.
- Increased the frequency of some structure spawns (especially Pillager Outposts).
- Removed fish weight.
- Changed the first Illager quest to something even MORE manageable than last time.
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
- Dodge rolling now has some invulnerability frames. You get 6 ticks of invulnerability out of the 8 tick roll.
- Rebalanced some of the existing uniques.

### Fixes
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
- Fixed fishing now dropping lesser/medium/greater fish.
- Fixed salvaging profession giving no experience.

### Mod Updates
- Updated Mine and Slash, Citadel, Supermartijn Core Lib, Supplementaries, Embeddium, Library of Exile, Moonlight, Domum Ornamentum, Easy NPC, FootprintParticles, ModernFix, Simple Magnets, MineColonies, APT, BlockUI, Bookshelf, CreativeCore, Cupboard, DeeperDarker, Domum, Dungeons Arise, Embeddium, Enhanced Visuals, Friendly Fire, Friends&Foes, Goblin Traders, Handcrafted, InsaneLib, Jade, NBTac, Resourceful Lib, Should Surfing, Sophisticated mods, Structurize, Supplementaries, Xaero's, Lightman's Currency, AmbientSounds, Curios, IPN, Polymorph, FTB Quests, CraftPresence, Terralith, Rubidium Extra, Collective, Combat Roll, choiceTheorem's Overhauled Village, GeckoLib, Incendium, Let Me Despawn, Puzzles Lib, Customizable Elytra.
- Added Server Core.
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
- Removed Lootbeams (for now).

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