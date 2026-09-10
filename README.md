# PatchNotes

# MapleStory Test World Update — Client 1.2.206 (Skill Adjustments)
**Posted:** September 10, 2026 (Thu) | Views: 17,705

Original: https://maplestory.nexon.com/testworld/news/all/198

---

## Table of Contents
1. Skill Adjustments
2. Combat Training Room (연무장)
3. HEXA Matrix Reset Scroll Support
4. Change Circulator Support
5. Sol Hecate

---

## 1. Skill Adjustments

### Common (All Classes)
- Buff icons now display remaining cooldown for Special Cores.
- Crowd-control (can't-act) status resistance duration reduced: 90s → 81s.
- On/off skill toggle state now persists after reconnecting.
- Fixed: some non-macroable skills gave no warning message when you tried to register them to a macro.
- The "can't register to macro" warning message text updated.
- Skill descriptions changed for: **Rune's Experience I**, **Overcoming Experience I** (renamed from "Overcoming Experience").
- **Luna Petit** pet skill: fixed activating in Meister Will's farming maps (beginner/intermediate/advanced/expert farms); fixed not deactivating properly when swapping world-shared pet slots.
- Fixed several skill effects not respecting the "effect transparency" option, including: Bishop's Angelic Touch–Atonement Brand, Xenon's Triangle Formation/Camouflage: Snipe (& VI), Photon Ray, Kinesis's Ultimate: Opening gravity field (& VI), Ren's Wolgeom-jeol'gi flame effects (& VI).
- **Empirical Knowledge**: chance to reveal weak point increased 31% → 76% (master level).
- **Flow of Battle**: now increases damage when enemies are nearby; stacking removed; damage bonus 16% → 15%.
- **No-Mind (Moa)**: stacking removed; damage buff now applies immediately on entering combat; duration 5s → 10s; damage formula changed.
- **Erda Nova**: attack range +~80%; now consumes HP + "Condensed Erda" (charges over time, max 2 stacks) instead of just HP.
- **Erda Shower** / **Erda Fountain**: now usable in Champion Raid: Dragon Isle.
- **Erda Permeation**: NEW skill — infiltrates enemy with Erda, slows them and applies a debuff that ignores collision.
- **Spider in Mirror** / **Crest of the Solar**: unusable in some non-hunting maps; gained permanent ATT/Magic Attack increase. Crest of the Solar: fixed Mechanic's flame-sigil damage vs. max 2 targets being wrongly applied at 1142% master level.
- **Sol Hecate** (common): fixed Noxy animation glitch in some Noxy motions. **Sol Hecate: Styx**: no longer applies Death Seed debuff; same damage regardless of class; cast effect added.
- **Blessing of the Maple Goddess**: removed the "extra stat increase + damage increase" during Maple Warrior; added a Final Damage increase instead; description/cast effect updated.
- **Empress Cygnus's Blessing** / **Transcendent Cygnus's Blessing**: removed damage-increase-during-duration; added Final Damage increase instead; description updated.
- **Transcendent Lynn's Origin**: removed ATT increase during duration; Final Damage increase 8%→10% (master level); description updated.
- **Grandis Goddess's Blessing**: many sub-effects reworked across Nova/Kaiser, Lef/Kaiser bonus-stat swap, Anima/Hoyoung — net effect: removed several conditional damage bonuses, added flat Final Damage increase, permanent Kaiser damage buff, and Hoyoung Cheon/Ji/In element Dosool Final Damage buff.
- **Otherworld Goddess's Blessing**: description changed; healing blessing no longer restores Demon Slayer's DF, now heals HP for all classes; Otherworld Void now triggers 5 times when not on cooldown during blessing.
- **Overload Mana**: cooldown 30s → 0.5s; fixed disabling at 0 MP; description updated.
- **Pirate's Flag**: removed party AP-invested-stat & mob-defense-ignore buffs; removed the deployable flag zone; icon/cast effect/sound updated. **Pirate's Flag VI**: same buff removals but gained a Critical Damage increase.
- **Guided Arrow** / **Return to Maple**: description updated.
- **Call Mastema VI**: Mastema's attacks can no longer hit bonus/reward monsters after boss fights.

### Explorer (Common)
- **Epic Adventure**: removed party damage buff for Explorer classes.

### Hero
- **Warrior Leap**: forward use now allowed mid-skill (except keydown skills); can double-jump forward then up.
- **Spirit Blade**: removed party ATT buff.
- **Rush**: cast motion removed; usable mid-skill (except keydown); icon/effect changed; attack function removed; knockback removed; travel distance changed; recast delay ~6% shorter; gained permanent ATT increase; can't be macroed.
- **Scarring Blade**: removed reduce-hit/ATT-down-on-bleed-target effect; added a damage buff during duration instead.
- **Raging Blow** (& Enhanced, & VI): hit effects/sounds updated.
- **Incising** (& VI): removed DoT application and bonus-damage-vs-DoT-target effects.
- **Advanced Final Attack**: gained permanent damage increase.
- **Enrage**: crit damage 20%→22%.
- **Sword Illusion**: combo-counter Final Damage buff now persists through death/revive; cast effect/sound updated; slash start delay ~50% shorter; full-slash delay ~24% shorter.
- **Furious Edge**: description changed; now hits 6 times via tracking; effect/icon/sound updated; max-spawn limit removed; hit count 3→4; damage 241%→142%.
- **Silent Cleave**: damage 6108%→5863%.
- **Rage Explosion**: slash damage 551%→771%; explosion damage 685%→959%.
- **Sol Hecate**: Sol Erda Fragment damage 343%→336%.

### Paladin
- **Warrior Leap**: same mobility change as Hero.
- **Divine Swing** / **Divine Charge** / **Divine Stigma** / **Blast** / **Advanced Holy Charge** / **Divine Convergence** / **Blast VI** / **Divine Judgment VI** / **Divine Charge VI** / **Divine Stigma VI**: converted from Holy Force-specific to normal skills, or their Holy Force–dependency removed.
- **Holy Charge**: effect now always active regardless of Holy Force skill use.
- **Final Attack**: bonus attack damage 80%→152%.
- **Rush**: same mobility rework as Hero's Rush.
- **Noble Command**: now passive; icon changed; removed nearby-enemy ATT/DEF/accuracy debuff; gained permanent mob-defense-ignore.
- **Combat Orders**: removed party skill-level buff.
- **Blast**: range +~30%.
- **Divine Judgment**: Holy Brand explosion damage 622%→946%.
- **Sanctuary**: damage 620%→889%.
- **Smite**: no longer triggers without a target in range.
- **Holy Unity**: adds a summoned "avatar of solidarity" mimicking your attacks; only Sacrosanctity now shares with bound party members; removed auto-share-on-attack and Final Damage buff.
- **Blessed Hammer**: removed auto-hammer-spawn during Holy Charge; hammer damage 1155%→2391%.
- **Grand Cross**: keydown damage 515%→804%; enlarged-cross damage 1040%→1248%.
- **Mighty Mjolnir**: hammer now prioritizes highest-HP target; first hit 535%→1130%; shockwave 605%→1278%.
- **Falling Justice**: added "Almighty Mode" (manual summon of judgment hammer); damage 1491%→2609%.
- **Sanctuary VI**: shock damage 237%→339%.
- **Final Attack VI**: 160%→336%.
- **Rising Justice**: 1060%→1929%.
- **Sacred Bastion**: first shockwave 787%→1637%; second 895%→1862%; judgment light 1200%→2304%.
- **Dominus Aurion**: shock damage 7647%→7188% (nerf); light judgment 7636%→7178% (nerf).
- **Divine Convergence**: hit 1: 1271%→1144%; hit 2: 1306%→1175%; hit 3: 414%→373% (all nerfs).
- **Sol Hecate**: 555%→1074%.

### Dark Knight
- **Warrior Leap** / **Rush**: same mobility rework.
- **Beholder's Buff / Reinforce**: removed Magic ATT increase; Beholder's Buff also loses party ATT/DEF/crit buffs; buff no longer clears on boss-waiting-map enter/exit.
- **Lord of Darkness**: crit damage 8%→9%.
- **Reincarnation**: Final Damage 30%→31%.
- **Darkness Aura**: sustained damage 590%→648%; dark slash 900%→987%.
- **Pierce Cyclone**: can jump during keydown; damage 583%→641%; finisher 1254%→1370%.
- **Beholder Impact**: cooldown 20s→60s; damage 260%→745%.
- **Beholder Shock VI**: 1344%→1547%; dark energy 860%→976%.
- **Dark Helidum**: piercing 2881%→2835%; strike 3874%→3850% (nerfs).
- **Darkness of Grace** variants: Devastation cooldown removed; shockwave 224%→311%; dark gust 425%→570%; Beholder Shock follow-up 789%→876%; Beholder's Punishment 477%→535%.

### Explorer Mage (Common)
- **Energy Bolt**: description changed.

### Arch Mage (Fire/Poison)
- **Elemental Drain**: on DoT application, now boosts Final Damage for a period.
- **Meditation**: removed party Magic ATT buff.
- **Flame Orb**: description changed.
- **Poison Breath**: DoT duration 10s→30s; DoT 60%→275%.
- **Elemental Reset**: description changed.
- **Poison Flare**: NEW skill — on poison hit, ignites a spontaneous toxic flame inside the enemy.
- **Explosion**: description changed.
- **Poison Mist**: DoT duration 6s→30s; description changed.
- **Teleport Mastery**: **removed**.
- **Elemental Adepting (Fire/Poison)** / **Master Magic** / **Fervent Drain**: description changed.
- **Poison Region**: DoT duration 10s→30s; DoT 204%→307%; unusable in non-hunting maps.
- **Mist Eruption**: removed DoT-count-based explosion damage scaling; explosion 125%→280%; removed 5+DoT-target cooldown-reduction; cooldown 10s→8s; boosted Poison Mist's DoT 300%→465%.
- **Ifrit**: DoT duration 2s→30s; DoT 140%→225%.
- **Flame Sweep**: DoT duration 5s→30s; DoT 240%→300%.
- **Meteor**: now applies DoT on hit; fixed can't-teleport-right-after-cast bug.
- **Flame Haze**: DoT 200%→318%; can now hit behind character.
- **Megiddo Flame**: DoT 700%→570% (nerf).
- **Fire Aura**: DoT 500%→600%.
- **DoT Punisher**: fire orbs now spawn extra based on Fervent Drain stacks; DoT 290%→1290%.
- **Poison Nova**: cloud explosion 1485%→1411% (nerf); DoT 660%→825%.
- **Fury of Ifrit**: now applies DoT on hit; respawns Ifrit at your location on recast; Ifrit respawns on revive if duration remained; range +~19%.
- **Poison Chain**: emitted poison now applies DoT; explosion 330%→825%; max poison-stack count 5→3; explosion-per-stack-growth 60%p→825%p; max explosions per target 9→3; final-stack gets new explosion effect.
- VI versions of the above (Flame Sweep VI, Flame Haze VI, Mist Eruption VI, Fire Aura VI, Ignite VI, Ifrit VI, Megiddo Flame VI, Meteor VI, Poison Region VI, Poison Flare VI) received matching/parallel numeric and DoT-duration changes.
- **Infernal Venom**: now applies DoT on hit.
- **Torrential Flame**: rain 2735%→2644%; explosion 3256%→3148% (nerfs).
- **Infernal Wave**: wave 764%→744% (nerf); fusion explosion 305%→316%; fixed missing hit-limit tooltip.

### Arch Mage (Ice/Lightning)
- **Meditation**: removed party Magic ATT buff.
- **Teleport Mastery**: **removed**; several "Teleport Mastery-X" sub-skills renamed to reference Blizzard/Thunder Spear/Teleport directly.
- **Frost Edge**: NEW skill — sharpens cold magic to boost Ice Aura's power.
- **Thunder Spear**: removed orb-summon; fixed-orb damage 296%→466%; removed normal-mob bonus damage; unusable in non-hunting maps.
- **Elemental Reset / Adepting / Master Magic**: description changed.
- **Chain Lightning**: 220%→180% (nerf).
- **Blizzard**: fixed can't-teleport-after-cast bug; description changed.
- **Freezing Breath**: removed on-hit DEF-reduction; gained permanent mob-defense-ignore.
- **Lightning Spear**: 135%→150%; keydown duration 2s→1.8s; finisher 702%→792%.
- **Thunder Break**: MP cost 1000→300; damage 860%→817% (nerf); cooldown 40s→30s; removed re-cast-to-anchor-lightning; now auto-targets nearest max-HP boss and drops lightning there; range +~30%.
- **Spirit of Snow**: attack interval −80%; max-hit cap added; damage 1715%→943% (nerf); respawns at your position on recast/revive.
- **Jupiter Thunder**: 871%→827% (nerf); removed shocked-target Final Damage bonus vs non-Jupiter/Frozen Lightning attacks.
- VI versions received matching changes (Chain Lightning VI, Blizzard VI, Elquines VI, Lightning Spear VI, Thunder Spear VI, Cryo Shock, Parabolic Bolt, Subzero Permeation) with various buffs/nerfs and cooldown/damage tweaks.

### Bishop
- Removed the Mercy/Vengeance skill split (unified).
- **Blessing Ensemble**: fixed lingering party bonus-XP text (function already removed).
- **Bless**: removed party ATT/Magic ATT/DEF buff.
- **Angelic Touch**: damage 350%→690%; hits 5→11; cooldown added; range +~83%; action delay −~8%; icon/effect updated; removed DEF-reduction-on-hit; now shares SP/key with Heal (separately keybound).
- **Teleport Mastery**: **removed**.
- **Divine Refinement**: NEW skill — boosts Stance & mob-defense-ignore via pure holy mana.
- **Divine Protection**: description changed.
- **Fountain for Angel**: unusable in non-hunting maps; shares SP with Holy Fountain, separately keybound.
- **Triumph Feather**: angel feather duration 4s→5s, now prioritizes highest-HP boss; shares SP with Dispel, separately keybound.
- **Master Magic**: description changed.
- **Advanced Bless**: removed party ATT/Magic ATT/DEF/max HP/max MP buff.
- **Resurrection**: removed revived-ally damage buff; gained permanent damage increase instead.
- **Angel Ray**: 225%→182% (nerf).
- **Holy Water**: touching the chalice now heals HP; usage range +~50%; INT-scaling duration bonus 5s→1s per 2500 INT; healing bonus 5%→1% per 2500 INT; added max healing cap; usable mid-other-skill.
- **Holy Blood**: duration 10s→20s; Final Damage formula changed; shares SP with Holy Water, separate key.
- **Genesis**: fixed can't-teleport-right-after bug.
- **Holy Symbol-Imbue Body**: description changed.
- **Vengeance of Angel**: removed mercy-to-vengeance conversion; gained Angel Ray self-heal-reduction + Final Damage buff during duration.
- **Prayer**: removed party Final Damage/HP-MP/attack speed buff & status-cure; now boosts damage/Final Damage for a duration regardless of INT; icon/effect/sound updated.
- **Angel of Libra**: **removed**.
- **Angel of Gemini**: NEW skill — summons twin angels to punish enemies.
- **Peacemaker**: added per-target hit cap; interval −~66%; Holy Light hit now triggers bonus hits equal to remaining orb charges; orbs can be dismissed mid-other-skill; removed Holy Light's damage buff.
- **Divine Punishment**: MP cost 40/hit→1000/use; removed prepare-then-fire, now a max-5s keydown skill; damage 715%→644% (nerf); interval −~13%; cooldown 1.5s→120s.
- VI versions (Angel Ray VI, Triumph Feather VI, Fountain for Angel VI, Angelic Touch VI, Genesis VI, Bahamut VI, Command of Heaven, Angel's Pledge) received matching/parallel changes — mostly damage rebalances (mix of buffs and nerfs) plus mechanical reworks matching the base skills.

### Bowmaster
- Fixed client freeze/stutter bugs on several skills (Quiver Cartridge, Flash Mirage, Mortal Blow, Advanced Quiver, Quiver Full Burst, Storm of Arrows VI, Quiver Cartridge VI, Flash Mirage VI, Extra Quiver Cartridge).
- **Double Jump**: forward-then-up jump chaining improved (multiple directions now chainable); cast motions removed for up-jump and descent.
- **Swift Surge**: cast motion removed; usable mid-skill (except keydown); icon/effect changed; attack removed; travel distance changed; recast delay −~6%; permanent ATT gain added; can't macro.
- **Quiver Cartridge**: selected mode now persists through reconnect.
- **Arrow Platter**: unusable in non-hunting maps; fixed leftover platter/buff icon on SP reset.
- **Concentration**: description changed.
- **Storm of Arrows**: 350%→364%.
- **Sharp Eyes**: removed party crit rate/damage buff.
- **Storm of Arrows VI**: 575%→598%; rapid-fire mode 750%→780%.
- **Arrow Platter VI**: same fixes as base + permanent ATT gain.
- **Point Blank**: arrow impact 5316%→5124%; single-point burst 5528%→5328% (nerfs).
- **Eye of Aquila**: storm 858%→2153%; shockwave 445%→1116%.
- **Sol Hecate**: 796%→824%.

### Marksman (Sinngun)
- **Double Jump**: expanded direction-chaining, cast motions removed for up/down jumps.
- **Swift Surge**: description/cast/effect/sound updated + same mobility rework as Bowmaster.
- **Sharp Eyes**: removed party crit buffs.
- **Arrow Illusion**: duration 30s→60s; removed attack/stun/pull/reflect functions; cast motion −~39%; effect changed.
- **Sniping**: max targets 1→2.
- **Advanced Enhance Arrow**: Enhance Sniping max targets 1→2.
- **Sniping VI**: max targets for base/enhance/ultimate all 1→2; Ultimate Sniping now consumes a charge on hit.
- **Repeating Crossbow Cartridge**: max targets 1→2.
- **True Sniping**: description changed; now auto-aims during keydown and fires on lock-on; max targets 12→5 (nerf); icon/effect changed; scope zoom-in effect added; sounds updated.
- **Split Arrow**: 1631%→1544% (nerf).
- **Fatal Trigger**: burst 5567%→5495%; strike 5694%→5600% (nerfs).
- **Lethal Punisher**: Lethal Bolt 750%→1098%; Lethal Burst explosive arrow 1290%→1928%.

### Pathfinder
- Relic Gauge **removed**.
- **Return to Fartham**: description changed.
- **Double Jump**: full direction-chaining, cast motions removed.
- **Relic Charge I / II**: **removed**.
- **Split Mistel** / **Relic Step** / **Triple Impact** / **Edge of Resonance** / **Combo Assault**: now consume MP on cast (previously relic-gauge based); Relic Step also got motion/icon/effect/sound rework and reduced recast delay.
- **Ancient Guidance**: now periodically heals HP/MP.
- **Sharp Eyes**: removed party crit buffs.
- **Ancient Astra**: now periodically consumes MP; all modes (Discharge/Blast/Transition) capped at 8s max duration and MP-gated.
- **Relic Evolution**: removed gauge-refill function.
- **Ultimate Blast**: MP-based now; removed gauge-consumption Final Damage scaling; damage 1500%→3000%.
- **Primal Tempest / Ancient Tempest**: MP-based now; removed gauge-on-hit refill.
- **Obsidian Barrier**: MP-based; removed party crit damage buff.
- **Relic Unbound**: fixed usable-during-other-cast bug; MP-based.
- **Relic Materialize**: now a proc on hit instead of manual; hits 8→2; damage 1090%→1002% (nerf).
- **Material Burst**: reworked into a 15s/max-6-use burst skill; cooldown 3.5s→60s (now benefits from CDR); removed Relic Evolution material bonuses; explosive arrow 288%→619%; ancient arrow 910%→1956%; shatter 1056%→2270%.
- **Forsaken Relic**: its attacks now trigger Ancient Wrath: [Ancient Force].
- **Relic Penetration**: 6183%→6103% (nerf).
- **Sol Hecate**: 1154%→1180%.

### Night Lord
- **Flash Jump**: forward-use now mid-skill compatible.
- **Mark of Assassin / Mark of Night Lord**: shurikens now only track the enemy they were thrown at.
- **Shadow Leap**: cast motion removed.
- **Shadow Blink**: description changed, motion removed, usable mid-skill, icon/effect updated, travel distance changed, recast delay −~6%.
- **Dark Flare**: unusable in non-hunting maps.
- **Showdown Challenge**: shurikens no longer proc Mark of Assassin.
- **Sudden Raid**: removed DoT; added normal-mob bonus damage; damage 494%→314% (nerf).
- **Purge Area (& Enhance)**: removed DEF/ATT-reduction debuffs on enemies inside; gained permanent mob-defense-ignore instead.
- **Dark Serenity**: Final Damage 15%→18%.
- **Spread Throw**: now hits all enemies in search range; Mark of Assassin now applies to all hit targets; throw angle changed.
- **Wind Demon Shuriken**: hits all in range; damage 615%→676%.
- **Darkness Shuriken**: fixed nearby players hearing your sound effect.
- **Quadruple Throw VI**: hits all in range with Mark of Assassin applying to all; Enhanced version range +~66%.
- **Showdown Challenge VI / Sudden Raid VI / Dark Flare VI / Mark of Assassin VI**: parallel changes to base versions.
- **Life and Death**: slash 1024%→1433%; giant shuriken 1158%→1014% (nerf).
- **Crucial Assault**: wave 5128%→5056%; explosion 5717%→5637% (nerfs).
- **Shadow Ritual**: hit1 5508%→7435%; hit2 2581%→3484%; finisher 363%→490%.
- **Sol Hecate**: 795%→862%.

### Shadower
- **Flash Jump**: expanded direction-chaining.
- **Muspelheim**: master level 20→10; motion removed; usable mid-skill; icon/effect/sound updated; attack/knockback removed; travel distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Meso Explosion**: per-coin damage 100%→85% (nerf).
- **Dark Flare**: description changed; unusable in non-hunting maps.
- **Pick Pocket**: fixed coins occasionally dropping at wrong location.
- **Meso Guard**: NEW skill — block enemy attacks using mesos.
- **Cruel Step**: Final Damage 24%→22% (nerf).
- **Bloody Pocket**: fixed coin-drop-location bug; crit damage 20%→15% (nerf).
- **Sudden Raid**: 494%→195% (big nerf); removed on-hit DoT; added normal-mob bonus damage.
- **Smokescreen**: removed party crit-damage-to-targets-inside buff; now deploys at your location; no longer benefits from cooldown reset.
- **Veil of Shadow**: description changed; ally attacks persist through death/revive.
- **Life and Death Chosen (살생유택)**: NEW skill — choose a kill target; can convert Incision into Incision: Annihilation.
- **Incision**: new "Annihilation" mode added; wound duration limit removed; wound debuff stacks up to 1; wound duration cap removed; using Assassinate/Sonic Blow into Incision: Annihilation no longer consumes the wound debuff.
- **Sonic Blow**: can change direction mid-attack; can cancel by recasting; attack duration 2s→1.8s; interrupted-attack cooldown-refund per remaining hit 3.3s→4.5s; combo damage 1470%→2103%.
- VI versions (Meso Explosion VI, Dark Flare VI, Sudden Raid VI, Veil of Shadow VI) parallel changes.
- **Covert Shadow**: removed Dark Sight-duration-based Shadow Edge upgrade; Shadow Edge now triggered by Smokescreen/Veil of Shadow use instead; Shadow Edge duration 3s→15s; added a one-time +15s extension when combining Smokescreen and Veil of Shadow triggers; fatal blow 160%→137% (nerf).
- **One Strike, Two Cuts (일도양단)**: hit1 960%→1152%; hit2 782%→938%; finisher 850%→1020%.
- **Authentic Darkness**: 5016%→4966% (nerf).
- **Trance**: Assassinate: Annihilation slash 400%→571%; Crush: Annihilation flurry 388%→553%; sword-shadow 567%→809%; fixed prone-state exploit for both Annihilation modes.
- **Sol Hecate**: 798%→848%.

### Dual Blade
- **Flash Jump**: description changed; forward-use mid-skill expanded; can't up-flash-jump mid-air-skill; direction-chain jumping added.
- **Sharp Slash (& Enhance)**: description changed.
- **Tornado Spin**: description/MP-formula changed; motion removed; usable mid-skill (mostly); removed Blade Ascension chain; attack function removed; travel distance changed; recast delay −~6%; permanent ATT gain; Dark Sight no longer breaks on use; can't macro.
- **Fatal Blow / Slash Storm (& Enhance) / Flying Assaulter / Venom**: description changed.
- **Bloody Storm**: description changed; removed Tornado Spin permanent-damage-boost and chain-ability.
- **Blade Ascension / Chain Hell / Shadow Evasion / Phantom Blow**: description changed; Shadow Evasion also lost its "guaranteed crit after dodge" and gained permanent ATT instead.
- **Sudden Raid**: description changed; DoT removed, normal-mob bonus added; 494%→415% (nerf).
- **Dummy Effect**: description changed; removed dummy-triggers-evasion-on-hit.
- **Thorns Effect**: description changed.
- **Blade Storm**: can jump during keydown.
- **Karma Fury**: description changed; MP 500→100; slash start delay −~33%; slash interval −~67%.
- **Blade Tornado**: MP 750→100; spin range +~35%; spin effect changed; typhoon interval −50%, range +60%; per-target whirlwind cap 6→4; whirlwind damage 880%→1320%.
- **Haunted Edge**: description changed; MP 750→100.
- **Hidden Blade VI**: 480%→695%.
- **Life and Death Absolute (생자필멸)**: entering boss-wait maps/Combat Room fully charges attack-count for triggering Yaksha's Fury.
- **Blade Fury VI**: Phantom Blow VI damage bonus 42%p→72%p.
- **Sudden Raid VI**: description changed; same DoT-to-normal-mob-bonus swap; 1020%→709%.
- **Dark Wind Slash (암영난참)**: sword wind 298%→501%.
- **Sol Hecate**: 675%→727%.

### Explorer Pirate (Common)
- **Pirate Leap**: forward-use now allowed mid-skill.

### Viper
- **Vortex Jump**: forward mid-skill use + direction chaining.
- **Advanced Dash**: fixed command-mode unusable mid-skill bug.
- **Flicker Dash**: NEW skill — improved dash, fast forward charge.
- **Physical Training**: master level 5→4; STR/DEX formula changed.
- **Screw Punch**: master level 20→10; MP/damage formula changed; pressing down mid-dash now stops it immediately.
- **Flow Guard**: NEW skill — deflect enemy attacks with mastered energy.
- **Groggy Mastery**: removed crit-rate/damage-vs-debuffed-target bonus; added permanent crit rate/damage instead.
- **Sea Serpent Enrage**: removed serpent-mark-on-hit, added mark-activates-on-hit instead; now hits an area rather than a single target.
- **Serpent Assault Enrage**: per-target hit cap 15→7; damage 420%→458%; hit count 4→8; now area-based.
- **Time Leap**: removed party cooldown-reset; removed reuse-cooldown-on-effect.
- **Wind Booster**: removed party attack speed buff.
- **Serpent Mark**: NEW skill — Viper's attacks empowered by serpent power for a duration.
- **Lightning Form**: duration 55s→30s (nerf).
- **Fist Enrage VI**: 450%→482%; Super Fist Enrage 270%→291%; its shockwave 420%→453%.
- **Sea Serpent VI**: description changed.
- **Sea Serpent Enrage VI / Serpent Assault Enrage VI**: parallel changes to base versions (per-target cap 10→4, damage 853%→1467%, hits 6→9, area-based).
- **Haymaker**: aftermath 4235%→3990%; critical wound 4550%→4270% (nerfs).
- **Neptunus Advent**: search range +~46%; Sea Neptunus mark-mechanic swapped like above; damage 1050%→1369%; Neptunus Assault 1061%→1288%.

### Captain
- **Escape Shot**: motion removed, usable mid-skill, icon/effect changed, attack removed, distance changed, recast delay −~6%, permanent ATT gain, can't macro.
- **Head Shot**: can't be used without a target in range.
- **Continual Aiming**: mark persists through death; Final Damage formula changed, 25%→28%; crit damage formula changed, 20%→17% (nerf).
- **Head Shot VI**: same no-target restriction; Death Hail too.
- **Firecracker**: aerial fire 4311%→4259%; blast 4311%→4259% (nerfs).
- **Aerial Bombardment**: Air Strike 840%→983%; Alpha Strike 3376%→3949%.
- **Sol Hecate**: 678%→696%.

### Cannoneer
- **Cannon Leap / Jump / Drift**: description changed; motion/attack function removed for Jump and Drift; Drift also got icon/effect/sound update, distance change, −~6% recast delay, permanent ATT gain, can't macro.
- **Monkey Magic**: removed party HP/MP/all-stat/move-speed/jump buff.
- **Slumber**: **removed**.
- **Monkey's Blessing**: NEW passive — permanent Final Damage/crit damage/crit rate.
- **Hyper Monkey Spell**: removed party buffs (same as Monkey Magic).
- **Magnetic Anchor**: unusable in non-hunting maps.
- **Support Monkey**: duration 60s→600s.
- **Big Huge Gigantic Cannonball**: description changed.
- **ICBM**: contaminated zone damage 1100%→652% (nerf).
- **Full Maker**: removed party damage buff and supply-drop; max bombardment interval −51%.
- **Special Monkey Escort**: duration fixed at 30s; per-summon hit totals now apply (ends early if all summons exhaust hits); Monkey Cannon 660%→667%; Monkey Bomb 990%→1036%.
- **Magnetic Anchor VI**: unusable in non-hunting; permanent ATT gain added.
- **Support Monkey VI**: duration 62s→600s.
- **Barrel of Monkeys**: aftermath 4067%→3990%; scatter bombing 4263%→4130% (nerfs).
- **Mega Cannon Bombard**: sustained fire 1259%→1810%; explosion 2462%→3738%.
- **Sol Hecate**: 1805%→1631% (nerf).

### Cygnus Knights (Common)
- **Elemental Shift**: description changed; up-use motion removed; forward mid-skill chaining expanded, direction-jump chains added.
- **Glory of Guardians / Queen of Tomorrow**: removed Mihile/Cygnus-class party damage buff.

### Mihile
- **Soul Attack**: now a permanent Final Damage + crit-rate buff.
- **Soul Jump**: description changed + mobility rework.
- **Shining Pierce**: 190%→100% (big nerf); removed on-hit darkness application.
- **Royal Guard**: removed counterattack function; success sound changed; successful block now grants an ATT/Final Damage "resonance" buff instead.
- **Encourage**: removed party ATT buff and Royal Guard tier-1/2/3 counter-damage boosts.
- **Soul Assault**: 145%→65% (nerf); removed darkness application.
- **Shining Chase**: motion removed, icon/effect changed, attack removed, distance changed, −~6% delay, usable mid-skill, can't macro.
- **Advanced Soul Attack**: same permanent buff conversion + added extra damage boost.
- **Soul Link**: removed per-party-member damage bonus and Royal Guard-triggered party ATT/Magic ATT share.
- **Advanced Royal Guard**: 4th/5th consecutive successful blocks now also grant the resonance buff; description updated.
- **Offensive Defense**: resonance-buff-active + Soul Light hit now triggers a light shockwave (hits up to 6 targets).
- **Soul Release**: 460%→265% (nerf); removed darkness application.
- **Combat Mastery**: gained a damage-increase function; description updated.
- **Advanced Offensive Defense**: removed Royal Guard counter-enhancement; light shockwave cooldown 10s→8s.
- **Shining Cross (& Assault)**: nerfed (530%→371%, 326%→198%); removed darkness application.
- **Install Shield**: 225%→450%; removed normal-mob bonus; unusable in non-hunting maps.
- **Soul Rage**: removed Soul Light darkness-chance buff; light shockwave cooldown 10s→8s; added Light of Courage shield-duration/damage-reduction penalty during Soul Rage, but also added Final Damage buff + Offensive Defense cooldown reduction on Soul Light hit.
- **Royal Guard-Ignore Guard → renamed Royal Guard-Reaction.**
- **Deadly Charge**: sound/effect changed; charges 5 times; damage 825%→210% (big nerf); removed darkness application and enemy debuff.
- **Soul Majesty**: removed Install Shield's Offensive Defense debuff trigger.
- **Clau Solais**: now always deals 570% master-level damage regardless of Royal Guard stacks; slash hits 5 times; hit count 15→12; cooldown 12s→15s; removed darkness application and post-use Royal Guard duration extension.
- **Sword of Soul Light**: Royal Guard defend-window 0.5s→0.3s (fixed incorrect tooltip); afterimage 1370%→986%; Soul Light Slash 968%→774%; Light Force Ray 1370%→822% (nerfs); removed normal-attack-triggers-Soul-Light-Slash and custom command; removed darkness application on hit.
- VI versions (Shining Cross VI, Assault VI, Final Attack VI, Royal Guard VI, Deadly Charge VI, Install Shield VI, Offensive Defense VI, Soul Majesty VI, Light of Courage Enhance, Durandal, Knight Immortals, Radiance of Valor) got matching mechanical/numeric parallels — mostly damage nerfs alongside the counterattack-removal reworks, plus Install Shield VI gaining permanent ATT.

### Soul Master
- **Luna Divide**: effect changed.
- **Rising Sun / Falling Moon**: fixed occasional deactivation on map transfer.
- **Soul Leap**: description + mobility rework.
- **Loud Rush / Silent Move**: description/effect changed; motion removed; recast delay −~6%; usable mid-skill; attack removed; distance changed; can't macro (Silent Move keeps its no-attack function too).
- **Soluna Power**: Celestial Cleave now generates both sun and moon sword-auras.
- **Cosmic Shower**: unusable in non-hunting maps.
- **True Sight (& Enhance & Ignore Guard)**: now a buff skill for self mob-defense-ignore + Final Damage; descriptions updated.
- **Elysion**: rift's blackout effect now respects effect-transparency setting.
- **Flare Slash**: soul energy now erupts from enemy's center; no longer gets cooldown reduction from Loud Rush/Silent Move stance changes.
- **Cosmos**: attack cycle −~67% (−~70% during Cosmic Forge); adds a galaxy-collapse effect after enough hits.
- **Cosmic Shower VI**: unusable in non-hunting; permanent ATT gain.
- **Cosmic Burst VI**: orb 1080%→1218%.
- **Totality**: wind pressure 3459%→3370%; fierce slash 3808%→3691% (nerfs).
- **Celestial Cleave**: hit1 1371%→1660%; hit2 1053%→1258%.
- **Sol Hecate**: 909%→1021%.

### Flame Wizard
- **Firework**: mobility rework (forward mid-skill/chain jumps).
- **Blazing Rush**: description changed; motion removed; usable mid-most-skills; icon/effect/sound updated; attack removed; distance changed; recast delay −~6%; permanent Magic ATT gain; can't macro.
- **Maelstrom**: no longer triggers without a target in range.
- **Blazing Extinction**: Fox Mode 375%→330% (nerf); expanded aerial usable range.
- **Infernorize**: Fox Mode cooldown 30s→20s; removed on-hit cooldown reduction.
- **Spirit of Flame**: summoned avatar now persists through reconnect.
- **Burning Legion**: icon/effect updated; removed party damage/attack-speed buff.
- **Blazing Orbital Flame**: interval −~50%.
- **Flame Discharge**: foxfire 1100%→990% (nerf).
- **Infinity Flame Circle**: 1900%→1767% (nerf).
- VI versions (Blazing Extinction VI, Infernorize VI) parallel changes.
- **Flame Concerto**: explosive flame 4900%→4582% (nerf).
- **Ignis Requiem**: origin flame 1112%→2324%; flame explosion 1831%→3614%; action delay −~18%.
- **Sol Hecate**: 765%→803%.

### Wind Breaker
- **Gust Shift**: jump-during-keydown added; description + mobility rework.
- **Windwalk**: description/icon/effect/sound updated; ground-use motion removed, delay −~6%, distance changed; usable mid-skill; can't macro.
- **Trifling Wim I/II/III**: spirit-energy damage increased across the board (e.g., I: 170%→227%, enhanced 210%→263%; similar scaling for II/III).
- **Storm Bringer**: giant arrow 620%→775%.
- **Emerald Dust**: description changed; removed nearby-mob DEF-reduction, added permanent mob-defense-ignore instead.
- **Cygnus Phalanx**: spear-troop damage 1485%→1430% (nerf).
- **Howling Gale**: cooldown added; removed wind-energy-stockpiling and its summon-scaling; always applies slow now; per-target hit cap added; wind gusts now move toward enemies periodically; hit count 3→6; first gust 1715%→1045% (nerf); second gust 945%→1045%.
- **Idle Wim**: 925%→1360%.
- **Wind Wall**: whirlwind 935%→1375%.
- **Vortex Sphere**: description changed; 960%→791% (nerf).
- **Trifling Wim VI**: 420%→560%; enhanced 675%→844%.
- **Storm Bringer VI**: 938%→1172%.
- **Mistral Spring**: wind blade 1670%→5726% (big buff); spirit-energy variants nerfed (1320%→780%, 1440%→840%, 1275%→729%).
- **Element Tempest**: wave 5619%→5320% (nerf).
- **Sylph's Breath**: breath damage increased (1030%→1481%, 1599%→2284%).
- **Anemoi**: can now be registered to skill sequences; removed the "great spirit brings victorious wind" effect; summon time −~34%.
- **Sol Hecate**: 894%→849% (nerf).
- **Cygnus Phalanx VI**: charge 2694%→2594%; spear troop 2114%→2026% (nerfs).

### Night Walker
- **Shadow Jump**: removed throw-skill-finisher-cancel-via-jump and its Dark Sight trigger; up-use motion removed; forward mid-skill chaining expanded.
- **Silent Rush**: description/motion/icon/effect changed; usable mid-skill; attack removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Rapid Evasion**: recast delay −~26%.
- **Triple/Quadruple Throw**: finisher motion −~92%.
- **Shadow Momentum**: removed throw-skill-speed-up function.
- **Quintuple Throw**: finisher motion −~83%.
- **Darkness Omen**: duration 7s→3s; cooldown fixed at 120s; no longer benefits from cooldown-reset or summon-duration-extension; damage 370%→902%.
- **Shadow Bite**: motion −~40%.
- **Quintuple Throw VI**: hits all in search range; finisher motion −~83%.
- **Darkness Omen VI**: same duration/cooldown lock; damage 820%→2060%.
- **Silence**: slash 808%→2060%; shadow shuriken 900%→450% (nerf).
- **Stygian Command**: pitch-black veil 4466%→4493%; darkness dominion 3976%→4000%.
- **Singularity Throw**: motion −~40%; erosion 313%→501%; crush 418%→668%.
- **Sol Hecate**: 744%→767%.

### Striker
- **Element: Lightning**: fixed buff-icon-clearing-on-boss-exit bug; entering boss/Combat Room/Misty Forest maps now maxes out the Lightning buff stack, as does any cooldown-reset content.
- **Gale**: same max-stack-on-entry/reset behavior for its damage buff.
- **Thunder Wolf (뇌랑)**: NEW skill — charges forward with surging lightning power.
- **Extreme Armor**: master level 10→9; damage/crit-rate/damage-reduction/stance formulas all changed.
- **Chain**: same max-stack-on-entry/reset behavior.
- **Typhoon**: same max-stack-on-entry/reset behavior.
- **Wind Booster**: removed party attack-speed buff.
- **Thunder God / Ocean God Descent / Divine Thunder Unity**: descriptions changed; Ocean God Descent action delay −~66%.
- **Thunderclap VI**: description changed; using Gale during Heaven-Earth-Split now bypasses the follow-up wave's cooldown for an extra wave, but that extra wave itself gains a cooldown.
- **Typhoon VI**: same max-stack behavior.
- **Ocean God Descent VI**: description changed; action delay −~66%.
- **Ocean Wave VI**: description changed; damage 1040%→673% (nerf); gained normal-mob bonus damage.
- **Annihilating Blade**: fierce assault 4312%→4205%; torrent 4557%→4419% (nerfs).
- **Ocean Sovereign's Devastation**: tyrant's form 1182%→1965%; battlefield devastation 1311%→2181%; fixed a Combat Room replay icon glitch.
- **Sol Hecate**: 629%→633%.

### Hero (Legends) Common — "영웅 공통"
- **Heroes' Oath**: removed Legends-class party damage buff.

### Aran
- **Combat Step**: description changed; ground-use effect/motion reworked, usable mid-skill, can't macro; aerial up-jump and forward-then-up/up-then-forward jump chains added.
- **Final Charge**: description/icon/effect changed; motion removed; recast delay −~6%; usable mid-skill; attack removed; no longer gets extra cooldown when used during Beyonder; distance changed; permanent ATT gain; can't macro.
- **Frozen Ground**: unusable in non-hunting maps; effect position changed.
- **Blessing Maha**: removed party ATT/Magic ATT buff.
- **Maha's Blessing**: action delay −~33%.
- **Beyonder VI**: effect/sound updated.
- **Frozen Ground VI**: unusable in non-hunting; permanent ATT gain; effect position changed.
- **Frost Blaster**: storm 6027%→5913%; ice-slash 5464%→5360% (nerfs).
- **Maha Unleashed**: Beyonder Absolute variants (Black Tortoise/Vermillion Bird/Azure Dragon) 2336%→2516%; Final Beyonder Absolute 3951%→4255%.
- **Sol Hecate**: 1076%→1001% (nerf).

### Evan
- **Come Back!**: description/effect/sound updated.
- **Swift-Come Back! / Dive-Come Back! / Breath-Come Back! / Sword-Come Back!**: **all removed**.
- **Magic Amplification**: on-hit MP recovery added.
- **Circle of Mana III / Thunder / Earth**, **Dark Fog**: now can trigger Dragon Sparking on hit.
- **Dragon Potential**: gained permanent attack-speed and Final Damage increases.
- **Circle of Mana IV**: can trigger Dragon Sparking; 2nd hit removed; cast motion +~73%; chains into Come Back!/Elemental Blast; effect/sound updated; hits 4→8; damage 273%→286%.
- **Magic Mastery**: proficiency-gain formula changed (70%→72%); crit-damage formula changed (20%→17%, nerf).
- **Dragon Master**: can now cancel an in-progress Mir skill to use another.
- **Summon Onyx Dragon**: reworked into "channel the ancient Onyx Dragon's power" (no longer summons a dragon); icon/effect/sound changed; adds Final Damage buff during duration; can be registered to skill sequences.
- **Elemental Blast**: elemental-hit Final Damage buff now 15% flat, stacks capped at 1; 2nd/3rd/4th elemental hit delays reduced (~59%/~56%/~45%); effect/sound updated.
- **Dragon Break**: per-target hit cap added; first-hit range +~89%; all hits now equal range; damage 1909%→2863%.
- **Imperial Breath**: first-hit cast time −~50%; duration 1.7s; damage 1760%→3016%; effect/sound updated.
- **Break-Come Back!**: **removed**.
- **Spiral of Mana**: can trigger Dragon Sparking; reworked into a direct mana-body strike; cooldown added; damage 159%→636%; effect/sound updated.
- **Circle of Mana VI / Thunder VI / Earth VI / Wind VI**: matching Dragon-Sparking-trigger and (for Mana VI) the same chain/damage rework as base.
- **Union Drive**: mana strike 5320%→4772%; resonance wave 5810%→5211% (nerfs).
- **Dragon Soar**: range +~13%; damage 1679%→1956%.
- **Vertical Finisher**: 1427%→1662%.
- **Soar-Come Back!**: **removed**.

### Luminous
- **Twinkle Flash / Sylphid Lancer**: fixed aerial-use bugs.
- **Poetic Meditation**: removed party Magic ATT buff.
- **Larkness Resonance**: NEW skill — power that manifests differently based on Light/Dark.
- **Twilight Nova**: Final Damage 33%→37%; fixed aerial-use bug.
- **Magic Mastery**: crit damage 18%→22%.
- **Armageddon**: no longer triggers without a target in range.
- **Memorize**: Fate's Torrent 950%→380% (big nerf).
- **Absolute Kill-Add Range**: fixed reduced rear/low attack range on acquisition.
- **Gate of Truth**: MP cost 1000→500.
- **Punishing Resonator**: MP cost 1000→300; fixed aerial-use bug.
- **Baptism of Light and Dark**: MP cost 2000→300.
- **Liberation Orb**: MP cost 1200→1000.
- **Lustrous Orb**: dark erosion 3710%→3500%; flash 3710%→3500% (nerfs).
- **Twilight Nova VI**: fixed aerial-use bug.
- **Sol Hecate**: 787%→855%.

### Mercedes
- **Spirit Jump**: keydown-jump added; description/mobility rework; can't chain into other skills anymore.
- **Charge Drive**: description changed.
- **Leaf Tornado**: can now chain into Verian Surge: Glory hit 3.
- **Unicorn Spike**: removed bonus-damage-taken debuff.
- **Water Shield**: action delay −~33%, now affected by attack speed.
- **Ignis Roar**: removed combo-skill Final Damage/attack-speed trigger; Final Damage 17%→37%; gained permanent attack speed and damage increases.
- **Ishtar's Ring**: removed on-hit Ignis Roar duration extension; arrow damage 316%→490%.
- **Legendary Spear**: removed mob-defense-reduction debuff.
- **Lightning Edge**: description/icon/effect/sound updated; motion removed; usable mid-skill; attack removed; distance changed; permanent ATT gain; can't macro.
- **Spirit Escape**: usable in air without needing a prior attack skill.
- **Defense Break**: mob-defense-ignore 25%→67%.
- **Legendary Spear-Reduce Armor → renamed Legendary Spear-Extra Target.**
- **Elemental Ghost**: duration 50s→30s (nerf); spirit energy now always appears; its Final Damage ratio 45%→50%; its Ishtar's Ring/Irkalla's Breath ratio 22%→16% (nerf); Eurel's Form 900%→1366%.
- **Irkalla's Breath**: removed Ignis Roar duration extension on hit; keydown-jump added.
- **Royal Knights**: description changed.
- VI versions (Ishtar's Ring VI, Leaf Tornado VI + Spirit Enchant, Legendary Spear VI, Unicorn Spike VI, Gust Dive VI, Strike Dual Shot VI) parallel changes with various buffs.
- **Unfading Glory**: now extends Elemental Ghost duration if used during it.
- **Elemental Spirit**: arrow barrage 6158%→5053% (nerf).
- **Verian Surge**: removed bonus-damage-taken debuff; Glory hit1 790%→959%; Glory hit2 (debuff removed) 1450%→1809%; Glory hit3 667%→824%.
- **Elemental Ghost Enhance**: Final Damage ratio 60%→70%; Ishtar's/Irkalla's ratio 30%→22% (nerf).

### Phantom
- **Steal Skill**: several skills can no longer be stolen (Rush, Muspelheim, Tornado Spin, Cannon Drift); using the Crystal Garden central-hall adventure log now lets you steal from ALL classes.
- **Skill Management**: fixed old-skill-not-unequipping bug on swap; added preset management for equipped skills; Talent of Phantom Thief disabled while Skill Management UI is open; pre-cooldown no longer benefits from cooldown-reset.
- **Skill Quick Management**: NEW skill — quickly switch Skill Management presets.
- **Judgment AUTO/MANUAL**: mode now persists through reconnect.
- **Swift Phantom**: description changed + mobility rework.
- **Phantom Charge**: description/icon/effect/sound updated; motion removed; usable mid-skill; attack removed; recast delay −~6%; can't chain with Breeze Carte; distance changed; permanent ATT gain; can't macro.
- **Ultimate Drive**: keydown-end action delay removed.
- **Tempest of Cards**: cooldown 18s→20s (master level); cooldown now applies immediately on cast; max keydown 5s→2s; removed mob-defense-ignore debuff.
- **Twilight**: usable in air; effect/sound updated.
- **Soul Steal**: **removed**.
- **Phantom of Aria**: NEW skill — Aria's lingering wish protects the Phantom.
- **Tempest of Cards-Cooldown Reduce**: reduction 20%→15% (nerf).
- **Joker**: keydown-end delay removed; removed party card-effect sharing.
- **Blackjack**: card 1540%→1320%; released card 1265%→1100% (nerfs).
- **Mark of Phantom**: added no-teleport-with-down-key option and a custom-command no-teleport mode.
- **Rift Break**: 1430%→1320% (nerf).
- **Tempest of Cards VI**: effect/sound updated; cooldown 18s→20s; immediate cooldown on cast; max keydown 2s→1s; removed mob-defense-ignore debuff.
- **Ultimate Drive VI**: keydown-end delay removed.
- **Lamour Carte**: reworked to replace Noir Carte during duration; duration 40s→6s (big nerf); Joker/Defying Fate use during it extends duration; removed Joker-triggered damage boost; damage 1350%→1210% (nerf).
- **Moonlit Serenade**: slash 4733%→4480%; moonlight 5997%→5705% (nerfs).
- **Flèche Retour**: combo 382%→649%; counter-thrust 458%→776%.
- **Sol Hecate**: 493%→504%.

### Eunwol (Kanna/Blade Master style — 은월)
- **Chukji (축지)**: description changed; removed move-while-casting and cast-cancel functions; action delay −~71%.
- **Doyak (도약)**: description + mobility rework.
- **Backward Step**: description changed; motion removed; removed cast-cancel function.
- **Sohon Veil**: unusable in non-hunting maps; effect position changed.
- **Fierce Charge (맹진)**: NEW skill — a powerful forward charge.
- **Binding Technique**: usable in air; cast effect changed.
- **Weaken**: description changed; removed chance-to-possess-with-weakening-spirit; gained permanent damage increase instead.
- **United Front**: master level 9→8; ATT/damage/crit-damage formulas changed.
- **Sohon Barrier**: description changed; passive doesn't trigger during Restraint mode.
- **Vigor**: description changed.
- **Spirit's Avatar**: usable in air.
- **Hojugaesi**: description changed; gained crit damage increase.
- **Gwimunjin (귀문진)**: description changed; removed the spirit-gate-release burst and its crit-damage debuff mechanic; can register to skill sequences; dark spirit 935%→1365%.
- **True Ghost Slash**: description changed; range +~3%.
- **Crushing Fist Technique**: can move/jump during keydown.
- **Heavenly Ghost Night Slash**: hit1→2 chain delay −40%; hit2→3 chain delay −40%; hit3 action delay −~18%.
- **Sohon Veil VI**: description changed; unusable in non-hunting; effect position changed; permanent ATT gain; Fox Spirit VI gets permanent damage boost too.
- **Yeongwol**: spirit pressure 1553%→1478%; spirit execution 1328%→1264% (nerfs).
- **Yeonwoo Gyeokpung**: cast effect changed.
- **Sol Hecate**: 570%→618%.

### Resistance (Common)
- **Will of Liberty / Demonic Fortitude**: removed party damage buff for Demon/Resistance/Xenon classes.

### Blaster
- Fixed occasional macro-unusable bug.
- **Magnum Punch / Revolving Cannon / Release Pile Bunker / Explosion Move / Double Fang / Ducking / Gauntlet Booster**: descriptions changed; Explosion Move also lost its attack function, motion removed for forward use, gained a Limiter Mode option (spend MP instead of bullets, usable while reloading, but limited aerial combo count); Ducking also got −25% action delay (now affected by attack speed); Gauntlet Booster's master level 10→9, MP-cost/duration formulas changed.
- **Explosion Spurt (익스플로젼 스퍼트)**: NEW skill — explosive-powered charge forward.
- **Sway**: description changed; action delay −25%.
- **Rift Press / Magnum Cannon**: description changed.
- **Shock Wave Punch**: Double Fang damage-bonus 180%p→136%p (nerf).
- **Flash Move**: description changed; Magnum Punch damage-bonus 216%p→186%p (nerf).
- **Revolving Cannon Upgrade III**: damage-bonus during Magnum Punch 210%p→128%p; during Double Fang 170%p→103%p (nerfs).
- **Hyper Magnum Punch**: description changed; usable in air.
- **Maximize Cannon**: duration 50s→40s; overheat-reduction procs 20→13; Blast Hammer Smash max uses 38→24 (all nerfs).
- **Release Pile Bunker-Bonus Guard**: description changed.
- **Bunker Buster**: description changed; duration 50s→40s; damage 485%→461% (nerfs).
- **Vulcan Punch**: can change direction and move/jump during keydown.
- **Burning Breaker**: description changed; direction change during keydown; no longer dashes at keydown-end; auto-consumes up to 5 extra bullets periodically.
- **Afterimage Shock**: description changed.
- **Magnum Punch VI**: 800%→716% (nerf).
- **Double Fang VI**: 680%→576% (nerf).
- **Release Pile Bunker VI**: description changed; several sound effect updates for cylinder-gauge-full cast and shockwave variants A–D.
- **Burst Pile Bunker**: min chain-delay into Hammer Smash −50%; sound effects updated.
- **Revolving Cannon Mastery VI**: 700%→626% (nerf).
- **Revolving Cannon VI**: description changed; 675%→522% (nerf).
- **Hurricane Mixer VI**: description changed.
- **Vanguard Impact**: shock 2132%→2110%; energy remnant 3063%→3033% (nerfs).
- **Overheat Punch**: blackout effect now respects transparency setting; strike 1821%→2111%; smash 1144%→1318%.
- **Sol Hecate**: 594%→634%.

### Battle Mage
- **Yellow Aura**: removed party attack-speed buff; on/off state now persists on reconnect.
- **Death**: fixed can't-use-in-air bug.
- **Drain Aura / Blue Aura / Dark Aura**: on/off persists on reconnect; Blue Aura description changed; Dark Aura removed party damage buff.
- **Dark Lightning**: removed teleport-triggers-attack function.
- **Finish Blow**: 330%→880%.
- **Dark Genesis**: 520%→1850%; hits 8→10; lightning-attack damage 250%→1000%.
- **Debuff Aura**: **removed**.
- **Aura Enhance**: NEW skill — upgrades your aura, marks nearby enemies with a black sigil.
- **Necrotic Hex**: NEW skill — death spell that partially ignores enemy defense.
- **Battle King Bar**: 1080%→2000%; hits 7→8; gains a post-hit mana burst.
- **Debuff Aura-Enhance → renamed Drain Aura-Enhance.**
- **Union Aura**: reaper's scythe 300%→350%; party Battle Mages can now use Dark Aura even during your Union Aura.
- **Black Magic Alter**: unusable in non-hunting maps; gained permanent Magic ATT; with HEXA Enhance Core active, gains permanent Final Damage/Magic ATT for Black Sigil & Dark Pentacle.
- **Unholy Pact**: NEW skill — choose which reaper form to summon via another death contract.
- **Grim Reaper**: duration 30s→60s; removed kill-count/boss-hit duration-extension; removed the 50%-attack-interval-during-Master-of-Death function.
- **Grim Reaper: Unbound**: NEW skill — fully unleashed dark-magic reaper form.
- **Death VI**: fixed can't-use-in-air bug.
- **Finish Blow VI**: 666%→1200%.
- **Battle King Bar VI**: 690%→1375%; hits 5→8; mana burst 555%→1000%, hits 5→10.
- **Dark Lightning VI**: removed teleport-attack function.
- **Dark Genesis VI**: 890%→2560%; hits 8→10; Death Whip 250%→730%, hits 10→12; lightning 430%→1110%.
- **Gloomy Aura**: eruption 4410%→4165%; crack explosion 5565%→5250% (nerfs).
- **Mortis Edge**: 933%→1658%; Chaos Edge 311%→804%.
- **Sol Hecate**: 759%→848%.

### Wild Hunter
- Fixed jaguar occasionally looking off to other players.
- **Jaguar Riding**: mount state persists on reconnect.
- **Savage Leap**: forward-then-up jump chain; forward mid-skill use expanded; fixed effect glitch while Draw Back active.
- **Predator's Leap**: description changed; removed prey-mark duration limit.
- **Howling**: removed party ATT/Magic ATT buff.
- **Whiteout Rush**: description/MP-formula changed; motion removed for forward dash; effect changed; usable mid-skill; attack/knockback removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Trap Seeder**: unusable in non-hunting maps.
- **Wild Vulcan: Apex**: grenade-explosion effect now renders behind character.
- **Sharp Eyes**: removed party crit buffs.
- **Wild Vulcan: Overdrive**: jump-during-keydown added.
- **Wild Vulcan: Apex VI**: same effect-layer fix.
- **Trap Seeder VI**: description changed; unusable in non-hunting; permanent ATT gain.
- **Gear Storm**: strike 2303%→2242%; indiscriminate bombing 5415%→5318% (nerfs).
- **Resonance: Wild Pierce**: interval changed; strike 990%→1048%; raid 928%→984%.
- **Sol Hecate**: 826%→773% (nerf).

### Xenon
- STR/DEX/LUK gained from wearing Arcane/Authentic Symbols rebalanced (Arcane: 144/198 base, 48/66 bonus → various new values; Authentic: 240/330 base, 96/132 bonus, similarly scaled — see table below).
- **Symbol type table (base / enhanced base → new values):**
  - Arcane Symbol: 144 → 198 (base), 48 → 66 (enhance)
  - Authentic Symbol: 240 → 330 (base), 96 → 132 (enhance)
- **HEXA stat enhancement STR/DEX/LUK table** (levels 1–10, main stat and sub stat before/after) — values scaled up roughly 37–38% at every level (e.g., level 1: 48→66 main, 48→66 sub; level 10: 960→1320 main, 480→660 sub).
- **Surplus Supply / Multilateral I / Promesse Assault / Multi Mode Linker / Aviation Liberty / Energy Spline**: descriptions changed.
- **Sudden Propel**: description changed + mobility rework (forward mid-skill, no up-use mid-air-skill, direction-chain jumps).
- **Incline Power / Radialnerve Refine / Multilateral II / Quicksilver Sword: Focus / Ion Thruster**: description changed; Radialnerve Refine also gains a stat increase.
- **Linear Perspective**: description changed + stat increase added.
- **Minority Support**: description changed; removed INT gain; STR/DEX/LUK gain 25→75.
- **Xenon Mastery**: description changed + stat increase added.
- **Multilateral III / Combat Switching: Shootdown**: description changed.
- **Diagonal Chase**: description/MP-formula/motion/effect changed; can't macro; attack/knockback removed; permanent ATT gain; post-cast move-start delay −~82%.
- **Horizon Chase**: description/MP-formula changed; motion removed; effect changed; attack removed; distance changed; recast delay −~6%; usable mid-skill; can't use prone; can't macro.
- **Pillar Scramble**: description changed.
- **Virtual Projection**: description changed + permanent stat increase.
- **Extra Supply**: description changed.
- **Dualbreed Defensive**: description changed; removed INT gain; STR/DEX/LUK 10→450 (huge buff).
- **Triangle Formation**: description changed; removed accuracy-reduction debuff; enemy-position cast effect hidden from other players; damage 340%→166% (nerf).
- **Multilateral IV**: description changed.
- **Blade Dancing**: fixed occasional mid-keydown skill-use exploit.
- **Purgerope Masquerade: Snipe**: description changed; effect hidden from others; 325%→286% (nerf).
- **Purgerope Masquerade: Barrage / Bombardment**: description changed; Bombardment also 370%→320% (nerf).
- **Hologram Graffiti: Force Field**: description changed; unusable in non-hunting maps.
- **Hologram Graffiti: Support**: **removed**.
- **OOPArts Code**: description changed; Final Damage 32%→5% (big nerf).
- **Time Capsule**: **removed**.
- **Xenon Expert / Offensive Matrix**: description changed; removed crit damage bonus (Expert), added stat increase to both.
- **Multilateral V / VI**: description changed; VI also loses its Final Damage buff.
- **Confine Entangle**: description changed; usable in air; requires a target; range +~615%; action delay −~19%.
- **Meltdown Explosion**: description/effect/sound changed; action delay −~77%.
- **Amaranth Generator**: description changed.
- **Mega Smasher**: jump during keydown; damage 660%→627%; deployed version 550%→523% (nerfs).
- **Hologram Graffiti: Fusion**: description changed; removed party damage buff and evade-charges-energy function; can change modes via Multi Mode Linker; damage 495%→240% (big nerf); gained normal-mob bonus damage.
- **Hologram Graffiti: Flicker**: NEW skill — deploy a dense, cutting-edge hologram field.
- **Photon Ray**: icon changes on extra-lock completion; lock mode persists through map-move/revive; photon cannon 880%→827% (nerf).
- VI versions of Masquerade/Triangle Formation/Hologram Graffiti/Meltdown Explosion/Blade Dancing got matching nerfs and mechanical parallels.
- **Artificial Evolution**: bombing 710%→1600%; enhanced airframe 960%→622% (mixed).
- **Neoteric Thrice**: wave 4900%→3185%; energy burst 3032%→1970%; quantum blade 956%→621% (nerfs).
- **Rail Gun Cannonade**: fixed blackout-effect glitch at non-100% transparency.
- **Sol Hecate**: 616%→511% (nerf).

### Mechanic
- **Jet Booster**: description changed; Double Acceleration forward-use expanded mid-skill; direction-chain jumps; Mechanic Dash ground-use expanded mid-skill.
- **Metal Armor: Human**: ride state persists on reconnect.
- **Gatling Shot / Advanced Gatling Shot / Rocket Booster / Massive Fire: IRON / IRON-B / Rocket Punch / Advanced Homing Missile**: description changed.
- **Drill Rush**: **removed**.
- **Skid Dash**: NEW skill — instantly bursts propulsion for a rough forward charge.
- **Homing Missile (& VI)**: description changed; now an on/off toggle equipping a multi-target missile pod; initial search range +~27%; re-search range +~78%; refire cooldown added.
- **Robot Launcher: RM7**: unusable in non-hunting maps.
- **Metal Armor: Tank**: description changed; ride state persists on reconnect.
- **Support Waiver: H-EX (& Reinforce, Party Reinforce, Persist)**: **all removed**.
- **Magnetic Field**: unusable in non-hunting maps.
- **Support Protocol**: NEW skill — permanently runs a combat-support protocol.
- **War Machine: Titan**: action delay −~63% (now attack-speed-scaling); motion/effect/sound changed; delay-to-first-Titan-hit −~34%; removed mash-to-charge-gauge damage amp and Titan's melee-range auto-attack; hit effects reworked.
- **Robot Factory: RM1**: unusable in non-hunting maps.
- **Combat Optimization System**: NEW skill — activates a combat-optimized system.
- **Distortion Field**: description changed; interval −64%; per-target hit cap added; damage 350%→525%; hits 2→5.
- **Bomber Time**: duration 10s→20s; cooldown 60s→120s; boosts Homing Missile search ranges during its window (+~27% / +~178%).
- **Robot Launcher: RM7-Persist / Robot Factory: RM1-Persist**: NEW skills — extend the respective summon's duration.
- **War Machine: Titan-Reinforce**: NEW skill — boosts Titan's damage.
- **Multiple Option: M-FL**: description changed; Gatling Cannon 440%→715%; Missile 650%→1055%.
- **Micro Missile Container**: MP 1000→200; fire-delay −~81%; effect/sound updated; damage 935%→1214%.
- **Metal Armor Full Barrage**: description/motion changed; MP 1500→1000; removed cast-invulnerability, homing-missile synergy bonuses, and mid-cast buff-skill usage; keydown removed (now a direct deploy); effect/sounds updated; usable in air; damage 880%→1595%; hits 12→13.
- **Meca Carrier**: description changed; MP 1250→500; summon duration 50s→40s; cooldown 120s→60s; added max-launch cap (despawns early once reached); fighter damage 486%→595%.
- **Distortion Field VI**: matching changes; damage 720%→895%; hits 2→6; Intense Distortion Field no longer clears an active Distortion Field.
- **Intense Distortion Field**: description changed; removed reflect-immunity and periodic-attack function; action delay −~23% (no longer attack-speed-scaling); motion/effect/sound updated; wave 1990%→940% (nerf); wave hits 15→9 (fires 9 times).
- **Metal Armor: Extermination**: bombing 5832%→5250% (nerf).
- **Buster Station**: missile 295%→469%; explosion 370%→602%.
- **Sol Hecate**: 913%→1050%.

### Demon (Common)
- **Demon Jump**: description + mobility rework.

### Demon Slayer
- **Dark Thrust**: motion removed; usable mid-skill; icon/effect/sound updated; attack removed; removed multi-target-pull; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Demon Trace**: movement range limited in boss maps.
- **Bloody Raven**: description changed; action delay −~25%.
- **Concentration**: gained permanent mob-defense-ignore.
- **Devil Cry**: removed on-hit ATT/DEF/accuracy debuff.
- **Dark Bind**: no longer triggers without a target; range +~25%.
- **Infinity Force**: now consumes HP instead of Force.
- **Demonic Fortitude**: removed party damage buff.
- **Demon Awakening**: description/effect changed; Enhanced Demon Slash hits 1–2: 830%→893%; hit3: 930%→1007%; hit4: 1065%→1170%; range increases on hits 1–3 (~22%/~75%/~10%).
- **Jormungandr**: can summon the underworld dragon in air; summon state persists regardless of platform; recast respawns at current location.
- **Demon Bane**: added direction-change via arrow keys; keydown combo damage 730%→1080%.
- **Demon Impact VI**: icon/effect changed; max targets 5→10; damage 675%→900%; chains hit 5 times; on-hit Force recovery added; slow-debuff duration 20s→60s; cooldown added; removed periodic auto-upgrade to Demon Chain.
- **Demon Slash VI**: effect changed; hits1-2 340%→689%; hits3-4 325%→732%; range increases (~105%/~73%/~28%).
- **Demon Explosion VI**: permanent Demon Impact VI damage bonus 70%p→83%p; removed Demon Chain permanent-damage function.
- **Metamorphosis VI**: permanent Demon Impact VI bonus 15%p→50%p.
- **Devil Cry VI**: removed on-hit debuff; gained permanent Demon Impact VI damage bonus; removed Demon Chain bonus.
- **Cerberus VI**: auto-triggered Tartarean Cerberus VI during Demon Awakening: 430%→558%; hits 10→7.
- **Nightmare**: underworld's realm now persists for Nightmare's remaining duration even after Judgment of the Underworld triggers; wave 3000%→4815%, hits 4→6, procs 6→9; underworld flame 2229%→2653%; judgment 1760%→1408% (nerf).
- **Amethystine Intrusion**: explosion 7560%→7606%.
- **Wrath of Satan**: rift 1523%→1633%; origin darkness 972%→1112%; erosion 2283%→2742%.
- **Sol Hecate**: 1056%→1088%.

### Demon Avenger
- **Exceed**: max Overload 20→10; overload-needed-for-1%-Absolve-Life-lifesteal-reduction 2→1; removed Release Overload halving Exceed stage; removed stacking-overload-on-exceed-skill-during-exceed-skill; Exceed stage now persists until logout; boss-wait maps now max out both Exceed and Overload stages on entry.
- **Conversion Starforce**: fixed visible to other citizens via HEXA Matrix info; max applicable starforce 435★→550★.
- **Blood Contract**: bonus-HP-from-equipment ratio 50%→80%; reworked "reduced HP cost from 1st–4th job skills in certain no-heal situations" into a broader "reduced HP cost from skill use in certain no-heal situations."
- **Release Overload**: can now heal up to 50% max HP even during Demon Frenzy's heal-reduction; cooldown added; removed on-use Final Damage buff, gained permanent Final Damage instead.
- **Absolve Life**: now requires Release Overload as prerequisite skill.
- **Abyssal Rage**: ATT-gain 40→10 (nerf).
- **Shield Charge**: **removed**.
- **Blood Charge**: NEW skill — expel demonic blood for a propulsion charge.
- **Is Exceed Pain**: fixed Exceed: Execution VI / Moonlight Slash VI not getting the +20% Exceed-skill-damage buff.
- **Advanced Absolve Life**: Release Overload's Final Damage bonus 25%→16% (nerf).
- **Exceed: Execution**: effect changed; 540%→535% (nerf).
- **Shield Chasing**: on hit, no longer benefits from Absolve/Advanced Absolve Life healing.
- **Armor Break**: removed DEF-reduction debuff.
- **Bloody Imprison**: no longer triggers without a target.
- **Surpass Limit**: recast now ends it immediately.
- **Demonic Fortitude**: removed party damage buff.
- **Overwhelming Power**: removed permanent damage bonus, added permanent mob-defense-ignore instead.
- **Advanced Desperado Mastery**: ATT-gain 50→30 (nerf); removed permanent crit damage, added permanent mob-defense-ignore.
- **Exceed-Reduce Overload**: max permanent-reduction 2→1 (nerf).
- **Exceed-Bonus Chance**: description changed.
- **Demon Frenzy / Frenzy Break**: demonic blood attack 740%→570% (nerf); on/off state persists on reconnect.
- **Blood Fist**: no longer costs HP; reworked to a 1s window granting 30% damage reduction + healing 30% max HP; removed area-attack-on-cast; new passive: direct attacks trigger a "blood burst" hitting nearby enemies.
- **Dimension Sword**: can no longer hit boss-reward monsters afterward.
- **Revenant**: added a "can't heal above 78% max HP" cap during its duration; Thorn of Wrath hits no longer benefit from Absolve/Advanced Absolve Life healing.
- **Shield Chasing VI**: same healing-exclusion fix.
- **Exceed: Execution VI**: effect changed; 980%→941% (nerf).
- **Overmaximizing Exceed**: HP-threshold for the 0.3s-cooldown-reduction changed from <75% to <78%; damage 2415%→1437% (big nerf).
- **Requiem**: sword's roar can now be used mid-keydown-skill is now disallowed(clarify — actually the note says it CANNOT be used during keydown now); underworld sword persists for Requiem's remaining duration after roar triggers.
- **Ragebone Daredevil**: fury burst 5110%→3797%; crimson ruin 5180%→3879% (nerfs).
- **Rabid Carnage**: sustained attack 1626%→1469% (nerf); blade-spear strike 2076%→2206%; passive damage 1291%→2294%.
- **Sol Hecate**: 765%→693% (nerf).

### Kaiser
- **Vertical Connect**: now usable during Final Figuration.
- **Double Leap**: description + mobility rework.
- **Pierce Rush**: description/icon/effect/sound updated; motion removed; recast delay −~6%; usable mid-skill; attack removed; distance changed; permanent ATT gain; can't macro.
- **Will of Sword**: weapon-avatar summon time −~70%; summon-complete time −~80%; avatar damage 300%→510%.
- **Will of Sword: Charge**: cooldown 10s→20s; Morph Gauge gain +100%.
- **Wingbeat**: reworked into a passive — direct-use attacks now spawn a whirlwind at target location.
- **Petrified**: unusable in non-hunting maps.
- **Advanced Will of Sword**: avatar damage 450%→750%.
- **Final Trans**: cooldown 240s→120s; Final Figuration transform duration 60s→30s; using it while already in (non-Trans) Final Figuration extends duration by 30s.
- **Wingbeat-Persist → renamed Wingbeat-Ignore Guard.**
- **Wingbeat-Extra Attack → renamed Wingbeat-Extra Target.**
- **Guardian of Nova**: ancient Kaiser's attacks now trigger an ancestral combined-strike after enough hits.
- **Will of Sword: Strike**: icon/effect changed; removed ground-time-based damage scaling for the avatar; avatar now ignites flame right after landing; removed flame-hit-bypasses-Draco-Slasher-recharge-cooldown; flame damage 1540%→2200%.
- **Draco Slasher**: can now stack up to 5 charges.
- **Dragon Blaze**: description changed; several Will-of-Sword variants (base, Advanced, Strike, VI) now all trigger fire-burst + fireball generation.
- **Sword Strike VI**: gained a passive Wingbeat VI damage buff.
- **Will of Sword VI**: avatar 775%→1336%; Dragon Blow 3800%→6530%.
- **Petrified VI**: unusable in non-hunting; permanent ATT gain.
- **Wingbeat VI**: same passive rework as base.
- **Pyro Instinct**: flame 7213%→6737% (nerf).
- **Sol Hecate**: 775%→865%.

### Cadena (카인 — actually this is Kain, corrected below)

### Kain
- **Shadow Swift**: mobility rework.
- **Dread Bolt**: motion removed; usable mid-skill; icon/effect updated; attack removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Dragon Fang**: on/off persists on reconnect.
- **Death Blessing**: max-duration cap removed; damage 135%→120% (nerf); fixed death's-blessing-hidden-by-damage-skin bug.
- **Remain Incense**: crystal now prioritizes highest-HP boss; on/off persists on reconnect.
- **Advanced Death Blessing**: damage bonus 150%p→130%p (nerf).
- **Dogma**: crit damage 25%→17% (nerf).
- **Breath Shooter Expert**: Final Damage 37%→33% (nerf).
- **Chasing Shot**: arrow 352%→72% (big nerf); normal-mob bonus reworked from 30% to 310%p.
- **Incarnation**: removed party-attack-triggers-death's-blessing aura; fixed buff-duration display bug.
- **[Manifest] Dragon Burst**: MP 750→500; direction-recorrection window 0.5s→0.2s.
- **[Execution] Fatal Blitz**: MP 750→500; direction change mid-attack added.
- **Thanatos Descent**: death's arrow now persists for remaining duration after Realm of Death triggers; screen effect now shows if you don't trigger Realm of Death in time during the buff.
- **Grip of Agony**: recast respawns hand of agony at current position; damage 1480%→1320% (nerf).
- **[Execution] Poison Needle VI**: hit 710%→680%; combo 550%→520%; finisher 460%→430% (all nerfs).
- **Dragon Fang VI / Remain Incense VI / Death Blessing VI**: matching persistence/targeting changes; Death Blessing VI damage 610%→549% (nerf).
- **Chasing Shot VI**: arrow 676%→136% (big nerf); normal-mob bonus 30%→570%p.
- **Annihilation**: wave 600%→1200%; slash 720%→1440%; Death Blessing damage during Malice's Domain 675%→608% (nerf); with Incarnation 705%→635% (nerf); dragon's breath 900%→840% (nerf).
- **[Manifest/Execution] Malicious Flicker**: manifested malice 2450%→2555%; strike 2661%→2800%; blessing of the end 3148%→3290%.
- **[Manifest] Strike Impact**: hit1 1313%→1576%; hit2 1051%→1261%.
- **[Execution] Phantom Requiem**: carnage 420%→714%; rend 343%→789%.
- **Sol Hecate**: 650%→761%.

### Cadena
- **Agent Shift**: description + mobility rework.
- **Weapon Variety I/II/III/VI**: removed the weapon-swap Final Damage buff (except Chain Arts).
- **Physical Training**: gained Final Damage increase.
- **Summon Throwing Wing Dagger**: max-hit cap added; now prioritizes highest-HP boss; fixed odd movement.
- **Chain Sprint**: description/icon/effect changed; motion removed; usable mid-skill; sound updated; attack removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Temper**: gained mob-defense-ignore.
- **Weak Point Attack (& Converging)**: removed status-debuff crit bonus, added flat crit damage bonus instead.
- **Basic Detection**: Final Damage 4%→30%.
- **Summon Slashing Knife**: removed fear-status application.
- **Weapon Expert**: crit damage 15%→23%; gained Final Damage boost too.
- **Quick Service Mind II**: gained Final Damage boost.
- **Chain Arts: Tough Hustle**: description changed.
- **Chain Arts: Takedown**: barrage slash 990%→1080%; shockwave 600%→830%.
- **Summon Beating Needlebat**: removed daze-status; hits nerfed (330%→281%, 443%→371%, 653%→554%).
- **Professional Agent**: removed double-Weapon-Variety-buff mechanic, added flat Final Damage buff instead; explosion 220%→200% (nerf).
- **Chain Arts: Crush / Merchant's Special Elixir**: description changed.
- **A.D. Ordnance**: MP 1000→500; condensation 495%→1870%, hits 5→13, procs 38→5; sphere 1650%→2090%, hits 8→14; cooldown 25s→60s; removed reinstall-on-recast function; description changed.
- **Chain Arts: Fury**: giant chain 1045%→1100%; description changed.
- **Chain Arts: Maelstrom**: duration 15s→60s; unusable in non-hunting maps; gains a permanent Final Damage buff for all weapons except A.D. Ordnance/Chain Arts; removed the Stroke-hit2-only-chain restriction; now directly keybound.
- **Weapon Variety Finale**: 660%→605% (nerf).
- **Chain Arts: Stroke VI**: hit1 300%→330%; hit2 560%→590%; enhanced hit2 560%→590%; its shockwave 990%→1020%.
- **Weapon Variety VI**: removed swap-buff mechanic; gained permanent Final Damage instead.
- **Summon Slashing Knife VI / Beating Needlebat VI**: removed status debuffs; Needlebat VI hits nerfed (568%→513%, 783%→696%, 1160%→1016%).
- **Professional Agent VI**: same rework as base; explosion 360%→340% (nerf).
- **Chain Arts: Takedown VI**: barrage 1710%→1915%; shockwave 1015%→1421%.
- **Summon Shooting Shotgun VI**: nerfed at all ranges (~940%→910%, 837%→807%, 758%→728%).
- **Chain Arts: Crush VI**: description changed.
- **Summon Releasing Bomb VI**: 1000%→940% (nerf).
- **Summon Throwing Wing Dagger VI**: max-hit cap added; boss-priority targeting; 849%→790% (nerf); movement fix.
- **Sol Hecate**: 630%→801%.
- **Chain Arts: Maelstrom Enhance**: gains the same permanent Final Damage buff as base Maelstrom.
- **Chain Arts: Massacre**: slash procs 54→43; explosion procs 60→35 (both nerfed frequency).
- **Brutal Ravage**: strike 8123%→4410%; crush 8292%→4445% (big nerfs).
- **Chain Arts: Torrent**: reworked summon-trigger method (now direct keybind instead of combo-command); chain vortex no longer clears Maelstrom/A.D. Ordnance and vice versa; removed the vortex→Maelstrom-vortex conversion on explosion; removed prerequisite-skill requirement; explosion 573%→600%.

### AngelicBuster
- **Dress Up**: cash equipment stats (excluding weapon/ring) now only apply when worn in the Dress Up mode's normal slot — see official notice about the 9/17 stat-application change for AngelicBuster cash items if you're double-wearing stat items in both modes.
- **Successor / Magical Shift**: keydown-jump added; Magical Shift also got description + mobility rework.
- **Pink Skud**: description/icon/effect changed; motion removed; usable mid-skill; attack removed; distance changed; permanent ATT gain; can't macro.
- **Soul Seeker**: uptime +~150%.
- **Finitura Petuccia**: cooldown 40s→30s; removed on-hit DoT.
- **Soul Resonance**: keydown-end delay removed; aerial use now preserves Magical Shift charge count.
- **Soul Gaze**: crit damage 20%→17% (nerf).
- **Soul Shooter Expert**: Final Damage 21%→20% (nerf).
- **Super Nova**: recast respawns energy body at current location.
- **Mascot Familiar**: keydown-jump added.
- **Soul Seeker VI**: uptime +~150%.
- **Trinity VI**: condensed energy 847%→817% (nerf).
- **Genuine Encore**: cheer-balloon uptime +~150%; wave 5111%→5286%; charm-emission 5002%→5177%.
- **Popping Heart**: charging fan 1069%→2627%; charm-emission 1124%→2734%.

### Zero
- **Burst Jump**: fixed aerial up-cast letting you move mid-other-skill.
- **Burst Step**: motion removed; up/down delay −~47%; aerial up/down use capped at 2 consecutive; fixed accidentally triggering Rapid Time; fixed cancelling Rolling Assaulter mid-cast when used in air.
- **Divine Aura → renamed Divine Force**; removed party ATT/Magic ATT/attack speed/move speed/jump/DEF/elemental & status resistance buffs.
- **Shadow Strike**: removed left/right-key nearest-target-teleport function.
- **Blade Mastery**: mob-defense-ignore 30%→65%.
- **Combat Recovery**: description changed.
- **Armor Split**: removed Beta's chance-to-shatter-armor DEF-reduction; gained permanent mob-defense-ignore on Beta hits instead.
- **Advanced Earth Break**: electric zone 310%→120% (nerf); its normal-mob bonus 210%p→400%p.
- **Critical Bind**: description changed.
- **Rapid Time**: removed attacker-based stacking damage buff, gained permanent damage increase.
- **Time Distortion**: removed party attack-speed/damage buff.
- **Time Holding**: fixed chain-break bug with certain skills mid-cast.
- **Earth Break VI**: electric zone 485%→180% (nerf); normal-mob bonus 340%p→645%p.
- **Wind Cutter VI**: whirl 175%→149% (nerf).
- **Storm Break VI**: whirl 475%→404% (nerf).
- **Shadow Strike VI**: same function removal.
- **Bitemporis**: awakening 3815%→3745%; collapse 4130%→4015%; overlap 4305%→4235% (all small nerfs).

### Kinesis
- **Psychic Walk**: description changed + mobility rework.
- **Psychic Rush**: description changed; motion removed; usable mid-skill; icon/effect/sound updated; distance changed; recast delay +~25% (longer); can't macro.
- **Mental Reinforcement**: gained permanent mob-defense-ignore.
- **Psychic Smashing (& VI)**: removed on-hit DEF-reduction.
- **Psychometry**: unusable without a target in range.
- **Ultimate: Checkmate**: cooldown-reset for Ultimate skills now only applies to attacks used during Unleash.
- **Psychic Board**: fixed occasional client freeze on use.
- **Fractal Horizon**: 1078%→1063% (small nerf).
- **Gravity Object**: 268%→471%.
- **Sol Hecate**: 578%→643%.

### Lef (Common)
- **Race of God**: removed Lef-class party damage buff.

### Adele
- **Magic Circuit**: description changed.
- **Glint**: icon/effect changed; motion removed; usable mid-most-skills; attack removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Bolt**: forward mid-skill use + direction-chain jumps.
- **Wonder**: no longer consumes Shards on acquisition.
- **Territory**: reworked into "create your own domain filled with countless swords"; cast effect changed.
- **Squall**: no longer triggers without a target.
- **Territory-Persist → renamed Territory-Reinforce.**
- **Wonder VI**: description changed.
- **Territory VI**: same rework as base + effect change.
- **Einheit**: 5537%→5390% (nerf).
- **Aether Rufe**: reworked into a toggle — attacking starts it, recast or duration-end stops it; sustained hit 875%→1225%; Aether Sword 673%→942%.

### Illium
- **Magic Circuit**: description changed.
- **Crystal Portal**: fixed aerial up-cast movement exploit.
- **Rio**: usable in air.
- **Bless Mark (& Mastery, & Perfection)**: removed stacking function.
- **Crystal Charge (& Mastery, & Perfection)**: **all removed**.
- **Crystal Control**: removed 300s auto-reset of Crystal Charge; crystal now summonable in air; summon state persists on reconnect.
- Several skills reworked to no longer require Crystal Charge (now cooldown-based instead): **Crystal Skill: Mortal Swing, Glory Wing, Harmony Link, Deus, Deus VI**.
- **Curse Mark (& Mastery, & Perfection, & Perfection VI)**: reworked into a chance-based weaken effect that adds bonus hits to Illium's attacks (except Craft: Orb), instead of leaving a mark.
- Several skills reworked from mark-on-hit to bonus-hit-trigger: **Reaction: Domination (& II & VI), Glory Wing: Mortal Wingbeat (& VI), Reaction: Destruction VI**.
- **Crystal Skill: Mortal Swing**: cast motion added.
- **Machina**: usable in air.
- **Crystal Skill: Glory Wing**: description changed.
- **Crystal Skill: Harmony Link**: removed party Bless Mark application.
- **Crystal Skill: Deus → renamed Deus**: icon changed; usable without Crystal/Rio/Machina present.
- **Fast Charge → renamed Glory Wing: Zenith Wingbeat.**
- **Glory Wing: Harmony Wingbeat**: reworked into refining magic to further strengthen wings.
- **Crystal's Secret**: now benefits from Useful/Combat Orders and Collector's Elixir; proficiency/Final Damage/mob-defense-ignore formulas changed.
- **Primal Protection**: removed Bless-Mark-stack-scaling invulnerability, flat invuln duration 2.5s→6.5s instead.
- **Deus-Reinforce / Bonus Attack / Boss Killer**: description changed.
- **Gramholder**: 1220%→1104% (nerf).
- **Crystal Gate**: cooldown resets if it despawns early; fixed lingering gate on boss map enter/exit.
- **Glory Wing: Mortal Wingbeat VI**: mana storm 2200%→1870% (nerf).
- **Rio VI / Machina VI**: usable in air.
- **Crystal Skill: Deus VI → renamed Deus VI**: icon changed; usable without Crystal/Rio/Machina.
- **Craft: Longinus VI**: removed crystal-charge-on-hit function.
- **Exsidium**: wave 4830%→4655%; explosion 5075%→4900% (nerfs).
- **Glory Wing: Splendor**: erosion 2370%→3965%; resonance 1580%→2653%.
- **Sol Hecate**: 1215%→990% (nerf).

### Kali
- **Spark**: description + mobility rework.
- **Impulse**: master level 9→8; crit rate/damage formulas changed.
- **Mirage Step**: NEW skill — teleport a set distance.
- **Resonate**: uptime +~25% when no target in range.
- **Void Rush / Void Blitz (& VI)**: fixed visual bugs with Illusion Ring cosmetics (Giant Body/Giant Head).
- **Hex: Chakram Fury**: 735%→710% (nerf).
- **Chakram Expert**: crit damage 23%→17% (nerf).
- **Redemption**: Final Damage 35%→32% (nerf).
- **Arts: Astra**: 1100%→1045%; annihilation 1210%→1150% (nerfs).
- **Resonate: Ultimatum**: same no-target uptime bonus for the awakened version.
- **Hex: Pandemonium**: cast effect/sound/interval changed.
- **Void Burst**: fixed missing tooltip on buff-icon hover.
- **Hex: Chakram Fury VI**: dash 1435%→1322% (nerf).
- **Void Rush/Blitz VI**: same cosmetic fixes.
- **Resonate VI**: same uptime bonus.
- **Void Awaken**: hit1 4060%→4100%; hit2 4330%→4505%.
- **Hex: Dune Burst**: slash 237%→576%; sand explosion 426%→863%.
- **Sol Hecate**: 1261%→961% (nerf).

### Ark
- **Magic Circuit / Contact Caravan / Mystic Leap / Instinct Leap**: description changed; Mystic Leap & Instinct Leap also get mobility reworks (forward mid-skill, direction jumps).
- **Mystic Rush**: NEW skill — fast forward charge using Lef's mana.
- **Instinct Rush**: NEW skill — fast forward charge using the Specter's power.
- **Physical Training**: master level 5→4; STR formula changed.
- **Returning Hatred**: mark-activation range +~195%.
- **Knuckle Expert**: crit damage 30%→21% (nerf).
- **Fusion Complete**: boss-hit damage bonus 12%→10% (nerf).
- **Battle Frenzy**: Final Damage 20%→15% (nerf).
- **Charge Spell Amplification**: removed party charge-spell-buff sharing; using it now refreshes your own charge-spell buff to max duration instead.
- **Endless Suffering**: move/jump during keydown; damage 360%→396%; abyss watcher 420%→462%.
- **Ever-Hungering Beast**: description changed; no longer disappears on death.
- **Leaking Nightmare**: 1705%→1531% (nerf).
- **Leaking Terror**: 2035%→1832% (nerf).
- **Returning Hatred VI**: mark range +~195%.
- **Endless Suffering VI**: move/jump during keydown; damage 576%→645%; abyss watcher 672%→751%.
- **Awakened Abyss**: 1520%→1404% (nerf).
- **Whisper of Absolute Abyss**: abyssal energy 3896%→4186%; abyssal blade 4876%→5241%.
- **Primordial Torrent**: torrent 1688%→2674%; abyssal thorn 972%→1523%.
- **Sol Hecate**: 837%→866%.

### Ren
- **Blue Wind Step**: description + mobility rework.
- **Blue Void Mind IV**: Final Damage 20%→17% (nerf).
- **Plum Blossom Sword 5th Form: Heaven-Devouring Blossom Strike**: 720%→327% (big nerf).
- **Soul-Severing Sword Origin: Spirit Strike VI**: 1210%→1123% (nerf).
- **Blue Dragon Heaven-Piercing Sword: One Petal Falling Blossom, Thousand Ruins**: falling blossom 2153%→2170%; true shock 3815%→3850%; heaven's strength 2573%→2590%; effect position changed.
- **Blue Dragon Heaven-Piercing Sword: Ten Thousand Beheadings**: 402%→576%.

### Lara
- **Hop**: mobility rework (forward mid-skill, forward-then-up jump).
- **Mountain Wave**: motion removed; usable mid-skill; distance changed; recast delay −~6%; can't macro.
- **Dragon Vein Eruption**: down-key use now erupts all elemental veins at once; fixed occasional icon glitch.
- **Eruption: Rolling River / Whirlwind / Sunrise Well**: all now stop triggering their effect after a period of sustained combat outside boss maps.
- **Mountain Seed / Manifest: Wind Swing**: usable in air.
- **Manifest: Sunlit Ground**: removed party damage buff.
- **Trace of Dragon Vein**: motion removed; usable mid-skill.
- **Insight (혜안)**: mob-defense-ignore 40%→43%.
- **Vine Tangle**: no longer triggers without a target.
- **Great Tree**: removed map-wide mob-DEF-reduction; description changed.
- **Sun River Mountain Wind**: usable in air.
- **Dragon Vein Eruption VI**: same all-at-once down-key function.
- **Eruption: Rolling River VI**: same combat-timeout; wave 1025%→963% (nerf).
- **Eruption: Whirlwind VI**: same combat-timeout; 482%→465% (nerf).
- **Eruption: Sunrise Well VI**: same combat-timeout; damage 440%→425%; lava zone 708%→686%; volcanic bomb 480%→465%; DoT 195%→188% (all small nerfs).
- **Andamiro**: 5905%→5880% (nerf).
- **Embracing Breath**: eruption 720%→895%; fused earth-spirit's emission 670%→840%.

### Hoyoung
- **Blue Cloud Return / Shape Shift**: description changed.
- **Talisman Dosool → renamed Dosool**: now charges/spends Dosool directly instead of via talisman.
- **Sealing Gourd of Demons**: reclassified from Talisman-Dosool to Dosool skill; now spends Dosool on use.
- **Chosangbi**: mobility rework (forward mid-skill, no up-use mid-air-skill, direction-jumps).
- **Muunswaedo**: motion removed; usable mid-skill; icon/effect/sound updated; attack removed; distance changed; recast delay −~6%; permanent ATT gain; can't macro.
- **Phantom Duplicate Talisman**: can register to pet-buff auto-skill; reclassified to Dosool; clone damage 60%→38% (nerf).
- **Scroll Dosool → renamed Dosool Enhance**: description changed; removed charge-on-Cheon/Ji/In-hit and charge-on-talisman-use; (charging mechanic reworked/removed).
- **Tracking Ghost Fire Talisman**: reclassified to Dosool; ghost fire now teleport-tracks distant targets, and returns to you if it can't find one.
- **Fist Technique: Faint Life Change (미생강변)**: reclassified to Dosool; removed on-hit DEF-reduction.
- **Asura**: crit damage 20%→15% (nerf); mob-defense-ignore 10%→28%.
- **Annihilating Flame: Cheon**: description changed.
- **Shapeshift: Heavy Stone**: description changed.
- **Fist Technique: Absorbing Whirlpool → renamed Absorbing Whirlpool**: now MP-based instead of Dosool; vortex duration 40s→60s; removed reposition-via-recast; removed on-recast HP/MP party heal; unusable in non-hunting maps.
- **Absorbing Whirlpool: Release**: NEW skill — releases the vortex's energy to heal party HP/MP.
- **Fist Technique: Butterfly Dream**: reclassified to Dosool; description changed; can register to pet-buff auto-skill.
- **Sunki: Elixir of the Great Immortal**: MP 800→500; now fully refills Dosool on cast, then 3s no-Dosool-drain, then periodic regen for 9s.
- **Sunki: Clone Transformation Great Immortal**: no longer triggers without a target.
- **Fist Technique: Absorbing Whirlpool-Haste → renamed Absorbing Whirlpool-Haste** (name change only).
- **Crest of the Solar**: sigil damage 828%→770%; single-target sigil 1140%→1058% (nerfs).
- **Sunki: Ultimate Clone Barrage**: description changed.
- **Fist Technique: Mountain Spirit Summon**: reclassified to Dosool; action delay −~20%; sound updated; damage 1980%→1544% (nerf); roar 770%→1000%; despawns after 6 roars; recast respawns at current location.
- **Sunki: Descent of Overwhelming Force**: gods' strike now still triggers after Descent of Gods even post-buff; screen effect if you don't recast Descent of Gods in time; description changed.
- **Sunki: Cheon-Ji-In Illusion**: cooldown-less Cheon/Ji/In Dosool hits now reset clone-reappear delay to 0.5s; description changed.
- **Phantom Duplicate Talisman VI**: same pet-buff/reclassification changes; damage 386%→359% (nerf).
- **Tracking Ghost Fire Talisman VI**: same reclassification + tracking rework.
- **Fist Technique: Absorbing Whirlpool VI**: same MP-based rework; vortex 40s→60s; permanent ATT gain added; unusable in non-hunting.
- **Fist Technique: Butterfly Dream VI**: same reclassification.
- **Millennium Command (천세휘령)**: energy 3087%→3015% (nerf).
- **Sunki: Release of the Four Evils - Taotie**: strike 184%→552%; flurry 218%→283%; heaven's thunder 335%→670%.
- **Sol Hecate**: 639%→678%.

### Demon-class (Mercenary — 마족 Common)
- **Masterian Grit**: removed Mercenary-class party damage buff.

### Lethe
- **Invoke: Templar**: fixed odd Templar behavior on some maps.
- **Oblique Teleport**: added a lock to prevent teleport from also triggering; when locked, can be used on a separate keybind.
- **Overload: Templar Onslaught**: 900%→990%.
- **Overload: Vargar Trident**: 1500%→1650%.
- **Edict: Fell Storm VI**: 712%→783%.
- **Edict: Rampage VI**: 760%→912%.
- **Edict: Templar Arts VI**: 764%→917%.
- **Pact Manifest**: 184%→221%.
- **Absolute Rain**: mana chains 4340%→4377%; Ananke's Embrace 4760%→4800%.
- **Invoke: Templar VI**: same odd-behavior fix.

---

## 2. V Core Changes (skill-enhancement core reshuffling)
Many classes had their "combined" V enhancement cores restructured due to the mobility-skill (dash/rush) reworks above — cores tied to removed dash-attack functions were deleted, merged into remaining cores, or converted to V Points. Highlights:
- **Hero/Paladin/Dark Knight**: Rush-enhancement cores deleted or merged into Leap Attack cores.
- **Arch Mage (Fire/Poison)**: Poison Region/Meteor/Megiddo core now also covers Poison Flare; Explosion/Poison Mist core no longer includes Teleport Mastery (removed).
- **Bishop**: Angel of Libra core → Angel of Gemini core.
- **Bowmaster/Marksman**: Swift Surge enhancement core removed/merged into Retreat Shot core; Marksman also merges Arrow Illusion core into Arrow Blow core.
- **Shadower**: Muspelheim core → Savage Blow core; Edge Carnival core merged.
- **Dual Blade**: Tornado Spin core removed, merged into Sharp Slash/Fatal Blow/Slash Storm core.
- **Captain/Cannoneer**: Escape Shot / Cannon Jump / Cannon Drift cores removed and merged into adjacent cores.
- **Mihile**: Royal Guard core reworked into Offensive Defense/Soul Majesty core; new Final Attack core split out; Shining Chase/Pierce merged.
- **Soul Master/Flame Wizard/Night Walker/Aran**: various dash-related enhancement cores removed/merged (Loud Rush/Silent Move, Blazing Rush, Silent Rush, Final Charge).
- **Evan**: Breath-Come Back! function removed from Dragon Breath core; Summon Onyx Dragon core removed & merged.
- **Luminous**: new Memorize core added, merged into Absolute Kill/Death Side core.
- **Mercedes/Phantom/Blaster/Wild Hunter**: similar dash-enhancement-core removals/merges (Lightning Edge, Phantom Charge, Explosion Move, Whiteout Rush).
- **Xenon**: Hologram Graffiti core renamed to Hologram Graffiti: Force Field core; Diagonal Chase & Horizon Chase cores removed, merged into Ion Thruster core.
- **Mechanic**: Drill Rush core removed/merged into Gatling Shot/Rocket Booster core; Support Waiver: H-EX core removed, merged into Distortion Field/War Machine: Titan core.
- **Demon Slayer**: Dark Thrust core removed, merged into Demon Trace/Soul Eater core.
- **Demon Avenger**: Shield Charge core removed, merged into Inhale Vitality core.
- **Kaiser**: Pierce Rush core removed, merged into Flame Shot/Impact Wave core.
- **Kain**: Dread Bolt core removed (converted to V Points based on gem cost); Death Blessing/Chasing Shot/Sneaky Sniping core restructured (old version converted to V Points); Dread Bolt core renamed to Chasing Shot core.
- **Cadena**: Chain Arts: Stroke/Takedown/Crush cores merged into Stroke/Takedown core; Chain Sprint core → Chain Arts: Crush core (old cores converted to V Points).
- **AngelicBuster**: Pink Skud core removed, merged into Successor/Bubble Star/Sting Explosion core.
- **Adele**: Glint core removed, merged into Plain core.
- **Illium**: New Glory Wing: Zenith Wingbeat core added, merged into Glory Wing: Mortal Wingbeat/Crystal Skill: Mortal Swing core; Deus core icon & name updated to "Deus Enhance."
- **Ren**: New Heaven-Devouring Blossom Strike core added, merged into Spirit Strike Origin core.
- **Hoyoung**: Muunswaedo core removed, merged into Sealing Gourd/Heavy Stone core; Absorbing Whirlpool/Butterfly Dream core name updated *(document cuts off here)*.

---
