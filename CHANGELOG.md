# Changelog

## [0.9.1b] - 2025-02-02

### Updates
- Some Teams UI improvements thanks to Poe!
- Certain build-enabling buffs have been increased from 30s back to 5 mins like before.
- Armor and Dodge Talent Nodes have been buffed.
- Stun effect now also gives -100% Damage.
- Health from Strength has increased by 25%.
- Reduced Asura cast time drastically.
- Refresh cast time has reduced drastically.

### Fixes
- Fixed some missing weapon compats.
- Fixed Auras not working.
- Greatsword range is now 4.5 instead of 3.5, in line with other 2H weapons.
- Rejuv and Astral Totem are now correctly tagged as magic.
- Fixed Advance Team crash.
- Disabled Sack, Urn, and Lunch Baskets due to an exploit.

### Mod Updates
- Updated Waystones, Doggy Talents Next, Advanced Team.

## [0.9.1] - 2025-02-02

### General Updates
- Partying in CTE2 has been revamped once again! I've removed Sed's Parties now that we have Clefal's Advanced Team! This party mod is integrated with Mine and Slash and is accessible via the Inventory GUI (command has been disabled). In fact, all team GUIs are now accessible via the inventory!
- Effect text overlay is actually visible now.
- Quest UI has been revamped and updated - thanks Poe! This includes the experience and point reward icons!
- Repeatable quests have been moved out of the main lines and into a new Chapter to prevent players from getting "stuck". The pre-req quests will tell you if it unlocks an Repeatable Quest, and the Repeatable Quest will also indicate this.
- Added a new repeatable quest for Pillagers/Vindicators and one for the Forgotten.
- Increased MIMI default output volume.
- Certain Mine and Slash features such as damage log are now enabled by default.
- Added a new Mana Infusion recipe for Flint duplication.
- Disabled Krampus spawns.

### Fishing Updates
- Overhauled Fishing difficulty - they should be a lot easier now. I've standardized the difficulty levels so it's generally Easy, Medium, Hard. Hard fish are about as difficult as Cod and Red Grouper before the update.
- Loot Crate chance from Fishing has increased from 2% back to 5% since it's more difficult to perform.
- Through the power of datapacks, Lure Enchantment now affects how many fish you can get from each pull. Higher Lure = more fish.
- Increased the spawn rate of some of the rarer fish.
- Further increased experience gain for Fishing Profession.

### Mine and Slash Class Updates
- Added a new Warlock Skill: Summon Wisp! Summon a slow moving Wisp that follows the nearest enemy and eats away at their life force, dealing Physical and Cold Damage every 0.5s. The Wisp has a base duration of 10s and does not count towards the summon max.
- Skills that self-damage now have some warning text.
- Skills should feel a bit more responsive now. Removed some legacy cooldown thing.
- Buffs duration has been reworked slightly. Buffs that only apply to self are typically much shorter in duration now, and buffs that apply to allies are still lengthy.
- Battle Orders duration has increased from 20s to 30s.
- Gong Strike and Whirlwind Defender variants that scale off Health now scale off a static amount of Health instead of increasing per level. The value is somewhere between what it used to be.
- Fighter Skill damage scaling has been standardized to be in line with other Skills.
- Charge damage now scales a bit off of Move Speed instead of each level adding Area of Effect.
- Improved some Brawler Skill visuals.
- Fury max level is now 4 instead of 16.
- Eighth Gate no longer costs Energy.
- Eighth Gate no longer has a cast time.
- Anti-Gravity Smash now does damage on the initial hit, but subsequent damage has been lowered. This change makes the Skill feel a bit more impactful and reliable.
- Spirit Offensive hit radius has increased by 50%.
- Triple Blitz and Omnislash now come out much quicker.
- Asura now has a short cast time.
- Asura Energy Scaling has increased a bit, but the self damage is now 33% instead of 25%.
- Crusader Auras can now be toggled by recasting them.
- Crusader Auras no longer cost Energy to cast, but instead the effect gives the user a hefty reduction to Mana/Energy Regen (except for Meditation) which is mitigated with levels into the Aura. This change was made due to the "ease" of access to Auras as powerful buffs with small opportunity cost. Since Auras don't drain Mana or Energy or anything, a reduction to regen is appropriate.
- Meditation has been nerfed slightly.
- Persecutory Thrust damage has increased by 50%.
- Comeuppance cast speed has been halved.
- Comeuppance damage has been increased by 10%.
- Holy Fire damage has been reduced by 50%.
- Holy Immolation has been reworked. Instead of dealing % of the Mob's Health as Fire Damage, it now gives the user a chance to cast Immolate on the initial Burn proc, which does AOE Fire Damage. Immolate scales slightly off of the Caster's Health.
- Elementalist had a bit of a rework. Fire Skills no longer apply Scorched. Instead, they give the caster Overheat on cast, which significantly increases their Spell Damage at the cost of Mana Regeneration and Leech Effect. Additionally, Cold Skills no longer apply Bone Chill. Instead, they will remove a stack of Overheat, and if they do, will recover a small amount of Mana to the caster. Note that Fire Trap, Flame Strike, Fire Totem, still apply Scorched.
- Other Skills that apply Bone Chill now apply Slow/Lethargy instead.
- Ice Shard, Chilling Field, and Blizzard apply Slow.
- Ice Shard Mana Cost has been reduced by 50%, but the Damage has also been reduced by 20%.
- Mage Armor has been reworked - now any Skill tagged with Burst can trigger Elemental Burst. The enemy does not need to be under any effects. The chance to trigger it has been lowered.
- Refresh has been reworked and no longer resets cooldowns. It's now cast 4 times over 4s (can be quickened with Cast Speed). Each cast removes a stack of Overheat and recovers a small amount of Mana.
- Refresh max level is now 8 and is available starting level 1.
- Mage Circle required level has increased. It now also gives MORE Skill Damage instead of flat. Values have been adjusted.
- Heat from Steam Cloud has been renamed to Steam.
- Steam Cloud now gives 25% MORE Steam Cloud Damage per stack instead of 35% Steam Cloud Damage.
- Removed Physical tag from Mage Armor/Elemental Burst.
- Charged Bolt now implicitly has Barrage, meaning the extra projectiles all go forward.
- Garden of Thorns now requires a Mage Weapon.
- Garden of Thorns now comes out much quicker.
- Cyclone now pulls enemies towards it if they have a Thorn stack.
- Frost Blade now gives Cold Penetration instead of Cold Damage.
- Chronobreak no longer knocks back.

