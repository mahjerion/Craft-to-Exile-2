# Changelog

## [0.7.3b] - 2024-11-12

### Updates
- Blood Spark was reworked to reduce Weapon Damage instead of Health. The calculations show that this ring is still good if you build Health.
- Stone of Jordan now gives less Damage.

### Fixes
- Fixed Arrow Barrage, Ricochet Shot, and Resonance having unknown stats.
- Fixed some missing localization.

### Mod Updates
- Updated MineColonies.

## [0.7.3] - 2024-11-12

### Updates
- Updated Super MC Network IP to cte2.supermcnetwork.com.
- New Map GUI screen has been added that shows your Map completion % and other information.
- You now teleport to the Boss through the GUI instead of using an item.
- Map upgrades are now triggered through the GUI when outside of the Map.
- Health and Mana Scaling on offensive Skills has been reduced by 25% across the board. This change plus the Weapon Cap fix will result in a lower ceiling.
- Codex are stronger at higher rarities.
- Archmage Support has been reworked to only work with Weapon Skills. Might be controversial but the issue with the old implementation of Archmage was that it was essentially a double dip (with a small opportunity cost) for Lightning Skills. I wanted to keep the gem without straight up making it useless for other builds. This change does affect other non-Lightning casters (who also already stack Mana), but the idea is that this gem should provide more diversity for non-caster builds.
- Archmage Support has been renamed to Mageblade Support.
- Barrage Support Gems now give 1 less additional Projectile.
- Non-Weapon Damage Scaling sources on Skills have had their caps reduced drastically. This was sort of a bug where the cap was 3x higher than it should have been.
- Sources of Energy to Physical Weapon Damage have been nerfed greatly.
- Resource Leech Cap base is now 5% instead of 10%.
- Unique Ring that scales with Health has been reworked to give less scaling.
- New Runeword: Hailstorm! This can only be crafted on Pants. Hailstorm gives the wearer a new Ranged Skill: Hailstorm (see below for details). Additionally, this Runeword provides Phys to Cold conversion and bonuses to Cold Damage.
- New Skill: Hailstorm! Hailstorm requires a bow/crossbow and fires in rapid succession multiple ice pellets which have increased Freeze Damage.
- Last Tracker set now provides Weapon Skill Damage bonuses instead of Energy to Phys Wep DMG.
- New Elemental Attack Damage stat. Currently only found on Jewel, Jewelry, and Weapon prefix "Catalyzing". This stat increases any elemental damage from a source that's not tagged as "Magic", so Weapon Skills and Basic Attacks, mostly.
- Almost all sources of X per Y stat has been reworked to % of X Gained as Y to be more clear to players, and compatible with other stats.
- Mana Battery now gives 30% of Damage Absorbed by Mana instead of 35%.
- Witch's Brew no longer gives any Health Regen penalties.
- Battlemage Ascendancy that ignores Lightning Resistance now gives a large bonus to Lightning Penetration instead.
- Battlemage Gained as Mana stats have been reduced in potency.
- Battlemage Resolve and Battle of Wit now gives bonus Elemental Attack Damage instead of Elemental Weapon Damage.
- Bulwark of Flesh and Agile Hand Ascendancy nodes now give 25 Health/Accuracy per 10 Strength/Dexterity instead of 10 per, respectively.
- Almost all Skills have been overhauled, they now have interesting stats associated with them which reward investment. For example, levels into Gong Strike increase your chance of generating Endurance Charges.
- New Lv. 30 Rogue Skill: Bola! Throw a weighted chain at the enemy, forcing it to succumb to gravity and fall to the ground for a brief moment.
- Rogue Passive that grants Energy to Phys Wep DMG is now Ailment Damage.
- Double Strike is now longer incorrectly tagged as Area.
- New Lv. 10 Warlock Skill: Blade of Desecrated Hallows! Turn your Weapon frost just in time for the Holidays. Converts Phys to Cold and gives a bonus to all Cold Damage!
- Improved Warlock Skill particles.
- Explode Minions Weapon Scaling cap is now 3x instead of 5x Weapon Damage for the Summon Health scaling part.
- Lowered Explode Minions Weapon Scaling by about 10%.
- Thorn Bush is no longer tagged as a Totem.
- Putrid Breath projectiles now travel 50% further.
- Acid Cloud now does double damage on full Soul stacks instead of hitting twice.
- Acid Cloud no longer generates a Soul stack.
- Halved Cast Time of Acid Cloud and Black Hole.
- Black Hole cooldown is now 8s instead of 10s.
- Soul stacks from Curses, Acid Blast now last 8s instead of 5s. 
- Greatly reduced Summon Skeletons Summon Damage bonus due to fix regarding Summon Damage stat on Skills.
- Summon Damage Weapon Scaling has been reduced to 50% from 100% of Weapon Damage. This sounds big but I promise it's not that bad due to the Summon Damage fix.
- Battery Fusillade Mana Cost has been reduced slightly.
- Chain Lightning and Lightning Orb Weapon Damage Scaling per level has increased by 50%.
- Lightning Spear Weapon Damage increased by about 10-15%.
- Galvanic Blade Weapon Damage Scaling has increased by about 10-20%.
- Magma Totem has been reworked on the back-end to be more consistent.
- Magma Totem now ticks twice as often but deals half the damage.
- Entangling Seed is now properly tagged as Physical instead of Chaos.
- Increased Explosive Arrow Damage by 25%.
- Arrow Barrage Weapon Scaling per level has been reduced. 115% instead of 125% Weapon Damage at level 16.
- Trap Weapon Damage Scaling per level has been reduced by about 17%.
- Encased and Envenomed damage have been reduced by about 20%.
- New Lv. 25 Warrior Skill: Incinerating Weapon Toss! Throw out your weapon toss, spinning it rapidly. The weapon will deal damage to enemies caught in it's wake. If in Fighter Stance, teleport to your weapon once it reaches the end. If in Defender Stance, the weapon also explodes at the end, knocking back and dealing damage in an area.
- Leap has been reworked into Charge. Upon use, rapidly rush forward and deal damage to the first enemy hit.
- Gong Strike and Whirlwind Weapon Scaling in Defender Stance has decreased to be more in line with the Fighter Stance counterpart.
- Gong Strike and Grapple are no longer incorrectly tagged as Area.
- Gong Strike now targets in front of you, and it now reaches further.
- Grapple range has increased.
- Fighter's Damage Received passive has been correctly changed to Damage Reduction, and the value per level has decreased from 1.5% to 1%.
- Ensnaring Melody cooldown reduced by 20%.
- Ritardando can now be learnt at level 10 instead of 15.
- Garden of Thorns no longer uses charges.
- Cyclone now travels 50% further.
- Cyclone now ticks damage every 4 ticks instead of 5 ticks.
- Frozen Orb explosion radius is now 3.5 instead of 2.5.
- Blizzard Weapon Damage Scaling has increased by about 15%.
- Sources of Damage to Cursed have been brought in line with other stats.
- Ondal's Wisdom staff now gives +2 All Skill instead of +3 and gives less Cast Speed.
- Nerfed most sources of Cast Speed.
- Cooldown Reduction has been buffed slightly.
- Jewel Corruption affixes have been buffed.
- Sources of Damage Over Time and Ailment Damage and Chance have been lowered. This includes Burn/Freeze/Electrify/Poison/Bleed. Some of these were affected more than others.
- Lowered certain item drop rates such as Support Gems, Auras, Uber Fragments, Watcher Jewels.
- Increased the basic attack range of melee weapons.
- Gear Crafting Profession has a bit of a cost rework. Higher Rarity crafts now cost more Stones. Starting with Common at 4 Common Stones, to Mythic with 24 Mythic Stones.
- Profession Recipes on a whole are slightly more expensive, requiring more Gathering Profession materials.
- Enchantment Compatibility is now also capped per player, not just per item. The cap per player is 3x the cap per item, which is Enchant Lv. 6.
- Protection and Blast Protection now give percent Armor and Dodge Rating, respectively.
- Updated Captain Cornelia and Wither Quest to give hints on how to defeat them.
- Updated some Tag localization. They're properly capitalized now.
- Construction Wand crafting recipe has been updated to use Mine and Slash Stones. They will also no longer conflict with Mine and Slash Staves.
- Re-enabled the Accumulator and Large Connector. Don't remember why I disabled them.
- Added a new Prologue Quest that explains and provides the Master Bag.
- Removed duplicate quest in Exploration Chapter.
- Moved Merciless Ascendancy from Dragon Quest to They Knew You Were Coming.
- Starlit Crusher's Ent Walls no longer drop loot and now give less EXP.
- Wither Health reduced by 25%.
- Added Ascendancy icons to the Quests that are related in the Quest rewards.
- Act Bosses have been downshifted back to Rare from Epic.
- Experience gain has been reworked slightly. Exp leeway from level difference has changed from 2 to 3, and penalty range is now 6 levels instead of 10. So before, you would get full exp from mobs +/- 2 levels, 70% exp from mobs 3 levels different, and 0% from mobs 10 levels different. Now, you will get full exp from mobs +/- 3 levels, 66% from mobs 4 levels different, and 0% from mobs 6 levels different.
- Mob experience gain has been reduced.
- Overall Mob Damage has decreased substantially. Like probably 20-30% or so on top of the other changes below.
- Reduced Map Mob Damage bonus per Tier from 6% to 4%.
- Reduced Map Mob Health bonus per Tier from 20% to 15%.
- Uber Maps are now always Mythic.
- Upped Boss and Uber rarity static Health.
- Reduced Uber Boss damage by about 8%.
- Removed BOMD from Uber Boss pool due to issues with TP and blocks.
- You can no longer open Dispensers in Maps.
- Maps no longer drop. You can craft a Common Map instead. This is possible due to Maps always scaling to player level and upgrades being determined by Map success.
- Map Quests in Act V have been updated.
- Gear now shows base stat % and value when holding Shift.
- Updated some localization to be more clear regarding Gained as, Per, Physical Damage as Extra...
- Added % signs where necessary to help with some stat clarity. Eg. % Damage per Endurance Charge.

