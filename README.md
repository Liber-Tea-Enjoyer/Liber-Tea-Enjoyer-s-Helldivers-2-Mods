# Liber-Tea-Enjoyer-s-Helldivers-2-Mods
Mods for Helldivers 2 with a little shot of Liber-Tea.
# Liber-Tea-Enjoyer's Helmet and Cape Passives v2.1

**Your helmet and cape now count.** In the base game only your body armour's passive does anything in a mission; helmets and
capes have none. This mod gives every helmet and cape the passive of the armour set it belongs to, and makes all three pieces
count in missions. Wear the same passive on two or three pieces; mix different passives and you get all
of them.

## What it does

- **Every helmet and cape carries the passive of its armour set.** A helmet or cape takes the armour's passive of the body armour sold with it (the same Warbond or Superstore page). A helmet that belongs to no set carries Extra
  Padding; a cape that belongs to no set carries Democracy Protects. THERE MAY BE MISTAKES HERE, PLEASE LET ME KNOW IF YOU FIND ANY.
- **1, 2 or 3 pieces** (body, helmet, cape) with the same passive give the 1-, 2- or 3-piece values in the table below.
- **Different passives add up**, with three exceptions so no mix gets out of hand:
  - **Stealth** (Scout, Feet First, Reduced Signature): they all now have reduced noise and "enemies see you closer" passives because reduced signature essentially made the others redundant.
    Any 2 pieces: noise -55%, enemies see you 50% closer. Any 3: -60% and 60%.
  - **Explosive damage** (Fortified, Ballistic Padding, Reduced Signature, Extra Padding and the three Concussive Paddings)
    and **crouch recoil** (Fortified, Engineering Kit, Blunt-Force Mitigation): a mix never goes past the best of them at that
    many pieces (for example Fortified + Ballistic Padding + Reduced Signature = explosive damage -75%, not -90%). This is for balance reasons.
  - Fire, gas, acid and arc resistance add up freely (a mix can make you immune), and so does the map ping.
