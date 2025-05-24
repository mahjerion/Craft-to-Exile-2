# Changelog

## [0.9.4] - 2025-05-24

### Updates
- There's a new Potion Quick Consume key that's by default set to Y. This is now mentioned in Taking On Work in Act I.
- Armor and Armor Toughness vanilla stats now grant 0.1% Gear Defense instead of 0.5% Armor. This is now mentioned in the Lost Page in Act III.
- Firing Kunai is now instant instead of requiring a charge up.
- Holy Fire's damage increased from 10% to 11% of your Max Health.
- Holy Fire's self-damage portion is now 33% of your Max Health instead of 40%.
- Proc Skills such as Blood Explosion, Cinder, Ignite Explosion, Immolate, Kinetic Blast, Profane Explosion, and Venom now have a built-in cooldown of 10 ticks instead of 5 ticks. This change was made to target the really low cooldown proc Skills which were just too overwhelming in terms of combat power.
- Reduced Holy Immolation's Immolate proc chance by 20% (40%->80% instead of 50%->100%).
- Hemmorhage's proc Blood Explosion on crit chance and Critical Damage reduced to 4% per stack, down from 5%.
- The below changes were made to make the Brawler feel more fluid and more rewarding for pulling off a full combo.
- Brawler Skills now have a base cooldown of 1.5s instead of 2s.
- Brawler Finishers have had their Weapon Damage Scaling increased by 50%. For example, Raging Dragon used to scale from 150%->200% with levels, now it scales from 225%->300%. Note that the Energy Scaling on Asura remains untouched.
- Eighth Gate self damage is now 35%->17.5% instead of 50%->25%.
- Overheat now grants 25% MORE Spell Damage per stack instead of 20%.
- Cooling off Overheat now recovers 10% of your Mana instead of 50% of your Weapon Damage.
- Mage Circle now grants 20%->40% MORE Skill Damage instead of 12.5%->25%.
- Shaman Lightning projectile Skills have had their damage increased by 5%.
- Cyclone damage increased by 10%.
- Hunter's Mark now has a max of 1 stack instead of 10. 
- Hunter's Mark now causes the enemy to gain 30%->60% Damage Received instead of 10%->25%.
- Increased Chronomancer damage across the board by approximately 10-20%. This change and the changes below are meant to make the Chronomancer a little more rewarding to use, as the setup is quite lengthy.
- Timewinder Alpha mode now causes enemies to take 50%->100% more lightning damage taken instead of 25%->50%.
- Chronobreak Alpha + Beta mode resistance decrease is now 20%->40% instead of 15%->30%.
- Corporeal Respite Bleed Resistance penalty is now -50%->-25% instead of -60%->-30%.
- Tome Offhand Physical Resist increased by 33%.
- Chaos stat which gives Damage Reduction now gives Physical Resist.
- Added a new suffix that can appear on Jewelry and Offhands that gives Physical Resist.
- Refined Storage Controller capacity is now 24k instead of 1024k - performance related.
- Disabled Crow spawns - performance related.
- Sound fixes for Poison Cloud and Resonance.

### Fixes
- Fixed an issue where Pink Brewberry was providing 60.07 food diversity instead of 0.07.
- How Bad Could It Be in Act I now requires kills instead of the Advancement.
- Dissassembler's Method tooltip now correctly states 2x instead of 3x EXP.
- Fixed entity level overrides for Harvest and Obelisk Maps.
- Fixed an issue where Waystones weren't generating correctly.
- Coin Minting is disabled correctly now, even if the Coin Minter is somehow earned.
- Fixed Watcher Map end room which was causing crashes.
- Looting Enchant tooltip now correctly says 1% instead of 2% Item Find.
- Fixed some log spam from Outer End.
- Attempt fix at Umvuthana and Monastery natural spawns.
- Fixed a broken task in Act V.
- Fixed an issue where you could offhand a weapon while holding a Spear.

### Mod Updates
- Updated CTOV, Aggro Indicator, AmbientSounds, Balm, Carbon Config, Chloride (Embeddium), CraftPresence, Doggy Talents, Dungeons Enhanced, Ender's Delight, Enhanced AI, Enhanced Celestials, Entity Loot Drops, EntityJS, Euphoria Patcher, Extreme Sound Muffler, FancyMenu, First Join Message, Framework, ImmersiveMC, In Control!, Jade Addons, Kiwi, Legendary Tabs, Lightman's Currency, Lithostitched, Macaw's, Mine and Slash, MCA, ModernFix, Moonlight, More Sniffer Flowers, Mowzie's Mobs, Mysterious Mountain Lib, Nirvana Library, Oh The Tree's You'll Grow, Repurposed Structures, RoE Weapons, Shoulder Surfing, SkyBreaker, Sophisticated mods, Supplementaries, UniLib, U Team Core, Waystones, Xaero's mods.
- Updated Complementary Shaders.
- Added Data Anchor.
- Removed Hidden Names - performance issues.
- Removed Custom NPCs - was only supposed to be used for Official Server but was causing huge performance issues.