### Fixes
- Fixed an issue where Magic Shield damage from environment was not taking mitigation into account.
- Fixed a bug where Thorns effect would cap out at 100% of Weapon Damage on consumption when dealing damage. It now correctly caps at 300%. Thorns was basically a dead effect before.
- Attempt to disable Glares again.
- LootBeam lag should be fixed.
- Fixed some incorrect Quest subtitles in Exploration.
- Fixed Extractor Quest in Act II.
- Fixed incorrect recipe in Quest description of Taking On Work in Act I.
- Fixed some missing localization.
- Map lag from client side should be reduced greatly.
- Fixed Civilization from the Past referencing Mirror dim.
- Fixed Blue Skies dimension giving tons of Fishing XP.
- Hopefully fixed Boss Scroll TP bug.
- Some null errors on block mining should be fixed.
- Infusion re-rolling should be fixed.
- Backpack Fluid GUI is fixed.
- Omens are now repairable.
- Fixed an issue where innate Skill stats were not applying to downstream Skills. Eg. Summon Damage on Summon Skills was not working.
- Fixed Professions being able to overlevel past cap.

### Mod Updates
- Updated Mine and Slash, Xaero's Minimap, MineColonies, Moonlight, NotEnoughAnimations, Sophisticated Core/Storage, Supplementaries, Immediately Fast.
- Removed Sound Physics - caused a decent amount of lag.

