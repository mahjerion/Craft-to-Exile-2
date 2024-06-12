# Archived Changelog

## [0.5.2b] - 2024-02-16

### Updates
- Offset player Health so that instead of having a flat +60 and 40 that scales with level, it's now 50 and 50. This should result in more Health at higher levels.
- Reduced player Mana and Energy by about 16%.
- Reduced base flat Magic Shield on Cloth Chest by about 25%. Other sources remain unaffected.
- Reduced Health and Magic Shield scaling on Gong Strike, Whirlwind, and Blizzard.
- Increased Golem damage per level.
- Golems now have some innate Threat Generation.
- Increased Wind Slash damage by about 20-25%.
- Increased Quake damage by about 8%.
- Increased Quake radius from 1.5 to 2.
- Ghast and Fortified Reflexes penalties are slightly higher (-25% to -33%).
- Summoner Game Changer Talent now provides -50% Golem Damage instead of -90%.

### Fixes
- Fixed GMP Barrage having +4 Projectiles instead of +6.
- Hopefully fixed some server configs not applying (Stamina removal for example). If not, you may need to manually copy the files from defaultconfigs into the serverconfig folder of your world save.

## [0.5.2] - 2024-02-16

### Updates
- Undying Will has been reworked completely. Instead of briefly providing large amounts of Damage Reduction and other attack stats, it now increases Damage Taken slightly and grants the user the Berserk effect on kill for a short duration (10s). You can have up to 10 stacks of Berserk, with each stack increasing your Movement Speed, Attack Speed, and Cooldown Reduction.
- Reduced Quake's explosion damage radius from 3 to 1.5. Quake was unintentionally hitting mobs with every explosion. It can still do that with some investment.
- Quake now ticks every 4 ticks instead of 3 and travels a little further.
- Wind Slasher now moves twice as fast but travels half as far.
- Wind Slasher damage has been reduced by 33%.
- Leap now uses charges instead. The cooldown and charge regen rate have been modified accordingly.
- Lowered volume of Sharpen.
- Piercing Dagger Throw and Puncture Bleed Damage bonuses have been doubled.
- Reduced the damage of Minstrel skills by about 10-20%.
- Reduced Mana and Energy Regen from Hymn of Vigor.
- Reduced Damage Reduction and Health/Magic Shield Regen from Hymn of Perseverance.
- Changed flat Critical Hit to percent in Hymn of Valor.
- Increased Player starting health to 100, from 60. Note that this extra 40 health does NOT scale with level.
- Reduced mob damage scaling by about 33%.
- A new currency has been added that can increase the rarity of a Map. Maps now also drop as Common rarity only. The idea with this change is so players can essentially "choose" what type of challenge they want rather than be at the mercy of RNG rarity drops. Quest has been updated to reflect this change.
- Updated Map Affixes to be more in line with Augment and Support Gem variance changes.
- Some of the more egregious Map Affixes have also been toned down (extra damage, crit).
- Map Tier Health scaling has increased. Damage remains the same.
- Sources of flat Magic Shield on gear has been buffed by roughly 100%. Rings and Tomes base values are unchanged.
- Mana on Basic Attack Hit has been removed from all non-Mage weapons. It has also been reduced slightly on Mage weapons.
- Full Talent Reset potion recipe now uses Utherium Crystal instead of Blue Skies Sol Nut.
- Golemancer Game Changer Talent now provides flat Summon Health and flat Golem Damage instead of more.
- Summoner Game Changer Talent now grants -90% LESS Golem Damage.
- Mana Battery now applies before Magic Shield. The description has been updated.
- Rebalanced Spear and Helmet/Boot flat Damage/Defense prefixes. Spears get buffed and Helmets and Boots get nerfed.
- Passive Block Chance now shows up in the Hub GUI.
- Some new upgrade paths for Sophisticated Stack Upgrades have been added.
- Changed Gate of Labyrinth's recipe to use Froststeel Ingots instead of Forgotten Ingots.
- Completely removed Stamina from the game. Quests have been updated to reflect this.
- Increased max Skill Level with + Skills. Before it was 21 (+5), now it's 24 (+8). Half of the max Skill level without bonuses seems about right.
- Removed sources of the Skelewag Skull and Tendon Whip weapons. The Tendon Whip may make a return in the future...

### Fixes
- Fixed some incorrect Quest dialogue in Professions tab.
- Fixed Rested Experience death penalty being inverse.
- Fixed Resource Pack for RS not being on by default.
- Disabled WSTweaks blades due to a bug.
- Hopefully fixed an issue where Dimension Runes weren't dropping as frequently as they should have been.
- Fixed Profession's recipe for level 41-100 Dexterity Potion being broken.
- Fixed players spawning in bizarre biomes such as the Ocean due to presence of village.
- Fixed some stat localization errors.
- Fixed Toq Rune still having range.
- Fixed Stare of Abyss giving MORE Chaos Resist instead of flat.
- Fixed Summon Capacity perk accidentally being mislabeled as a Game Changer Talent.
- A bunch of stat fixes.
- On Kill effects have been fixed. They were not working when kills were from Basic Attacks.
- Magic Shield players rejoice! Mobs have a short Basic Attack cooldown now. This should prevent players from being melted from mobs with not cooldown such as Slimes.

