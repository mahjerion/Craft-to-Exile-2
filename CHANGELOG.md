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

## [0.9.0d] - 2025-01-26

### Updates
- Self Damaging Skills no longer take into account stats when calculating damage. That means self damage can't crit, it won't receive bonuses to Skill Damage, etc. Resistances still apply.
- Holy Fire now deactivates if it deals damage to you while below 25% Health + Magic Shield.
- Eighth Gate now does 50-25% Health self damage instead of 60-30%.
- Self Damaging Skills have been streamlined to scale with max Health and Magic Shield instead of weapon damage, since the damage is no longer affected by damage stat bonuses. This also means you don't have to do that balancing act of not doing too much damage or you'd kill yourself (except this still applies to Holy Fire).
- Added names to Classes GUI.
- Favor is now capped at 2500 instead of going indefinitely.
- Increased Twilight Forest difficulty substantially.

### Fixes
- Fixed Holy Immolation proccing Frost Nova.
- Removed the last source of Scroll of the Dead Sea.
- Fixed Enchantment system. Should be able to apply more Enchantments to a variety of items now.
- Fixed players having -25% Resistances at level 1.
- Fixed crash on world creation.
- Fixed infusion fails not incrementing uses.

### Mod Updates
- Updated Shoulder Surfing, Mine and Slash, Library of Exile.

## [0.9.0c] - 2025-01-26

### Updates
- Chronomancer has had a small redesign. Alpha, Beta, and Gamma stacks are now consumed upon Skill completion. Additionally, they now have a max stack size of 3.
- Timewinder ground effect's radius is now 1 instead of 1.25, and the effect only lasts for 2s on the ground instead of 3s.
- Timewinder Beta mode and Alpha + Beta mode have swapped.
- Chronobreak Cold and Lightning Resistance reduction is now increased from -10-20% to -15-30%.
- Pulsar Singularity Trap's Gamma mode now also applies negative Lightning and Chaos Resistance in addition to the pull.
- Crusader Retribution stack size is now capped at 5 instead of 3.
- Mojang loading screen is now in dark mode.
- You can now only have one Aura Effect active at a time, meaning two players with different Auras won't be able to stack. This is to prevent groups of 8 people sharing every Aura buff...
- Added some clarity on Fury and Safeguard buffs.
- Reduced default Damage Tilt Strength option to 25%.

### Fixes
- Fixed some unintended behaviour due to Vanilla repairs where you add two of the same item into the Crafting Table. The method is removed now.
- Should fix server configs not being updated correctly with 0.9.X.
- Corrected some weapon types.
- Fixed Maps requiring Resistances again. I mean, technically you need at least -50%...
- Fixed Void Worm End Rune and Heart Container drop rates.
- Fixed Flugel Tiara recipe.
- Fixed a typo where Fury buff was called Elemental Assault.
- Fxied Smoked Monster Flesh not being tagged as a Hammer.
- Fixed an issue in VR where movement was not working due to Shoulder Surfing.
- Fixed some passive icons being squares instead of circles.

### Mod Updates
- Updated ImmediatelyFast, ModernFix, Vivecraft.
- Removed Death Backup. The files take up a lot of space and we stable now.

## [0.9.0b] - 2025-01-25

### General
- Moved default chat position to not cover stuff, but at the same time made it obvious to players that they'll need to move it to their own preferred spot.
- Changed some passive icons that were duplicates of others.

### Fixes
- Fixed VR Settings button being unclickable.
- Fixed certain aggressive entities being untargetable due to FriendlyFire.
- Fixed missing localization for Scythes.
- Fixed incorrect Stance description.
- Fixed incorrect Holy Immolation stat description.
- Fixed some typos in Anti-Gravity Smash and Flowing River Rush.
- Fixed random tick speed being 0.
- Fixed First Weapon reward including an obsolete Trident instead of Spear.
- Fixed some unachievable hat items.
- Fixed FLAN.
- Fixed Parallel Convergence healing enemies when used with a Gamma stack.

### Mod Updates
- Downgraded FLAN.

## [0.9.0] - 2025-01-25