## [0.7.2b] - 2024-11-07

### Updates
- Act Boss rarity has been increased from Rare to Epic. Mini-Bosses remain untouched at Rare.
- Blast Protection now gives 0.5% Elemental Resist per level instead of 0.75%.

### Fixes
- Fixed a bugged out datapack for Blast Protection.

## [0.7.2] - 2024-11-07

### Updates
- Crafting Stations should show items that are missing from the recipe.
- Casting Skills now costs main hand durability, but will not break the item. At 1 durability the item is considered broken and cannot be used to cast.
- Archmage Support now scales from 3-9% instead of 5-15%.
- Increased Black Hole damage scaling by about 10%.
- Whirling Blades damage scaling per level has decreased very slightly.
- Quake damage scaling decreased by 20%.
- Quake projectile explosion AOE decreased by 25%.
- Improved Whirlwind visuals.
- Improved Fireball visuals.
- Buffed Magic Find sources slightly.
- Buffed Wealth and Azuna's Ring a little more than slightly.
- Animations to Talent/Ascendancy Tree have been added. Thanks Clefal!
- Made higher rarity exploration in Maps a little easier to obtain.
- Decreased Boss Health substantially, but it may be offset by the fix to Boss Rarity.
- Disabled the Pyramid Map. It's still under construction.
- Updated Enchant to MNS stat compat to be cap of 6x whatever the Enchant gives per level.
- Updated LootBeam config.
- Changed Mutant Skeleton armor set recipe to be more difficult to obtain.
- Enabled Sky Raiders.
- Trying some performance enhancements on the Official Server.

### Fixes
- Hopefully fixed an issue where mobs in Maps could teleport outside of the Map.
- Fixed a bug where Bosses weren't correctly spawning as Rare rarity.
- Fixed proc when hit/block effects not working properly.
- Fixed some Infusion affix IDs being misleading.
- Fixed Megatorches being uncraftable.
- Fixed Mutant Skeleton armor set being uncraftable.
- Fixed Gauntlet drops on death.
- Fixed BOMD Uber Bosses not doing anything when hit.
- Fixed an issue where Ascendanancy points were not being given to players. They were all being given to Mahjerion.
- Crafting Station fix implemented, includes Dissassembler's fix.
- Fix Uber Bosses not dropping loot.
- Fixed Boss Arenas not appearing.
- Fixed Uber Boss Maps allowing you to upgrade to the next Boss Map right away.
- Fixed Ascendancy points bein unobtainable even through cheats.
- Inventory Sorter deleting items has been fixed (including Curio slots). Hence, the mod has been re-added.
- Re-disabled Glares.

### Mod Updates
- Re-added Inventory Sorter - this is a fork of the original with less issues.
- Added fix GPU memory leak - client-side helper.
- Added Client Crafting - client-side helper.
- Added Fast Async World Save.
- Added Alternate Current - redstone calculation improvements.
- Replaced Better Ping Display with PingHUD. Should have better compatibility.

## [0.7.1] - 2024-11-06