### Mod Updates
- Updated Chunk-Pregenerator, Cuisine Delight, Domum Ornamentum, Embeddium, Kobolds, Lightman's Currency, Mine and Slash, MineColonies, Moonlight, Multi-Piston, Mutant Monsters, Oculus, Puzzles Lib, Sophisticated mods, Supplementaries.
- Added Biome Spawn Point - prevents players from spawning in the Ocean...
- Added Fast Paintings - will help with performance.

## [0.5.1] - 2024-02-12

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!

### Updates
- Added a new Lv. 1 Augment called Basic Augment which buffs Basic Attacks and Attack/Draw Speed. This Augment has been added to the appropriate Quest rewards.
- Augments' stat variance has increased. Higher Rarity Augments will be more powerful.
- Attack Speed sources have been buffed drastically (almost 100% across the board).
- Increased player base Mana and Energy by 50%.
- Increased kill experience rewards by 100%.
- Lowered Campaign Quest experience rewards by 50%.
- Rested XP death penalty is 25% instead of 50% now.
- Added more types of weapons to "Your First Weapon" Prologue quest.
- Doubled duration of Undying Will and Mirror Image. Due to a bug, stat bonuses from effects take a bit of time to apply so these buffs were realistically lasting like 1-2s.
- Increased Minstrel's Hymn durations by 50%.
- Increased Prestissimo's duration from 10s to 12s.
- Buffed Minstrel's Hymns and Prestissimo. Also improved their Skill descriptions.
- Sharpen has been reworked a bit. It now stacks up to 5 instead of 10, and the Attack Speed buff has decreased by about 33% (max of 30% per stack to 20% per stack). Cooldown and duration of the buff have been reduced to be in line with other stack-based buffs. It was supposed to be a single time use buff, but due to players providing positive feedback regarding the stacks, I've decided to keep it that way.
- Execute and Snipe damage has increased by about 30%.
- Double Strike damage scaling has increased slightly. At max level it now does 4% more damage.
- Flicker Strike damage has increased by about 16%.
- Whirling Blades damage has increased by 100%.
- Piercing Dagger Throw damage has increased by about 6%.
- Ricochet Shot damage has increased by about 5%.
- Fan of Knives damage has increased by about 16%.
- Increased Health scaling on Gong Strike and Whirlwind in Defender Stance by about 50%.
- Profession Armor crafting now also requires a Leather. This also fixes the Gear Crafting issues.
- Increased Map mob density by about 100%.
- Removed Master Bag Curios slot.
- Further increased MineColonies Citizen stats to maybe help with Husbandry.
- Map drop rate in Maps has been increased SUBSTANTIALLY (about 6x).
- Reduced Map difficult per Tier by about 50%. Maps at higher difficulties were way too difficult.
- Since Runes don't have rarity, they now all provide the same stats every time (no range). This is how it worked in D2 as well.
- Rune drop rate has been reduced.
- Augment Gems have been rebalanced a bit. In general, their ceiling is higher and floor is lower. This is to give higher rarities more impact.
- Flat Weapon Damage and Defense from flat Weapon Damage and Defense prefixes has been lowered.
- Prefix sources of percent Weapon Damage and Defense have been buffed slightly.
- The prefix that gives flat and percent Weapon Damage has been changed to Accuracy and percent Weapon Damage.
- Lanterns no longer set fire when they break.
- Base Stamina, Max Stamina, and Stamina gain per Vessel has been tripled.
- Mob Rarity weights have been adjusted. Previously, the weights for Common to Mythic were 243:81:27:9:3:1. They are now 1024:256:64:16:4:1 instead.
- Mob Rarity difficulty scaling has been changed slightly. Uncommon to Rare have slightly less Health, and Legendary and Mythic mobs now have more Health. Mythic mob have about 40% more Health than previously. Stat scaling has also increased slightly, with Mythic mobs now having about 20% more stats than previously. Damage has also been increased very slightly (12.5% by Mythic).
- Mob Rarity rewards scaling has been increased substantially. Mythic mobs rewards have almost been tripled.
- The idea with the above Mob Rarity scaling changes is to make them a little more rare and difficult, but much more rewarding. So instead of "dreading" these mobs, one might look forward to the challenge.
- Gear Rarity Salvage Experience and Output scaling has been increased. Mythic Salvage Experience and Output has increased by 67%.
- Changed default Chunk Loader keybind to F8.
- Drastically nerfed sources of Magic Find and Increased Quantity.
- Lowered particle count of Blizzard, Chilling Field, and Frozen Orb.
- Doubled Blood per 10 Strength and Health restoration effects on Blood for Blood Mage.

### Fixes
- Fixed Canary config file.
- Fixed Leap having incorrect tags.
- Fixed Main Menu being laggy.
- Fixed Flame Splash Potion crashing clients.
- Fixed Inventory functions not being available due to the pause function. Disabled the pause from ModernUI.
- Fixed Leap shooting you way up.
- Fixed Battery Fusilade not being learnable and therefore causing NPE issues.
- Fixed Gateway of Overworldian Nights causing NaN issues.
- Bows and Crossbows can no longer roll Warlord's prefix which provided Attack Speed.
- Fixed incorrect quest dialogue in Act V.
- Fixed some Skills still having only 1s cooldown instead of 2s.
- Fixed Gear Crafting issues with Armor recipes taking priority.
- Fixed a bug where Vital Points wasn't working as intended.
- Fixed a bug where Skills and Summons would hurt Summons.
- Fixed a bug where you could still cast Skills that cost Energy, even though you were at 0 Energy.
- Fixed a bug where Weapon Damage stats weren't working as intended.
- Fixed an issue where Blood Mage's Blood was not regenerating if your Health was full.