- **Adreno-Defibrillator on any piece** brings you back once after a death (body intact), and the last stand afterwards
  lasts **60 / 120 / 180 seconds** with 1 / 2 / 3 Adreno pieces (the game's normal: about 5 seconds which was utterly useless and not worth taking).
- **Integrated Explosives:** the blast when you die is 3x bigger and now has demolition force 40, the strength the game needs to close bug
  holes and destroy fabricators from the outside (the game's normal: 30, which cannot).
- **An overlay box in the Armory and on the mission loadout screen** shows exactly what your set gives: each piece's share and the
  totals, in the game's own lettering. It pops up when using either a mouse or controller and goes away when you leave the armour lists.
- Friends can join you; they do not need the mod. Only your armor will be affected. Nothing is sent to anyone and nothing is saved to your account.

## Requirements

- **Bingus Shared Loader** (the mod runs through it; keep it enabled).
- A mod manager (**HD2 Arsenal** or **HD2ModManager**).

## Install

1. Install Bingus Shared Loader and a mod manager if you don't have them yet (both are on Nexus Mods).
2. If you have an earlier version of this mod, disable or remove it first.
3. Add `Liber-Tea-Enjoyer's Helmet and Cape Passives v2.1.zip` to your mod manager, enable it, keep Bingus Shared Loader
   enabled, and deploy.
4. Start the game and open the Armory: the box shows what your set gives.

## Uninstall

Disable or remove it in your mod manager and deploy again. Everything lives in the game's memory while it runs and is gone when
you close the game. Nothing is saved to your account or your save data. The mod writes one small log file
(`LTE-helmet-cape-passives.log` in the Bingus loader's log folder), replaced each time you start the game, and a one-line
font note beside it (`LTE-helmet-cape-passives-fontmark.log`).

## Compatibility

- **HD2 Transmog:** not tested together yet. I wanted to make it compatible before release but people were pestering me to release now and do transmog compatibility later. Compatibility hopefully comes in v3; until then use both at your own discretion.
- **Vanilla Plus Megapack:** works alongside it.
- **Other mods that change armour passives:** use my mod or theirs, do not use both.
- **Game version:** made for game version 1.8.46015. Before changing anything the mod checks that every value it expects is
  there; after a game update it will likely break. Check back for an update after a game patch.

## Known issue

- With the **Vitality Enhancement** booster in your squad, the Adreno last stand does not end by itself. This will be looked into for v3.

## The passives

"1 / 2 / 3 pieces" = how many of your pieces (body, helmet, cape) carry the passive. "Normal" is the game's own value, which only
the body armour gives (helmets and capes give nothing in the base game). "Speed" and "Stamina regen" are in the Armory's own units
(a medium armour has speed 500 and stamina regen 100). The stealth, explosive damage and crouch recoil lines follow the mixing
rules above.

| passive | effect | Without Mod (body only) | With Mod (1 piece) | With Mod (2 pieces) | With Mod (3 pieces) |
|---|---|---|---|---|---|
| Extra Padding | Armour | +50 | +100 | +200 | +300 |
|  | Explosive damage | - | -10% | -20% | -30% |
| Scout | Noise | - | -50% | -55% | -60% |
|  | Enemies see you closer | 30% | 40% | 50% | 60% |
|  | Map ping | every 2 s | every 2 s | every 1.5 s | every 1 s |
|  | Stamina regen | - | +25 | +50 | +75 |
|  | Sprint speed | - | +15% | +30% | +45% |
| Fortified | Explosive damage | -50% | -50% | -60% | -70% |
|  | Crouch recoil | -30% | -30% | -50% | -70% |
| Electrical Conduit | Arc damage | -95% | -95% | -100% | -100% |
|  | Extra arc bounces | - | +1 | +2 | +4 |
| Engineering Kit | Grenades | +2 | +2 | +4 | +6 |
|  | Crouch recoil | -30% | -30% | -50% | -70% |
| Med-Kit | Stims | +2 | +3 | +6 | +9 |
|  | Stim time | +2 s | +3 s | +6 s | +9 s |
|  | Speed | - | +25 | +50 | +75 |
| Servo-Assisted | Throw range | +30% | +30% | +60% | +90% |
|  | Limb health | +50% | +50% | +100% | +150% |
|  | Grenades | - | +3 | +5 | +7 |
| Democracy Protects | Survive a lethal hit | 50% | 50% | 60% | 70% |
|  | No chest bleeding | yes | yes | yes | yes |
|  | Armour | - | +25 | +50 | +75 |
| Reinforced Epaulettes | Primary reload | +30% | +30% | +60% | +90% |
|  | Melee damage | +20% | +30% | +60% | +90% |
|  | Avoid limb injury | 50% | 50% | 100% | 100% |
|  | Armour | - | +25 | +50 | +75 |
|  | Ammo (all weapons, not backpacks) | - | +10% | +20% | +30% |
| Inflammable | Fire damage taken | -75% | -75% | -100% | -100% |
|  | Fire damage dealt | - | +10% | +20% | +30% |
|  | Stims | - | - | - | +1 |
| Peak Physique | Melee damage | +40% | +60% | +120% | +180% |
|  | Ergonomics | +30 | +30 | +60 | +90 |
|  | Sprint | - | +10% | +20% | +30% |
|  | Armour | - | +25 | +50 | +75 |
| Advanced Filtration | Gas damage taken | -80% | -80% | -100% | -100% |
|  | Gas damage dealt | - | +25% | +50% | +75% |
|  | Grenades | - | +1 | +2 | +4 |
| Unflinching | Flinch | -95% | -95% | -100% | -100% |
|  | Armour | +25 | +25 | +50 | +75 |
|  | Stims | - | +1 | +3 | +4 |
|  | Map ping | every 2 s | every 2 s | every 1.5 s | every 1 s |
| Acclimated | Fire, gas, acid, arc taken | -50% | -50% | -60% | -70% |
|  | Stims | - | +1 | +2 | +3 |
|  | Grenades | - | +1 | +2 | +3 |
| Siege-Ready | Primary reload | +30% | +30% | +60% | +90% |
|  | Ammo (all weapons, not backpacks) | +20% | +30% | +60% | +90% |
| Integrated Explosives | Grenades | +2 | +4 | +8 | +12 |
|  | Blast on death | 1x blast radius | 3x blast radius | 6x blast radius | 10x blast radius |
|  | Blast demolition force | 30 (cannot close bug holes or destroy fabricators from outside) | 40 | 40 | 40 |
| Gunslinger | Sidearm reload | +40% | +40% | +80% | +120% |
|  | Sidearm draw | +50% | +50% | +100% | +150% |
|  | Sidearm recoil | -70% | -70% | -80% | -90% |
|  | Ammo (all weapons, not backpacks) | - | +10% | +20% | +30% |
| Adreno-Defibrillator | Revives | 1 | 1 | 1 | 1 |
|  | Last stand | about 5 s | 60 s | 120 s | 180 s |
|  | Stim time | +2 s | +2 s | +4 s | +6 s |
|  | Stims | - | +1 | +2 | +4 |
|  | Arc damage | -50% | -50% | -100% | -100% |
| Ballistic Padding | Chest damage | -25% | -25% | -50% | -75% |
|  | Explosive damage | -25% | -25% | -50% | -75% |
|  | No chest bleeding | yes | yes | yes | yes |
|  | Armour | - | +25 | +50 | +75 |
| Desert Stormer | Fire, gas, acid, arc taken | -40% | -40% | -55% | -70% |
|  | Throw range | +20% | +20% | +40% | +60% |
|  | Grenades | - | +3 | +5 | +7 |
| Feet First | Noise | -50% | -50% | -55% | -60% |
|  | Enemies see you closer | - | 40% | 50% | 60% |
|  | Objective range | +30% | +100% | +200% | +300% |
|  | Legs never break | yes | yes | yes | yes |
|  | Limb health | - | +50% | +100% | +150% |
|  | Speed | - | +25 | +50 | +75 |
| Reduced Signature | Noise | -50% | -50% | -55% | -60% |
|  | Enemies see you closer | 40% | 40% | 50% | 60% |
|  | Stamina regen | - | +25 | +50 | +75 |
|  | Explosive damage | - | -15% | -30% | -45% |
| Rock Solid | Melee damage | +40% | +60% | +120% | +180% |
|  | Knock-down | -30% | -30% | -60% | -90% |
|  | Armour | - | +50 | +100 | +150 |
| Supplementary Adrenaline | Stamina when hit | +2 (game units) | +20 | +40 | +60 |
|  | Armour | +25 | +50 | +100 | +150 |
|  | Stamina regen | - | +50 | +100 | +150 |
|  | Stims | - | +1 | +2 | +3 |
| Concussive Padding, Reinforced | Explosive damage | -50% | -50% | -60% | -70% |
|  | Armour | +30 | +60 | +120 | +180 |
|  | Primary reload | - | +15% | +30% | +45% |
|  | Sidearm reload | - | +15% | +30% | +45% |
|  | Support reload | - | +15% | +30% | +45% |
| Concussive Padding, Grenadier | Explosive damage | -50% | -50% | -60% | -70% |
|  | Grenades | +2 | +3 | +6 | +9 |
|  | Primary reload | - | +15% | +30% | +45% |
|  | Sidearm reload | - | +15% | +30% | +45% |
|  | Support reload | - | +15% | +30% | +45% |
| Concussive Padding, Hazmat | Explosive damage | -50% | -50% | -60% | -70% |
|  | Gas damage | -25% | -35% | -70% | -100% |
|  | Sidearm recoil | -30% | -30% | -60% | -90% |
|  | Primary reload | - | +15% | +30% | +45% |
|  | Sidearm reload | - | +15% | +30% | +45% |
|  | Support reload | - | +15% | +30% | +45% |
| Oxygenator | Walk, run, sprint speed | +10% | +25% | +35% | +45% |
|  | Extra sprint | - | +10% | +20% | +30% |
|  | Stamina regen | - | +25 | +50 | +75 |
|  | Speed | - | +25 | +50 | +75 |
|  | Stims | - | +1 | +2 | +3 |
| Kinetic Displacement Mitigation | Fire damage | -50% | -50% | -100% | -100% |
|  | Impact damage | -30% | -30% | -60% | -90% |
|  | Avoid limb injury | 50% | 50% | 100% | 100% |
|  | Stims | - | +1 | +2 | +3 |
|  | Ammo (all weapons, not backpacks) | - | +10% | +20% | +30% |
| Blunt-Force Mitigation | Knock-down | -30% | -30% | -60% | -90% |
|  | Impact damage | -30% | -30% | -60% | -90% |
|  | Crouch recoil | - | -20% | -40% | -60% |
|  | Armour | +25 | +50 | +100 | +150 |
| True Grit | Support reload | +30% | +30% | +60% | +90% |
|  | Ergonomics | +20 | +20 | +40 | +60 |
|  | Ammo (all weapons, not backpacks) | - | +10% | +20% | +30% |
|  | Sidearm reload | - | +10% | +20% | +30% |
| Standard Issue | nothing | - | - | - | - |

## Thanks

A big thank you to the Helldivers 2 modding community. The mods and findings people have shared helped us learn how the game works and made this mod possible.

## Version history

- **v2.1:** helmet and cape passives now work in missions; 2 or 3 pieces stack; the mixing rules above; the Adreno revive and
  a longer last stand from any piece, with no re-select; Integrated Explosives' death blast gets demolition force 40 (bug
  holes and fabricators); the box in the Armory and on the mission loadout screen.
- **The first release:** helmets and capes showed their set's passive in the Armory, but the game only applied the body
  armour's passive in missions.

  # Liber-Tea-Enjoyer's Unlimited Swimming v1

**Never drown again.** In the base game a Helldiver in deep water drowns after about 5 seconds. This mod sets the drowning
timer to about 28 hours, so in practice you never drown: swim across lakes and rivers as long as you like, then climb out.

## What it changes

| | Base game | With this mod |
|---|---|---|
| Time in deep water before a Helldiver drowns | 5 seconds | 100,000 seconds (about 28 hours) |

That is the only change.

- **Only Helldivers.** Vehicles (FRVs, exosuits, tanks) and enemies have their own drowning settings, which this mod does
  not touch: in deep water they behave as in the base game.
- **Everything else about water is the game's own:** floating, swimming speed and the way water slows you are not changed.
- The game's **"You are drowning" warning** is not changed either, so it may still appear in deep water. It is only a
  warning now: the timer behind it runs for about 28 hours.
- **Known limit:** if you end up in deep water with no way to climb out, you float there instead of drowning.

## Who needs it

**Install it on your own PC.** It changes the drowning timer in your own game.

Not confirmed yet: whether it also covers squadmates without the mod when you host, and whether it still covers you when
you join a host who does not have it. Until that is tested, the safe way is for everyone who wants it to install it.
Friends without the mod can still join you, and you can still join them.

## Requirements

- **Bingus Shared Loader** (the mod runs through it; keep it enabled).
- A mod manager **HD2 Arsenal**.

## Install

1. If you don't have them yet, install **Bingus Shared Loader** and a mod manager (**HD2 Arsenal**).
   All of them are on Nexus Mods.
2. Add `Liber-Tea-Enjoyer's Unlimited Swimming v1.zip` to your mod manager.
3. Enable it, keep Bingus Shared Loader enabled too, and deploy.
4. Start the game, find some deep water and go for a swim.

## Uninstall

Disable or remove it in your mod manager and deploy again. Nothing is saved to your account or your save data. The change
lives in the game's memory while the game runs and is gone when you close it. The mod writes one small log file
(`LTE-unlimited-swimming.log` in the Bingus loader's log folder), replaced each time you start the game.

## Compatibility

- **Vanilla Plus Megapack, including Shallow Water Diving:** works alongside it. Shallow Water Diving checks the
  Helldiver's drowning settings before it runs, but only the two numbers that place the drowning point on your body. This
  mod changes a different number (the timer), so those checks pass and shallow-water dives work as before (tested in game
  with Shallow Water Diving on).
- **Other mods that change the drowning time:** use only one of them. This mod never writes over a value it does not
  recognise, so it will not fight another mod for it.
- **Game version:** made for game version 1.8.46015. Before changing anything the mod checks that the value it expects is
  there. If a game update moves or changes it, the mod changes nothing rather than the wrong thing.
- **No menu and no settings.** It is always on.

## Thanks

- **shalzuth's HelldiversData** (on GitHub), whose published descriptions of the game's settings named the drowning timer.
- **CowboyBingus**, for **Bingus Shared Loader**, which this mod runs through, and for **Shallow Water Diving**, whose
  check of the same Helldiver record confirmed we had the right one.
- And the Helldivers 2 modding community.

## Version history

- **v1:** first release.