### Updates
- You no longer receive Ascendancy Points from leveling. There is now a new Ascendancy Chapter that shows you how to gain Ascendancy Points. For now, these are gained from various tasks in the Campaign. You will cap out at 7 points still. Note that players may have 0 or negative points upon updating - complete the quests and you should be all good.
- Updated Prologue Quest 9c regarding extractors.
- Hunter Potion now has a short 5 tick cast time.
- Set default Jukebox music volume to 35%, in line with game music.
- Implemented some Map entity spawn restrictions to help with lag a bit.
- Mob spawns in Maps is now more strict and despawn if you're too far. They will reappear if you come back.
- Reduced the spawn rate of some Nether structures substantially.
- Removed the annoying click sound on message send.
- Lowered Stone Golem spawn rate by 90%.
- Increased minimum View Distance on servers.

### Fixes
- Fixed some Skills showing as level 1 when they weren't.
- Fixed Hunter Potion causing players to enter infinite animation loop.
- Fixed some lang stuff.
- Fixed M&S Profession Crafting Station UI.
- Fixed Copper Backpacks not being equippable in the Curio slot.
- Fixed Reward from Overworld Mirror being free.
- Fixed Unique stats rolling way too high.
- Fixed Unique stat ranges showing incorrectly.
- Fixed some Proc Skills not being supported by Support Gems correctly.
- Fixed Mob HP being way too high.
- Fixed Mobs having way too much resistance.
- Fixed Skills respecting mob invulnerability frames.
- Fixed Infusions not working correctly.
- Fixed Passive Points showing as Ascendancy Points under list stat sources command.
- Fixed Imbuing Table being uncraftable.
- Fixed some Cold Resist stats being invalid.
- Fixed Curse of Tongues having an invalid stat.

### Mod Updates
- Updated Mine and Slash, Supp Squared, CreativeCore, MineColonies.
- Removed Incendium - laggy and didn't offer much for us. Updated Quests accordingly.

## [0.7.0c] - 2024-11-05

### Updates
- Unlimited Mana change has been reverted to 3% Mana per Sec. It now also gives 10% increased Mana Regen.
- Rebalanced Summons a bit.
- Should be a substantial performance boost.

### Fixes
- Fixed Projectile Damage Reduction causing log spam.
- Fixed Hammer Damage stat not working.
- Fixed Talent Rewards not being given correctly.
- Fixed default keybinds so now it's more obvious players need to set the last 4 themselves.
- Fixed Summons incorrectly stating they deal Fire Damage.
- Fixed Puncture causing players to enter an infinite animation loop.
- Fixed some null Quest rewards.
- Fixed Currencies not going into the Master Bag.
- Fixed being able to cast some Skills even if you had 0 points in them.

### Mod Updates
- Updated Farmer's Delight, Mine and Slash, Skin Layers 3D.
- Removed Stellarity. Came with a bunch of bloat and is also a large source of lag. I've updated related quests.

## [0.7.0b] - 2024-11-05

### Fixes
- Fixed Ascendancy point capping at 6.
- Fixed server issue due to Risk of Rain mobs.
- Fixed legacy Overworld Mirror quest appearing.
- Fixed inventory sorting issue by removing the mod.

## [0.7.0] - 2024-11-05