### General Updates
- We now have Party GUI! Use /party to create new parties that allow you to view the health of your teammates! Note that the numeric value will be inaccurate, but you can get a percentage idea.
- New CTE2 Title!
- UI updates to make the pack feel more coherent, thanks to Poe! Crafting Tweaks, Polymorph, Doggy Talents, Spice of Life are included. This also includes a new loading bar! This also includes new buttons that can be accessed from inventory!
- Now comes with VR support (albeit a bit primitive atm)! There are integrations with Minecraft mechanics (such as the Crafting Table) and custom bindings! Check out the quest in the Prologue Chapter for more information!
- Favor system has been reworked to be more achievable and relevant. Instead of capping at 100k, it now caps at 2500. Other changes are included as well.
- Refined Storage energy costs of upgrades have been lowered substantially.
- Refined Storage External Storage no longer costs energy.
- Some Refined Storage blocks have had their "Botania" costs shifted up front. For example, External Storage no longer requires energy to run but requires a Elementium Ingot.
- Botania's Corporea system has been re-enabled.
- Botania's Drum of the Wild has been re-enabled for the Official Server.
- Updated the Lightman's shop to include the new MCA villagers. Thanks Poe!
- MCA Villagers now should be protected by the Friendly Fire mod.
- You now earn 1% interest on coins in your Bank.
- Mine and Slash Crafting Profession experience gained has been changed to increase exponentially with rarity of craft, instead of being a linear increase.
- Backpacks can use upgrades even when not worn now.
- You can no longer break or steal backpacks in other peoples claims.
- Unique Prophecy reward is now rarer and much more expensive.
- Removed Skeleton Demoman from Maps.
- Monster Flesh is now tagged as a Hammer.
- Doggy Talents treat recipes have been adjusted to be more difficult.
- Fishing Profession Loot Crate chance has been lowered from 5% to 2%.
- Due to new Stardew Fishing minigame, Fishing Profession experience has doubled.
- Disabled the Eternal Candy.
- Disabled Sliding Block due to crash.
- Disabled the Heaume of the Blinding Abyss due to crash.
- Death Totem from chests has been re-enabled.
- Elytras can no longer be obtained from Nether Ships.
- Dummy DPS mode is re-activated and now accurate thanks to passenger!
- Non-Blue Skies tools will now work in Blue Skies dimensions. Mobs will also be properly damaged now.
- Cages and Conducting Bones are now disabled in Maps.
- You will now see what structure you are entering thanks to EC's Structure Credits.
- More information on tools is now displayed thanks to Tool Stats.
- The Disassembler's Learning Method now grants x2 EXP instead of x3.
- Blacklisted some entities from Neat bar config.
- Think Before Drop has been added and configured to prevent you from accidentally throwing your weapon away in the heat of battle! This mod prompts you to press the drop key twice before the item drops and has been configured to only work with weapons.
- Re-enabled Botania Rannuncarpus.
- Added Iron Ingots to higher-tiered Map loot tables.
- Death EXP penalty now only starts at level 50.
- Rested EXP death penalty is now 25% instead of 75%.
- Neat Bars that display health now include Magic Shield in the value.
- Double Doors now only works with doors.
- Added disabled text to Divider since it doesn't work.
- Removed first person overlay from Three-Point Helmet.