### Mod Updates
- Updated CoroUtil, Crabber's Delight, CraftPresence, CraftTweaker, Create Additions, CreativeCore, EMI, FastWorkbench, Framework, JEI, Lightman's Currency, Mine and Slash, MineColonies, Moonlight, More Sniffer Flowers, Not Enough Animations, PacketFixer, Placebo, Resourceful Lib, Saturn, Showcase Item, Supermartijn's Core Lib, Supplementaries, WATUT.

## [0.5.0] - 2024-02-08

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!

### Updates
- Added a BRAND NEW CLASS: The Rogue - the Rogue can specialize in quick movements to overwhelm the enemies, or focus on devastating blows. With the Rogue, you can empower your Basic Attacks to deal tons of damage, or go invisible to strike your enemies with a critical back stab. Don't want to get too close? Keep your distance with high-speed movement options and Crossbow Skills!
- Added 1 new PATREON-designed Unique and 1 new PATREON-designed Runeword! Thanks to Captain Clogs and Namsic for your continued support! If you would like to support me on Patreon, please visit https://www.patreon.com/crafttoexile!
- PATREON-designed Unique (Captain Clogs): Oathbreaker - This Unique Hammer grants large bonuses to Curse users, at the expensive of their own Health...
- PATREON-designed Runeword (Namsic): Tempest - This Hammer Runeword augments Galvanic Blade's Discharge, giving hits from Discharge a 50% chance of casting a new Skill, Lightning Bolt (see below), and large bonuses to Basic Attack Damage and Speed.
- New Skill: Lightning Bolt - strike the enemy with a quick bolt of lightning, dealing high amounts of Lightning Damage to the target.
- Added a new low-level Necklace Runeword: Impedement - reduces your experience gain to 0.
- Added a new mid-level Ring Runeword: Prism - provides Elemental Resistances and a bit of Health.
- Added 7 new Runes that can only be found from Bosses in dimensions. Each Rune is associated with a dimension. For example, the new Owd rune can only drop from Hermit Abysswalkers or the Invoker.
- Regarding above, Quest descriptions for the Bosses have been updated, and a new Quest explaining this has been added in Act I.
- Some existing Runewords have had their required Runes updated to incorporate the above change.
- Added 4 new Uniques with custom assets (Thanks Nozium!) that drop in Map Tier 80+ - Last Tracker Uniques which comes in a set of 4 (Helmet, Chest, Legs, Boots). This set of Uniques increases Critical and Energy stats and provides a bunch of speed! It also converts Energy into Physical Damage...
- Dexterity now provides a bit of Draw Speed as well.
- Critical Damage nodes on the Talent Tree have been buffed.
- Critical Hit passives have been buffed.
- Resource on Hit Support Gems have been converted to Steal gems (Lifesteal + Spell Lifesteal, Spell Manasteal, Energysteal). They have also been converted to Lv. 20 Support Gems. Note that besides now also being Lv. 20, Magic Shield On Hit Support Gem remains unchanged.
- Totem Damage and Cooldown Support gem has been reworked to give much more CDR but now reduces damage.
- Added 2 new Support Gems: Cluster Traps Support Gem (Lv. 30) and Trap Damage Support Gem (Lv. 10).
- Quest rewards and shops have been updated to reflect the above.
- Player base resource regen has been reduced by 20%.
- Lowered Proc Skills Bone Shatter and Discharge cooldowns from 2s to 1s.
- Skill cooldowns is now minimum of 2s instead of 1s. This basically affects spammables.
- Mage Circle has been buffed. It now has a radius of 4 rather than 2. The buff also lasts 5s instead of 1s, so you can leave the circle temporarily and retain the buff. Mage Circle cooldown has also been reduced from 30s to 15s.
- Refresh and Mage Circle no longer cost Mana.
- Fire and Frost Golem Basic Attacks now deal their respective element.
- Blizzard, Frozen Orb, and Chilling Field no longer apply Bone Chill.
- Frost Armor is now called Mage Armor.
- Bone Shatter has been renamed to Elemental Burst.
- Elemental Burst now deals Cold and Fire damage, rather than Cold and Physical.
- Elemental Weakness has been renamed to Scorched. The effect remains the same.
- Mage Armor now grants the caster the ability to trigger Elemental Burst (instead of Bone Shatter) on certain spells only (Blizzard, Frozen Orb, and Chilling Field) if the target has the Bone Chill effect.
- Mage Armor now also grants the caster the ability to trigger Elemental Burst on certain spells (Armageddon, Steam Cloud, Meteor) if the target has the Scorched effect.
- Skill Tooltips have been updated to reflect the above.
- Frost Nova now heals nearby allies.
- Frost Golem Summon Damage per level has increased from 2-20% to 4-40%.
- Lowered Frost Nova's radius from 7 to 6.
- Chilling Field cooldown is now 10s instead of 1s (oversight).
- Magma Orb damage has been reduced by about 15%.
- New Lv. 5 Fighter Skill: Leap - jump forwards to quickly reposition yourself.
- Undying Will no longer costs Mana.
- Grapple now has a 6 second cooldown.
- Improved Grapple visuals.
- Wind Slasher Mana Cost has increased.
- Wind Slasher weapon scaling per level has decreased slightly.
- Summon Skeletal Army summons now last 12s instead of 10s.
- New Lv. 20 Minstrel Skill: Ensnaring Melody - play an alluring song which affects an area and deals Physical Damage to enemies each second. Charmed enemies are also slowed and dealt additional damage. The Skill also has innate Spell Lifesteal.
- Prestissimo no longer costs Mana but now lasts 10s instead of 15s.
- Prestissimo now also increases Draw Speed.
- Shooting Star is now called Mending Ostinato. It now chains as well.
- New Lv. 25 Shaman Skill: Lightning Warp - quickly teleport yourself forward. Leveling up this skill reduces the Mana Cost and cooldown.
- New Lv. 10 Shaman Skill: Cyclone - send out a torrential gust of wind, dealing damage quickly to enemies caught in the projectile's path.
- Improved Lightning Skill visuals.
- Lowered Astral Totem Mana recovery per second by about 40%.
- Increased Thorn consumption damage by 200% (tripled).
- New Lv. 10 Hunter Skill: Hunter's Mark - fire an arrow that marks the first enemy struck. Marked enemies take extra damage, and are targeted by your Summons.
- Doubled the Weapon Damage scaling of Enflamed, Envenomed, and Encased from the Ranger Traps.
- Poison Trap has been renamed to Death Trap, and now additionally pulls enemies into its position upon activation.
- Arrow Storm has been reworked to be more Arrow Storm-like.
- Improved Charged Bolt visuals.
- Quickdraw now provides a buff that increases Draw Speed rather than instant arrow shooting.
- Quickdraw now lasts 8 seconds instead of 6 seconds.
- Craft Arrows no longer costs Mana.
- Disabled WATUT sounds.
- In addition to Paragliders, we now have Heart Containers and Stamina Vessels from the Paraglider mod. Heart Containers increase your Health by 2. You can get a maximum of +200 BASE Health from Heart Containers (that's flat Health btw!). Stamina Vessels increase your Stamina by 100. You start with 1000 Stamina and have a cap of 3000 Stamina. You can find Spirit Orbs randomly in chests which can be used at Goddess Statues to exchange for these Containers/Vessels. You can also sometimes earn Heart Containers from killing Bosses!
- Running and Swimming now consume Stamina.
- Added new Prologue and Act I quests for the above.
- Lowered SOL bonuses to Move Speed.
- Updated some misleading stat names such as Melee Damage (which is now Melee Skill Damage).
- Due to the found bug, reduced Map Tier difficult multiplier from 25% to 10% per Tier.
- Added a new Quest explaining Character Resistances in Act III and how it drops as you level.
- Moved Campaign Gem and Unique Shops to a separate Quest tab.
- Mobs have a little bit of innate Accuracy and Dodge now.
- The Forgotten Guardian now spawns at level 35 instead of 40.
- Increased Profession Lesser/Medium/Greater resource drop rates by 100%.
- Increased Husbandry Profession drop rates by 75-100% (total of 200% increase for the Lesser/Medium/Greater resources due to above change).
- Profession recipes for Alchemy, Cooking, and Enchanting/Gear Crafting have been updated to include resources from higher level dimensions.
- Profession recipes for level 1-20 no longer require a Lesser Resources, to make them streamlined.
- Quests have been updated to reflect the Profession changes above.
- New Quest in Professions to further help with learning how to craft.
- Profession Tool Affix names and descriptions have been updated to be more detailed.
- Added a blurb about ATMs in the Prologue Quest line.
- Rings and Necklaces now appear on Inventory HUD GUI by default.
- Updated Combat Roll UI position.
- Buffed Souring Winds enchantment substantially.
- You can now cage Mooblooms.
- Default dot colours in Xaero's Minimap have been updated. Hostiles are now red, friendlies are green, neutrals are white, items are yellow, and tameables are light blue.
- Changed default rendering speed for Dynamic Lights to Normal, from Real-Time.
- Re-enabled Explorer's Compass and Nature's Compass in Blue Skies dimensions... for now.
- Lowered Quick Stack radius a bit.
- FTB Right-Click with Hoe/Axe/Harvesting has been enabled.
- Re-enabled Flying Furball in Doggy Talents.
- Disabled Lootr chests from spawning outside of world border. Should improve performance.
- Added a little warning on Open to LAN.
- Drastically lowered impact and spawn chance of the WTF Boom Creeper. Also, it no longer says WTF.
- Rebalanced Farming for Blockheads' Market prices to be much more reasonable.
- Lowered Rune drop rate.
- Lowered Chocobo sound volume.
- Auras/Aura Gems have been renamed to Augments.
- Chunk Loader items have been added. There are 4 types: single, basic, advanced, and ultimate. You can craft these at anytime. A Quest has been added to introduce these.
- Updated Refined Storage textures - credit goes to BlackAuresArt!
- Added a Curios slot for M&S Master Bag.
- Lowered Player starting health a bit to offset new Heart Containers.
- Updated more loot tables to include Mine and Slash loot - especially in other dimensions.
- Increased frequency of Lesser/Medium/Greater Crystals from MineColonists Lucky Ore.

### Fixes
- FIXED A HUGE BUG WHERE MAP AFFIXES AND TIER/RARITY BONUSES WERE NOT APPLYING.
- Fixed Hammers still requiring Energy.
- Fixed Bounty Board quest in Act II requiring a quest from Act III.
- Items previously not viewable in JEI are now viewable in JEI (now EMI).
- Fixed some missing and broken localizations.
- Fixed a bug where Nature's Balm was Weapon Scaling cap was too low.
- Fixed a bug where Minstrel Skills were failing to check for the Charm effect and always applying.
- Fixed Money Mending costing too little on servers.
- Implemented some fixes that should hopefully prevent chunk loading issues seen in Blue Skies dimensions.
- Fixed quest bugs.
- Fixed Lightman's Persistent Trader issues.
- Fixed an issue with FTB Teams + Quests where Quests rewards could be earned twice.
- You no longer get Farming EXP from Potatoes.
- Fixed Soaring Winds not working in Elytra Slot.
- Fixed the Curios slots a bit.

### Mod Updates
- Updated Architectury, Aggro Indicator, Better Archeology, Better Combat, BlockUI, Bookshelf, Canary, Chat Heads, Citadel, Comforts, CraftTweaker, Create Crafts and Additions, Cupboard, Curios, Domum Ornamentum, Embeddium, Embeddium++, FindMe, FTB Quests, Geckolib, JEI, Kobolds, Lightman's Currency, Lootr, MineColonies, Mine and Slash, ModernFix, Moonlight, More Overlays, More Sniffer Flowers, Oculus, Puzzle Dungeon, Puzzles Lib, Resourceful Lib, Showcase Item, Sophisticated mods, Sound Physics, Structurize, Supplementaries, Textrues Embeddium Options, Traveler's Titles, WST, Xaero's, YUNG's API.
- Added ImmediatelyFast.
- Added EMI.
- Added Modern UI - adds improvements to the UI.
- Added Jade Addons.
- Added Musical Instrument Minecraft Interface - provides more tools for us to use.
- Added Chunk Loaders.
- Added Paraglider.
- Removed Better Chunk Loading.
- Removed Reblured - replaced by Modern UI.
- Removed FPS Reducer - replaced by Modern UI.
- Removed Ding - replaced by Modern UI.
- Removed WI Zoom - replaced by Modern UI.
- Removed Music Maker Mod.

## [0.4.1] - 2024-01-24

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!

### Fixes
- Fixed Hellish Gateway not showing up.
- Fixed Chain Lightning using way too many particles.
- Fixed Magma Orb crashing clients on servers.
- Fixed Talent Point reward for Wither kill.
- Fixed missing Open to Lan button.

### Mod Updates
- Updated Illager Invasion, PuzzlesLib, Structurize.

## [0.4.0] - 2024-01-24

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!

### Updates
- Added a new PATREON-designed Unique! Thanks to quad01man for your support! The Written Word. This Unique Tome grants the user a new Skill called Grand Cross and provides the user with stats that would benefit a healer. If you would like to support me on Patreon, please visit https://www.patreon.com/crafttoexile!
- Added a new Necklace Runeword: Rain - a low-mid level Runeword for Totem users.
- New Skill: Grand Cross - deals Lightning damage in an area and heals allies around the caster 3 times.
- Added a new Hammer/Spear Runeword: Call to Arms - this Runeword grants you access to a new buff Skill, Battle Orders!
- New Skill: Battle Orders - increases nearby allies' Skill Damage, Health, and Magic Shield for a short duration. Higher levels increase the duration.
- Added 6 more new Uniques! Cloak of Defiance makes damage taken go to Mana instead of Health. Also find the Genji set (Helmet, Chest, Leggings, Boots) and receive a boost to your melee damage. Each piece of the set gives you a 25% chance to trigger the new Skill, Slice on each hit! This skill can only trigger once off cooldown. Lastly, also added Martyr's Blade which takes advantage of the Terrible Sword's self-damaging mechanic to do tons of damage!
- New Skill: Slice - deal Physical damage in an area around you.
- New Skill: Splinter - linked to Chilling Touch, summon hits can proc this Skill.
- The Terrible Sword is no longer craftable.
- Increased scaling of resources with damaging Skills, such as Gong Strike, Chain Lightning, etc.
- New Lv. 15 Shaman Skill: Galvanic Blade - imbue your weapon, converting your Physical damage into Lightning damage. Also gives your critical Lightning damage a chance to cast Discharge, which does Lightning damage in a small area around the struck enemy.
- New Lv. 25 Shaman Skill: Battery Fusillade - fire out a stream of Lightning orbs to wreak havoc on your foes. These orbs scale highly with Mana, and the Skill intrinsically provides Critical Damage boost.
- Changed Magma and Frost Totem placement to behave more like other totems.
- Lightning Nova has been reworked into Charged Bomb. Throw out a ball of lightning which explodes upon impact, dealing Lightning damage in an area.
- Improved Shaman Lightning Skill visuals.
- Chain Lightning projectile now lasts a bit longer.
- Lightning Spear projectile now lasts a bit shorter.
- New Lv. 20 Sorcerer Skill: Steam Cloud - provides the user with a stack of Heat that deals AOE Fire Damage every 0.5s around the caster. Each cast of Steam Cloud increases the effect stack by 1, further increasing the damage and area of Steam Cloud.
- New Lv. 15 Sorcerer Skill: Frost Armor - buffs the user, increasing their Magic Shield. Also causes Cold Damage on Frozen enemies to have a chance of casting Bone Shatter, which deals Cold and Physical damage in an area around the enemy.
- Fire Nova has been reworked into Magma Orb. Summon a fire orb at your position which pulsates every second, dealing fire damage in an area. After 3s, the orb explodes, dealing more damage in a larger area.
- Explosive Arrow, Meteor, Armageddon and Meteor Arrow no longer apply Elemental Weakness. Only the new Magma Orb, Fireball, Fire Trap, Flame Strike, and Magma Totem do.
- Elemental Weakness effect has been buffed. It's now -25% Elemental Resist instead of -10%.
- Fireball now has increased Burn Damage that scales with the Skill's level.
- Blizzard now has increased Freeze Chance that scales with the Skill's level.
- Frozen Orb damage has been reduced by about 30% at higher levels.
- Heart of Ice has been reworked to give Magic Shield for 10s to nearby allies, and also provide a huge boost to Magic Shield for 5s.
- At max level, Fighter and Defender Stance penalties are 0. Buffs have been toned down to compensate.
- Melee Skills' damage scaling has increased by about 10% across the board (except Quake).
- Undying Will damage reduction has been reduced slightly.
- Pull is now called Grapple, and targets enemies in front rather than around. It now also taunts enemies if you're in Defender Stance.
- New Lv. 15 Warlock Skill: Putrid Breath - lay waste to enemies in front of you with slow-moving clouds that deal Chaos damage upon impact. This skill has increased Poison Chance.
- Poison Cloud now has increased Poison Chance that scales with the Skill's level.
- Reworked Chilling Touch. It's still a melee Skill that causes your summons to attack the struck enemies, but now it also applies a debuff that gives your summon hits a chance to proc Splinter, which deals physical damage in a small AOE.
- Reduced the Mana cost of Explode Minions.
- Reduced the Mana cost of Summon Skills by 25%.
- Reduced the cooldown of Return Summons from 15s to 6s.
- Return Summons no longer attempts to stun, slow, or damage your pets.
- Ritardando Slow has increased in duration by 66%.
- Resonance now fires 3 projectiles and travels very quickly.
- Resonance damage scaling has been increased. Technically, the damage scaling should have been lowered to compensate for the above, but it turns out I forgot to buff this Skill during one of my earlier buffs so the damage was lacking THAT much.
- Doubled the speed at which Trap Skills are sent out at, thereby increasing their distance.
- Added Weapon Skill tag to some Skills that were missing (such as some Ranged Skills).
- Increased Explosive Arrow's area by 50% and increase damage scaling slightly. It also no longer applies a slow.
- Added a new Draw Speed stat that can be found on Bows and Crossbows. The stat increases the rate at which you prepare your arrow.
- Added new implicit Bow and Crossbow types that have Draw Speed.
- Talent Tree Attack Speed nodes now also provide Draw Speed.
- Added a new rarer Pickaxe stat: Block Reach - increases the range at which you can mine/interact with blocks.
- Changed most instances of flat Critical Hit to increased.
- Player base Critical Hit is now 5% instead of 1%.
- Buffed Accuracy Support Gem.
- Changed Accuracy Support Gem to Lv. 1.
- New Lv. 10 Support Gem: Faster Cast Support Gem.
- New Lv. 40 Support Gem: Magic Find Support Gem.
- The above Support Gems have been added to their respective shops. Magic Find Support Gem is a high level rare drop-only Support Gem.
- Mine and Slash armor crafting now costs 4 Stones instead of 2, since we now have the type modifiers.
- Mob Affixes have been reworked completely, we have over 10 new mob affixes and some have been changed to suffixes.
- Reduced sources of core stats.
- Due to a bug with regen being double what it should have been, I have buffed Increased Mana/Energy Regen per point of Int/Dex, Increased Mana Regen from Static, Passive Skills, etc.
- Spice of Life rewards have been revamped. Rewards are slightly easier to reach, and you can get new bonuses such as Block Reach, Movement Speed, and Combat Roll Distance!
- Moved the quest from Culinary Delights regarding Spice of Life to Act II for more visibility.
- Mine and Slash food and potion buffs have been changed slightly.
- Reduced Dodge from mob affix Evasive.
- Acrobat now gives flat Spell Dodge and reduces armor.
- Mana Battery damage reduction has been reduced from 50% to 35%.
- Mana Battery no longer gives Lightning Resist and now instead reduces max Energy.
- Increased Gateway contribution towards anti-farming experience and drop penalty by 33%.
- Endless Gateways have been turned into non-endless Gateways.
- Gateway drops have been reworked slightly. You'll no longer get useless discs, saddles, horse armor, etc. The drops have also been reduced a bit and weighted more heavily towards Mine and Slash items.
- Hellish Fortress Gateway boss is now a Wildfire rather than a buffed Piglin Brute.
- Increased experience gain from kills by 150%.
- Increased Favor loss on death by 100%.
- Maps now start dropping at level 55 instead of 60.
- Increased Map difficulty.
- Reduced Map experience penalty for lower rarities.
- Buffed Map Mob Affixes for Elemental Damage.
- Slightly increased Map sizes and pack size.
- Added a new option once you reach Act IV to reset your Campaign quest progress. This is mostly useful for players looking to make new characters on the same world. This will NOT reset any Talent Point rewards you've earned.
- Quests not found in the main Acts now provide experience scaled to your level. It's not a percentage, as it would be too strong at higher levels (people could just horde % rewards till 99), but it should tremendously help the leveling experience and reward players for doing non-M&S things.
- Diving Kit and Three-Bolt Helmet quests in Act III have been properly reassigned as Main Quests.
- Professions quests now also provide experience.
- Reduced experience rewards from Quests in the main Acts slightly.
- Made some changes to streamline quest progression. Also highlighted the Professions quest tab in a Prologue quest.
- Basic Attacks no longer cost Energy.
- Lowered Basic Attack damage of Bows and Crossbows to compensate for the above.
- Increased base Mana Regen substantially. After the double tick bug is taken into account, it's still a 25% increase from before.
- Increased base Energy Regen, but after the double tick bug is taken into account, it's about a 30-40% decrease from before. As Energy is now only really used for Skills and Blocking, it should be okay. Some item sources of Energy Regen are still slightly higher than Mana.
- Axe and Hammer Basic Attack damage multipliers have been swapped because apparently Axes are slower.
- Lowered sources of Block Chance or changed them to percent rather than flat.
- Shields now have innate Block Chance stat.
- Block Chance stat has been renamed to Passive Block Chance and the description has been updated.
- Guardian Aura has been renamed to Vitality Aura since we have 2 Guardian Auras...
- Updated Quest rewards to reflect above changes.
- We now have a Target Dummy that displays your DPS dynamically!
- Set GUI back to what it was previously. The GUI at the bottom is too difficult to see.
- Runed rarity items are now a bit more rare.
- Added the Mods button to the UI.
- There is now a 10% experience boost for each character you have that's above your current character.
- Rare items can no longer roll 2 sockets.
- Added Mine and Slash items to some custom mod loot tables. Notably, Farmer's Delight loot tables and Terralith loot tables.
- General performance improvements.
- Updated the Disassembler's Learning Method's recipe to make more sense.
- Potentially removed useless enchantments on certain weapons. Such as Sharpness and Sweeping Edge. They may still be obtainable, but most sources (incl. enchanting) should be removed.
- Anti-mob farm doesn't apply to some drops now.
- Updated some UI descriptions.

### Fixes
- Another attempt at fixing the Blue Skies bosses (seemed to actually fix it this time).
- Fixed incorrect information panel in Class GUI.
- Moved the default Inventory HUD to bottom right.
- Fixed incorrect or missing localization.
- Fixed an issue where Pull (now Grapple) would sometimes not apply Shred or Stun.
- Fixed a bug where Wood Staves weren't able to roll Looting.
- Fixed a stat sync issue.
- Sorting inventory no longer causes Mine and Slash items to auto-insert/apply.
- Fixed an bug where player tick events were happening twice as many times as they should have. This means if you had 30 Mana Regen, you'd regen 60 every second...
- Some Stat Soul bugs should be fixed.
- Fixed right-clicking with Hoe not harvesting.
- Jewels no longer generate as Runed.
- Souls/Runed issues should be resolved.
- Fixed a bug where Unique items could roll 2 sockets.
- Resonance no longer mistakenly applies Charm to enemies upon hit.
- Disabled Eye of the Blaze/Shulker/Pillager from Nature's Aura as they were causing crashes. They're also kind of obselete due to Explorer's Compass.
- Fixed some localization.

### Mod Updates
- Updated Air Hop, AmbientSounds, Better Chunk Loading, BlockUI, Canary, Combat Roll, CreativeCore, Doggy Talents, Embeddium, Embeddium++, FancyMenu, Farmer's Delight, FTB Library, FTB Quests, GeckoLib, JadeColonies, Kiwi, Konkrete, Mine and Slash, MineColonies, ModernFix, Moonlight Lib, PuzzlesLib, Structurize, StyleColonies, Supplementaries.
- Added MmmMmmMmmMmm (Target Dummy).
- Added Chat Colours - text formatting in chat.
- Added Ender Trigon - revamps the Ender Dragon boss fight.
- Added Jump Boat - you can now jump while boating.
- Added What Are They Up To - see what other players are doing.
- Added Damage Vignette.
- Added Forge Config Screens - lets you modify configs from in-game.
- Added FTB Quests and Achievements Optimizer.
- Added Inventory Essentials.
- Added Inventory Sorter.
- Removed Chess mod. I mean... yeah.
- Removed Inventory Profiles Next.

## [0.3.1b] - 2024-01-09

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Fixes
- Fixed broken Gateway of Darkness recipe.
- Fixed missing localization.
- Fixed an affix causing players to brick.
- Fixed errored Gateways (the rest of them).

### Mod Updates
- Updated Skin Layers.

## [0.3.1] - 2024-01-09

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
- Selecting your Class will create a shortcut to the Class tree in the Class GUI.
- Large update to the gear affix pool. Offhands now have many more interesting affixes, weapons have new + Skills affixes, and custom weapon types like Hammers, Daggers, and Spears get some more love. 
- Added 3 new Support Gems: Physical To Fire/Cold/Lightning (Lv. 20).
- New Lv. 30 Sorcerer Skill: Blizzard - deal damage in a large area.
- Minstrel Skills can now be used with any weapon type.
- Reduced Mana and Energy Regen per Int/Dex point.
- Reduced base regeneration values by a hefty amount. I did not realize that regeneration was happening every second instead of every 3 seconds. Please let me know if I've overdone the nerf though.
- Buffed Regen passives in Class trees.
- Lightning Spear no longer applies Static.
- Lowered Mana cost of Lightning and Frost Nova slightly.
- Static buffs have been nerfed to be percent rather than flat.
- Reduced Suffix sources of Str/Int/Dex.
- Nerfed On Hit support gems.
- There is a new Status Effect entry in the Hub Wiki.
- When you get hurt with Magic Shield, a sound will now play.
- Sleep percentage required is now 25% of players instead of 50%.
- Experience from Slimes has greatly reduced.
- Renamed Minion Explosion Gamechanger since there's now a Skill with the same name.
- Increased the penalty from multiple projectile support gems.
- Increased PVP damage factor.
- Reduced the duration of the Hymn buffs but also reduced their cooldown.
- Gateway end of wave rewards have been nerfed. Too much loot!
- Changed default M&S HUD to be bottom centered rather than top left.
- Defender Stance no longer periodically taunts nearby mobs. I've upped the Threat Generated stat from it by a lot to compensate.
- Added a new Suffix that increases Str/Int/Dex by percent.
- Changed Grief and Cure Rune order to prevent overlap.
- You will now be alerted why you can't cast a Skill.
- Increased the recipe cost of Extractor.
- Updated default UI a bit.
- Changed loot weights for the simple dungeon chests.
- Rune minimum level req. is now lower across the board.
- Mid-level Runes are now a bit more rare, higher level Runes should be mostly unaffected.
- Mob level variance has been introduced, mobs now spawn +/- 1 levels.
- Item drop level variance has been reduced from 3 to 1.
- Pretty substantial optimization changes on the back-end which should improve server performance and performance in Maps.
- Blacklisted Maps from AmbientSounds, should greatly improve performance in the dimension.

### Fixes
- Blue Skies bosses should take damage from Mine and Slash stuff now.
- Fixed Chaos Resist being 25% higher than it should have been.
- Fixed a suffix incorrectly posing as a prefix.
- Fixed Damage Received showing red when negative.
- Fixed custom weapons using incorrect Stat Soul textures.
- Fixed Anvil Upgrade recipe for backpacks.
- Fixed the Acrobat Gamechanger.
- Fixed Gateway of Darkness recipe being extremely difficult.
- Souls modifiers can no longer be used on non-armors.
- Healing no longer applies Threat.
- Fixed some weird instances of Runed rarity items when they shouldn't have been Runed.

### Mod Updates
- Updated Mine and Slash, Better Archeology, Canary, CraftTweaker, Embeddium++, Enchantment Descriptions, EnhancedAI, Friends and Foes, Minecolonies, Moonlight, Smoothboot, Supplementaries, Resourceful Config, Saturn.
- Removed GML.
- Removed Variable Spawner Hardness.
- Removed Enhanced Visuals - causing issues with Mine and Slash.

## [0.3.0c] - 2024-01-05

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Updates
- Added missing updated textures for Sophisticated mods. Thanks Skullbushi!
- Changed number of sockets based on item rarity. Common to Rare can spawn up to 2 sockets, Epic to Unique can only spawn up to 1. A new type of Runed item can spawn with a minimum of 2 and a max of 6.
- Buffed the damage scaling of almost all Skills.
- Increased the area of Fire and Frost Nova to more appropriately match the visuals.
- Fighter Stances now have a cast time of 0, and last 30 minutes instead of 3.
- Increased the Magic Shield you get from Tomes drastically.
- Changed Mana and Energy Regen from Int/Dex to be percent rather than flat.
- Increased base Energy Regen substantially due to above change.
- Lowered Energy cost of basic attacks.
- Changed Garden of Thorns to apply 1 stack per cast instead of 3. I did not realize it cast 5 times.
- Added a few more Gateway Pearls throughout the Acts as quest rewards.
- Changed the First Weapon quest weapon rewards to Rare Lv. 3 weapons instead of Common Lv. 1.
- Lowered starting resist and subsequent resist bonuses/penalties by a flat -25%.
- Reduced the amount of particles from Fighter Stances.
- Fighter Stance (the offensive one) penalty to damage taken is less penalizing.

### Fixes
- Fixed Summon Skills not working properly.
- Fixed Tridents not being considered Spears.
- Fixed missing Gateway recipes and localization.
- Hopefully fixed a crash related to Canary.
- Fixed an incorrect dependency requirement in Act I.
- Fixed Salvaging and Cooking Stations using incorrect textures.
- Fixed localization error with Of the Yeti and Of the Storm.
- Fixed incorrect armor/pant textures for Rare Plate gear.
- Fixed Shred not doing damage in Defender Stance.
- Fixed Garden of Thorns not casting properly.
- Fixed missing Gateway Pearl rewards.
- Fixed Stat Souls still showing the question mark.
- Removed Illusioner Totem drops. It has been causing issues.

### Mod Updates
- Updated Better Archeology, Not Enough Animations, Shoulder Surfing, CTE2 Essentials, Puzzles Lib, Blue Skies.

## [0.3.0b] - 2024-01-04

### Reminders
- Mine and Slash damage code went through a bit of a refactor, so if you notice anything please let us know!
- Back up your Xaero's folders and your options.txt file just in case!
- If you start the game and you have like 3 different things bound to the "R" key, the custom keybinds probably didn't apply for you. You can get them by resetting your keys in the keybind menu, or you can find them in /config/defaultoptions as "options_default.txt"!

### Fixes
- Fixed Fighter Gong Strike and Stance Skills being incorrect level.
- Fixed some missing Runeword localization.
- Fixed a server-side crash.
- Fixed some Mine and Slash datapack errors.
- Fixed an issue regarding the Persistent Traders.
- Fixed Overworldian Nights Gateway failing on Creeper explosion.
- Removed an unused legacy Quest regarding accessories.

### Mod Updates
- Updated Mine and Slash.

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
- Evasive mob affix has been nerfed, but now also grants mobs some Spell Dodge.
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