### General Updates
- A HUGE thank you to Raspy, Rami, Sparkz, and DingoDango for their support as Netherite Patrons!
- New PATREON Unique Shield! A Father's Love, designed by Raspyutin/Jubban! This shield provides substantial bonuses to Block Chance and Threat Generation in addition to other useful stats. It also provides a good amount of Magic Find. Congratulations to Raspy on the baby boy!
- New PATREON Unique Necklace! Harmony of Dusk and Dawn, designed by Rami! This interesting necklace gives the user bonuses based on the time of day. Stay vigilant during the day, and take advantage of your opponents at night...
- New PATREON Unique Ring! Blood Spark, designed by Sparkz! Blood Spark brings a new stat to CTE2 - damage increases based on the wearer's max health!
- New PATREON Unique Armor! Amblypygid, designed by DingoDango! In addition to a massive boost in defenses, this backpack/armor gives you the chance to gain the Pedipalp effect on hit, grappling nearby enemies!
- 2 new Unique "sets": Oath of Mahj and Nebula's' Robes. These two sets consist of a helmet, chestplate, legging, and boots. Oath of Mahj pieces can be found after tier 40 and are defensive based. Nebula's Robes are an end-game set similar to Last Tracker and Genji's and are for spell-casters. These sets have special models. Thanks Nozium!
- Replaced United server with Super MC Network's server on the server list. Thanks for the continued support!
- UI update thanks to Skullbushi!
- Builders rejoice! Chipped and Construction Wand have been added. Chipped adds plenty of options when building and Construction Wand will make things easier when building large structures!
- New quest chapter: Epilogue! A new challenging way to conclude the campaign series!
- New bosses have been added to the Otherside. Check out the quests in the Epilogue!
- Switched around the Disenchanter quest with the Imbuing Table quest.
- Added a quest going over Chipped and Construction Wand.
- Added a new Lost Page regarding the new Codex gear type in Act IV, around when they're unlocked.
- Added a new Lost Page in Act II going over Rested Experience.
- Villager trades now replace Emeralds with Iron Coins rather than Emerald Coins.
- Coins can now appear in Map chests!
- Amber from More Sniffer Flowers drops have been reworked to be mostly plant-based.
- Gateway timers have been standardized to 5 seconds. Before, they ranged from 5-20s!
- Gateways are now more expensive to craft (except for Overworldian Nights).
- Added new Bountiful rewards. There are now Mine and Slash currencies and stones!
- Improved Mine and Slash content in chest loot table rewards.
- Improved Cooking for Blockheads compatibility. Thanks DingoDango!
- New Combat Music has been added. If you have 3 or more mobs in the vicinity, Combat Music will trigger! Listen to 8 new tracks while fighting. If no mobs are detected around you for 10s, the music will fade. Not sure if this actually works. Would love to hear from players.
- Blue Skies Boss Combat music has been replaced.
- Find new Sea Dwellers in the Ocean depths. They spawn in Villages and will trade you goodies for Aquamarine - a new item dropped by Drowned, Squids, and Guardians.
- New Potted Mimics have been added!
- MineColonies magic potion now only requires 16 Mistletoe instead of 64.
- Some new Risk of Rain mobs have been added.
- Temporary Spawner cooldown is now 60s instead of 180s.
- Gysahl Green spawn chance reduced to 25% of what it used to be.
- Removed Overworld Mirror dimension. This world didn't really take the properties of the Overworld correctly, and we don't need it anymore either.
- Abyssologer natural spawn has been removed. It now spawns as a boss in the Overworldian Nights Gateway.
- Witches no longer cast Dark Arts, meaning they no longer summon Villagers.
- SoL and Cuisine Delight compat has been added.
- New Mine and Slash features available in the Hub, including show EXP.
- Character GUI has been improved greatly. You can now rename your characters.
- The in-game MNS Library has been improved. You can now filter, scroll, search, etc.
- Mine and Slash tooltips have been drastically improved.
- Changed the font used to be more RPG-like.
- Updated some sound effects and the font. Thanks to Poe for the permission.
- Updated default keybinds.
- General performance and stability improvements.