### Mine and Slash Class Updates
- A NEW CLASS HAS ARRIVED: Brawler! This combo-based class utilizes a string of Skills to decimate their foes. Their versatility in effects is unparalleled. Start with basic attacks to gain a Combo Starter stack, which is used to cast Combo Starter Skills. Combo Starter Skills will consume the stack and generate a Combo Linker stack, which is used by Combo Linkers. Similarly, Linkers will consume the Linker stack to generate a Combo Extender stack, which is finally consumed by a Combo Finisher. Explore the different combinations of Skills and create your own playstyle!
- ANOTHER?! NEW CLASS HAS ARRIVED: Crusader! Harnessing the power of the divine (Fire + Lightning), lay waste to enemies with new Skills or empower nearby allies with Auras. The new holy (Fire + Lightning) Skills can utilize Retribution stacks which are gained from blocking to become more defensive. However, Retribution stacks are optional. Auras are powerful buffs - only one can be equipped at a time. Most Auras empower your allies as well as yourself, but some Auras deal damage to enemies...
- A-N-O-T-H-E-R?!?!?!? NEW CLASS HAS ARRIVED: Chronomancer! This caster class utilizes the power of time (Cold + Lightning) to warp their enemies out of existence (not really). The Chronomancer utilizes 3 different types of stacks: Alpha, Beta, and Gamma. Depending on the configuration of stacks currently active, the Chronomancer's Skills become augmented. A lot of the Chronomancer Skills employ area control tactics and self-preservation through time manipulation!
- Added a bunch of new Skill animations. Huge thanks to Poe for these! A few animations have been updated. Arrow Storm, Recoil Shot, Backflip Fire Wall have new animations as well.
- New Lv. 20 Elementalist Skill: Blood Boil. Deal a small amount of Fire and Cold damage to nearby enemies with an increased chance of Burn and Freeze. Enemies hit are also taunted.
- New Lv. 10 Hunter Skill: Kick. Knock back and deal a small amount of Physical Damage to enemies right in front of you.
- New Skill: Bolt. Super basic Physical projectile obtained from Staves.
- Hybrid-cost Skills now cost less of the minor resource to cast.
- Arachnid Inoculations is now tagged as Summon.
- Fighter's Stance Skills have been reworked a bit. The stats they provide have been changed. Fighter Stance no longer gives Critical Hit, and Defender Stance no longer gives Damage Reduction. Defender Stance now gives Knockback Resistance.
- Fighter's Stance Skills now have a base cooldown of 2s instead of 10s.
- In addition to the above, Fighter Stance now grants 8% MORE Damage dealt to Stunned enemies, and Defender Stance now gives increased duration of Immobilizing effects (Stun, Slow, etc.).
- Fighter's Boomerang Skill has been renamed to Axe Throw.
- Axe Throw now uses a charge system similar to traps.
- Charge now provides Knockback Resist during the effect.
- Whirlwind AOE size has increased from 2 to 3. In Fighter Stance, it has increased from 2.67 to 4.
- Replaced Fighter's Vampiric Blood buff with a new Skill: Meditate. Recover 10% of your Health every second over a base duration of 8s. During this activation, you are stunned. The max level for this Skill is 1.
- Increased Taunt AOE radius from 3 to 5.
- All Elementalist Fire Skills have had their damage increased by 10%, except for Meteor and Steam Cloud which increased by 20%.
- Refresh is no longer tagged as a Buff.
- Refresh cooldown is now 90s instead of 180s.
- Leveling Refresh now gives it Cooldown Reduction and Cast Speed.
- Heart of Ice radius has been reduced from 4 to 3.
- Elemental Burst now uses Support Gems from Mage Armor Skill.
- Lowered Elemental Burst AOE radius from 3.5 to 2.
- Improved Elemental Burst visuals.
- Frost Nova heal amount has been lowered by about 33%.
- Heart of Ice is now correctly tagged as a Buff.
- Scorched now reduces Elemental Resistances by 10% instead of 25%.
- Hunter's Mark is now a level 20 Skill instead of 10.
- Wounds effect now reduces healing received by 50% instead of 25%.
- Trap Skills now cost Energy instead of Mana.
- Frost Trap damage at level 1 has been lowered but scaling per level has increased. At max level it's the same, and overleveled it's now stronger.
- Fire Trap damage has been reduced by 25% at level 1 and 20% at max level.
- Arrow Totem weapon damage scaling per level has been reduced by about 30%.
- Fire Totem damage has been reduced by about 5%.
- Frost Totem damage has increased by about 10%.
- Lightning Totem weapon damage scaling has been reduced by about 10%.
- Shaman Lightning Skills have had their Weapon Damage scaling reduced by about 10-15%. The Mana scaling remains untouched.
- Shaman passive that gives Armor based on Mana has been reduced from 2% to 1%.
- Shaman passive that gives Elemental Penetration has been reduced from 2% to 1%.
- Whirling Blades has been renamed to Cloak of Hidden Blades.
- Cloak of Hidden Blades is functionally the same as Whirling Blades but now deals half Physical, half Chaos Damage.
- Increased the cost of Cloak of Hidden Blades slightly.
- Venom and Flame Splash Potion Mana costs have been reduced by about 20%.
- Venom and Cinder now have a 0.25s cooldown, instead of 0.05s.
- Venom and Cinder now properly have a stat for basic attack hit procs. This means the procs for basic attacking now respect the cooldown period.
- Revenant Slam is now correctly tagged as a Weapon Skill.
- Curses have been nerfed, most debuffs have been reduced in effect - especially the penetration stats.
- Curse visuals have been improved.
- Curse radius has increased from 2.5 to 4.
- Summons are no longer tagged as Magic or Ranged.
- Summon base damage has been tripled, but the Summon Damage stat you get from the Skill itself has halved. Damage increases without any investment. This is a huge buff because it means bonuses to Summon Damage from other sources are also now more effective. This change does not affect Summon Spiders (they don't have innate Summon Damage stat).
- Summon Spider scaling has increased from 0.5 to 0.8.
- Summon Spider hitbox is now the size of Cave Spiders instead of normal Spiders.
- Improved Summon Skeletal Army and Arachnid Inoculation descriptions.
- Minstrel Healing Skills are now properly tagged with Area and Song.
- Minstrel offensive Skills have been rebalanced to be in line with other Skills (buff).
- Clamor, Crash, Clatter sound has been changed to be less obnoxious.
- Charm effect has been nerfed slightly.
- Some Skills and effects have received particle and sound updates.
- Except for Undying Will, all buffs that lasted 1 minute before now last 5 minutes instead.

### Mine and Slash Item/Stat Updates
- NEW WEAPON TYPE: Gauntlet! Gauntlets are STR/DEX hybrid weapons with a very high attack speed.
- NEW WEAPON TYPE: Scythe! Scythes are two-handed STR/INT hybrid weapons.
- NEW WEAPON TYPE: Greatsword! Greatswords are two-handed STR weapons which can deal high damage.
- Staves now grant a new Skill as a base stat: Bolt. Bolt is a basic Physical projectile meant to give casters a "ranged basic attack". This Skill costs no Mana, and has a 1s cooldown.
- Newly implemented SET BONUSES! Only seen on a few items at the moment - namely the end-game Genji, Oath of Mahj, Last Tracker, and Nebula sets.
- New PATREON-designed Runeword: Crater! This item was designed by WornWar. Modifies Trap Skills to detonate upon impact! Also grants bonuses to Trap cooldown and Area of Effeect, at the expense of some Trap Damage!
- New Contributor-designed Unique Totem: Lantern of Lost Ghosts! This item was designed by Poe (the player). When held, gain the benefits of Ghost Shroud and a bonus to Magic Shield. Additionally, when hit, have a chance to proc Smoke Bomb. This item uses a custom model from Poe himself!
- New Contributor-designed Unique Axe: Sol's Way! This item was designed by councilfarciminis2. This slow axe boasts great range and a chance to proc Frost Nova on Movement Skill hits! Additionally, it makes your basic attacks propel you forward a bit.
- New Unique Axe: Wither's Flame. This mid-level axe gives your attack hits a chance to proc Armageddon, in addition to receiving bonuses to Fire Damage.
- New Unique Staff: Poet's Pen. This staff alters the new default Bolt Skill on your staff to proc Kinetic Blast on hit. Kinetic Blast causes a series of explosions in an area upon impact, with each explosion dealing damage.
- New Prophecy Unique Chainmail Pants: Fracture Splint. This high-level Unique grants you the chance to cast Summon Skeletons on kill! However, this Skill proc does NOT respect cooldown period!
- New Unique Gauntlet: Facebreaker. This simple Unique gives large bonuses to Weapon Damage!
- New Unique Greatsword: Shiversting. This Unique gives bonuses to Freeze Resistance!
- New Unique Greatsword: Starforge. Starforge reduces all Elemental Damage dealt, but also causes all Lightning Damage to always Electrify.
- New Unique Scythe: The Reaper's Toll. This Unique gives bonuses to Armor Penetration, Lifesteal, and Critical Hit!
- Genji, Oath of Mahj, Last Tracker, and Nebula have been nerfed. Additionally a portion of their stats have been moved to the new set bonuses.
- Some Runewords have been updated to allow the new Gauntlet type.
- Doombolt Chaos Penetration has been reduced from 50-60% to 30-40%.
- Terra Blade no longer gives -40% Attack Speed. The item base itself however now has a lower Attack Speed.
- Skin of the Vipermagi now has a custom model.
- Bulkwark Bleed Resistance has been reduced to 50%.
- Limbsplit Unique now has a custom model.
- Bloodspark Health Regen penalty has been increased slightly.
- Runeword stat variance has been increased (nerf).
- Flickering Flame Runeword can now only be crafted on Pants.
- Flickering Flame Runeword now only gives +1 To Fire Skills instead of 1-2.
- Insight and Plague Runewords no longer give Augment cost reduction. Plague has gained new stats to offset this. Insight bonus to Mana Regen has doubled.
- Infinity Runeword Lightning Penetration has been reduced from 65-75% to 40-50%.
- Staves now give Mana on Bolt Hit instead of Mana on Basic Hit. The amount you get is less than before.
- Restrained Destruction Support Gem now gives 8-24% MORE Magic Skill Damage instead of 9-27%.
- All Penetration Support Gems (including Armor) have been reduced in effectiveness.
- Defensive Minions Support Gem has been renamed to Elusive Minions Support Gem to reduce confusion.
- Mageblade Support Gem now scales from 2-6% instead of 3-9%.
- Increased Daw Rune drop rate from Arachnarch by 20% (20% -> 25%).
- End and Wir Rune resistance stats have been nerfed.
- Steam Cloud on Kill proc now can proc on kills from Steam Cloud. The same is true for Putrid Breath.
- Max Cooldown Reduction is now 60% instead of 75%.
- Instances of x per y stat have been changed to percent of x as y stat. This is to fix the problem with stat priority. Eg. The Beast gave 20-30 flat Health for every 10 Strength, but it was not affected by bonuses to Health. Now, it gives 100-150% of Strength as Health, which will be affected by bonuses to Health.
- Base Gear Armor and Dodge stats have doubled, and Magic Shield stats have increased by 25%. This applies to hybrid armor types as well.
- Sources of all Elemental Resist have been nerfed.
- Most sources of Physical Resist have been lowered or removed.
- Most sources of Damage Reduction have been lowered.
- Fortify now gives 8% Damage Reduction instead of 10%.
- Flugel Tiara is now a Unique that gives penalties to combat stats.
- Elytras are now considered Mine and Slash gear and are level gated.
- Gear Soul Cleaner can no longer be used on the Terra Blade, Flugel Tiara or Elytra.
- Mana Cost stat is now called Resource Cost and applies to Energy costs as well.
- Increased Slice damage from Genji set by 50%.
- Slice cooldown is now 1s instead of 2s, to be in line with other proc Skills.
- Level Up Currency Orb is now max 10 uses instead of 5.
- Nerfed sources of Item Find.
- Swords and Axes can no longer Dexterity-based stats.
- Dark War Blade and Nightmare Scythe are re-enabled and given appropriate new weapon types.
- Some existing weapons have had their types changed (eg. MCA: Reborn Scythe is now a Scythe).
- End and Sid Rune have been reworked. End Rune now gives Damage Suppression instead of Physical Resistance, and Sid Rune now gives Magic Find instead of Item Find.
- Ailments now have a visual particle indicator.

### Quest Updates
- Botania Chapter has been revamped thanks to the efforts of FeelingOwl and CreatorBurden.
- Quests have had a general passthrough and update thanks to CreatorBurden.
- New quests have been added detailing: Anti Mob Farm, Botania quests, Mega Torch, etc. Thanks again to CreatorBurden.
- Added some new Professions quests in Act III and IV. These quests should help a bit with the experience gain from level 45-55.
- Reorganized some Act III quests to make it more clear where you should go.
- Experience gain from quests starting in Act IV onwards has increased drastically (about 30-50%).
- Added a new quest type: Repeatable Quests! You'll find some in each Act.
- Added some quests in the Homestead Chapter going over FramedBlocks.
- Chipped quest has been moved to the FramedBlocks quest line.
- Added a new Bestiary IIb quest for Zombie Clowns.
- Added a 8 new collectible hat rewards in quests.
- Reduced some requirements in Botania Chapter.
- Botania Elven Traders quest now reads for tags for the Livingwood.
- Botania dependencies have been shifted a bit to help newer players more.
- Added a warning regarding the Wroughtnaut on the Steely Resolve quest.
- Updated Exploration Chapter.
- Updated the description for Slippery Swimmer, since you can now encounter Eels in Gateways.
- Added a blurb about Neptunium in Act III Diving Suit quest.
- Added a blurb on how to get the Transmuting Elixir in Bestiary VIb.
- Performed some quest formatting clean-up (up until Storage).
- Updated earlier quest rewards to include new weapon types.

### Gateway/Mob Updates
- HUGE Map reworks and rebalancing thanks to DoutingDonut, SelfSlain/Villain, and FeelingOwl. They literally updated almost every map!
- Added 2 new Maps thanks to DoutingDonut, SelfSlain/Villain! Check out the Watcher and End Maps!
- Harvest layout has been replaced with a new one thanks to the builders!
- Added 3 new Map Boss Arena layouts!
- Added a new Uber Boss Arena layout!
- Maps now have a cooldown of 3 minutes, and downgrading Maps now has a cooldown of 5 minutes. These changes were made in an effort to reduce layout abuse and should not affect genuine gameplay.
- Mobs in Maps now receive 66% increased bonus Health per tier than previously.
- Mobs in Maps now receive 50% increased bonus Damage per tier than previously.
- Raids have been disabled. Any Raid-only items are technically obtainable through Gateways, structures, etc.
- Added a new Gateway of the Depths which contains Act III Undergarden mobs, including the Umvuthi!
- Act Gateways now have a cooldown period of 5 minutes instead of 1 minute.
- All Act Gateways now have a 1% chance to proc instead of 0.5-3%.
- Last wave (Eel) in Gateway of the Ice Maze now has a time limit of 90 seconds instead of 50 seconds.
- Pixies from Botania can no longer spawn Gateways.
- Added a chance for Anglerfish to spawn a Gateway of the Deep Sea, which can spawn the Maze Mother.
- Alchemist in Act IV now takes 100% increased damage from Projectiles and Arrows.
- Starlit Crusher and Arachnarch are now minimum level 50 instead of 55.
- Ender Dragon is now minimum level 50 instead of 55.
- Void Worm is now minimum level 55 instead of 60.
- Warden is now minimum level 60 instead of 65.
- Zombies, Husks, etc. can no longer spawn with fishing rods.
- Fisherman Zombie now can spawn with fishing rods, and the chance is much higher than before.
- Leaping mobs have been changed to only be on Wolf-type creatures. This includes summoned Wolves.
- Snow Golem damage has been reduced by 90%.
- All larger-sized spiders (Cave Spider and up) can now spew webs. This does NOT include summoned Spiders and Mother Spider.
- Void Worm now spawns with half the amount of Health.
- Ferrous Wroughtnaut can now be damaged regardless of phase.
- The second version of the Gaia boss now has a high chance of dropping Mine and Slash Runes. This includes the high runes (Oru -> Yun), but does not include Dimension Runes.
- Vindicators, Pillagers, and Wither Skeleton coin drops have been reduced.
- Added a bunch of new Map Affixes.
- You no longer get penalized for having low resistances when going into Maps. I don't believe in hard-gating players out of Maps for lack of resistances, as there are other defensive layers they might have gotten. However, don't expect to survive if you don't have any defensive layers at all. Some of the new Map affixes are particularly nasty.
- The Mother Spider no longer spawns in Maps EXCEPT for Nature-themed Maps.
- Mother Spider now only spawns in deeper Y levels in the Overworld.
- Spiders now web much less often.
- Seagulls can no longer steal your Sweet Lance.
- MOST Bosses are no longer affected by Anti-Mob Farm.
- Some Mob Affixes now come with particle effects. Mostly this is applicable to the Elemental Damage ones for now.

### Mine and Slash Talent/Ascendancy Updates
- Talent Tree lag has been reduced.
- Elemental Overload now gives 25% MORE Elemental Damage instead of 30%.
- Improved Elemental Overload description.
- Harmony's Magic Shield Heal now works with Increase Healing.
- Ghast now gives -40% Magic Shield instead of -33%.
- Reduced Wandering Bard stats.
- Chieftain Ascendancy's Fire Penetration has been reduced from 25% to 20%.
- Primordialist Ascendancy's Elemental Penetration has been reduced from 20% to 18%. I've also collapsed the 3 elements into one stat.
- Necromancer Ascendancy's node which gives Fire and Chaos Penetration has been reduced from 25% to 15%.
- Trickster MORE Dodge Ascendancy now gives 12% MORE instead of 15%.
- Ghast and Trickster Ascedancy which gives Magic Shield > Dodge now gives less.

### Fixes
- Fixed some localization.
- Fixed Black Hole not playing sound.
- Fixed Encased not doing damage.
- Fixed a missing connector on the right side of the Talent Tree.
- Fixed Cruel Ascendancy not giving the points.
- Potentially fixed a crash.
- Disabled Dead Sea Scroll.
- Title screen no longer refers to Create/Colonies.
- Fixed a bunch of invalid Skill sound and particles - thanks Margineanu65!
- Fixed an issue where Gateways were proccing way too often in Act I.
- Fixed Combat Talent not working.
- Fixed a prominent duping method.
- Removed Display Delight quest.
- Fixed Residents of the Void quest requriing incorrect Stalker.
- Fixed a bunch of quests showing the wrong location.
- Fixed some quest not requiring dependencies to be complete.
- Fixed Map Affix Elemental Resist penalty not being Max Elemental Resist.
- Fixed some rare crash instances.
- Fixed Botania flower recipe disablements.
- Fixed Ritardando description outright lyin'.
- Fixed an issue where Blue Skies Bosses were not dropping Dimension Runes.
- Fixed some impossible quests.
- Map exploration announcements are no longer dimension wide.
- Boss multiplication in Maps should be fixed.
- Fixed Attack Speed per Accuracy stat being 10x as strong as it should be.
- Thorn Bush now correctly does Physical Damage instead of Chaos.
- Disabled Trident weapon type which was supposed to be deactivated.
- Fixed some Damage Reduction stats taking into account incorrect health values (target vs. source).
- Fixed Mind of the Council using the incorrect Mana to Weapon Skill Damage stat.
- Fixed instances of servers not opening due to CompoundTag.
- Fixed NaN Health bug.
- Fixed cases of Maps overriding old Maps, resulting in no mobs.
- Runed Jewel now correctly adds last affix at Mythic upgrade.
- Fixed some cases of stats being applied twice.
- Procced Skills now actually use Mana Cost.
- Fixed DOTs dealing damage 1 extra time.
- Loot Chests can no longer be salvaged.
- Ailment Resistance working incorrectly has been fixed.
- Block Chance now correctly requires a shield again.
- Fixed Heart Container drops only dropping from Wither instead of all bosses like stated.
- Fixed some Blue Skies fishes giving EXP and loot.
- Properly disabled Cannons.
- Fixed a few long-standing dupe issues.
- Sweet Lance is now correctly tagged as a Spear type for Better Combat.
- Fixed Poison Trap not teleporting units to it correctly.
- Fixed fixed Leech Cap stat scaling with player level.
- Fixed Traps triggering on allies under certain circumstances.
- Spectators no longer count as players.
- Fixed some structure-related crashes.
- Removed source of lag on first item pick up.
- Fixed Rejuvenation effect not buffing itself.
- Fixed an issue where certain items such as the Watcher Eye Jewel drop rates were lower than they should have been.
- Fixed a crash that was caused by Snow Golems in the Black Citadel structure.

### Mod Updates
- Updated FLAN, ModernFix, Loot Beams, Xaero's mods, CreativeCore, Moonlight, Oh The Trees You'll Grow, Polymorph, Sophisticated mods, Balm, Fast Aync World Save, Mine and Slash, Citadel, Corgilib, Kiwi, Shoulder Surfing, Amendments, Anti Mob Farm, Auto Repair Kits, Born In Chaos, Connectivity, CraftTweaker, Curios, Doggy Talents, Enhanced Celestials, FTB Library, FTB XMod Compat, Geckolib, InsaneLib, Itemphysic Lite, Lightman's Currency, Lithostitched, Not Enough Animations, Oculus, Oh The Biomes We've Gone, Packet Fixer, Supermartijn Core Lib, Temporary Spawners, U Team Core, Chat Heads, CraftPresence, CTOV, JEI, Smooth Chunk Save, Project Vibrant Journeys, EMI, TrashSlot, UniLib, Friends & Foes, Inventory Sorter, Oh The Biomes We've Gone, Cooking for Blockheads.
- Updated from Forge 47.2.12 to 47.2.25.
- Added Armor Set Bonuses.
- Added KubeJS.
- Added EntityJS.
- Added Refined Polymorphism - adds compat between RS and Polymorph.
- Added SBM Charcoal Block.
- Added Fzzy Config for Loot Beams.
- Added Long NBT Killer.
- Added NaNny.
- Added Sky Breaker - fixes some compat with Blue Skies.
- Added Structure Credits - see what structure you've entered!
- Added Tool Stats.
- Added ColoredWater.
- Added Think Before Drop - prevents accidental dropping of weapons.
- Added some Sky Village compat datapacks.
- Added ChatPlus.
- Added Parties.
- Added RoE Weapons - thanks Poe!
- Added Stardew Fishing - revamps how fishing is done!
- Added Vivecraft, ImmersiveMC, VR API.
- Re-added Pick Up Notifier and removed Loot Journal.
- Replaced Spice of Life: Apple Pie for Onion edition.