### Mine and Slash Talent/Ascendancy Updates
- Champion's Cruel Fate no longer gives Damage Suppression and instead gives Damage Reduction when on Very Low Health.
- Champion's Cruel Fate values have been readjusted.
- Champion's Blood Splatter Augment Effect has increased and the chance to trigger a Blood Explosion has increased.
- Juggernaut's Unyielding has been nerfed slightly.
- Refined Taste no longer increases Leech. And the bonus to Leech Cap has been reduced.
- Reckless Defender now gives Damage Suppression in exchange for chance of receiving ailments.
- Netherite Bastion has been reworked. Instead of Armor, Healing Received, and a penalty to Dodge, it now gives % of Physical Damage Taken as Fire Damage and an increase do Fire Damage Received.
- Twincast penalty is now -20% MORE instead of -35% MORE.
- Defense stat nodes have been standardized. The numbers were sort of all over the place now, but tl;dr Armor and Dodge nodes got buffed. Regen nodes got buffed. Magic Shield and Health nodes are the same as before.

### Mine and Slash Map and Mob Updates
- Something players have been asking for: earlier Dimensions (Act I - Act V) now get revamped starting at level 50. The level ranges for the Dimensions are reset and increased once you hit level 50 onwards. There is a new Lost Page going over this at the end of Act III, but for example, Overworld still scales from 1-15, but again at level 50-70. This should allow players to "go back" to explore fun Dimensions without feeling punished for being overleveled.
- Added a new gameplay mechanic that can occur before and in Maps! Ancient Obelisks can randomly be found in place of loot chests, and are wave-based encounters that can be modified by specific Currency Orbs!
- Added 2 new Harvest Maps.
- Readjusted some Prophecy reward costs.
- Map Affixes have been nerfed in the sense that the negative effects are lessened and the variance has been reduced.
- In combination with the above, Map Mob bonuses per tier has increased slightly to offset the change.
- Removed Sorcerers, Yetis, Stalkers (Outer End), and King Spiders from the Map pool.
- Mob base Critical Damage has been lowered. Instead of having a base of 100%, it's 50% (so on crit, Mobs do 50% extra damage, not double).
- Mob and Map Affixes that affect their Critical stats have been adjusted (overall nerf).
- Target Dummy no longer has resistances or defenses.