### Mine and Slash Class Updates
- SKILL CASTING NOW HAS CUSTOM ANIMATIONS!
- Most Mage/Ranged Skill AOE have been reduced substantially. This includes Traps, Totems, Curses, etc. Melee Skills remain untouched.
- Buff Skill Radius have been reduced by 20%.
- Weapon Skills no longer benefit from Cast Speed to Cooldown due to the Attack Speed changes.
- Charge and Cast Bar GUI have been redesigned.
- New Minstrel Skill: Rallying March. Channel this skill for 7s. While channeling this skill, nearby allies receive a major buff to Damage, Damage Reduction, and Move Speed.
- New Hunter Skill: Magic Missile. This arrow skill has a very high bonus to accuracy and also follows your target!
- Arrow Storm has been reworked slightly. Instead of lasting 10s and having a 20s cooldown, it now lasts 4s and has a 4s cooldown. The Energy Cost has been reduced to compensate.
- All other Bow/Crossbow Skills in the Hunter tree have had their Energy Cost reduced.
- Reduced the cost of Arrow Totem.
- Hunter Trap Skills now give an increased chance of applying elemental status effects.
- Fire Trap now uses the charge system.
- All 3 Trap Skills have had their charge system reworked a bit. The cooldown period for all 3 is now 0.5s instead of 1s (2s for Poison Trap). This means you could "unload" all your traps at once. Additionally, Fire Trap has the shortest recharge rate, at 3s per charge. Frost Trap is 4s, and Poison Trap is 5s.
- Poison Trap has been reworked. Instead of dealing damage upon detonation, it now spawns a poison cloud which damages enemies in it. The damage from the cloud no longer applies Envenomed. Poison Trap still pulls enemies in on detonation.
- Frost Trap has been reworked. It now detonates and stuns nearby enemies for 1s. After that, it continues to pulse every 2s for 4s, with each pulse dealing damage and also stunning the enemies for 1s. Only the initial pulse applies Encased.
- Quickdraw is now tagged as Offensive as well.
- Flicker Strike and Double Strike Weapon Scaling has increased by about 10%.
- Flicker Strike cooldown is now 2s instead of 3s.
- Puncture now has a flat 50% Bleed Chance instead of 25%.
- Puncture Bleed Damage bonus has increased by 50%.
- Piercing Dagger Throw now has a flat 50% Bleed/Poison Chance instead of 25%.
- Piercing Dagger Throw Bleed/Poison Damage bonus has increased by 50%.
- Snipe and Ricochet Shot Energy Cost has been reduced.
- Snipe and Execute's bonuses to crit have been increased.
- Execute cooldown is now 2s instead of 8s.
- Fan of Knives now fires one additional projectile.
- Smoke Bomb now gives 100% increased Critical Hit for 3s upon use.
- Smoke Bomb cooldown is now 13s instead of 20s.
- Whirling Blades now lasts 8s instead of 12s and has a cooldown of 8s instead of 10s.
- Whirling Blades Weapon Scaling per level has been reduced slightly.
- Mirror Image is now tagged as Defensive as well.
- Flame and Venom Splash Potion cooldowns are now 5s instead of 6s.
- Lightning Warp now has a cooldown of 6s instead of 20s, but has a cast time of 1s.
- Astral Totem now lasts 8s instead of 7.5s.
- Astral Totem cooldown is now 20s instead of 30s.
- Chaos Totem now lasts 8s instead of 7.5s.
- Chaos Totem now has a cooldown of 12s instead of 20s.
- Lightning Totem and Frost Totem cooldown is now 10s instead of 16s.
- Fire Totem cooldown is now 9s instead of 14s.
- Rejuvenation Totem duration is now 8s instead of 7.5s.
- Rejuvenation Totem cooldown is now 12s instead of 15s.
- Static effect now gives 4% percent Critical Hit and 8% Mana Regen instead of 5 and 10.
- Fighter Stance now also provides a small amount of flat Critical Hit.
- Whirlwind now gives bonus damage based on Attack Speed.
- Boomerang is now correctly tagged as a Weapon Skill.
- Grapple cooldown is now 4s instead of 5s.
- Taunt cooldown is now 8s instead of 10s.
- Black Hole now has a 12s cooldown instead of 20s.
- Cyclone now costs less Mana.
- Entangling Seed cooldown has been reduced from 20s to 10s.
- Curse Skill effects have doubled. Curses were not impactful enough for the amount of trouble they were. Damage remains unchanged.
- Curses now have a 10s cooldown instead of 20s.
- Despair now additionally reduces enemy Move Speed substantially.
- Agony Curse now gives -% MORE to Accuracy instead of buffing enemy Move Speed.
- Summons should now correctly be affected by Support Gems.
- Explode Minions now has a 1s cast time.
- Armageddon costs significantly less Mana.
- Chilling Field now lasts 5s instead of 8s.
- Chilling Field cooldown is now 5s instead of 10s.
- Blizzard costs less Mana.
- Blizzard duration has changed from 8s to 6s.
- Blizzard cooldown has changed from 20s to 10s.
- Mage Circle cooldown is now 8s instead of 15s.
- Mage Armor is now tagged as Defensive as well.
- Bone Chill is now tagged as Immobilizing as well.
- Frost Nova is now tagged as Heal as well.
- Charges are no longer tagged with anything but "Charge".
- Slow is now tagged as Immobilizing as well.

### Mine and Slash Talent and Ascendancy Updates
- True Hit now gives 20% MORE Critical Damage instead of 25%.
- Refined Taste Gamechanger now gives 15% Health Leech Cap instead of 40%.
- Guardian's Ascendancy that provides Positive Effect Duration now provides Defensive Effect Duration instead.
- Juggernaut's Ascendancy that provides Move Speed and Immunity to Slowness now also grants 15% Cooldown Reduction.
- Juggernaut's Untiring now gives 2% Health per Sec instead of 3%.
- Juggernaut's Untiring now gives 35% Health Regen instead of 40%.
- Hunter Ascendancy that gives 50% percent Critical Hit now gives 2% flat instead.
- Necromancer's Flesh Army now gives 35% Summon Health instead of the stat that converts player Health into Summon health.
- Arcanist's Unlimted Mana now gives 2% Mana per Sec instead of 3%.