## [0.9.3b] - 2025-04-22

### Updates
- NOTE! If you're having issues with joining Map dimensions, you will need to run "/dungeon_realm wipe_world_data", turn off the server, and then delete the dimension folders for dungeon_realm.
- New weapon type: Kunai! These are basically daggers that can fire a single projectile every 2s.
- You can now view other players builds with mouse middle click or share your own builds!
- Added a quest explaining Ancient Obelisks earlier on.
- Updated quest descriptions for Maps.
- Infinity enchantment no longer works with non-basic arrows.
- Hemorrhage Gamechanger no longer gives flat Critical Hit.
- Infection Gamechanger now gives 15% more Ailment Damage instead of 20%.
- Entities in Map dims should no longer drop their default loot. They will still drop coins and Mine and Slash loot.
- Reduced Map mob density to offset mob spawn radius fix.
- Added search keywords for Talent Tree.
- Added a Quick Loot button in chests that allows you to move items to the Master Bag.

### Fixes
- Fixed GUI issue with creating Mine and Slash teams.
- Fixed Telepass recipes and Bountiful rewards that used the old Pearl of Home item ID.
- Fixed an issue where Maps were spawning in chests outside of the Map dimensions.
- Fixed an issue where damage numbers were showing up incorrectly in All chat tab.
- Messed up loot drops in Harvest, Obelisk, etc. should be fixed.
- Fixed an issue where players spawned in the void in a Harvest Map.
- Fixed GUI issue where Mods and Open to LAN button were incorrectly placed.
- Fixed Map crashes where players would hang on join.
- Fixed Summon AI incorrectly damaging and targetting every living entity.
- Crossbows should be fixed and can be fired even during slight server lag.
- Fixed Map drop rates being too high.
- Fixed Harvest Map where you could fall through the hole.
- Fixed an issue where Minotaurs would spawn like crazy on a Map.
- Increased mob spawn radius in Maps which should help with Mobs spawning on top of players. But probably it was the Command Blocks people saw that they used as indicators for spawn points which helped players avoid spawns on top of them.
- Iron Golem spawning in Sandstone Arena should be fixed.
- Attempted fix of Bosses of Mass Destruction spawns. They should only spawn in Deeper Darker, and the structures should no longer be cut off.
- Navigating backpack no longer resets mouse position.
- Backpack pickup priority should be fixed.
- Map dims are filled with bedrock again which should help prevent mobs from spawning or TPing outside the map.
- Fixed an issue where Jewel currencies weren't respecting the Not Corrupted rule.
- Fixed an issue where you could enter the Map dimension without a Pearl of Home.
- Fixed an issue where high level mobs were appearing in Ancient Obelisks and Harvest.

### Mod Updates
- Updated Sophisticated mods, Advanced Team, EntityLootDrops, Library of Exile, Mine and Slash, Dungeon Realms, EMI Loot, Polymorph, UniLib, AmbientSounds.
- Added What's Your Build - view other players builds or share your own!
- Removed Structure Credits - lag pain point.
- Removed Item Borders - causing compat issues with our existing borders.

## [0.9.3] - 2025-04-18

