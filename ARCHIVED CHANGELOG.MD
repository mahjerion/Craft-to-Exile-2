# Archived Changelog

## [0.9.1c] - 2025-02-04

### Updates
- Aura penalty has been lessened. It's now a static -20% instead of going from -40% to -20%.
- Reverted Target Dummy resistance changes, they were affecting penetration stats.
- Safeguard and Fury now give more % chance to get their respective stacks per level.
- Fury and Safeguard now last 5 mins instead of 1.
- Safeguard max level is now 4.
- Lowered Tier mob damage scaling by 20%. The previous increase to this in combination with core stat nerfs was too much.
- Accurate mobs no longer get Critical Hit.
- Critical mobs no longer get Critical Damage.
- Penetrating mobs have been nerfed drastically.
- Lowered Alpha Yeti, Blockchain Goblin, Minoshroom, Minotaur, and Winter Wolf penetration values.
- Reduced Warped Mosco damage by 25%.
- Improved Ailment descriptions even more.
- Modified Repair Kit Stone consumption value and increased Repair Kit repair rate.
- Proc Skills no longer consume resources.
- Blizzard has received the same treatment as Gong Strike and Whirlwind, and the amount of MS it scales with is now static instead of increasing per level.
- Updated Gladiator_5 to use Physical Damage instead of Physical All Weapon Damage - functionally the same, just using an updated stat.
- Reduced Twilight Forest difficulty by about 12.5% or so.
- Revisited Prophecy Rewards. Weights have been shifted so you're now more likely to find higher-rarity Prophecies. However, costs have increased as an offset.
- Scythe of the Harvest has been changed to a Helmet and is now called Bounty of the Harvest. The level to Harvest has also increased from 4 to 12-16.
- Netherite Bastion now gives 35% Fire Damage Taken instead of 50%.
- Corporeal Respite now gives 50% Physical Hits Damage Reduction and -60-30% Bleed Resistance instead of -150-100%.
- Sniper Gamechanger now gives 40% More Basic Attack Damage as well.
- The description on Projectile Skill Damage stat has been updated.
- Chronomancer Skills have been changed to consume stacks on use instead of upon completion.
- Reduced the cost of Turbo.
- Map Affix nerfs/readjustments (buff for player). Reducing volatility/variance.
- Chat box is immovable by default now, but there is a message on join showing you how to move it (Right CTRL).
- Added some Undergarden Delight quests.
- Added Milady Hat reward to Homestead quests.
- Upped default Map Gen Mob Radius (doesn't apply to Official Server).
- Positive Effect Strength nodes have been nerfed.
- Generosity now gives 20% Positive Effect Strength instead of 25%, and it now also gives 8% Damage Received.
- Moo.

### Fixes
- Fixed Krampus still spawning when it shouldn't have been.
- Fixed Harvest and Boss Map rooms not generating.
- Fixed Aquaculture fishes not being obtainable via fishing.
- Fixed Obelisk teleport issue.
- Fixed Katar not being registered as gauntlets.
- Fixed some Party stuff.
- Fixed Prophecy issues in Maps.
- Fixed Buster Sword unknown stat.
- Fixed Hyperion Greatsword unknown stat.
- Fixed Master Backpack recipe.
- Fixed Self Damage Skill description typo saying the opposite.
- Fixed Mage Circle missing the Area and Buff tags.
- Enabled FancyMenu for Advance Team UI.
- Disabled the crafting of coinpile blocks due to an exploit. Sorry. :(
- Fixed some Fishing loot tables being broken.
- Orb of Foolish Risk no longer works on non-Jewels since they're static ranges anyway.
- Fixed some weapons have incorrect ranges.
- Quality now shows on gear correctly.
- Fixed mobs insta-death on spawn bug.
- Receive Ailment stat is now red when positive.

### Mod Updates
- Updated Library of Exile, Mine and Slash, Advanced Team, Aggro Indicator, Connectivity, CraftTweaker, EMI Loot, Farmer's Delight, Legendary Tabs, Lithostitched, Undergarden Delight, Waystones, Supplementaries, Sophisticated Mods.

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
- Fixed Prophecy-specific Unique reward being a thing.
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

## [0.8.4b] - 2024-12-11

### Updates
- Updated links to Discord to use new custom URL: https://discord.gg/craft-to-exile
- Added a new Plate Chest Unique thats really hard to find.
- Some Uniques and Runewords have been changed to provide bonuses to Magic Shield instead of, or in addition to Health.
- Some Uniques and Runewords have been changed to provide bonuses to Energy instead of, or in addition to Mana.
- Percent Leech stats now trigger off of bonus damage as well.
- Lowered Wither damage by about 18%.
- Added some quest descriptions for some of the Fishing Chapter quests.
- Added a little blurb at the Wither quest about level differentials penalties.
- Increased spawn rate of Skelewags.

### Fixes
- Fixed Stormwielder Unique not proccing Chain Lightning.
- Fixed Revenant Slam not dealing Chaos Damage.
- Fixed Discharge not playing sound correctly.
- Fixed missing Discharge tag.
- Fixed some structures not spawning in Deeper Darker.
- Fixed Ballista Runeword being unavailable.
- Fixed Auto Repair Kits not consuming materials.
- Fixed Stones spamming chat when used on Auto Repair Kits.
- Fixed weird interaction with Soul Modifiers and offhands.
- Hopefully fixed keybind issues with Mine and Slash.
- Fixed Golems not having base Skill proc chance.

### Mod Updates
- Updated Lightman's Currency, Auto Repair Kits, Mine and Slash.
- Replaced Loot Beams with Clefal's version for improved performance and compatibility.

## [0.8.4] - 2024-12-10

### Mine and Slash Updates
- Marauder Gamechanger and Armor-clad Faith Unique now give flat penalty to Attack Speed and Move Speed again.

### Fixes
- Fixed some quest localization.
- Fixed Lifestealer stats.
- Fixed spawn of Lifestealer and Nightmare Stalker.

### Mod Updates
- Added InControl.
- Removed Dimension Viewer.

## [0.8.3] - 2024-12-10

### General Updates
- Ice and Fire has been replaced with Born in Chaos. Born in Chaos mobs/structures have been populated Blue Skies to some extent. Their mobs are also found in Maps and have replaced most of the quests.
- We now have Auto Repair Kits which can help prevent items from breaking unexpectedly! Keep these kits charged and they'll automatically repair your equipment for you. Higher tier kits have more capacity and repair more at a time.
- Mining Profession no longer drops blocks and instead drops the ores directly.
- Lowered Structure spawn rate of Bathhouse and Lighthouse.
- Final wave of Gateway of the Ice Maze now summons an Eel.

### Quest Updates
- Epilogue Achievement quest now gives an Epic Hat Bag.
- Added a new quest regarding Auto Repair Kits.
- Nomad now requires only 3 upgrades instead of 5.
- Advanced Storage no longer references Create and now references Botania.
- Big Band Player no longer requires impossible items.
- Quest mistakenly mentioning Zinc has been changed to Silver.

### Mine and Slash Item/Stat Updates
- Added a new stat: Roll Cooldown which lowered recharge time for Combat Rolls. It currently can appear on Boots and Totems as a suffix.
- New Unique: Terrablade. Yes, it's that Terrablade. The Terrablade gives bonuses to Melee Damage and Projectiles. Note though that bonuses to projectiles don't actually affect the projectile from Terrablade.
- Armor-clad Faith now gives - percent instead of flat Attack Speed and Move Speed. The penalty values have been lessened.
- New Ring Runeword: Destruction. This ring gives the user a bunch of proc stats...
- New Sword Runeword: Hurricane. Gain Physical to Cold and Lightning Damage conversion stat in addition to bonuses to Whirlwind!
- New Weapon Runeword: Breath of the Dying. This 6 Rune Runeword gives big bonuses to damage and a chance to cast Putrid Breath on Kill.
- New Boots Runeword: Lavaspur. This Runeword gives substantial bonuses to Fire Damage mitigation, including Fire Damage Reduction.
- New Crossbow Runeword: Ballista. Give up bonus mulitiple projectiles and speed for a chance to hit once, and HARD.
- Nerfed Exile Runeword stats.
- Venom and The Novice Runewords can now be placed on Axes (forgot).
- Crossbow basic attack damage increased by 25%.
- Staves and Daggers can be affected by Attack Damage now.
- Gateway on death maximum stat cap reduced.
- Pressing SHIFT now shows you locked sockets.
- Reduced player base Mana/Energy Regen by 33%.

### Mine and Slash Class Updates
- New Lv. 10 Elementalist Skill: Fire Wall! Spew forth flames on the ground that knockback enemies and keep them away from you.
- New Lv. 30 Shaman Skill: Chain Lightning Totem! This totem periodically sends out a Chain Lightning projectile that behaves like Chain Lightning. It deals a bit less damage than Chain Lightning, but every level in Chain Lightning increase the damage of Chain Lightning Totem!
- New Lv. 25 Minstrel Skill: Clamor, Crash, Clatter! Send out a brutal sound wave that hits nearby enemies. Expend an Endurance Charge to also deal Fire Damage and apply Scorched, a Power Charge to also deal Lightning Damage and briefly stun enemies, and/or a Frenzy Charge to also deal Cold Damage and slow enemies. Using this Skill has drawbacks, as it deals Physical Damage to the caster as well.
- Grand Cross from The Written Word now deals 300% of Weapon Damage instead of 150% each activation, for a total of 900% Weapon Damage instead of 450%, and now deals Lightning Damage to the caster instead of healing nearby allies. The self damage is equal to 20% of the user's Health + Magic Shield, but can be mitigated.
- Arrow Totem has a cooldown of 2s instead of 1s now. The charge regen time remains the same.
- Arrow Totem now costs a bit of Energy.
- Totem Skills have had their Mana Costs increased.
- Reduced stat bonuses of Sharpen by 50% per level (25% overall).

### Mine and Slash Talent Tree/Ascendancy Updates
- New Gamechanger: Combat Talent! This node is near the Bow start and grants the player the following: Gain +25% MORE Ranged Skill Damage on Melee Skill Hit, Gain 25% MORE Melee Skill Damage on Ranged Skill Hit.
- Steady Hand now gives 20% Increased Damage instead of 30% MORE Damage. It now also gives +500% MORE Accuracy (you're not supposed to miss with this).
- Marauder now gives -20% Reduced Attack Speed instead of -30% Attack Speed. Similarly, it now gives -20% Reduced Move Speed instead of -20% Move Speed.
- Cruel Ascendancy points are now earned from Steely Resolve in Act III instead of Slippery Swimmer.
- Added some new Knockback Resist and Move Speed nodes to the Talent Tree.

### Mine and Slash Mob/Map Updates
- Increased Anglerfish spawn rate.
- Lowered spawn rate of Farseers drastically.
- Removed Ferrous Wroughnaught and Knight Phantom from the Uber Boss pool.

### Fixes
- Fixed leech localization, oops.
- Fixed FLAN config regarding buy/sell.
- Fixed incorrect information regarding Ascendancies in the bubble.
- Fixed missing localization for Frenzy Charge When Hit.
- Gateway of the Raider penultimate wave has been fixed. It was incorrectly spawning the Invoker instead of Inquisitor.
- Fourth Wave of Gateway of Emerald Grove has been fixed/replaced with a new mob.
- Fixed Lightman's Currency font issues. You'll need to unequip the Redcap_LC_Retexture7.5.zip Resource Pack.
- Fixed Smoke Runeword giving percent Chaos Resist instead of flat.
- Fixed Act Gateways not proccing. They also now abide cooldown rules.
- Crafting Stations crafting a few times instead of all has been fixed.
- Maybe fixed 0 HP mobs.

### Mod Updates
- Updated ModernFix, Moonlight, Lightman's Currency, Lootr, ModernUI, Mine and Slash, Sophisticated mods, Doggy Talents.
- Added Auto Repair Kits.
- Added YDM's Weapon Master - displays your items on your self.
- Added Hidden Names - remove player name tags as it interferes with Neat bar.
- Added Born in Chaos.
- Removed Display Delight.
- Removed FindMe due to an exploit.
- Removed Ice and Fire.
- Removed Formations due to crash.

## [0.8.2] - 2024-12-06

### Updates
- Added new soul modifier currencies for the hybrid armors.
- Cleaned up the leech stat descriptors and naming convention.
- Steal/Spellsteal stats now only apply to HITS. This change does not apply to Elemental Steal, and DoT Steal (obv).
- Tomes now give a small amount of Physical Resistance.
- Totems now give some Elemental Resistance.
- Added 2 new prefixes, one for Totems which provides Move Speed, and one for Shields which provides Knockback Resist.
- Buffed Dragons.
- Lowered the volume of the Level Up sound.
- Lowered positioning of Fighter Stance particles so it's not as in your face.
- Lowered Hummingbird, Crow, and Cockroach spawns - lots of lag.

### Fixes
- Players no longer show skulls.
- Infusions should be fixed.
- Currency/Socketing is now changed back to ding sound! Level up is still the same.

### Mod Updates
- Updated Sophisticated Storage, CreativeCore, AmbientSounds, Mine and Slash, EntityCulling, Moonlight.

## [0.8.1] - 2024-12-05

### Updates
- Updated the modpack landing page on CurseForge: https://www.curseforge.com/minecraft/modpacks/craft-to-exile-2
- New Lv. 20 Support Gem: Focused Shot! Increases Projectile Damage greatly but prevents you from adding any additional projectiles.
- Gear rarities incrememnt again instead of all capping at 100. The overlapping stat range amount is larger now, though.
- Witch Gateway is now spawns much fewer Witches and instead spawns some Zombies as well.
- Zombies now have innate Move Speed.
- Husks now have innate increased Health.
- Reduced Act Gateway proc chance.
- Disabled Mutant Skeleton Leggings and Boots.
- Disabled Supplementaries Cannon.
- If you're banned FLAN deletion time is now 5 days instead of 30.
- Reduced Zombie fishing rod chance by 20%.
- Destiny Quest now lets you use command as a reward.
- You can no longer cage Villagers.
- Ice and Fire Lich is now level 45 and Frostmaw is now level 50.
- Pixie and Cyclops have been moved to Everdawn and the End, respectively.
- Moved Cyclops quest to Act V.
- Substantially lowered spawn rates of Ice and Fire mobs/structures, especially in the Overworld.
- Reduced Umvuthana pack size.
- Lowered Naga spawn rate in Undergarden.
- Reduced Vindicator damage by 10%.
- You can no longer cook babies.
- Disabled Gorgon.
- Silver Ore now gives Mining EXP.
- Tried to address some lag.

### Fixes
- Removed Warden Legs instead of Chest. Oops.
- Fixed Act III Gateway spawning the wrong type of Troll.
- Fixed Act III Gateway Umvuthana wave.
- Fixed level up sound being used for other activities.
- Fixed Bestiary III requiring incorrect mob to kill.
- Hopefully fixed some sources of lag.
- Fixed Frost and Fire Golem innate Spell Chance not applying.
- Added a bunch of missing gear compats.
- Fixed Brigandine Chest having too much Armor.
- Block now works on bonus damage too.
- Offhands now correctly drop if requirements are not met.

### Mod Updates
- Updated Sophisticated mods, some Delight mods, Mine and Slash.
- Updated Ashen Custom Font.
- Added Euphoria patches.
- Removed TownTalk.

## [0.8.0b] - 2024-12-03

### Updates
- Modified some FE requirements for Refined Storage.
- Endurance Charges now give 2% Damage Reduction instead of 3%.
- Changed Act III Gateway so that Forgotten are a separate wave.
- Lowered Siren spawn rate.
- Disabled Terra Blade.

### Fixes
- Fixed an issue where Mobs were casting Black Hole.
- Fixed Arachnid Inoculation not proccing.
- Fixed passive mobs spawning Gateways.
- Removed Siren from Overworld.
- Fixed an unknown stat under Raider Ascendancy.
- Fixed incorrect gear compat typo.
- Fixed missing Tide Pike compat.
- Fixed missing Botania axe compats.
- Fixed a Botania Quest auto-completing.
- Fixed localization.
- Fixed Arcane Ward and Armor-Clad Faith Uniques with missing stats.
- Fixed Venom Runeword using incorrect Runes.
- Fixed Wake of Destruction using incorrect stat.

### Mod Updates
- Updated Mine and Slash.
- Removed JadeColonies.

## [0.8.0] - 2024-12-03

### General Updates
- Create has been removed, and Botania has been added! This is a pretty big change that might be met with some resistance, but Botania fits the pack a lot better in terms of what it can provide. Some rewards from Botania are combat focused, in contrast to Create which were mostly automation-related. Additionally, Botania's performance and exploits are far far far less than what we had with Create.
- MineColonies has been replaced with Minecraft Comes Alive! In my head, both of these mods achieve very similar goals for what I wanted out of them. They both provide players an alternative way to manage their base - allowing them to play out the role of a leader of a town. However, the main difference is that Colonies was too parasitic in terms of time. If you started investing a bit of time into Colonies, you'd soon find yourself only messing with Colonies. Minecraft Comes Alive fixes this problem (in my opinion). First off, MCA replaces Villagers completely - this means more seamless integration with the RPG aspect of the pack. Not only does it let you play the role of a leader, you can even mingle and form relationships with the villagers. It's not longer just a 'side' thing, as you literally start off in a village!
- Overhauled biome generation with BYG, new dungeons, and an overhauled End!
- The End has new biomes and structures, and some new interesting gear that can be crafted.
- Increased Dungeons Arise structure spawn rates by about 25%.
- Blue Skies dimension structure and mob spawn rates have been increased.
- Populated Undergarden, Blue Skies dims, and Otherside with some fun structures and tons of new mobs from Ice and Fire, Mowzie's, When Dungeons Arise!
- Increased spawn rate of Aquamirae structures.
- Gateway of Overworldian Nights has been changed to spawn Strays instead of Skeletons. It also spawns less mobs per wave.
- Gateway of Overworldian Nights now cost an additional 1 gold coin to craft.
- Added a crafting recipe for Soul Star and updated recipe accordingly.
- Nerfed Stone Golem Health by a lot.
- Sophisticated Storage and Backpack recipes have been made significantly cheaper. You no longer need to invest into Tech for them.
- Combat Roll base cooldown is now 3s instead of 2s.
- Combat Roll Multi-Roll Enchantment has been disabled.
- Combat Roll Longfooted and Acrobat max level have been lowered to 2 and 5, down from 5 and 10, respectively.
- Disabled recipes for Warden and Mutant Monsters Chest armors.
- Air Hop was removed, so this enchant is no longer available. You can get it through Botania Trinkets now.
- A lot of items have had their tech crafting requirements overhauled due to the removal of Create and addition of Botania.
- Added some new loading screen tips!
- Some unobtainable items are now hidden from JEI - thanks Elico!
- Reduced Baby Zombie spawn chance.

### Quest Updates
- Added a whole new section to the Epilogue Chapter which goes through Twilight Forest. Quests in the Epilogue don't provide experience rewards and instead give item rewards. Note that this is a level 90 zone.
- Homestead Chapter has been redone. It now introduces you to Minecraft Comes Alive instead of MineColonies.
- Technology Chapter has been redone. It now introduces you to Botania instead of Create.
- A new Bestiary Quest line in Act I has been added, tasking you with finding various high-level mobs in the Overworld.
- Added some new quests in Act V showcasing Outer End.
- Added a new Act V quest regarding the Shelterer.
- Added some new Professions Quests throughout the Campaign.
- The Unique shop in the Shops Chapter is now only available after completing a new quest in the Epilogue.
- Act IV Quest experience reward has been increased throughout.
- Added some new kill quests in the Undergarden, Blue Skies dimensions and Deeper Darker for the new mobs.
- Updated description for finding Oxygelium. You can find them from Tortured Souls, which can be forcefully encountered in the Gateway of the Ice Maze.
- Enderiophage description has been updated. You can build these things too.
- Added a quest for Display Delight.
- You can now view recipes directly from Quests.
- Some Quests have been reworked.
- Re-added the Prologue Quest going over broken key binds.

### Mine and Slash General Updates
- New Craft to Exile 2 pre-Map mechanic! Mobs in dimensions up to and including Act V can now spawn Gateways on death. The Gateway they spawn depends on which dimension you're currently in! Successfully completing the Gateway gives you rewards which may include the Dimension-specific Rune!!!
- Cooldown Reduction now applies to Charge Cooldowns as well.
- Projectile Damage has been reworked. Instead of working on any Skills tagged with Projectile OR any Skills as long as user is wielding a bow, it now only works if the Skill is tagged with Projectile.
- Reduced base Mana and Energy Regen by 25%.
- Elemental Resist suffixes have been buffed by 25%.
- Players and Mobs now have a base Shock and Shatter Proc Chance of 10% and 5%, respectively.
- Added a new cool sound on level up.
- Profession Infusion and Gear Crafting has been reworked a bit so that the cost of Stone starts low and goes up as you increase in level instead of being based on rarity. Of course, the cost still goes up with rarity as it requires higher rarity Stone, but crafting a Common vs. Mythic at level 10 will still only cost 2 Stones each, instead of 4 and 24. There was also a bug where a bunch of recipes had the incorrect Stone rarity as part of the recipe.
- Tier 1 Jewelry Crafting now uses Copper instead of Zinc Ingots as the identifier.
- Lowered the crafting cost of Sharpening Stones.

### Mine and Slash Item/Stat Updates
- New PATREON Unique Tome! Arcane Ward, designed by NEON! This tome provides HUGE bonuses to Mana and Damage Absorbed as Mana at the expense of damage. Ever wanted to be a Mana-tank? Now you can!
- The following contributor-designed items were designed by the hardworking volunteer builders and testers Kaecie, DoutingDonut, Realworldjedi, Villain, and DuskTheSnep. These builders spent countless hours working on new Maps, fixing Maps, and the jaw-dropping spawn found on the Official Server! There are more contributor-designed items on the way, so stay tuned!!!
- New Contributor-Designed Unique Boots! Glazed Frenzy, designed by DoutingDonut! These boots give a substantial damage bonus to ranged builds at the expense of having to roll for positive resistances.
- New Contributor-Designed Unique Tome! Order of Despair, designed by Realworldjedi! This truly Unique Tome gives Damage to Cursed Per Soul Stack at the expense of Curse Effectiveness!
- New Contributor-Designed Unique Helmet! Call of the Void, designed by Villain! This high-level helmet enables something players have been asking for... Low Health builds! With this helmet equipped, you can't regenerate Health or steal Health. You can still heal through Skills, however. The helmet provides the user a 20% chance to cast Healing Aria on hit!
- New Contributor-Designed Unique Chest! Armor-Clad Faith, designed by Kaecie! This high-level chestplate provides increasing Damage Reduction the lower your Health. Additionally, it provides bonuses to Health, Grapple, and Knockback Resist at the expense of Attack and Move Speed!
- New Contributor-Designed Runeword Axe! Carpe Noctem, designed by DuskTheSnep! This Axe Runeword adds substantial bonuses to Cold Damage and converts your weapon's Physical Damage to Cold. It also provides bonuses to Attack and Move Speed.
- New Moderator-Designed Unique Axe! Stormwielder, designed by Theesle! This Axe converts your Physical damage to Cold and causes your attack hits to spew out Chain Lightning!
- NEW Base Armor types!!! We now have dual-stat armors: Brigandine (STR/DEX), Chainmail (STR/INT), and Vest (INT/DEX). These armor types are fully integrated and come with their own new Uniques (found below).
- Dagger, Hammer, and Spear stat reqs have been increased by 25% to stay in line with the new Base Armor Types.
- Helmet implicits have been renamed and reworked. Each type of helmet (cloth/leather/plate) can roll from 4 different implicits, rather than all sharing from the same 5 implicits. That means 7 new implicits have been added, and existing ones reworked.
- Stat rarities have been reworked a bit, instead of lower rarities always rolling really bad stats (Common only rolled 0-10%), now all rarities have a chance of rolling the between stat range of 0-100%. However, higher rarities have lower volatility, eg. Rare is 30-100%, and Mythic is 75-100%. The number of affixes still increases with rarity, however.
- 26 new Uniques for the new armor types. There's too many to reveal in the changelog, so here are some hints. There's a Unique that provides a substantial bonus to Physical Resist, some Uniques that have interaction with Endurance/Power/Frenzy Charges, a Unique with a new Proc stat, a Unique that gives Jewel Sockets, a Unique that gives MORE Summon Damage per Power Charge. Check them out in the Hub Library!
- How Uniques drop has been reworked. They now have a minimum level AND Tier required before dropping. All Uniques have had their drop levels and Tiers adjusted. Every 10 levels, the pool of findable Uniques increases. Any Uniques that can drop below level 60 do not care about Tiers, meaning you can find these Uniques as you adventure! That means the pool of findable Uniques before Maps is now 108, up from 48! The remaining Uniques that drop starting at level 60 care about Tiers - every 20 Tiers more Uniques get introduced into the mix. The last currently findable Unique can be found in level 90 Maps, at Tier 100.
- Added 8 new Runewords! Radiance, Turbulence, Smoke, Exile, Insight, Malice, Heavenly Tear, and Venom. Check them out in the Hub Library!
- A Father's Love Unique now gives 6% flat Block instead of 8%.
- Azurewrath Unique now also provides Increased Area of Effect.
- Bulkwark Unique now gives more percent Armor.
- Duskdeep Unique now gives flat Heatlh.
- Dying Breath Unique now gives Damage to Cursed instead of Curse Duration.
- Limbsplit Unique now also gives Area Damage.
- Nagelring Unique now also gives percent Energy.
- The Beast Unique now gives much more Health per 10 Strength.
- The Written Word Unique now grants 50% Increased Healing instead of 25%.
- Towering Physique Unique now gives a MORE bonus to Magic Shield instead of PERCENT.
- Trolltimber Spire Unique now gives 33% less Health than previously.
- Voltaxic Rift Unique now grants additional Lightning and Chaos Weapon Damage instead of converting Phys.
- Voltaxic Rift Unique local Weapon Damage bonus has been reduced to compensate for the above.
- Voltaxic Rift Unique now give +2 Ranged Skills instead of +1.
- Redbeak Damage on Low Health has been nerfed a bit.
- Winter Chill Unique now gives MORE Cold Damage instead of increased.
- Stealth Runeword can now be crafted on chests.
- Flickering Flame Runeword can now be crafted on pants.
- Chains of Honor now requires an additional Ita Rune to craft.
- Rebalanced chest Infusions by reducing their power by about 40-50%.
- A bunch of damage-based Augments have been nerfed. They were missed.
- Removed a duplicate Infusion which gave Armor and Magic Shield.
- Added a missing Infusion for chests which give Dodge and Magic Shield.
- Quality on gear now provides a flat bonus rather than being a multiplier (buff).
- Legendary drops are no longer announced in chat, only Mythic and Unique.
- Damage Reduction and Damage Suppression stats have been nerfed. Some sources of Damage Reduction have been changed to Physical Resistance as well.
- Sources of Cast Speed and Cooldown stats have been nerfed.
- Cooldown Reduction now caps at 75% instead of 80%.
- Rune droprate has been lowered by 75%.
- Rune primary drop source is now from chests. The drop rate per chest is 10%. Before Maps, you can get up to Eno/Xer Runes. In Maps and Twilight Forest, chests will have up to Yun Rune. Note that Boss Runes won't drop from these pools. Higher Tier Maps will drop more Runes.
- Increased values of Move Speed from almost all sources.
- Increased Passive Block Chance implicit on Shields by 20%.
- Spear Weapon Damage reduced to be 1.5x of one-handed weapons instead of 1.66x.
- You can now only apply ailments if the hit isn't blocked.
- Damage Reduction cap is now 50% instead of 75%.
- Passive Block now reduces damage by 50% instead of fully.
- You can no longer dodge ailments.
- 'Low' is now considered 50% and instead of 30%.
- 'Very Low' is considered 25%.
- Leech Cap sources have been nerfed or changed to PERCENT from FLAT.
- Ailments can now proc from 'bonus' damage.

### Mine and Slash Map/Mob Updates
- Mobs and Bosses have had their scaling completely reworked. Feedback is appreciated. In general, mobs scale a lot harder now but multipliers from rarity, entity-specific configs, dimensions, tiers, etc., all scale much less. There should be fewer "gotcha" moments now. This allows me to scale mobs harder overall without worrying about outlier mobs as much. Of course, this can still happen but it will happen much less often.
- Mobs that are too high level now have a Skull next to their name.
- How Map progress is tracked has been changed slightly. You no longer need to scout the entire Map before the Map progress updates.
- Vampire Mob Affix has been nerfed substantially.
- Massive Mob Affix now gives 25% MORE Health instead of 30% MORE.
- Massive Mob Affix now also gives the mob 50% Knockback Resistance.
- Mob Map Affix which provides Move Speed now also provides Knockback Resistance.
- Added some new mobs to Map pool.
- Added some new mobs to the Uber Boss and regular Boss pools.
- Removed BOMD from Uber Boss pools.
- Boss and Uber stat multiplier has been reduced.
- Bosses have been nerfed (Maps and Dimensions).
- Boss and Uber mobs can only spawn 1 Affix now. They're hard enough as it is...
- Mob Rarity loot and EXP multiplier have been readjusted to compensate for bonuses from Map Tier, entity type, etc. It's been lowered on the higher end, but lower rarities remain untouched.
- Higher Rarity mobs now have resistance to Chill/Slow.
- Dimension Bosses no longer spawn at a specific level, they now spawn at a minimum of that level.
- Map affix which gives players - Resists has been changed to - Max Resists.
- Map and Mob affixes that modify Mob damage to elemental are now mostly conversions instead of bonus.
- Map Resistance requirements have been reduced.
- Map Lives is always at 3 now instead of 5 -> 3, Common -> Mythic.
- Uber Frags are limited to 1 drop per Boss/Uber Boss.
- Uber Frags now only drop from Legendary and Mythic Maps.
- Uber Bosses now cast anti-CC every few seconds, removing negative effects from themselves.
- Prophecy Coins are now rarer.
- Prophecy coin cost modifiers have been reworked. Higher rarities are now more expensive.
- Effectiveness of Chill from Freeze ailment is now reduced on higher-rarity mobs.
- Mobs can now apply ailments.
- Mobs now have a bit of innate Armor Penetration.
- Map and Mob Affix penalties have been lowered to reduce "spikes" in difficulty.

### Mine and Slash Talent/Ascendancy Updates
- New Talent located near the Spear starting point: Immutable. Sacrifice Dodge and some Elemental Resistances for massive defenses against ailments.
- New Talent located near the Axe starting point: Marauder. Gain large bonuses to Melee Damage at the expense of Attack and Move Speed.
- New Talent located near the Hammer starting point: Brutalizer. Basic Attack Hits give the user Brutalizer stacks which give MORE Physical Damage per stack for 6s.
- New Talent located in between the Staff and Dagger starting point: Ghost Shroud. Upon successfully dodging, gain a Ghost Shroud stack. When hit, consume a Ghost Shroud stack to gain a buff which recovers 9% of your Magic Shield over 3 seconds.
- New Talent located near the Staff starting point: Twincast. Gain +1 Projectile Count and -35% Reduced Projectile Damage.
- Masochism has been moved to the Bow starting point.
- Unstoppable Ascendancy node now gives 100% Knockback Resistance.
- Battlemage Ascendancy which provides Health to Mana now grants 30% instead of 25% and also provides 6% Mana Regen.
- Battlemage Ascendancy which provides Mana to Energy now also grants a bit of Energy Leech Cap.
- Battlemage Ascendancy which provides Mana to Energy now grants Energy Steal instead of Regen.
- Battlemage Ascendancy which provides 40% Lightning Penetration has been changed back to Lightning Damage Ignores Elemental Resists. However, it now longer only applies to critical hits, and applies to all Lightning Damage. This node also now provides a small bonus to Lightning Damage.
- Champion Ascendancy which provides bonus to Augment Effect now provides more Augment Effect.
- Champion Ascendancy which provides Damage when on Low Health now gives 20% Damage Received instead of 25%.
- Some of the Elementalist nodes now provide Elemental Resists.
- Gladiator Block per Endurance Charge and Physical Health Leech have been buffed.
- Guardian Damage per Endurance Charge has increased from 6% to 8%.
- Ranger Ascendancy chance to gain Gale Force on hit has increased from 10% to 15%.
- Ranger Ascendancy which gives LMP now gives -40% penalties to Damage and Heal Power instead of 30%.
- Ranger Ascendancy which gives LMP now also correctly gives -40% Heal Power.
- Raider Ascendancy which provides Health Leech and Cap now also provides Energy Leech and Cap.
- Some of the Trickster defensive nodes have been dialed down a bit.
- Juggernaut Ascendancies give less slightly Health/Armor/Health Regen.
- Lich Ascendancy now gives a bit more Magic Shield.
- Necromancer Block Chance sources have been buffed.
- Chieftain Ascendancy which gives 10% MORE Health has been reduced to 5%.
- Ascendant Ascendancy nodes which provide bonuses to Augments have been buffed.
- Other Ascendant nodes now give a bit more Critical Damage and Damage Reduction.
- Assassin Ascendancy node which gives MORE Damage per Power Charge now gives 4% per Power Charge instead of 2%.
- Assassin Ascendancy node which gives MORE damage to targets near full health now also gives MORE damage to targets on low health.
- Curse Master Gamechanger now gives 25% more Damage to Cursed instead of 30%.
- Versatility now gives -3% Max Ele Res instead of -5%.
- Glancing Strikes now gives 20% Damage Received instead of 25%.
- Collateral renamed to Focused Technique.
- Major Block Chance nodes now give 1% Flat Block Chance and 6% Increased instead of 20% Increased.
- Physical Weapon Damage has been changed to Attack Damage by The Spear starting point on the Talent Tree.

### Mine and Slash Skill/Passive Updates
- You can now earn an additional 4 Passive points for earning the new Epilogue Achievement. You'll need to (almost) fully complete Twilight Forest for it!
- You can now earn an additional 2 Skill points for defeating each of the Twilight Forest bosses, for a total of 10 points!
- Buff Skills now show some sort of indicator for their range on cast.
- New Lv. 10 Warlock Skill: Revenant Slam! Slam the ground in front of you, dealing Cold Damage in an area and leaving residual desecrated ground in front of you. While present, Ice Rocks shoot out from the ground in the desecrated ground, dealing Cold Damage to any enemies hit. If you have 5 Soul Stacks, instead deal Chaos Damage in an area and have Chaos Balls shoot out from the ground, dealing Chaos Damage. Note that the Ice Rocks knock enemies back, whereas the Chaos Balls don't.
- New Lv. 20 Shaman Skill: Arachnid Inoculation! Give yourself a buff that converts your Physical Damage to Chaos and provides Chaos Resistance. Additionally, while under the effects of the buff, Chaos Hits have a chance to cast Summon Spider which are short-lived Chaos Summons that don't obey Max Summon Capacity. Chaos Critical Hits have an increased chance of proccing this effect. Note that hits from Summon Damage don't trigger this proc.
- Thorn Bush has been moved from Warlock to Shaman and is now a level 1 Skill.
- Static Effect now gives 5% Mana Regen per stack instead of 8%.
- Lightning Warp Cooldown has been reduced from 6s to 4.5s.
- Lightning Warp Mana Cost has been reduced by 10%.
- Lightning Warp no longer has a cast time.
- Galvanic Blade Proc chance has been reduced by 20%. If you're proccing via crit this change does not affect you.
- Summon Wolf now grants 50% increased Summon Health per level.
- Fighter/Defender Stance have collapsed into one Skill Toggle now. This is only possible due to recent back-end changes!
- Incinerating Weapon Throw now performs an initial hit in front on use.
- Quake AOE has increased by 33%.
- Charge now lasts half as long.
- Charge now does something a bit differently depending on what stance you're in. In Fighter Stance, travel 50% faster than in Defender Stance, but in Defender Stance, stun enemies in an area upon collision.
- Snipe and Execute now deal one bigger hit rather than hitting twice while Invisible.
- Execute hit box has been fixed and will reach further out in front of you rather than to the sides.
- Execute is no longer tagged with Area.
- Snipe damage has been reduced by 9%. I'm pretty sure it scaling up to 6 instead of 5 was a typo as it doesn't make sense that Snipe is better than Execute.
- Execute and Snipe no longer deal double damage while invisible. They now deal 50% more damage instead.
- Execute now deals increased damage to targets on low health. Damage to enemies on low health should be similar to damage dealt in 0.7.3b.
- Snipe now deals increased damage to targets near full health. Damage to enemies on full health should be similar to damage dealt in 0.7.3b.
- Smoke Bomb now provides Invisibility for 10s instead of 5s, and Speed for 5s instead of 3s.
- Flicker Strike base Cooldown is now 4s instead of 2s.
- Whirling Blades damage has been reduced by about 10%.
- Bola now requires you to be level 20 instead of 30.
- Rogue passive which gives Phys to Chaos now gives 6.25 instead of 6 per level.
- Magic Missile damage has been reduced by about 12-15%.
- Explosive Arrow now has the Area tag. Technically this is a fix but it's also a buff.
- Trap Skills now have a 75% larger trigger radius which should make them feel a lot more consistent.
- Trap Skill AOE has increased from 2.5 to 3.
- Minstrel passive which gives Heal to Skill Damage now gives 6.25 per level instead of 10.

### Mine and Slash Support Gem Updates
- New Lv. 1 Support Gem: Faster Attacks! Supported Skills gain bonuses to Weapon Skill CDR and Damage.
- New Lv. 10 Support Gem: Void Manipulation! Supported Skills gain bonuses to Chaos Damage at the expense of Elemental Damage.
- New Lv. 20 Support Gem: Fortify! Supported Skills grant Fortify on Melee Hit, which provides 10% Damage Reduction for 4s.
- New Lv. 20 Support Gem: Endurance Charge On Hit! Supported Skills have a chance of generating an Endurance Charge on hit. It also causes each Endurance Charge to increase Damage.
- New Lv. 30 Support Gem: Iron Will! Supported Skills grant gain Spell Damage based on Strength. Iron Will also provides some inherent bonuses to Spell Damage.
- The above new Support Gems have been added to the shops.
- You can now only equip 1 Cooldown Support Gem type at a time for each Skill.
- Mageblade Support Gem no longer reduces Weapon Damage.

### Fixes
- Fixed an issue where Discharge was not triggering off of Critical Hits.
- Fixed some localization.
- Fixed some missing tag localizations.
- Fixed some Quest typos.
- Fixed an issue where Act III Achievement was incorrectly requiring Disenchanter Quest.
- Fixed an issue where Act IV Achievement didn't require Disenchanter Quest.
- Fixed Energy to Dodge Passive in Hunter tree not working.
- Unique and Runeword Base Stat stat range has been corrected. Runeword Base Stat range is equivalent to Legendary (60-100%) and Uniques are equivalent to Mythic. Note that these changes don't apply to non-Base Stats. Base Stats are the gear defense/damage.
- Runeword non-Base Stat ranges have been fixed and no longer always roll between 70-85%.
- Mobs spawning with incorrect number of affixes has been fixed.
- Some Profession Station fixes.
- Fixed Quivers not working in Curio.
- Hopefully fixed Farseer spawns.
- Fixed Elemental Burst to be correctly tagged as Fire.
- Removed uncraftable Conductor block from MIMI quest.
- Fixed an 'issue' where stats that gave + Skills and had a range would only give the upper stat range if you had a 100% roll.
- Currencies not breaking gear when they were supposed to has been fixed.
- Fixed a typo that said Ticks instead of Seconds for Charge Regen...
- Fixed Final Stand Ascendancy only affecting Physical Basic Attacks.
- Fixed a typo with Profane Explosion Proc stat on Cursed Enemies - it didn't mention that the enemy needed to be cursed.
- Fixed an issue where Flame Strike was mistakenly applying Scorched regardless of Stance.
- Fixed sources of Lightning and Cold DOT Damage on the Talent Tree.
- Fixed a bug that caused Boss mobs to explode with way too much loot.
- Lag with homing projectiles should be fixed.
- Fixed an issue where only one player could apply an ailment to a mob.
- Blocking sound is fixed.
- Fixed Infusion rerolling on upgrade.
- Fixed Infusion rerolling rarity.
- Fixed an issue where people installing the modpack were getting JSON errors due to Java 21.
- Fixed Profession recipes using same rarity Stone.
- Hopefully fixed Elemental Purity penalty to Physical Damage not applying.
- Some basic attack cooldown issues should be fixed.
- Damage conversion has been fixed.

### Mod Updates
- Updated Chat Heads, Mine and Slash, Sophisticated Mods, Supplementaries, Friends & Foes, PuzzlesLib, DeeperDarker, Doggy Talents Next, Skin Layers 3D, Aquaculture, Connectivity, Formations, Framework, FTB Library, Lightman's Currency, Lithostitched, Moonlight API, NBTac, Supp Squared, Bountiful, Sounds, U Team Core.
- Updated Forge.
- Added Minecraft Comes Alive (MCA)! You can now interact with Villagers - even manage them!
- Added Twilight Forest and Twilight Forest Bosses Resurrection!
- Added Ice and Fire - these mobs have been populated in different dimensions.
- Added Mowzies Mobs - these mobs have been populated in different dimensions.
- Added Dungeons Enhanced - new dungeons.
- Added Oh The Biomes We've Gone - rehauled biomes.
- Added Project: Vibrant Journeys - more life to terrain generation.
- Added The Outer End - overhauled End.
- Added FramedBlocks - replaces Domum.
- Added Display Delight - place foods down as decoration!
- Added Botania - new tech replacement!
- Added Simple Backups.
- Added new Resource Pack: Redcap's Currency Retexture!
- Removed MineColonies.
- Removed Combat Music - buggy.
- Removed Domum Ornamentum.
- Removed Nature's Aura.
- Removed Create.
- Removed Air Hop - replaced by Botania trinkets.

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

## [0.6.2] - 2024-06-24

### Updates
- When Dungeons Arise dungeons have had their Enchantment drops reworked. Big thanks to DingoDango for this!
- Oxygelium can now be dropped from Tortured Souls. Quest description has been updated to reflect this change.
- Fishing message spam has been removed.
- Rune reroll chance has increased... a lot. Like you would never guess how much.
- Tier 4 Runes (incl. Dimension Runes) have had their stat ranges changed. It is not longer 75-125%, it's 100-125%.
- Oru Rune Weapon Damage has been nerfed from 8-12% to 8-10%.
- Damage Feature now shows more information.
- You can no longer use Prophecy Altars if enemies are too close.
- Mobs in maps still persist, but will now cap at about 30 mobs/map. If you run through a map without killing mobs first then they'll start despawning after 30.
- Invoker Health has been reduced by 50%. It was increased since it was an Uber boss, but was then removed from the Uber boss pool and forgotten.
- Master Bag now no longer requires a Sophisticated Backpack to craft. It instead takes a Supplementaries Sack.
- Ailments have been slightly reworked.
- Burn has changed from 75% damage over 3 seconds to 100% damage over 3s.
- Bleed has changed from 75% damage over 5 seconds to 120% damage over 5s. This may be reworked in the future but for now it gets buffed.
- Poison has changed from 100% damage over 10 seconds to 150% damage over 10s.
- Freeze/Chill has changed from 100% of damage accumulated to 85% damage accumulated. It still applies a slow.
- Electrify has changed from 125% of damage accumulated to 100% damage accumulated.
- Shatter and Shock Proc Support Gems proc chance stat is now 20-60% instead of 25-75%.
- Ailments can no longer crit (again).
- Ailment Duration stats have been changed so the math actually adds up and you can get extra ticks of the ailment. Eg. before Bleed Duration on the Talent Tree added up to a measly 8% which wasn't enough to trigger another tick of Bleed.
- Added some new nodes on the tree with Burn and Bleed Duration.
- Added some new Poison nodes between the Bow and Dagger starting positions.
- Steady Hand no longer gives -100% Critical Hit. It still reduces Critical Damage by 100%.
- Raider Double Damage chance is now 25% instead of 40%. I now know how it actually works.
- Chieftain's Swift Burn now grants -20% Totem Duration instead of -50%.
- Wandering Bard Gamechanger now gives -35% Song Duration instead of -50%.
- Bloody Dance Gamechanger now gives -40% Bleed Duration instead of -50%.
- Some egregious instances of level VIII or X Vanilla enchantment sources have been culled.
- Undergarden chests are no longer covered by the spawner, making them accessible without the need to destroy the spawner.
- Spears should now be throwable and properly take stats into account (unconfirmed).
- Reverted change to Create Washing. Iron and Gold Nugget rates are back to normal.
- Strength now gives 5 flat Health per point instead of 2.
- Strength now gives 0.3% Crit Damage per point instead of 0.25%. The tooltip was misleading because it was rounding the 0.25% to 0.2%.
- Mobs now have more innate Armor, Dodge, Elemental Resist, and Accuracy.
- Mob and Map Dodge and Armor affixes have been upped slightly.
- The goal of the below changes is to offset flat sources crit chance. Right now, there is an over-reliance on getting crit from Dex and Jewels. Ideally, the power of crit should remain relatively the same as it was in the previous patch, but realistically, it will likely drop if most of your crit comes from Jewels/Dex.
- Player base crit has increased from 4% to 5%.
- Jewel affix with Critical Hit has been changed from flat to percent. Assuming base crit only (5%), the crit you get should be the same. Obviously if this was your main source of flat crit you will lose some.
- Crafted Unique Jewel affix with Critical Hit has been changed from percent to flat. Assuming base crit only (5%), the crit you get should be more, AND it's flat.
- Dexterity Critical Hit has been changed from 0.1% flat to 2% Increased Crit Chance. Assuming base crit only (5%), the crit per point is more. Then, with each additional flat crit this gets compounded.
- Slightly reduced sources of Dexterity on Uniques.
- Toq Rune flat Crit Chance stat has increased substantially. It no longer goes from 1-1.25%, it's now 1.5-2.5%. With the changes to other sources of percent this is in practice more than just double.
- Crit Chance Support Gem flat crit increased from 2% to 2.5%. With the above changes, I wanted to make sure lower leveled players still had an easily accessible source of flat crit if they wanted to go crit. This change should help them a bit.
- Power Charges now give 25% increased Critical Hit instead of 30% per stack.
- Affixes Of Brutality and Of Devastation have had their Critical Damage changed from 4-30% to 4-25%.
- Summon Skeletal Army's duration has increased from 12s to 20s.

### Fixes
- Fixed Bountiful rewards not including some custom rewards. Thanks Arona74 for spotting this.
- Fixed localization.
- Rerolling a Rune thats already maxed out will now fail.
- Food Stat and Augment Effect stat have been fixed.
- Orb of Imperfection and Orb of Chaos can no longer be used on Corrupted items.
- Fixed overlapping default keybind.
- Fixed a bug where a connection between the middle and outer ring was missing between the Bow and Dagger start on the Talent Tree.
- Fixed quest completion not registering.
- Fixed Raider's Double Attack Chance proccing 100% of the time.
- Fixed Runewords not being made.
- Fixed weapons not able to hit multiple targets when basic attacking.
- Fixed Sweeping Edge enchantment not being applicable. It also now increases the number of mobs you can hit or something with basic attacks.
- Null stat errors should be resolved, which should also resolve server disconnect loops.
- Fixed incorrect localization for Physical Skill Damage.

### Official Server Changes
- Create Washing no longer gives you Iron or Gold Nuggets.

### Mod Updates
- Updated Mine and Slash, Amendments, Balm, Collective, Crabber's Delight, CraftPresence, Create Additions, Embeddium, Explorify, FLAN, GeckoLib, Hit Inidication, Jade, Macaw's Lights, MineColonies, ModernFix, Moonlight API, Shoulder Surfing, Supplementaries, Structurize.
- Added Extreme Sound Muffler. By default the key is unbound, so if you want to use it just bind it.
- Temporarily removed Waystones and Lightman compat until it's fixed.

## [0.6.1c] - 2024-06-19

### Updates
- Map and mob Dodge affixes now give mobs half as much Spell Dodge.
- Mobs now have some innate Spell Dodge. These changes were made so players were made aware that yes, mobs can dodge Spells before they hit maps.
- Increased Confident Ruin Support Gem's Crit Damage multi slightly.
- Decreased Added Fire Damage Support Gem's Phys as Fire slightly.
- Favor no longer passively accumulates above 2500.

### Fixes
- Fixed Professions.
- Fixed incorrect Increased/More localization.
- Ailments can crit again.

### Mod Updates
- Updated Mine and Slash, FTB Quest Optimizer, Kiwi.

## [0.6.1b] - 2024-06-18

### Updates
- Homing Skills now only home if there is line of sight between the projectile and the mob.
- Quadrupled the time limit for the Invoker wave in the Gateway.
- Reverted Mending changes.
- Reduced cost of warping to 1 Copper/100 blocks, capped at 1 Iron.

### Mod Updates
- Updated Mine and Slash.

## [0.6.1] - 2024-06-18

### Updates
- Base Weapon Damage values have increased by 33%. This should translate to a near 33% increase in overall damage.
- Spears have received a 25% base Weapon Damage increase, on top of the above change.
- Strength now provides 0.25% Crit Damage instead of 0.5% per point.
- Strength now provides a flat 2 Health per point. With a moderate investment of 100 Strength, this results in 200 more flat health.
- Strength now provides 1% Summon Health instead of 0.5% Summon Health per point.
- Player Health now scales with a base of 80 instead of 50 (scaled) + 30 (flat, non-scaling). By level 100 this results in about 300-400 more flat health.
- Health Talents now give 3% instead of 2% Health. The big ones are now 8-10% instead of 5%.
- Intelligence now provides 0.5% Magic Shield instead of 1% per point. Since it is percent, the impact should be relatively minimal, maybe a 5-10% total drop?
- Critical Hit small nodes now give 12% Critical Hit instead of 15%.
- Critical Damage big nodes now give 8% Critical Damage instead of 10%.
- New Gamechanger Talent: Elemental Overload. On Crit, gain an 8s buff that increases Elemental Damage by 30% MORE. The Talent also gives you -100% REDUCED Critical Damage (no Critical Damage). You will find this new node where Defender used to be, between the Staff and the Hammer.
- Defender has been moved down to the Axe start.
- True Hit now gives -40% Non-Crit Damage instead of -25%.
- Ghast now gives 3 Dodge per 10 Magic Shield instead of 5.
- Stare of Abyss now gives 25% Chaos Resist instead of 75%.	
- Collateral now gives +30% MORE Weapon Skill Damage and -25% AOE instead of +20% and -50%.
- Steady Hand now gives +30% MORE Non-crit Damage instead of 25%.
- Mantra no longer gives a penalty to Crit Chance.
- Assassin's Cruel Poisoner now also gives 10% Chaos Penetration.
- Battlemage's Balance now gives 10 Mana per 10 Health instead of 5 per 10.
- Elementalist's Fire/Cold/Lightning nodes at the top no longer give +25% MORE Ailment Damage. However, they now give +15% MORE Elemental Damage instead of 10%.
- Gladiator's Violent Outbursts now gives 15% MORE Physical Damage and 20% AOE instead of 12% and 15%.
- Guardian's Bulward of Flesh now gives 10 Health per 10 Intelligence instead of 5 per 10.
- Hunter's Multiple Projectiles now gives -30% LESS Projectile Damage instead of -40%.
- Juggernaut's Unyielding now gives 8% AOE per Endurance Charge instead of 4%.
- Juggernaut's Unbreaking now gives 15% MORE Health instead of 10%.
- Raider's Quickness now gives a 40% chance for Double Attack.
- Trickster's Trickery now gives 1 Dodge per 10 Magic Shield instead of 3 per 10, but now also gives 14% Magic Shield and 14% Dodge.
- Removed Magic Find Support Gem from drop tables as it doesn't actually work on skills.
- Added Fire Damage Support Gem now also gives a bit of flat fire damage.
- Added Cold Damage Support Gem now also gives a bit of freeze chance.
- Crit Damage Support now gives 15-45% Crit Damage instead of 20-60%.
- Confident Ruin Support now gives 8-24% MORE Crit Damage instead of 15-45%.
- Mana Saver Support Gem now gives 5-15% MORE Non-crit Damage instead of 4-12%.
- Greater Mana Saver Support Gem now gives 6-18% MORE Non-crit Damage.
- You cannot have more than 1 Conservation Support Gem on a Skill.
- Mana Saver Support Gems have been renamed to Conservation Support Gem.
- Multiple Projectiles Support Gems now give a penalty to healing as well.
- Guardian Augment now gives twice as much Health and Magic Shield.
- Magic Shield Augment now no longer gives PERCENT Magic Shield and now gives 25% less flat Magic Shield.
- Armor Augment now gives only MORE Armor, but the value has doubled.
- Dodge Augment now gives half as much flat Dodge.
- Dodge Augment MORE multiplier has been changed to PERCENT, and has increased substantially.
- Runes now roll within a small range. The new range is +/-25% of whatever it was previously.
- Some Prophecy Uniques have had some stats moved around a bit. Additionally, the weightings on them have decreased which shouldn't really matter except for the random Unique generator in Act V.
- Dodge Map affix now also gives mobs Spell Dodge in addition to Dodge, similar to the mob affix.
- Frozen Orb and Cyclone are no longer considered projectiles.
- Galvanic Blade now allows users to proc Discharge on non-crits as well, at a lower chance.
- Blood, Ignite, and Profane Explosion cooldowns have been reduced from 1s to 0.25s.
- Of Brutality suffix can no longer roll on Necklaces.
- Magic Find stat has been tripled to compensate for previous mechanical changes to Magic Find.
- Ailments (also known as DoTs) can no longer crit. They already scale off of the initial hit's damage.
- A new toggle for Summon behaviour has been added to the Hub Feature tab. They can now act aggressively (old function) or defensively (new).
- Reduced stat requirements of gear by 20%.
- Added a new Lost Page quest highlighting the above.
- Stat screen now has a search bar.
- Disabled Dummy DPS meter since it's inaccurate anyway. Plus we have the M&S damage feature now.
- Regen Hunger cost doubled.
- Reduced chance of getting nuggets from Create washing.
- Updated Farming quest in Profession Chapter.
- Waystones now cost some coins to use. It's about 5 copper per 100 blocks.
- Mending enchantment has been reworked. You can now repair equipment with Mending in the Crafting Table using other pieces of gear (similar to Anvil), without paying experience.
- Increasde drop rate of Uniques by 3x, they are now as frequent as Mythics. But a reminder that Uniques are unaffected by Magic Find.

### Fixes
- Fixed Backstabbing enchantment unable to apply to Daggers.
- Fixed Sweeping Edge being disabled.
- Fixed Uber Fragments only dropping as level 50.
- Fixed Shatter and Shock doubling up on player stats. So if you got 30x damage, it was more like 30x and then 30x again.
- Some Map showing command blocks has been fixed.
- Players no longer benefit in stats from holding a weapon they don't have requirements for.
- Tooltip fixes.
- Disabled Create Toolbox due to dupe exploit.
- Removed Warden and Invoker from the Uber Boss pool.
- Fixed an issue where some Skills were incorrectly affected by Dodge.
- Disabled Warp Stone being useable by FTB Ultimine.
- Fixed Lootr textures.
- Fixed incorrect Ascendancy information in Quests and UI.
- Fixed missing enchantments for certain weapon types.
- Favor gain should be mostly fixed. May still see issues with chests.
- Map mobs should now be persistent.
- Summons now get attacked in maps. They were mistakenly considered allies to mobs.
- Fixed a bunch of Farming foods not giving experience. They should all give experience now. Thanks very much to CreatorBurden and the rest of the official server for the help!
- Fixed Salvaging not giving any Essences.
- Salvaging maps should now give Stone appropriately.

### Mod Updates
- Updated AmbientSounds, CorgiLib, Embeddium++, EMI, Entity Culling, Explorify, FLAN, Inventory HUD, JEI, Kiwi, Lightman's Currency, Macaw's Doors, Mine and Slash, MineColonies, Moonlight, NoFog, NotEnoughAnimations, Shoulder Surfing, Skin Layers 3D.
- Added Aquaculture's Delight.
- Added Undergarden's Delight.
- Added Waystones and Lightman's Compat mod.

## [0.6.0b] - 2024-06-14

### Updates
- Mine and Slash Skill keybind style (hold or toggle) is now a toggleable option. The default is the original toggle with 4 slots. If you want to hold, you can rebind Skill slots 5-8 and set the client config to be hold rather than toggle.
- Halved gear weapon damage and defense scaling for all Uniques and Runewords due to the below fix. Overall, Uniques and Runewords should see a huge buff (of about 30%). For example, a level 80 staff with base of 50 damage would have rolled about 100-150% weapon damage, ending up at around 100-150 weapon damage. A level 80 Mythic would have been at about 92-100 base weapon damage alone, without considering the bonuses from the stats... Now the base weapon damage of Uniques and Runewords will be in line with Mythics.
- Ascendant Ascendancy Augment buffs have been nerfed.
- Elemental Resist requirement for maps is not as stringent.
- On Hit and On Kill perks in the Talent Tree now scale to level.
- You can now get Impaling enchant on all weapons.
- At the end of the Prologue chapter, you can now choose another weapon (in case you change your mind or want to dual-wield).
- Removed Mutant Enderman from Otherwordly Map mob pool.
- Grapple cooldown is now 5s instead of 6s.

### Fixes
- Fixed Lightman's Terminal having 2 shops.
- Fixed Wallet missing from the menu wheel.
- Fixed some gems providing no stats.
- Fixed missing enchantment description localization.
- Fixed existing enchantment descriptions having a weird symbol.
- Fixed Splinter not working properly.
- Fixed Map Affix providing negative resists not requiring resists.
- Fixed a huge bug where Uniques and Runewords base weapon damage and defense stats were at the lowest base possible...
- Talent Tree search bar is fixed.
- Fixed Deerstalker Boots and Trolltimber Spire Shield not working.
- Archmage Support now increases Energy costs too. No more free Mana scaling.
- Fixed MIMI quest.
- Fixed pigs spawning in Fire maps.
- Fixed Feature page showing opposite.
- Fixed Tourmaline and Emerald gems.
- Fixed Leech Cap having a cap of 10%. Leech Cap stat now actually does something.
- Default keybinds should be fixed.
- Fixed some UI and localization errors.

### Mod Updates
- Updated Bookshelf, Gateways, ImmediatelyFast, Lightman's Currency, Mine and Slash, Moonlight.

## [0.6.0] - 2024-06-13

### Reminders
- TALENT TREE WILL RESET WITH 0.6.0!
- Back up your Xaero's folders and your options.txt file just in case!

### Updates
- New Transmog mod has been added which lets you change the appearance of an item into another item. This will replace Cosmetic Armor by 0.7.0. You can craft the Transmogrification Table to perform this new action.
- New Quest in Act I covering Transmogrification.
- Modpack stability and performance improvements.
- Increased EXP gain in Acts III, IV, and V. Players were reaching Act V at too low of a level. This should help alleviate.
- Doubled EXP rewards from Campaign Bosses.
- Death EXP penalty upped from 5% to 10%. This is partially due to the fixed double death bug.
- Megatorch and Feral Flare Lantern recipes are slightly more expensive now and require some Mine and Slash components.
- Increased mob health scaling in higher Map tiers.
- Increased mob stat scaling.
- Huge mob rework: lots of mobs in dimensions now have affinities for elements. They will do more damage of a particular element when it makes sense. Eg. Blazes now deal 50% Fire Damage, 50% Physical Damage.
- Added a Lost Page for the above change in Act II.
- All mini-boss health has doubled and damage increased by 50%.
- All boss (except Ender Dragon) health has quadrupled and damage increased by 50%.
- Reduced Crystal Zombie spawn weight by 17%.
- Increased Hermit Abysswalker spawn weight by 150%.
- Increased Anglerfish spawn weight by 50%, increased spawn amount by 1. Might help with Mother of the Maze spawn rates.
- Lowered Chocobo Health but gave them innate Elemental Resist and bonuses to Armor.
- Hermit Abysswalker, Warped Mosco, Forgotten Guardian, and the Void Worm now have innate stats. The Quests have been updated to reflect this.
- Prologue now mentions Gear Soul Crafting.
- The Witch Quest in Act I now gives a Support Gem as a quest reward...
- Humble Beginnings quest now has more information.
- Act III Civilization from the Past now requires Forgotten mob kills (new mob).
- Act III Slipper Swimmer description has been updated to be more accurate.
- Act IV mobs now have a minimum level of 35 that they spawn at.
- Wildfire quest now tells you where you can find them.
- Updated Favor Lost Page due to new Favor changes.
- Added a few more Lost Page quests to help with newer players.
- Added new recipes to convert the Mine and Slash rarity materials up and down (Lesser <-> Medium <-> Greater).
- Increased spawn rate of Dungeons.
- New Pirate Ships can be found on the Ocean!
- Some new dungeon structures can be found...
- Increased frequency of Towers which means more naturally occurring Waystones.
- Also increased frequency of naturally spawning Waystones not in Towers.
- Cuisine Delight is now compatible with more modded foods.
- Added a few more spawnable Villages from CTOV.
- Main Menu elements are a bit more spaced out. The changlog box is now larger.
- Fixed up some quest images.
- Gateways now must be at least 100 blocks apart from each other.
- Colonists now work in the rain.
- Entire colonies are now loaded as long as one chunk is loaded. Does not apply to Official Server.
- Certain mobs can now leap, throw Ender Pearls (once), and will actively avoid explosions.
- Cooking for Blockheads Countertops are twice as large now (inventory).
- Updated first join message to mention the menu wheel.
- Updated a bunch of enchantment descriptions.
- Chorus Fruit Pie recipe now requires some Mine and Slash Profession materials.
- Removed Light Staff recipe.
- Disenchanter now requires Tier 3 Mining Ore and the Imbuing Table to craft.
- Skeleton Armor now requires Mine and Slash Profession materials to craft.
- Lightman's Terminal now requies a Rare Stone to craft.
- Witches now have a chance to drop Blaze Powder.
- Certain previously disabled enchantments have been enabled again.
- Updated default Skill keybinds. No longer need to use CAPS LOCK.
- Disabled Poisoned Blade crafting recipe since it's kinda broken.
- Re-enabled Straddler spawns.
- Enderman and Warden coin drops have been scaled back.

### Mine and Slash General Updates
- New Mechanic: Ascendancies! You can now specialize your build further with Ascendancies. There are currently 16 Ascendancies. You get 1 Ascendancy point every 15 levels, capping at 7 points. You get an additional point at level 15. Ascendancies are NOT locked to certain Classes.
- New Map Mechanic: Prophecy! You can find altars in maps to apply curses to yourself. The more curses you have, the more Prophecy-specific currency you can gain from killing mobs. Use that currency to pick from deterministic rewards!
- New End-game Mechanic: Uber Bosses! Mobs in maps now have a chance to drop Uber Fragments, which can be combined into Uber Arena Maps. Enter the Arena Map, find the Uber Portal, and slay the Uber Boss for some powerful loot! Uber Bosses have a chance of dropping the coveted Abyss Jewels which can only be equipped in Jewel Slots if you're wearing the correct Augment. These Abyss Jewels grant very powerful effects!
- Maps now have a lives system. Higher rarity maps have less lives. When you run out of lives in a map, you can no longer enter it.
- You can no longer enter maps that are 3 levels higher than you.
- Maps now have some baseline Elemental Resistance requirement to enter, based on their difficult and rarity. Maps that have elemental mob damage affixes require higher resist. The required value isn't too high, this is mostly to help with players novice to ARPGs who are consistently getting one-shot.
- Maps now have names.
- Map Affixes now scale based on map rarity.
- Maps now contain modded mobs.
- Increased Map drop rate in non-maps from 0.35 to 0.5.
- Legendary and Mythic maps can drop in Epic maps now instead of one rarity lower. Epic maps can drop in common maps.
- Gems have been reworked! The level scaling is now linear and goes from 1-60 rather than 1-95. Additionally. the drop chance for higher tier Gems has increased. They were basically impossible to drop before. Gems have also gone through major stat changes. In general, stats from Gems is lower than Runes at the lowest tier, but by mid-tier they're on par, and by high-tier they're better. They also have some different stats not found on Runes.
- New Stat Type: Chaos/Corrupted Stats! Players from Craft to Exile might be familiar with this. When using an Orb of Chaos, there is a 75% chance to give the gear a powerful Chaos stat. However, there is a 25% chance that the gear will turn into a lump of coal. Thanks Len for your help!
- Non-Magic Skills now take into account the Caster's weapon type. So the Skill's damage can benefit from stats like "Sword Damage" if the Caster is holding a sword.
- New currency which rerolls a random affix.
- Currency Potential has been reworked. Items start with Potential which gets deducted from with each currency. At 0 potential, you can no longer apply currencies.
- Compatibility between Mine and Slash stats and non-Mine and Slash stats has been added. For example, the vanilla Armor stat now provides a small amount of percent Mine and Slash Armor. Compatibility has also been added for Armor Toughness (same as Armor), Attack Damage from weapons (adds a small amount of Total Damage), Vanilla Health (adds a small amount of percent Magic Shield), and Luck (adds a small amount of Magic Find).
- Compatibility between Mine and Slash stats and Minecraft Enchantments has been added. For example, Sharpness now increases Physical Damge by 4% per level. Any compat added to Enchantments will be reflected in the descriptions.
- Starting flat Critical Hit is now 4% instead of 5%.
- Strength now provides 0.5 Health Regen per point instead of 0.25.
- You can now only have 3 separate characters, down from 7.
- Rerolling Rune stats can never result in a lower stat than before.
- All source values of DoT/Ailment Damage in the Talent Tree and Passive Skills has doubled.
- Penetrating Mob Affix Armor Penetration has been reduced.
- There are now Power, Frenzy, and Endurance Charges. These can be obtained various ways, but mostly from Ascendancies.
- Added 8 new Support Gems: Aggressive Minions (Lv. 20), Defensive Minions (Lv. 20), Power Charge On Crit (Lv. 20), Archmage (Lv. 30), a new Chaos Damage Support Gem (Lv. 30), and 3 new Elemental Damage Support Gems (Lv. 5).
- The above Support Gems have been added to their respective shops.
- The following Support Gems have been buffed by about 35%: Brutality, DoT Damage, Ailment Damage, Melee Damage, Ranged Damage.
- Projectile Support gems have been nerfed. Their damage penalties have increased. You will still deal more damage if all or most of the projectiles hit. This extra damage is proportionate to the resource multiplier (if all projectiles from GMP hit, you will do more than if all LMP projectiles hit).
- Increase AOE Support Gem now gives less AOE.
- Greater Multiple Projectiles Barrage fires one less projectile.
- Plate and Leather Chest pieces have had their values adjusted to be more in line with Cloth.
- Profession EXP now ranges from 50-100% if you are lower level than the resource, rather than 0-100%.
- Players under level 10 now have a boost to Item Find.
- Magic Find has been reworked slightly. Overall it's less effective.
- Soul Modifiers can now be applied to non-crafted souls.
- Doubled MnS party radius.
- Favor Rework: instead of capping out at 250 and getting a 5% bonus, Favor now goes up to 100 000 and can give you up to a 25% bonus. Item rarity drops are also unaffected by this, so you can still get Mythic items at 0 Favor.
- Favor gain from chests reduced to 5, from 10.
- Favor loss on death increased to 500 from 250.
- New Effect Duration overlay.
- Magic Shield users can get knocked back on hit.
- Major UI improvements.
- Radius is now shown in Skill tooltips.
- Items salvaged through auto-salvaging will now go into the Master Bag.
- Low Energy penalty is no longer a thing.
- Increased Rune drop rate from 0.15 to 0.25.
- Oru Rune PERCENT weapon damage has been reduced from 24% to 10%.
- Refined Taste has been reworked. It now gives 25% Leech Effect instead of 50%. But it now also gives +40% Health Leech Cap instead of 2% and -90% Reduced Health Regen instead of -75%. It no longer affects Magic Shield Leech Cap and Mana Regen.
- Golemancer Gamechanger now gives +35% Golem Spell Chance instead of 25%.
- Acrobat Gamechanger now gives -20% Dodge MULTI, but instead of giving flat Spell Dodge, it now gives a 50% chance to take half damage.
- Curse Master Gamechanger now gives 30% MORE Curse Damage instead of 20%.
- Vital Point Gamechanger is now a MORE rather than FLAT increase.
- Many instances of Reduced Damage Received have been changed to Damage Reduction.
- Lowered Profession to Combat Rested XP rate.

### Mine and Slash Runeword/Unique Updates
- All Runewords have had their PERCENT Gear Damage/Defense bonus increased by about 20%+. Some weaker Runewords had a larger increase than others.
- Added 4 new Runewords: Patience (DoT), Concentrate (AOE), Supersonic (Move), Selflessness (Song). Thanks Len for your help!
- Infinity Runeword Lightning Penetration max has been reduced from 80% to 75%.
- Infinity Runeword can no longer be put on Daggers.
- Leaf Runeword can now give +1-2 Fire Skills instead of +1.
- Plague Runeword Bleed and Poison Damage bonuses has tripled.
- Steel Runeword Bleed Damage bonus has tripled.
- All Uniques have had their PERCENT Gear Damage/Defense bonus increased by about 33%+. Some weaker Uniques had a larger increase than others.
- Added 5 new Prophecy Uniques: Chained Oak, Curse of Numbers, Curse of Tongues, The Beast, Blood Curse.
- Air Disaster Ring now also gives PERCENT Mana Regeneration.
- Arch Gamble Staff now gives MORE instead of FLAT DoT Damage. The value has been lowered slightly. It now also gives a small amount of Elemental Resist.
- Autumn Harvest Ring now gives twice as much bonus to Food Stats.
- Bones of Ullr Boots now give 12% Move Speed.
- Chaber Cairn Hammer now gives PERCENT Health.
- Chin Sol Bow now gives 25% Physical to Fire instead of 10-15%.
- Curse Effect Ring now gives much more Increased Effect of Curses.
- Deerstalker Boots now gives 20% Trap CDR instead of 10% and now gives 8% Move Speed.
- Disfavour Axe Attack Speed minimum has increased from 16% to 24%. The bonus to Bleed Damage has also tripled.
- Doombolt Crossbow minimum values have increased. The bonus to DoT Damage is now MORE instead of FLAT.
- Doomslinger Crossbow minimum Health and Draw Speed values have increased.
- Ele Aegis Shield now gives Elemental Resist instead of Augmentation Effect.
- Ele Gamble Ring mininum values have increased.
- Fire Step Boots now give 10% Move Speed.
- Frostbreath Hammer Freeze Damage has increased from 10-20% to 60-80%.
- Futility of Suffering Necklace penalty to Mana and Energy Regen has been reduced from -25% to -10%. It now also gives +1 All Skills.
- Genji Domaru Chest now gives more Health and +2 Melee Skills instead of +1.
- Genji Kabuto Helmet minimum value for Elemental Resist has increased.
- Genji Sune Ate Boots now gives more Move Speed.
- Genji Tsutsu-Hakama Pants now gives more Attack Speed.
- Ghast Necklace now gives more Magic Damage, Strength, and Dexterity.
- Goblin Toe Boots minimum values have increased.
- Golemancer Chest minimum Summon and Golem Skill Chance values have increased.
- Haste Price Boots now gives Move Speed, and more PERCENT Armor. The Resource Cost penalty is also now 10% instead of 25%.
- Heavenly Tear Necklace now gives +1 Fire Skills, and bonuses to Fire Damage instead of Lightning Damage.
- Ice Stomper Boots now gives 5% Move Speed.
- Ichorstring Crossbow now always gives 20% Chaos Penetration instead of 10-20%. The bonus to Poison Damage has doubled.
- Insight Spear now gives 60-80% Mana Regen instead of 20-30%.
- Kuko Shakaku Bow minimum values have increased.
- Last Tracker Set now gives more Physical Weapon Damage per Energy.
- Lidless Wall Tome now gives more Cast Speed.
- Madness Pursuit Boots now gives Move Speed, and the penalties to resists have been reduceed drastically.
- Mana Dominion Helmet now correctly gives Gear Defense. The penalties to Energy and Health have been reduced, but the Mana per Intelligence and PERCENT Mana values have also been lowered slightly.
- Manald Heal Ring Manasteal has increased from 2-4% to 4-6%.
- Mara's Kaleidoscope Necklace now can give +1-2 All Skills instead of just +1. The minimum value for Elemental Resist has increased.
- Marrowwalk Boots now give a substantial FLAT boost to Health.
- Master Torture Necklace now gives MORE Damage to Cursed instead of FLAT. The range is 30-35 instead of 25-50. It no longer gives Frost Resist.
- Mjolner Hammer now gives +1 Lightning Skills, and the bonus damage to Chaining Skills has increased.
- New Dawn Flame minimum values have increased.
- Nokozan Relic Necklace now gives +1 Fire Skills.
- Pack Leader Helmet's bonus to Beast Skill Damage has increased.
- Saracen's Chance Necklace now gives +1 Ranged Skills.
- Sculpted Perfection now gives +1 Totem Skills.
- Silverbranch Bow now gives +1-2 Ranged Skills.
- Spark Aura Ring now also increases Burn Damage. The bonus to Burn Chance has also increased.
- Sparkfinder Boots now gives 6-8% Move Speed.
- Spring Blossoms Ring now gives 35-40% Increased Healing instead of 15-20%.
- Steelclash Shield now also provides 4% Damage Reduction.
- Stone of Jordan Ring now also gives +10% Total Damage.
- The Jade Tan Do Dagger's Poison Damage bonus has doubled.
- The Written Word Tome now gives more Increased Healing than before.
- Voltaxic Rift is now a Tier 80 Unique.
- Waterwalk Boots now give +8% Health.
- Weight of Leadership now gives +30-50% Summon Damage instead of just +30%.

### Mine and Slash Skill Updates
- Base damage of Skills has been revamped. This is an effort to streamline the Skill base values, as they were all over the place. For example, for some reason Black Hole and Boomerang had the same base values. In general, Weapon Skills have a higher base damage value than Magic Skills.
- Weapon Scaling and Base damage PER LEVEL for Arrow Barrage, Poison Blast, Chilling Touch, Double Strike, Fire Ball, Ice Shard, Lightning Spear, Piercing Dagger Throw, Gong Strike, Boomerang, and Power Chord have doubled. This is to make leveling these "basic" Skills more rewarding, as they were generally untouched and stayed at level 1.
- Most Magic Skills have had their base damage values reduced.
- Most Weapon Skills have had their base damage values increased.
- Healing Skills now have high base values, but their Weapon Scaling has been reduced substantially.
- Curses, Totems, Traps, and other smaller Effects are now more streamlined as well, with overall damage going up.
- Health and Magic Shield scaling on Gong Strike, Whirlwind, and Blizzard have been reduced by 50%.
- Weapon Scaling on all Melee Skills has increased by 10%.
- Weapon Scaling on Whirlwind has been increased by about 15-20%.
- Flame Strike Fighter Stance's Fireball Weapon Scaling has increased by 100%.
- Weapon Scaling on Blizzard has been increased by about 15-20%.
- Armageddon Weapon Scaling has increased by about 10-15%.
- Steam Cloud's Heat stacks last an addition 1s (4s -> 5s).
- Chilling Field Weapon Scaling per level decreased by about 3.75%.
- Frozen Orb damage during travel is now appropriately half of the explosion damage, rather than 66%.
- Frost Nova sounds have been changed to better suit the Skill.
- Heart of Ice's regeneration buff now only lasts 3s instead of 5s. The cooldown has also increased from 20s to 30s.
- Golems now have innate chance to trigger their associated Skill.
- Removed implicit threat generation from Golems.
- Meteor and Ice Comet Weapon Scaling have increased.
- Totems (except Arrow Totem) are now cooldown-based. The cooldown is generally double the duration of the Totem.
- Rejuvenation Totem's cooldown has been reduced from 30s to 15s.
- Arrow Totem charge regen time is now 8s instead of 10s, and the cooldown is now 1s instead of 2s.
- Batter Fusilade fires one less projectile per cast.
- Cyclone damage has increased by 10%.
- Mana Scaling on Shaman's Lightning Skills have been reduced by 50%.
- Hunter and Rogue Arrow Skills (except Arrow Barrage) damage has increased by about 20-30%.
- Recoil Shot damage has increased by about 20% (a lot more if you consider the bug).
- Summon Wolf now has implicit 25% threat generation.
- Summon Zombie, Skeletal Army, and Wolf have received increases to Health by 50% and Damage by 20%.
- Explode Minion Weapon Scaling has been reduced by about 18%. The Health Scaling remains unchanged.
- Added a new Unsummon keybind (Default: Delete).
- Grand Cross damage and healing has been increased.

### Fixes
- Fixed written book crash by making it impossible to place them down.
- Fixed Flame and Venom Splash potion mistakenly having a Weapon Damage cap. Functionally nothing changes, just the tooltip is a bit easier to read.
- Fixed a bug where Recoil Shot was doing almost no damage.
- Fixed Pharaoh Scepter being a bow instead of a staff.
- Disabled Golden Wagyu from Doggy Talents.
- Disabled Wand of Symmetry due to dupe bug.
- Disabled Shattered Carver.
- Disabled Lightman's Speed Upgrades. Doesn't really do anything anyway.
- Disabled Lightman's Trader Interface.
- Fixed Advanced Chunk Loader recipe.
- Chunk Pregenerator race condition has been fixed.
- Elytra Wing craft bug has been fixed. You will no longer craft 2 wings into just 1...
- Dupe bug involving Create Wrench has been fixed.
- Fixed an issue in Shoulder Surfing mode where projectiles wouldn't fire at the crosshair.
- Fixed Lightman's Money Mending enchantment ticking too much.
- Fixed an issue where a bunch of new Affixes were not included properly.
- Fixed Prism Runeword not appearing correctly.
- Fixed Daw Rune giving Fire Damage instead of Chaos Damage.
- Fixed an issue with Heretic Gamechanger giving MORE instead of FLAT...
- Issue where some weapons had the incorrect Gear type should be resolved.
- Fixed double death XP loss issue.
- Stats have been refactored, which should have fixed a lot of priority issues.
- Harvest should be fixed.
- Fake Players should be able to do damage now (Minecolonists).
- Summons no longer get map mob stats.
- Allies can no longer hit Summons.
- Fixed Summoned Skeletons not firing properly.
- Making a larger Runeword on top of a smaller one now overwrites the smaller one. Shouldn't really be an issue in CTE2 though.
- Fixed Armor behaving the opposite way on Mobs.
- Profession stations have been fixed.
- Max Elemental Resist should now reflect properly in the UI.
- UI fixes.
- Fixed an issue where Explode Minions was not actually exploding them.
- Projectiles should register hits more consistently now.
- Fixed a bug where the Lightning Damage mob map affix gave Burn Chance.
- Tried to fix Hidden Depths dependencies.
- Middle-clicking in Curio menu doesn't delete items anymore.
- Fixed recipe conflict for cutting Pufferfish. It no longer results in Fugu Slices/Pufferfish Slices. Now it only results in Pufferfish Slices. Further cutting the Pufferfish Slices results in Fugu Slices.
- Fixed Healing Aria not working.
- Fixed leather armor incompatibility with shaders. Thanks ThatOneMothGuy.
- Mending Ostinato is now correctly tagged as a Song.
- Explode Minions is now correctly tagged as Chaos.
- Fixed instances of broken MORE stats not doing anything by changing them to FLAT stats.
- Main Menu changelog no longer gets cut and wraps properly.

### Official Server Changes
- Colonies now unload after 2 mins instead of 10 mins.
- Entity cramming is capped at 8 instead of 16 now.
- You can no longer destroy spawners on the server (technically was a bug).

### Mod Updates
- Updated over 160 mods (too many to list).
- Updated Complimentary Shaders.
- Added Anvil Never Too Expensive.
- Added When Dungeons Arise - Seven Seas.
- Added GeckoLib Oculus Compat.
- Added Loot Journal.
- Added Transmog - soon will sunset Cosmetic Armor.
- Removed Pick Up Notifier - replaced by Loot Journal.
- Removed Chat Colors - breaks FancyMenu.
- Removed Better Third Person - Shoulder Surfing update replaces.
- Removed WaystonesTeleportPets - causing more issues than solutions. Can use Supplementaries Cages instead.

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