### Mine and Slash Item and Stat Updates
- A new gear type has been added: Codex. Codex are a 4th Curio slot item that start dropping at level 50. Codex reward players for equipping different types of gear (Runewords, Uniques, Mythics) by providing powerful stat bonuses for the amount of diversity you have equipped.
- Reset Potions have been reworked. There are now Minor/Major Reset Potions for Skills, Passives, Stats, Talents, and Ascendancies. Minor potions give 10 refund points, and Major potions perform a full reset.
- A bunch of new Orbs/Currencies have been added.
- Socket Extractor is no longer a thing. 2 new currencies to extract Gems or Runes have been added.
- New Ring Runeword: Chosen of Azuna - provides bonuses to attributes and Total Damage.
- New Necklace Runeword: Nature's Wrath - provides bonuses to Cold and Lightning Skills, and Mana. Also provides - Fire Resistance.
- ONLY RUNED gear can have Runewords.
- You can no longer insert Gems into Runed gear.
- Nerfed the stat range for Runewords from 70-100 to 70-85. This is equivalent to Legendary items. For context, Unique items and Mythic items roll 85-100.
- Runes have had their stats nerfed across the board.
- Supersonic Runeword now gives 30-50% percent Critical Hit instead of flat Critical Hit.
- Lowered Rune Drop rates by 40%.
- Weapon type requirement tooltips have been streamlined a bit to make more sense to the newer player.
- Attack Speed stat now applies to bows and crossbows! Draw Speed stat is now phased out.
- Attack Speed now applies to Weapon Skill Cooldown Reduction at 25% of its value. So 60% Increased Attack Speed now gives 15% CDR for Weapon Skills!
- Attack Speed stat has been adjusted accordingly.
- Gear Affixes have gone through a slight rework - mainly streamlining the ranges and bringing outliers in line.
- Nerfed/fixed Vanilla Enchantment to Stat compatibility. Turns out it was more of a misunderstanding. I thought the cap was global rather than per-gear. The cap values have been readjusted.
- Added 4 new Suffixes for Boots. These are rather rare, but provide bonuses to Jewel stats.
- You can now upgrade Jewels with newly found Currencies. Jewels have potential now as well.
- Reduced the flat Magic Shield from the Magic Shield Augment from 6-30 to 5-25.
- Reduced all sources of Increased Area by about 30%.
- Block Chance perks now give percent instead of flat.
- Suffixes Of Devastation and Of Brutality now give 5-25% Critical Damage instead of 4-30%.
- Augment Cost stat has been nerfed across the board by about 20-30% on most sources. Some rarer sources remain unchanged, such as Corrupt stats, Jewels, etc.
- Augment Effect stat has been nerfed in most places by about 20-30%. There was also a bug related to this stat that has been fixed.
- Tourmaline now provides buffs to Defensive Effects rather than Positive Effects on armors.
- Royal Skean Dagger implicit now gives 20-30% percent Critical hit instead of 30-50%.
- Ichimonji Unique Sword no longer gives Augment Capacity and gives additional Augment Effect and some Accuracy instead.
- Unique items have had a huge buff across the board. Note that many changes are not listed below.
- Unique item weightings have been standardized - they all drop with the same weighting except for Prophecy, Tier 80+, and specific chase Uniques.
- Uniques can now be salvaged.
- Support Gem that gives MORE Critical Damage now gives 8-24% instead of 9-27%.
- Effect Duration Support Gem now gives 10-30% instead of 15-45%.
- Back to Basics Augment attack speed buff has been halved.
- Archmage Support now works as intended, and no longer applies to skills that don't use Mana.
- Blood Amulet Necklace Implicit now gives 1-2% of Max Health Regen per Sec instead of 1-2 base Health Regen.
- HP/MS/Mana/Energy Ring Implicits have been standardized to 3-6 flat instead of 5-10 for HP/Mana/Energy and 7.5-15 for MS.
- Tourmaline Effect Duration has been reduced by 25%.

### Mine and Slash Mob and Map Updates
- Maps were reworked drastically. There is now an explicit boss at the end of each Map, found in a separate arena. To access it, you need to complete at least 50% of the Map (the more you clear, the better your reward will be). If you manage to kill the boss, it will spawn a portal to a reward room full of chests. The contents of the chests improve based on your Map completion.
- Additionally, Maps now only drop at Common Rarity. You can upgrade your Map at the Map Device after successfully killing a Boss. The amount you can upgrade it by depends on how successful you were at completing your last Map.
- Removed Firecaller from Map pool. They could teleport.
- Maps no longer have a level bound to them. The Map's level is determined by your level upon triggering the Map Device.
- New Map layout added! Check out the new spooky Night Terror Map! Thanks to Villain and DoutingDonut for your contributions! If you would like to delve into Map-making, give the Moderator team a shout.
- 4 new Uber Bosses have been added! The Lich, Void Blossom, Gauntlet, and Obsidilith!
- Uber Fragments now only drop from Map bosses. The drop rate has increased to 10%.
- Map difficulty per tier has increased by about 30%. This was done because Rare maps should be around where Mythic maps are now.
- Mythic and Legendary rarity items are no longer drop-bound by rarity. They can drop in Common areas and non-map dimensions!
- Lowered map drop rates in maps to about 15% of what it currently is.
- Mutant Creeper minions now give 20 times less experience as before.
- Reworked Prophecy rarity weights and cost multipliers. Higher rarities are now more rare and costly. Additionally, the minimum Tier for each rarity has been updated. Eg. Mythics only drop in Tier 60+, Uniques in 80+.
- Prophecy curses have been reworked slightly and are now more punishing.
- Prophecy GUI has been improved greatly.
- Mob damage and health scaling per dimension has increased. Instead of going from 5% to 30% (OW -> Deeper Darker), it now goes from 10% to 100%. This is to ensure that dimensions are getting harder.
- Mob damage and health scaling is now slightly exponential. It was linear previously.
- Mob damage from mobs much higher level than you (about 5) will deal additional damage.
- Mob armor per level has increased by 50%.
- Reduced Starlit Crusher's damage by 18%.