### Mine and Slash Item/Stat Updates
- New Unique Gauntlet: Assassin's Katar! This super high attack speed weapon gives substantial bonuses to Critical Hit!
- New Unique Gauntlet: Druidic Claw! This unique gives special bonuses to proccing Bleed!
- New Unique Greatsword: Buster Sword! Gives large bonuses to Area of Effect and Damage at the expense of taking more Damage!
- New Unique Scythe: Scythe of the Harvest! Grants the user a Skill called Harvest, which upon use consumes Thorns stacks to deal damage!
- Call of the Void now boosts all Damage instead of just Chaos Damage. Some of the values have been adjusted accordingly.
- The Written Word unique now has a custom model.
- Lightning Coil Unique now gives % of Physical Damage Taken as Lightning Damage instead of Physical Resist.
- Ceremonial Gauntlets now give Energy Steal instead of Elemental Damage.
- Imperial Greatsword now increases Physical Damage instead of Elemental Damage.
- Hyperion Greatsword now gives Area Damage instead of AOE.
- Hyperion Spear AOE implicit has been buffed.
- Increased crossbow basic attack damage multiplier from 2.4x to 2.8x.
- Scythes can now roll the + Skills for the elements.
- A bunch of Enchantments have been overhauled - in general, most weapons can have the same Enchantments. There are some exceptions where it makes sense, such as Backstabbing on Daggers.
- Elytra's are now craftable but require Chorundum. The rewards from defeating the Ender Dragon have changed to encourage players to craft one.
- Explorer's Compass is no longer useable in the Twilight Forest.
- Mana Spreaders are now silent.
- Auto Repair Kit values have been adjusted.
- Deconstructing Profession materials now yields a bit more.
- Removed naturally spawning Elytras.
- Added 24 new affixes, which include new suffixes specific to each weapon type.
- Two-handed flat weapon damage prefix has been buffed.
- In combat regen is now the same as out of combat regen. Most regen values remain untouched, so essentially regen has been doubled.
- Strength Health per point is now 2 instead of 5, and Armor is 0.25% instead of 0.5%.
- Intelligence Magic Shield per point is now 0.25% instead of 0.5%.
- Dexterity Attack Speed and Dodge are now 0.25% instead of 0.5% per point.
- The only sources of regen that have been halved are from the core attributes (Str/Int/Dex).
- Flat Regen affixes have been spread around on Jewels, Rings, and Necklaces.
- Suffixes of Mana and of Energy now give flat instead of percent and can now spawn on Necklaces as well.
- Suffix of the Mountain now gives flat Health instead of percent, and can appear on more Jewels, Rings and Necklaces.
- Now that I know how Accuracy and Armor Penetration are actually calculated, sources of these stats have been lowered.
- Armor Penetration can now go in the negatives.
- Magic Shield healing conversion now happens before Increase Healing stat.
- Updated some descriptions for Ailments to be more clear.
- Overhauled a bunch of stat names and descriptions for clarity. What was previously called a Spell is now Magic, and Weapon Skills are now tagged as Attacks, for example.

### Fixes
- Fixed Gauntlets and Daggers doing 0 damage when under Weakness potion effect.
- Disabled Tridents from Prophecy Rewards.
- Fixed inconsistent Click Once Read titles.
- Cold Snap cooldown is now correctly 2s instead of 5s.
- Fist of Judgment now correctly has the Weapon Skill tag.
- Fixed Timewinder particle effect.
- Arachnid Innoculation no longer has the Magic tag.
- Fixed some localization.
- Fixed some quests missing information.
- Fixed an issue where the condition for Holy Fire deactivating was being calculated incorrectly.
- Fixed some broken recipes.
- Fixed Footprint Particle config.
- Fixed an issue where instead of Minoshrooms dropping Heart Containers, Minotaurs were.
- Fixed Sharpness not being applicable to Scythes.
- Fixed a crash if players tried changing back to vertical hotbar.
- Clamor, Crash, Clatter and Inspiration are now correctly tagged as Songs.
- Fixed Elytra and Flugel Tiara gear type not being initialized on crafting.
- Fixed Elytra and Flugel Tiara not applying stats.
- Fixed some loot bag rewards in Profession Chapter.
- Fixed Leech Cap scaling with level for real this time.
- Fixed Chocobo quest not indicating Talent Point rewards correctly.
- Fixed Act III Achievment requiring an Act I quest.
- Fixed weapons held incorrectly in VR.
- Fixed Heart of Ice buff timers visual bug.
- Fixed an issue where certain Skills weren't working in Boss rooms.
- Fixed a Map affix giving All Resist instead of Elemental Resist.
- Fixed ailments proccing even if damage was converted away from the element.
- Fixed ailment base damage not being affected by conversions.
- Nether end room, Stone Brick end room, Mossy Brick 3-way room, Sewers corner room, and Sandstone Boss rooms have been fixed. Thanks Builders!
- Fixed missing entities from Anti Mob Farm mod blacklist.
- Fixed certain passive fish giving combat experience.
- Fixed Prophecy Unique reward being a thing.
- Corrected Battle of Wits stat description. It worked as intended but it said Health instead of Strength.
- Hopefully fixed Runewords failing to craft sometimes.
- Fixed Illusion of Defense showing as percent instead of on/off.
- Fixed a bug where Warped Mosco wasn't dropping Heart Containers.
- Fixed Skills showing the same effect multiple times.
- Fixed an issue with Bosses not respecting the Anti-Mob Farm blacklist.
- Fixed some attack speed cooldown issues interfering with Better Combat.
- Hopefully fixed an issue where basic attacks were triggering Anti-Mob Farm when it shouldn't have.

### Mod Updates
- Updated Shoulder Surfing, FTB Teams, MCA, Legendary Tabs, Fzzy Config, CraftTweaker, FTB Quests, InsaneLib, Library of Exile, Mine and Slash, Orbs of Crafting, RoE Weapons, Structure Essentials, Xaero's Minimap, EntityJS, FTB Library, Euphoria Patches, Sophisticated Mods, Oh The Biomes We've Gone, Amendments, Moonlight Lib, Supplementaries, Blueprint, EnhancedAI, Waystones, Anti-Mob Farm.
- Updated Complementary Shaders.
- Updated to Forge 47.2.27.
- Added Adventurer's Chest (Lootr) - Lootr Resource Pack.
- Added Ancient Obelisks.
- Added FTB Placeholders - icons for rewards from Poe.
- Added EMI Loot - can see loot tables in EMI now.