### Updates
- A bunch of backend refactors for Mine and Slash to improve compatibility and performance. If there are any issues please let us know!
- New Map League mechanic! Relics drop from Map Bosses and Uber Bosses, and socketing them into the Map Device will boost your Maps, allowing you to either 'juice' them up, or pick what specific content you want to play!
- Stardew Valley fishing has been improved! Compatibility with Aquaculture bobbers has been implemented.
- Skill sounds overhaul thanks to Poe! Most Skill have new sound files (over 100 new sounds files!) that should sound way more impactful!
- Added a bunch of new textures for gear and Mine and Slash items thanks to mscr.!
- There are 3 new one of a kind Gamechangers locked behind Blood Mage that provide additional interaction with Blood.
- Blood Mage now gives 60% Health to Blood instead of 50%.
- Overheat penalty to Mana and Energy has been reduced to 20% from 25% per stack, and the Blood penalty is now 10% per stack.
- Meditation has been changed to provide bonuses to Blood as well.
- Auras have been changed to only give -10% penalty to Blood Regen. Mana and Energy remain at 20%.
- Reworked some sources of Mana and Energy Regen into Resource Regen, which affects Mana, Energy, and Blood.
- Immolate now uses Support Gems from Holy Immolation and correct tags have been added.
- Retribution stacks now give 8% Armor per stack instead of 4%.
- Any Effects that have any negative component are no longer tagged as Positive, even if they're "buffs".
- Cold Snap and Zap weapon scaling increased by 10%.
- Timewinder weapon scaling increased by 15%.
- Phase Dive weapon scaling increased by 20%.
- Pulsar Singularity Trap scaling increased by 20%.
- Parallel Convergence scaling increased by 25%.
- Chronobreak scaling increased by 10%.
- Fire Wall and Ice Comet can now trigger Elemental Burst.
- Summon Wisp now summons 2 Wisps at 5 Soul Stacks.
- Summon Spiders now has a longer cooldown of 2s instead of 0.5s between procs.
- Summon Spiders damage has been reduced slightly.
- Combo Starter Skills have had a 5% increase in damage.
- Attack Speed now affects cast time on Attack Skills in addition to Cooldown Reduction at the same rate (25%).
- Added connected glass textures.
- Added Whistleshell Crab to kill list in Act IV quest.
- Increased difficulty of Ancient Obelisks.
- Improved Ancient Obelisks loot.
- Modified Ancient Obelisks spawns to include modded mobs.
- Map and Mob Affixes that convert Physical to Elemental Damage now have Gain Physical as Elemental Damage instead.
- New Sculptor mob and Monastery structure in the Undergarden (Act III). A new quest has been added.
- Lowered spawn rate of Umvuthana and Naga in the Undergarden.
- Epilogue boss kill quests have been changed task type: Consume Item, and they now require the trophy to be completed. This should make the quests a little more consistent when attempting to complete.
- Added some conversion recipes for OTBWG Crafting Tables and Beefs. Thanks Sainguin!
- Tons of quest updates and fixes! Thanks Poe!
- Sharpening Stone experience has been reworked.
- Added coin downgrade recipes thanks to CreatorBurden!
- MCA Villagers no longer take damage or deal damage to players and will lose there aggro apon attacked, they can still be killed by mobs.
- Boss drop rework/fix. Dimension Runes are no longer affected by Anti-Mob Farm, but they won't appear in EMI Loot anymore.
- Bows are now two-handed.
- Added one-handed Crossbows.
- Structures now respawn after a long period of time.
- You can now Sit with Default: Insert.
- As Illager Invasions are no longer possible, the Gateway will grant the Hero of the Village.

### Fixes
- Fixed Underminer spawns in Mineshafts.
- Fix Party GUI overlapping.
- Fixed Corrupted Jewels' Affixes being rerollable.
- Fixed impossible to complete High Roller quest.
- Fixed Assassin's Katar unique not showing up.
- Fixed Map and Obelisk teleport lag.
- Fixed Belly of the Beast food stat.
- Fixed some stat descriptions.
- Fixed Elven Traders being impossible.
- Fixed Lootr chest textures.
- Fixed Endermen spawning even when Mega Torches were placed.
- Fixed some Boss Runes not dropping.
- Summon pathing AI has been fixed/improved.
- Improved Kill Quest detection.

### Mod Updates
- Updated a bunch of mods.
- Updated Forge.
- Added Athena.
- Added The Harvest.
- Added Dungeon Realm.
- Added ROE Sound Effects.
- Added Loot and Entity Protection mods.
- Added Sit & Chill.
- Added Quest Kill Task Tweaks.
- Added Custom NPCs - mostly to be used for Official Server, but players can still use this as well.
- Added Respawning Structures.

## [0.9.2] - 2025-02-05

### Updates
- Chosen of Azuna Runeword has been nerfed.
- You can now have a max of 5 claims instead of 3.
- Ice Mazes can now spawn in Deep Cold Oceans as well.
- Lowered Bonescaller health by 20%.
- Removed Warped Mosco from Map Boss and Mob pool.
- Ancient Obelisk difficulty has increased.
- Magma Orb no longer gives Overheat, since Fire Golems cast it.
- Updated player GUI a bit. Moved effects down to the center.
- Updated Repair Kit quest to be a bit more descriptive.
- Common variants of weapons are now craftable.

### Fixes
- Fixed some localization.
- Fixed Overheat not applying to Blood.
- Fixed some Teams stuff.
- Fixed Act II quest requiring materials from Act III.
- Hopefully fixed some Player Data Error bug due to Connectivity.
- Fixed a Crafting output exploit.
- Fixed Elytra and Flugel Tiara not applying stats.
- Fixed mobs having innate Critical Hit.

### Mod Updates
- Updated Advanced Team, Ancient Obelisks, Connectivity, Mine and Slash.
- Downgraded Sophisticated Mods as we're trying to determine the cause of a Player Data Error on join bug.