### Mine and Slash Profession Updates
- Professions has gone through a overhaul. The Lesser/Medium/Greater materials are now a thing of the past. Recipes have been updated to reflect this.
- Alchemy and Cooking recipes have gone through a small rework - please refer to the quests/JEI.
- M&S Enchantment Profession has been reworked. It is now called Infusion rather than Enchantment. Also, stats no longer re-randomize on upgrade and will stay the same. To compensate this change, the profession recipes now give 1 scroll rather than 3.
- Massive thank you to DingoDango for all the help with this one! In addition to the above, the Enchantment system has a rework in what stats can roll on each gear type! Find new interesting effects - proc effects on helmets, defensive layers on chests, and more!
- A new Infusion currency has been added that randomizes the Infusion on the gear at the cost of potential.
- Vanilla to M&S Enchantment compatibility stats have been halved, and a cap has been introduced. In most cases, players won't hit the cap.
- Husbandry renamed to Animal Breeding.
- Reduced Farming EXP from Gloomgourds and Pumpkins.
- Profession stations will now attempt to take items from nearby chests for the currently locked recipe.
- There is now an EXP penalty for Professions when crafting/harvesting lower leveled items.
- Improved material and consumable item tooltips.
- Mastery Seals have been removed, as you can use downrank recipes.
- Crafted gear is now labelled.
- Salvage Station now poops out items that aren't salvagable.

### Fixes
- Fixed an issue where mobs could drop "Air" insetad of coins.
- Fixed bosses being coin-farmable. They now require you to kill them.
- All Attributes stat now scales properly.
- Fixed Chipped Emerald having a Cooldown Reduction of 6% instead of 3%.
- Removed the Empty Unique Sword.
- Fixed an issue with offhands taking durability damage.
- Fixed an issue where Watcher Stat when under effect of Decree of Frost Augment was giving an unknown stat.
- Fixed some localization in regards to Skill Damage.
- Ender Dragon Tip has been reworked into a generic boss one since that Tip is now obsolete.
- Fixed an issue where Cloth Chest and Pants were able to roll a flat MS stat meant for Helmets and Boots.
- Fixed an issue where config to fix inaccessible Undergarden chests was not applying correctly.
- Fixed Damage Received stat capping incorrectly.
- Fixed anti-mob farm not affecting Vanilla loot.
- Fixed an incorrect recipe for Epic Armor Crafting Soul.
- Fixed stat soul bugs.
- Fixed broken Champion Ascendancy perk.
- Fixed broken Reset Potion recipes.
- Fixed some issues with the Mega Torch working in the End.
- Fixed infinite raid glitch.
- Fixed Virulence Hearts effect showing up on GUI.
- Fixed Support Gem rewards of Page 8 of the Prologue Chapter by removing the incorrectly placed level 20 Support Gem.
- Fixed quest tooltip error in Professions Chapter.
- Fixed some recipes not staying disabled.
- Create memory leak has been fixed.
- Some dupe methods have been patched.
- Fixed Necromantic Defenses giving way more Summon Health than intended.
- Augment Effect stat has been fixed.
- Fixed a typo where the Arcane Potion was giving Melee Skill Damage instead of Magic Skill Damage.
- Thrown weapons should work now?
- Skills that affect and refer to summons now only apply to Mine and Slash summons. No more exploding Chocobos.
- Localization fixes.
- Mine and Slash item inventory interactions works properly now.
- Prophecy Unique reward now correctly gives any Unique including the Prophecy Uniques, instead of only the Prophecy Uniques.
- Summoned mobs now despawn correctly.
- Support Gems no longer rarely drop on death.
- Leech stat is fixed.
- Phys Conversion stat is fixed.
- Mobs should no longer despawn from maps upon death.
- Fixed a bug where Lootr chests were spawning in Maps.
- Projectile Protection enchant compat should be fixed.

### Mod Updates
- Updated over 120 mods.
- Updated Forge.
- Updated Complimentary Shaders.
- Added Combat Music.
- Added Chipped.
- Added Construction Wand.
- Added Bosses of Mass Destruction + CERBON's API.
- Added CrashExploitFixer - fixes an exploit.
- Added Moog's Nether and End Structures - new structures to explore!
- Added Sea Dwellers - find new underwater "villages" of Sea Dwellers and exchange Aquamarine for goodies!
- Added Pots and Mimics.
- Added Formations Nether - even more Nether structures!
- Added Loot Beams: Relooted!
- Added Dimensional Threading Reforked - EXPERIMENTAL.
- Added CullLessLeaves Reforged - improves client-side performance when near trees.
- Added Quest Freeze Fix.
- Removed Overworld Mirror Dimension. We don't really need it anymore, and it doesn't work too well.
- Removed FTB Quest/Advancement Optimizer.
- Removed WorldEdit from clients due to a memory issue.
- Removed Xaero's Minimap & World Map - Waystones Compatibility due to a major inconvenience in MP. If you're playing SP, feel free to re-add.