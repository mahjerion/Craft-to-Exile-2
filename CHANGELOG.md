# Changelog

## [1.0.6] - 2025-07-24

### Reminders
- Always back up your world saves, Xaero's folders, and your options.txt file just in case!

### Updates
- Added a new useable item that teleports you and your nearest allies to the Boss Teleporter block when in a map. This item is removed when you leave the map dimension. Thanks DubleDice!
- Increased bonus experience for partying up from 20% to 50%. With 2 players, the old behavior was 120% of experience divided by 2 = 60%. Now, it's 150% split to 2 = 75%.
- Increased ailment chance on a lot of skills that have it as a stat innately. Especially multi-hit skills.
- Reduced the area in which each individual ice chunk can hit by 33% for Glacial Phoenix.
- Ice Comet damage reduced by roughly 5%.
- Lowered number of heart particle effects on Frost Nova.
- Phase Dive mana cost reduced.
- Modified Fury icon to be a little different from Combo Extender icon.
- Wounds effect now applies +15% chance to receive Bleed effect and -10% Bleed Resistance instead of -50% Heal Effect on self (mobs don't really heal).
- Hunter's Potion no longer requires ranged weapons to use.
- Hunter's Potion cooldown reduced from 45s to 20s.
- Vexes now always spawn at common rarity.
- Split Defenders of the Nether into 2 quests, one for each boss. Added images to show what the structure looks like (thanks Kythulu!).
- Added a new quest going over Kobold Armor Trims in Act I.
- Added a new main-line quest in Act II for the Netherite Upgrade/Remnant Bastion.
- Quartz now gives more mining exp.
- Supplementaries Flower Box simple mode has been disabled - it can now contain more than one tall flower item per block.
- Turned off flower rendering in Xaero's maps by default.
- Changed weightings of Garnet and Amber blocks so they're a bit less strong.
- You can no longer get Corrupted Saplings or Corrupted Slime Balls. The Garbush Seed is obtainable through Amber and Garnet blocks.
- Removed Bonwiltia, changed Dyespria Seed drop to Dyescrapia, and moved Dyescrapia + Acidripia Seed drop from Amber to Garnet Block.
- Revamped the Sniffer Flowers quest line to reflect the above.
- Added conversion recipes that turn cobble and sand variants to cobblestone/sand. Thanks Sainguin!
- Disabled Red String Container and Tiny Planets due to exploit.
- You can now craft normal Waystones and Mossy Waystones with special recipes.
- Reduced the cost of the craftable Waystone drastically.
- Increased Bounty Slip rewards by double.
- Nerfed map salvaging output.
- Reduced cost of Kami Treat.
- Removed ALL ALLIES option in MNS Features hub as it doesn't accomplish what we wanted it to and it causes a ton of confusion.
- Updated MCA guard list so they target Born in Chaos mobs as well. Thanks Kuktar!
- Official servers now wipe the map/Harvest/Obelisk dimensions on a daily basis thanks to Poe.

### Fixes
- Fixed an issue where buttons and such were not interactable in Should Surfing mode. The camera now also properly decouples itself from the player unless holding a weapon or throwable.
- Fixed an issue where the chaos/corrupt stats that give phys as extra elemental damage change was not implemented correctly.
- Fixed an issue where Awful Ghast would sometimes not drop anything.
- Removed remnant button in settings menu.
- Unbound ChatPlus peek key due to conflict.
- Removed erroneous command block in Sewer2 map.
- Fixed a spot in Mansion map where mobs were getting stuck.
- Moved Harvest spawner in Aztec which was causing mobs to spawn in the wall.
- Fixed innate golem spell chance not working.
- Fixed Daw and Bri Rune drops in Blue Skies dims.
- Ferrous Wroughtnaut quest should be more consistent to complete now.
- Caught in the Web quest should be more consistent to complete now.
- Fixed missing Hemorrhager icon.
- Fixed level 80-99 jewelry profession recipes containing air.
- Fixed Windfury Runeword Cyclone being cast by enemies instead of user.
- Fixed no food stats on Cabbage Wrapped Elder Guardian.
- Disabled some MCA customization which was causing issues.
- Fixed a bug where Night Lich tower wasn't spawning.
- Fixed a bug where Unique drops were not respecting the minimum level requirement.
- Fixed Phase Dive knocking back (it should not).
- Fixed incorrect naming for Leech gems in Campaign Shop and rewards.
- Removed Offensive tag from Blessed Aim (shouldn't be there).
- Made some changes to the Obsidilith Arena that should alleviate some pain points on generation.
- Hopefully reduce Talent Tree lag.
- Fixed Nature Dungeon Uber Arena spawn.
- Removed incorrect Sharpening Stone gear crafting recipe.
- Fixed incorrect quest description for Harvest event.
- Fixed Lightning Golem casting Frost Nova.
- Fixed some vector stuff still happening even when KB was disabled.

### Mod Updates
- Updated Crafting Tweaks, Default Options, Dungeon Realms, EnhancedAI, EntityJS, FancyMenu, GeckoLib, Inventory Essentials, MCA, Mine and Slash, More Sniffer Flowers, Remnant Bosses, RoE Weapons, Sophisticated Backpacks, Xaero's.
- Added EMI Ores.
- Added Dimensional Threading.

## [1.0.5] - 2025-07-18

### Reminders
- Always back up your world saves, Xaero's folders, and your options.txt file just in case!

### Updates
- Added Remnant Gateway Pearl. Mentioned it in the quest.

### Fixes
- Fixed crash.
- Fixed incorrect lang for Ignite Explosion.

### Mod Updates
- Downgraded Waystones.

## [1.0.4] - 2025-07-18

### Reminders
- Always back up your world saves, Xaero's folders, and your options.txt file just in case!

### Updates
- Minor change but big impact: % x stat gained as y stat now has proper priority in calculations. This means something like Mantra, which grants % Mana gained as Flat Physical Basic Attack Damage no longer is calculated at the same time as % Health gained as Mana (thereby losing out on the bonus from Health). The general order (from first calculated to last) is: stats that scale from or into resources (Health per Mana, Armor per Mana, etc.) > general non-damage stat changes (includes defenses, regen, attributes) > damage stats, even if they scale off of Resources (Skill Damage per Magic Shield, Weapon Damage per Health, etc.) > functional/back-end stats (Draw Speed per Attack Speed, Weapon Skill Cooldown per Attack Speed).
- Archeology underwent an overhaul thanks to councilfarciminis2. Loot tables now include modded and Mine and Slash materials and should be more rewarding.
- Added server-side blacklist for summon targeting. Allays and Armor Stands are included.
- Added recipes for up to rare RoE weapons.
- Atronach unique is now a Tome instead of a Staff.
- Corrupted/Chaos stats that convert phys to an element now give gained as element instead.
- Battery Support Gem now also grants a penalty to leech effects caused by the supported skill.
- Added 2 new corrupts. Magic Find for rings, and Increased Quantity for necklace.
- Added 1 new jewel corrupt which gives MF and IQ.
- Added 2 new Augments: Critical Strikes and Critical Magnitude, which increased Critical Hit and Damage respectively.
- Most sources of Magic Find have increased.
- Gear drop rate increased by 25%.
- Mob despawn range in maps is higher, meaning they won't despawn unless you run further away.
- Map completion buffer has increased, making it a bit easier to reach 100% completion.
- Threshold for completion rarities has decreased, making it easier to reach Mythic, etc.
- Mob damage formula has been changed very slightly, resulting in increased mob damage at lower levels but should be roughly the same at high levels.
- Increased Obelisk loot rewards
- Harvest maps drop a bit less frequently.
- Increased Harvest mob spawns.
- Increased spawn rate of Woodland Mansions.
- Made a change that should cap the amount of damage your gear can take per hit, which should alleviate early game armors being blown up in one hit.
- Clarified Harmony Gamechanger.
- Frost Trap no longer stuns enemies with each pulse, but still stuns when the enemy is hit after receiving Encased.
- Frost Trap damage reduced to be more inline with what other traps are dealing.
- Crusader auras should now show the effect correctly.
- Juggernaut's Undeniable no longer gives Accuracy > Attack Speed, it now gives the user a chance to proc Grapple on crit.
- Slowed down Ossukage phase 2 greatly.
- Added 3 new craftable Waystone variants.
- Increased Mimi client sound volume.
- Blood Moon mob spawn rate lowered greatly.
- Increased kill experience gain by 33%, back to 1.0.0 rates.
- Increased mob spawns on official servers.
- Disabled specialized moon events on the official servers.

### Fixes
- Fixed Tridents sometimes being tagged as Trident type.
- Fixed the cool armors being soul cleanable.
- Fixed incorrect lang on foods for real this time.
- Fixed Lv. 100 jewelry crafting issue.
- Fixed Dimension Rune drops being bugged.
- Fixed FancyMenu log spam.
- Mowzies Mobs Spear can now have proper enchantments.
- Fixed summon targeting AI - they'll no longer ignore neutral enemies if they're angered.
- Fixed missing localization.
- Fixed Cursed Spear not being 2-handed.
- Fixed Gateway spawns.
- Fixed Nether Keeper and Awful Ghast drop rates for quest completion.
- Fixed missing model for Order of Despair unique.
- Tried fixing some broken line breaks in enchantment descriptions.
- Fixed Sculptor quest task requirements.
- Fixed inaccessible chests in the Victory Frigate.
- Fixed some Food Diversity milestones being wrong or missing.
- Fixed some stat localization inconsistencies regarding Attack Speed.
- Fixed potato exp bug.
- Fixed Remnant Saber not having weapon type.

### Mod Updates
- Updated Balm, Entity Culling, Entity Loot Drops, Inventory Essentials, Lightman's Currency, Mine and Slash, Packet Fixer, RoE Weapons, Simple Backups, Skin Layers 3D, Waystones.
- Updated Forge.
- Removed Controller Support Mod - I'll leave it as optional and keep all the information on setting it up on the wiki.

## [1.0.3] - 2025-07-15

### Updates
- Check out the CTE2 equivalent to POB https://cofeiini.github.io/cte2-planner/ by Lunia! It can only do Talent Tree planning, but this is massive! Huge props to Lunia and co.
- Added an additional Official NA Server Harrogath to the default server list. You'll only see this on a fresh install. For those of you just updating an existing instance, the IP is: crafttoexile2-harrogath.g.akliz.net
- We now have controller support! Please try it out and let me know how it is. Note that using controllers is NOT compatible with third-person view. https://github.com/mahjerion/Craft-to-Exile-2/wiki/Controller-Support
- Added a new Lv. 30 Support Gem: Battery! This gem grants Skill Damage based on your Magic Shield but has a higher Mana multiplier.
- Flicker Strike now targets the nearest enemy. If there are no enemies, it will teleport you straight. I made this change to differentiate it from some other movement skills. Also, it's more like PoE hehe.
- Corporeal Respite max level is now 8 instead of 16.
- Corporeal Respite no penalty to bleed damage taken has decreased.
- Chronomancer skills no longer require Mage Weapons.
- Arrow Totem arrow stays out 25% less duration - it flies 25% less distance.
- Brutalizer stat now shows the max amount you can have.
- Gateways now have a smaller radius for spawning mobs (no more mobs spawning on high ceilings) and will leash mobs back to the Gateway if they go 16 blocks out instead of 32 blocks out (no more witches that run off into the sunset).
- Added some sus blocks to the map reward rooms.
- Reduced mob count and rate in Obelisk and Harvest arenas.
- Act Gateways now have a 2 minute cooldown period, per player.
- You now get a Small Passive Reset Potion in the Prologue chapter.
- Backpack side quest now requires a Diamond Backpack instead of iron.
- Improved introduction to Runeword in Prologue chapter to clarify requirements.
- Act III quest where you need to find the Ice Maze no longer requires you to also find the deep frozen ocean biome.
- Made some hobby quests easier to complete.
- Improved description for Palette.
- Added descriptions to all the new compat food buffs that give Mine and Slash stats.
- Summon AI has been further improved. They can now trudge through water and swim.
- Backpacks now respect the autosalvage rules when using the button that takes from chest into backpack.
- Harvest and Ancient Obelisk maps now go into the Mine and Slash Master Bag.
- Improved Crafting Station text and swapped the start and stop icons so it's more intuitive.
- Salvaging Station no longer shows an empty slot that does absolutely nothing.
- Changed default keybind for build showcase to Ctrl + I so it doesn't overlap with magnet.
- Improved Curio slot visibility for Necklaces and Rings.
- Collapsed Body and Elytra Curio slots.
- Updated textures for Lightman's Currency wallets that were missing the updated textures.
- Botania Pixies no longer give experience and loot.
- Doggy Talents Doggy health increased by 25%.
- Quiver is now hidden from HUD by default.

### Fixes
- Fixed Siphoner missing localization and icon.
- Fixed Combat Talent missing localization.
- Fixed Rallying March missing localization.
- Fixed Infection missing localization and icon.
- Removed unused Combo Finisher effect.
- Fixed some Watcher Eye affixes missing localization.
- Fixed Bountiful rewards on servers.
- Fixed a bug where Gateways were spawning out the wazoo.
- Fixed Raging Dragon sound file being incorrect.
- Fixed Profession crafting quest referencing old recipe.
- Fixed an incorrect Bountiful objective involving the Bluebright Stick.
- Fixed a bug with Gear Crafting where Charoite and Diopside were not registering in the recipes.
- Old Create tip has been removed.
- Fixed Void Blossom spawning in Overworld.
- Fixed a spot in one of the Harvest arenas where mobs could get stuck.
- Fixed an issue where summons would beat everything up.
- Auto-salvaging no longer gives Rested Combat Experience or use up Rested Profession Experience.
- Fixed up some Doggy Talent quest descriptions.
- Fixed an issue where client config for effect bar GUI was incorrectly affecting spell hotbar GUI.
- Fixed an issue where when in a MnS party, your own damage numbers would be shown in duplicate.
- Fixed Botania impossible repeatable quest.

### Mod Updates
- Updated Advanced Team, Entity Loot Drops, Fzzy Config, Lightman's Currency, Mine and Slash, Modern Fix, Shoulder Surfing.
- Added Controller Support Mod and Union Lib.